# Restaurant App - Server

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project is the Final Capstone Project for the MIT xPRO Full Stack Development Course.
It involves a functioning Back End that allows you to store created users
	
## Technologies
Project is created with:
* Strapi: 3.6.8
* Stripe: ^8.181.0
	
## Setup
To run this project, install it locally using npm:

```
$ cd ../restApp/server
$ npm install
$ yarn develop
```



<!-- SQL FAQ -->

GraphQL < localhost:1337/graphql >

{
    restaurants {
        id
        name
        description
        image {
            url
        }
        dishes {
            id
            name
            description
            price
            image{
                url
            }
        }
    }
}