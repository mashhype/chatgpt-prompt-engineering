# chatgpt-prompt-engineering

The original version of this repo is found here: ralphcajipe/chatgpt-prompt-engineering: Jupyter code notebooks of "ChatGPT Prompt Engineering for Developers" by DeepLearning.AI and OpenAI. (github.com)

I have modified it slightly to work with Azure OpenAI which means setting some additional openai settings:
openai.api_key  = os.getenv('OPENAI_API_KEY')
openai.api_type = os.getenv("OPENAI_API_TYPE")
openai.api_base = os.getenv("OPENAI_API_BASE")
openai.api_version = os.getenv("OPENAI_API_VERSION")

in addition to changing the "model" parameter to "engine" in the openai.ChatCompletion.create() function.
