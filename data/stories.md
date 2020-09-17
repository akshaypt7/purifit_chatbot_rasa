## happy_path_cartridge_cost_&_purchase_link
* greet
  - utter_how_can_i_help
* where_to_buy_cartridge_&_cost_of_cartridge{"product":"shower filter"}
  - utter_details_of_cartridge_cost_&_puchase_link
* thanks
  - utter_welcome

## happy_path_life_of_cartridge
* greet
  - utter_how_can_i_help
* life of cartridge{"product":"washing machine filter,"life_of_product":"life"}
  - utter_life_of_cartridge
* thanks
  - utter_welcome

## happy_path_life_of_cartridge + ask name of product
* greet
  - utter_how_can_i_help
* life of cartridge{"life_of_product":"life"}
  - utter_ask_product_name
* inform{"product":"washing machine filter"}  
  - utter_life_of_cartridge
* thanks
  - utter_welcome  

## happy path ; where all the shower filter can be used
* greet
  - utter_how_can_i_help
* where_to_use{"where_to_use":"hot water"}
  - utter_answer_for_where_product_can_be_used
* thanks
  - utter_welcome 

## happy path : Gaurantee Details
* greet
  - utter_how_can_i_help
* Gaurantee_details
  - utter_gaurantee_details
* thanks
  - utter_welcome  

## path: Out of scope
* greet
  - utter_how_can_i_help
* out_of_scope
  - utter_sorry_didn't_understand
* out_of_scope
  - utter_sorry_i_don't_know_i_can_help_you_with_this      

## happy path_moodbot
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
