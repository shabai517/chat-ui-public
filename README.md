# pride-chat-bot
This is the chatbot-ui demo for Pride Team. It could be used to do the test for different llm models based on pride database.

## Home Page

In the home page, we have two items in the navigation bar. `Home` is the main page for the chatbot-ui demo which could be used to do the basic chat based on different llm modes.

### Choose LLM Model

First, we could choose different models for the chat. Currently, we support 

### Chat

## Database Page

In the database page, it could be used to maintain our pride data for the llms to do chat. All the answers will be given based on our database. If the perfomance is not good enough, it normally caused by two reasons:

- `llm` model is not good.

- `Database` does not cover the questions.

Currently, we use the pride `Help` page to be the dataset for the `llm` model. In the future, we could improve our database accordingly.


### Manage Database

In the Database page, we could manage our dataset for `llm` model. 

- `Add` : Click `upload` button to submit a new `markdown` file to the dataset to add more knowledge for our chat-bot. Currently, we only support the `markdown` file in the format like this: 

- `Delete` : Click `Delete` button to remove the useless dataset and it can not be recovered!

- `Download` : Click `Download` button to check the content of the file.


![Flow Chart](https://github.com/PRIDE-Archive/pride-chatbot/blob/main/flowchart.jpeg) 






