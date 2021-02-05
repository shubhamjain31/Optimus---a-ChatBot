# Optimus-a-ChatBot

Creating a simple Python chatbot using Natural language processing and Deep learning.

## Installation  
##### Create an environment

```javascript
$ python3 -m venv venv_chatbot
```

##### Activate it
Mac / Linux:

```javascript
$ source venv_chatbot/bin/activate
```

## Usage

### Run

```javascript
python3 train.py
```

This will dump data.pth file. And then run
```javascript
python3 chat.py
```

## Customize
Have a look at intents.json. You can customize it according to your own use case. Just define a new tag, possible patterns, and possible responses for the chat bot. You have to re-run the training whenever this file is modified.

```javascript
{
  "intents": [
    {
      "tag": "greeting",
      "patterns": [
        "Hi",
        "Hey",
        "How are you",
        "Is anyone there?",
        "Hello",
        "Good day"
      ],
      "responses": [
        "Hey :-)",
        "Hello, thanks for visiting",
        "Hi there, what can I do for you?",
        "Hi there, how can I help?"
      ]
    },
    ...
  ]
}
```

## Tools
- Python
- Pytorch
- NLP
- CSV
