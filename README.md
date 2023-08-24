# pride-chat-bot
This is the chatbot-ui demo for Pride Team. It could be used to do the test for different llm models based on pride database.

## Home Page

In the home page, we have two items in the navigation bar. `Home` is the main page for the chatbot-ui demo which could be used to do the basic chat based on different llm modes.

![Home](https://github.com/shabai517/chat-ui-public/blob/main/readme_image/home.jpg) 

### Choose LLM Model

First, we could choose different models for the chat. Currently, we support `llama2-chat`, `GPT4ALL`, `chatglm2-6b`, `mpt-7b`, `baichuan-7b`, `vicuna-13b`.

![Flow Chart](https://github.com/shabai517/chat-ui-public/blob/main/readme_image/llm_models.jpg) 

### Chat
Second, we could do the normal chat in the `input`. All the content will shown in the dialog box. We also support to resend the last question by clicking `Resend last question` and clear all the chat history by clicking `Clear`.

![Chat](https://github.com/shabai517/chat-ui-public/blob/main/readme_image/chat.jpg)

When you ask a question to the chat-bot, it will give you the answer accordingly. If you would like to know how the chat-bot provide the reply or what knowledge the chat-bot utilize to summarize the reply, you could click `relevant` button in the reply.

![Relevant](https://github.com/shabai517/chat-ui-public/blob/main/readme_image/relevant.jpg)

It will open another page to show the `knowledge` which is based to summarize the answer and help the users figure out how this reply comes out.

![Knowledge](https://github.com/shabai517/chat-ui-public/blob/main/readme_image/knowledge.jpg)

## Database Page

In the `Database` page, it could be used to maintain our pride data for the llms to do chat. All the answers will be given based on our database. If the perfomance is not good enough, it normally caused by two reasons:

- `llm` model is not good.

- `Database` does not cover the questions.

![Help Page](https://github.com/shabai517/chat-ui-public/blob/main/readme_image/pride_help.jpg)
Currently, we use the pride `Help` page to be the dataset for the `llm` model. In the future, we could improve our database accordingly.


### Manage Database

![Database](https://github.com/shabai517/chat-ui-public/blob/main/readme_image/database.jpg)

In the Database page, we could manage our dataset for `llm` model. 

- `Add` : Click `upload` button to submit a new `markdown` file to the dataset to add more knowledge for our chat-bot. Currently, we only support the `markdown` file in the format like this: 

- `Delete` : Click `Delete` button to remove the useless dataset and it can not be recovered!

- `Download` : Click `Download` button to check the content of the file.

**`Size` and `CreateTime` have not been implemented** 





