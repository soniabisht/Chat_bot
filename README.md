# Chat_bot
RASA chatbot
To install rasa and use it:
python -m pip install rasa
python -m pip install spacy
python -m spacy download en_core_web_md
python -m spacy link en_core_web_md en
1.	Rasa has two parts: NLU and CORE
2.	To train RASA NLU we use nlu.md
3.	To train RASA CORE we use stories.md

•	chatbots provides 24*7
•	a good first point of contact
•	reduce wait time for customers
•	minimize human interventions hence reduce cost
•	scalable
•	integrate easily to popular messaging and even voice messaging platforms
•	boost your brand perspective
For more information, visit
https://towardsdatascience.com/create-chatbot-using-rasa-part-1-67f68e89ddad
https://legacy-docs.rasa.com/docs/nlu/0.13.0/quickstart/
https://rasa.com/docs/rasa-x/installation-and-setup/install/local-mode
Every application has its help center-> so a chatbot can be used there for resolving queries..
To build training data: 
https://rodrigopivi.github.io/Chatito/
https://yuukanoo.github.io/tracy/#/agents
Types of slots:
•	Text: basically, a string
•	Bool: is_authenticated, if it true then only u can proceed forward
•	Categorical: take one of n values
•	Example: Values can be Low, high o medium 
•	Float: example price, min_value or max_value can be set
•	List: To store multiple values in a slot, so by default only one value can be stored in a single slot
•	Unfeatured: to only store some info.
==============
When running using action.py
Error: 
ERROR    rasa.core.actions.action  - Failed to run custom action 'action_best_offer'. Couldn't connect to the server at 'http://localhost:5055/webhook'. Is the server running? Error: Cannot connect to host localhost:5055 ssl:default [Connect call failed ('::1', 5055, 0, 0)]
For this first we need to run the server using the following command rasa run actions

Python -m rasa train
Python -m rasa shell

Voice Chatbot
rasa run -m models --endpoints endpoints.yml --port 5002 --credentials credentials.yml
TTS
Pip install mpyg321
Pip install gtts
STT
pip install pipwin
pipwin install pyaudio
pip install SpeechRecognition

Error building wheel for cryptography: Update pip to latest version

