# Project : SOLARIIX
### GROUP 9
## DEMO CHATBOT


## Overview

Chatbot uses llamaindex to index the 10K reports
for the 4 largests US banks

Prompt is match with best match in index pdf file and content is
uploaded to ChatGPT 3.5 turbo along with prompt.

To run, you will need to load the 10-k files from the data directory.
Prior to sending up to ChatGPT LLM, need to add your
OpenAI ket to the .streamlit directory in the
secrets.toml file
(openai_key = "sk-algf .... ").

To run , open a terminal window and enter :
 streamlit run /Users/.../FIN6777/Project/rag_chatbot/chatbot.py

