
![logo batours](https://github.com/stefanyy16/batours/assets/104126597/0e6fbddc-1740-4691-91f3-b82ecf945ace)

# BATOURS
### Bandung Tourism Spot Recommendation (BATOURS) is mobile application designed to revolutionize the way people discover and choose vacation destinations in Bandung.

## Table Of Contents
* About Project
* Repository
* Machine Learning
* Mobile Development 
* Cloud Computing 


## About Project
| Team ID | Theme|
| --- | --- |
| C23-PC719 | Tourism, Cultural, and Hospitaly |

## Team
| ID | Name | Path | University | 
| --- | --- | --- | --- |
| M181DSX2117 | Muhammad Fachreza Anggana Sukma | Machine Learning | Universitas Indonesia |
| M041DSX2763 | Fata Falih Hilmi | Machine Learning | Institut Teknologi Tangerang Selatan |
| C208DKX4242 |  Reza Fahrezi Raihan | Cloud Computing | Universitas Jenderal Achmad Yani |
| C287DSX2949 |  Wisnu Shena Arrafi | Cloud Computing | Universitas Negeri Surabaya |
| C309DSY2785 | Stefany Mariyori | Cloud Computing | Universitas Pendidikan Indonesia |
| A208DKY4345 |  Rayi Syifa Adriana Firmansyah | Mobile Development |  Universitas Jenderal Achmad Yani | 

## Background Information : 
With an overwhelming number of travel options available today, it can be challenging for individuals to find the perfect vacation spot that suits their preferences and needs. BATOURS aims to address this problem by providing personalized recommendations for vacation places.

## Repository
| Name | Link Repository |
| --- | --- |
| Machine Learning | [Repository Machine Learning](https://github.com/ZaeRaihan/BATOURS-ML.git) |
| Mobile Development | [Repository Mobile Development](https://github.com/ZaeRaihan/BATOURS-Mobile.git) |
| Cloud Computing | [Repository Cloud Computing](https://github.com/ZaeRaihan/BATOURS-API.git) |


# Machine Learning
You can see all the machine learning code in this [ML](https://github.com/ZaeRaihan/BATOURS-ML.git)

## Model
### Recommendation System - Collaborative Filtering
Collaborative Filtering models are known for their ability to provide personalized recommendations by leveraging the collective intelligence of a user community. They can effectively capture user preferences and provide relevant recommendations based on the collaborative behavior and preferences of similar users.

## Dataset 
1. [Kaggle Dataset](https://www.kaggle.com/datasets/aprabowo/indonesia-tourism-destination)

# Mobile Development 
Batours is an application built using Kotlin programming language, you can see all the mobile development code in this [repository](https://github.com/ZaeRaihan/BATOURS-Mobile.git) and to see the application usage guide you can see the following link.

## User Interface
![WhatsApp Image 2023-06-16 at 01 55 07](https://github.com/stefanyy16/batours/assets/104126597/ad71a36b-72ec-4a62-a4ee-974d31edd21b)


## How to Clone this Project
* You can clone the batours application 
* Open in androd studio
* Please wait geadle project synchronization
* End

## Clone project ini android studio
* * Open the android studio
* Click menu file -> new -> project from version control
* Enter the **batours ** app repository [repository link](https://github.com/ZaeRaihan/BATOURS-API.git)
* Please wait gradle project synchronization
* End

# Cloud Computing
# Express API Starter

### Dev Setup
- Nodejs - Express
- Docker
- Docker Compose

### Environtment Setup
- Clone this repository
- Copy .env.local to .env
- If you want up to server use .env.production
- Copy config.example.json to config.json
- Set your environment too


### Mongodb User Setup
- Copy init-mongo.example.js to init-mongo.js
- Change up to you
```
db.createUser(
    {
        user : "yourusername",
        pwd : "yourpassword",
        roles : [
            {
                role : "readWrite",
                db : "db"            
            }        
        ]    
    }
)
```

### How To Use
- Install package that used in this project
```
npm install or yarn install
```
- Next run mongo container
```bash
docker-compose up -d
```
- Last 
```
nodemon or node index.js
```


### Postman Docs

https://documenter.getpostman.com/view/4289441/T1LTejTW



### Version
1.0.0

### Contribution
Feel free to make Pull Request
