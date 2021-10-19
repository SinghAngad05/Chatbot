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
  
## Password Reset
* reset_password
  - utter_reset_password
  
## predict plus
* about_predict_plus
  - utter_predict_plus
  
## Pass to human
* Pass_to_human
  - utter_Pass_to_human
  
## Support Ticket
* Support_ticket
  - utter_Support_ticket