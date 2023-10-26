**WEBSITE & CHATBOT DEVELOPMENT**

Deployment of the chatbot: The chatbot uses 3 different kinds of data resources to give out responses, 
1. CSV file,
2. JSON file,
3. Open AI API.
The bot uses the GPT LLM to provide when the answers do not match from other 2 resources.

Use case: This type of Chatbot will be used when the startups handle different domains' data in parallel

Install dependencies
```
$ (venv) pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Run
```
$ (venv) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (venv) python chat.py
```

Step 1: chatbot creation with sample intents.
Step 2: College club website development. 
Step 3: Integration of chatbot with website and changing the intents according to our website requirements.

![image](https://github.com/Vedarutvija/chatbot-web/assets/52282654/2152a47c-8708-4d78-8923-8ae0e611e503)


