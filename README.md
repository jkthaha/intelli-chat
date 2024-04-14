# Langchain RAG Chatbot that can also use tools

This is a chatbot that can do RAG as well as utilise the structured langchain tools. Most langchain chatbot agent implementations online show 
how to implement one of the above. Its either really good at RAG or the agent can perform actions using tools based on the user's prompt

The intelli-chat however can take a decision based on the user prompt and take the required action.

> Sometimes it can misinterpret and may end up using a tool when actually a knowledge base lookup was needed or the other way around.
