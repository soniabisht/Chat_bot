## greet + fetch_account_details
* greet
	- utter_how_can_I_help
* fetch_account_details
	- utter_ask_account_number
* give_information{"accountnumber": "1234567890"}
	- utter_ask_email
* give_information{"email": "abcdefghi@gmail.com"}
	- utter_ask_mobile_number
* give_information{"mobile": "9876543210"}
	- action_send_details
* goodbye
	- utter_goodbye

## greet + assistance
* greet
	- utter_how_can_I_help
* assistance
	- utter_ask_issue
* goodbye
	- utter_goodbye


## greet + offers
* greet
	- utter_how_can_I_help
* offers
	- utter_ask_name
* give_information{"person": "Shobhit"}
	- utter_ask_email
* give_information{"email": "abcdefghi@gmail.com"}
	- utter_ask_mobile_number
* give_information{"mobile": "9876543210"}
	- action_send_offers
* goodbye
	- utter_goodbye

