# API_REST


### RESTful API in Node.js.


Project to build API for TOGOLESE soccer players statistics management and deploy this API on Heroku website.


> # Tools used to build the API :

- [x] NodeJS

- [x] Express.js – Fast, unopinionated, minimalist web framework for Node.JS

> # Packages installed :

- [x] nvm – Node Version Manager

- [x] npm – Node Package Manager

- [x] Node.js

- [x] Express installed with npm (npm install express body-parser morgan).

> # How to Use :

## POST https://murmuring-cove-22047.herokuapp.com/api/v1/stats/

>> ### This will create the stats a player

// this is the input examples

```
 {
  "id": 206,
    "name": "Nadir Ayeva",
    "club_player": "Orebro Syrianska, Suède",
    "wins": 10,
    "losses": 3,
    "points_scored": 7     
 }
```  
  
// and it will return json file like this
```
 {
    "id": 206,
    "name": "Nadir Ayeva",
    "club_player": "Orebro Syrianska, Suède",
    "wins": 10,
    "losses": 3,
    "points_scored": 7
 }
 ``` 
## GET https://murmuring-cove-22047.herokuapp.com/api/v1/stats/206

>> ### This will get the stats for player 206

// it will return json file like this
```
 {
    "id": 206,
    "name": "Nadir Ayeva",
    "club_player": "Orebro Syrianska, Suède",
    "wins": 10,
    "losses": 3,
    "points_scored": 7
 }
  ```
## PUT https://murmuring-cove-22047.herokuapp.com/api/v1/stats/206

>> ### This will update the stats for player 206

// this the input 
```
 {
    "id": 206,
    "name": "Nadir Ayeva",
    "club_player": "Orebro Syrianska, Suède",
    "wins": 30,
    "losses": 13,
    "points_scored": 10
 }
 ``` 
// and it will return json file like this
```
 {
    "id": 206,
    "name": "Nadir Ayeva",
    "club_player": "Orebro Syrianska, Suède",
    "wins": 30,
    "losses": 13,
    "points_scored": 10
 }
 ```
## DELETE https://murmuring-cove-22047.herokuapp.com/api/v1/stats/206

>> ### This will delete the stats for player 206
```
 {
    "id": 206,
    "name": "Nadir Ayeva",
    "club_player": "Orebro Syrianska, Suède",
    "wins": 30,
    "losses": 13,
    "points_scored": 10
 }
 ``` 
// and it will return an empty json file
