`Wein für Sie`: Wine-Recommendation
=============
![cover](https://github.com/yudinii/practice_/assets/157538170/723acb58-1667-4007-a4cc-0e6d396523fc)

[Wein für Sie](https://public.tableau.com/app/profile/aminov.alidzhon6857/viz/WineDashboard_17053558456560/Main_dashboard2) provides detailed information about wineries, wines, their ratings, and food pairings. It is designed for wine enthusiasts and professionals seeking extensive wine-related data. 
  
We utilized Google Cloud BigQuery for data storage and manipulation and applied Apache Airflow to create end-to-end data pipeline. 
  

    
Why we made `Wein für Sie`
-------------
![introduction](https://github.com/yudinii/practice_/assets/157538170/dfd1f3e3-b17d-440a-af42-c076cd581c08)

![why we made this](https://github.com/yudinii/practice_/assets/157538170/eaef1d4b-0971-46f7-9179-37aef48c5153)
  

Getting started
-------------
![how it works](https://github.com/yudinii/practice_/assets/157538170/1147e0eb-7237-48da-aebb-4c286202aa10)
![how it works1](https://github.com/yudinii/practice_/assets/157538170/0e1d39be-be9a-4a54-9d00-c3cc0618d9e1)

  
you can also copy the sample code below: 

#### 1) Get Wineries  
* Sample Request
```
GET https://apide.fly.dev/wineries
```
* Sample Response Body
```ruby
[
    {
        'website': 'http://www.vinicolaperini.com.br', 
        'wineryid': 10001, 
        'wineryname': 'Casa Perini'
    }
]
```
#### 2) Get Wine Information
* Sample Request
```
GET https://apide.fly.dev/wine
```
* Sample Response Body
```ruby
[
    {
        'abv': 7.5, 
        'acidity': 'High', 
        'body': 'Medium-bodied',
        'code': 'BR', 
        'country': 'Brazil',
        'elaborate': 'Varietal/100%',
        'grapes': "['Muscat/Moscato']", 
        'harmonize': "['Pork', 'Rich Fish','Shellfish']",
        'regionid': 1001, 
        'regionname': 'Serra Gaúcha',
        'type': 'Sparkling', 
        'url': 'https://i.imgur.com/ff9UaLf.jpg', 
        'vintages': "[2020, 2019, 2018, 2017]", 
        'wineid': 100001, 
        'winename': 'Espumante Moscatel',
        'wineryid': 10001
    }
]
```

#### 3) Get Wine Ratings  
* Sample Request
```
GET https://apide.fly.dev/ratings
```
* Sample Response Body
```ruby
[
    {
        'avg_rating': 4.5, 
        'vintage': '1994',
        'wineid': 174184
    }
]
```

#### 4) Get Harmonizer Suggestion 
* Sample Request
```
GET https://apide.fly.dev/harmonizer
```
* Sample Response Body
```ruby
[
    {
        'snack': 'Aperitif',
        'url': 'https://i.imgur.com/wE2P1rn.jpg'
    }
]
```


### Data Cleaning 


### BigQuery

  
### Tableau


### How to use

![Screen%20Recording%202024-01-27%20at%2010 24 20-2](https://github.com/yudinii/practice_/assets/157538170/886f3a15-cee4-4948-891b-366945f062e6)

<img width="970" alt="Screenshot 2024-01-27 at 11 02 00" src="https://github.com/yudinii/practice_/assets/157538170/0df8aa81-99e1-4778-965d-a99d07a93e10">



  
