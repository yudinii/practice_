`Wein für Sie`: Wine-Recommendation
=============
![cover](https://github.com/yudinii/practice_/assets/157538170/723acb58-1667-4007-a4cc-0e6d396523fc)

[Wein für Sie](https://public.tableau.com/app/profile/aminov.alidzhon6857/viz/WineDashboard_17053558456560/Main_dashboard2) provides detailed information about wineries, wines, their ratings, and food pairings. It is designed for wine enthusiasts and professionals seeking extensive wine-related data. 
  
We utilized Google Cloud BigQuery for data storage and manipulation and applied Apache Airflow to create end-to-end data pipeline. 
  

    
Why we made `Wein für Sie`
-------------
![introduction](https://github.com/yudinii/practice_/assets/157538170/dfd1f3e3-b17d-440a-af42-c076cd581c08)

![why we made this](https://github.com/yudinii/practice_/assets/157538170/0c3e35b8-bc15-4276-bd55-f9274a59b8f3)

  
Getting started
-------------
![api](https://github.com/yudinii/practice_/assets/157538170/aaa55c0b-6104-4a10-9372-b529e77851bd)

![api1](https://github.com/yudinii/practice_/assets/157538170/f11bdc92-3c9e-4835-b82e-6c80206be05d)

  
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


      
![pipeline_edit](https://github.com/yudinii/practice_/assets/157538170/972ceeeb-fcf2-4eca-ba40-c77500034e6d)

```
pip install -r requirements.txt
```
  
![pipeline1](https://github.com/yudinii/practice_/assets/157538170/ae878010-4c8c-4677-891c-2b9e58da12bb)

![pipeline2](https://github.com/yudinii/practice_/assets/157538170/b37bd870-816a-4ba5-8d81-021934ea6bab)

![pipeline3](https://github.com/yudinii/practice_/assets/157538170/7355970c-b9a5-4506-b197-24fdf96252d8)

![pulling](https://github.com/yudinii/practice_/assets/157538170/4bfd077f-d399-4029-b1a9-e1e4b3a241fa)

![pulling1](https://github.com/yudinii/practice_/assets/157538170/9a052ae9-e0ff-4ee2-bc28-46a87ac6f70b)


![bigquery](https://github.com/yudinii/practice_/assets/157538170/ce290aa2-7c8f-4c4a-a721-ed42a5c3d21c)


  
![Dashboard](https://github.com/yudinii/practice_/assets/157538170/7e63cd4a-c548-4579-b6b5-5154f44ed0b9)

![Dashboard1](https://github.com/yudinii/practice_/assets/157538170/643a895f-6482-4a7d-9209-f658858322b3)

![Dashboard2](https://github.com/yudinii/practice_/assets/157538170/c0d891ba-8b28-4f20-ab5c-fd1aeb7e9b02)



### How to use

![Screen%20Recording%202024-01-27%20at%2010 24 20-2](https://github.com/yudinii/practice_/assets/157538170/886f3a15-cee4-4948-891b-366945f062e6)

<img width="970" alt="Screenshot 2024-01-27 at 11 02 00" src="https://github.com/yudinii/practice_/assets/157538170/0df8aa81-99e1-4778-965d-a99d07a93e10">



  
