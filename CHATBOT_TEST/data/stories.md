## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
  
## what is corona
* corona_intro
  - utter_corona_intro

## how does corona spread
* corona_spread
  - utter_corona_spread

## corona food spread
* corona_food_spread
  - utter_corona_food_spread
  
## corona in india
* corona_spread_india
  - utter_corona_spread_india
  
## happy weather
* greet
  - utter_greet
* weather
  - utter_city
* city
  - action_weather_api
  
 ## Food
 * greet
  - utter_greet
 * food
  - utter_food
 * vegetarian
  - utter_vegetarian
 * non-veg
  - utter_non_veg