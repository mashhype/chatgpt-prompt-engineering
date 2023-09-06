<<<<<<< HEAD
# ChatGPT Prompt Engineering for Developers
Jupyter code notebooks of "ChatGPT Prompt Engineering for Developers" by DeepLearning.AI and OpenAI.

In ChatGPT Prompt Engineering for Developers, you will learn how to use a large language model (LLM) to quickly build new and powerful applications.  Using the OpenAI API, you’ll be able to quickly build capabilities that learn to innovate and create value in ways that were cost-prohibitive, highly technical, or simply impossible before now.

This short course taught by Isa Fulford (OpenAI) and Andrew Ng (DeepLearning.AI) will describe how LLMs work, provide best practices for prompt engineering, and show how LLM APIs can be used in applications for a variety of tasks, including:

- Summarizing (e.g., summarizing user reviews for brevity)
- Inferring (e.g., sentiment classification, topic extraction)
- Transforming text (e.g., translation, spelling & grammar correction)
- Expanding (e.g., automatically writing emails)

In addition, you’ll learn two key principles for writing effective prompts, how to systematically engineer good prompts, and also learn to build a custom chatbot. 

All concepts are illustrated with numerous examples, which you can play with directly in our Jupyter notebook environment to get hands-on experience with prompt engineering. 
=======
# chatgpt-prompt-engineering

I have modified it slightly to work with Azure OpenAI which means setting some additional openai settings:
openai.api_key  = os.getenv('OPENAI_API_KEY')
openai.api_type = os.getenv("OPENAI_API_TYPE")
openai.api_base = os.getenv("OPENAI_API_BASE")
openai.api_version = os.getenv("OPENAI_API_VERSION")

in addition to changing the "model" parameter to "engine" in the openai.ChatCompletion.create() function.
>>>>>>> refs/remotes/origin/main
