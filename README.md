# LLMFAST

llmfast is your go-to Python library for simplifying the development of Large Language Model (LLM) applications. With just a few lines of code, you can harness the power of LLMs, saving you time and reducing complexity. Our library offers effortless integration, minimal coding requirements, and full customization to meet your unique needs. It's designed for optimized performance, ensuring smooth application execution, even with extensive language model usage. Explore our comprehensive documentation and examples to kickstart your LLM application development journey with ease. Unlock the potential of LLMs today with llmfast!


### Chatbot

Import the `Chatbot` class: In your Python script, import the `Chatbot` class from `llmfast`. You can do this by adding the following line at the beginning of your code:

```python
from llmfast import Chatbot
```

- Obtain an OpenAI API key: To use the `llmfast` library, you'll need an API key from OpenAI. If you don't have one, sign up on the OpenAI website and obtain an API key.

- Create a `Chatbot` instance: Initialize the Chatbot class with your OpenAI API key and specify the desired role for your chatbot. Here's an example of creating a `Chatbot` instance:

- Replace `"YOUR-OPENAI-API-KEY"` with your actual OpenAI API key, and `"ENTER-YOUR-CHATBOT-ROLE"` with the desired role for your chatbot.

- Deploy the chatbot: Set the `deploy` parameter to `True` when creating the `Chatbot` instance. This will deploy the chatbot and make it available for use.

- To deploy or terminate the deployment of a chatbot created using the `mlfast` library, you can set the `deploy` parameter to `True` or `False` when creating the `Chatbot` instance, respectively.


```python
Chatbot(api_key="YOUR-OPENAI-API-KEY",
        role="ENTER-YOUR-CHATBOT-ROLE",
        deploy=True)