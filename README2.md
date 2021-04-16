RASA CHATBOTS
1.	To install rasa-x:	
	pip install rasa-x --extra-index-url https://pypi.rasa.com/simple

	To install rasa and use it:
python -m pip install rasa
python -m pip install spacy
python -m spacy download en_core_web_md
python -m spacy link en_core_web_md en

1.	Rasa has two parts: NLU and CORE
2.	To train RASA NLU we use nlu.md
3.	To train RASA CORE we use stories.md

1. chatbots provides 24*7
2. a good first point of contact
3. reduce wait time for customers
4. minimize human interventions hence reduce cost
5. scalable
6. integrate easily to popular messaging and even voice messaging platforms
7. boost your brand perspective
For more information, visit
https://towardsdatascience.com/create-chatbot-using-rasa-part-1-67f68e89ddad
https://legacy-docs.rasa.com/docs/nlu/0.13.0/quickstart/
https://rasa.com/docs/rasa-x/installation-and-setup/install/local-mode
Every application has its help center-> so a chatbot can be used there for resolving queries..
To build training data: 
https://rodrigopivi.github.io/Chatito/
https://yuukanoo.github.io/tracy/#/agents
Types of slots:
1. Text: basically, a string
2. Bool: is_authenticated, if it true then only u can proceed forward
3. Categorical: take one of n values
4. Example: Values can be Low, high o medium 
5. Float: example price, min_value or max_value can be set
6. List: To store multiple values in a slot, so by default only one value can be stored in a single slot
7. Unfeatured: to only store some info.
==============
Python -m rasa train
Python -m rasa shell
rasa run actions
To-Do
http://docs.deeppavlov.ai/en/master/features/models/ner.html  -> other package, not for Chatbot, can be used in Conversational screen to map entities and highlight them in more interactive way.

https://blog.rasa.com/how-to-build-a-voice-assistant-with-open-source-rasa-and-mozilla-tools/


https://www.whoson.com/chatbots-ai/building-a-smarter-service-desk-the-benefits-of-using-a-chatbot/



