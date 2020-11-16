# Tell Story
> A story generator that is inspired by Mad Libs. A user adds a sentence based on the last sentence they can see and generate the full story at the end.   

## Setup

To get started, clone this repo and then:

```
cd TellStory
npm install
npx knex migrate:latest
npx knex seed:run
npm run dev
```

You can find the server running on [http://localhost:3000](http://localhost:3000).

## User stories (MVP)

1. As a user, I want to see the instruction on how to play this game. 
1. As a user, I want to see the random starting sentence. 
1. As a user, I only want to see the last sentence of the story.
1. As a user, I want to add a sentence and submit it.
1. As a user, I want to generate a story.
1. As a user, I want to print my story. 

## Stretch Goal
[x] Update CSS.
[x] Add print story button.
[] Make it multi-player
[] Have a random word generator 

## Team

- Kahu 
- Nimesh
- Karishma
- Matt

## Software development approach
Pair programming

## Tasks to complete 

- [X] Prepare boilerplate
- [X] Create tables 
- [x] Add data to the seed file
- [X] Build server and routes 
- [X] Create handlebars  
- [x] Write database functions 
- [X] Styling with CSS
- [x] Test the product
- [X] Deploy to Heroku 

## Language/Technology we are using in this project 

- JavaScript 
- Html5 and CSS3
- Express-Handlebars 
- Express
- Knex.js
- SQLite3

## Link to Heroku
https://tellstory-pohutukawa.herokuapp.com/

