# OpenWebUI-Assistant-OpenAI
This repository assumes that you have already installed Open WebUI. I have not used Docker.

Create your assistant in the OpenAI dashboard, generate an API key, and use this code to integrate it into Open WebUI. Remember that it is a FUNCTION, not a pipeline.

Version:

conda 24.11.0

Python 3.11.11

openai== 0.27.0

pydantic==1.10.21

typing_extensions==4.12.2

1. Dependencies

   pip install --upgrade openai pydantic typing-extensions

2. Create the assistant and the API key on the OpenAI platform.

   <img width="497" alt="Image" src="https://github.com/user-attachments/assets/5c03576d-9ea5-4f3e-891c-77923842d579" />

3. Create a function with the data in Open WebUI.

   <img width="1276" alt="Image" src="https://github.com/user-attachments/assets/59f4b905-5562-4c49-bc56-5a879871893b" />
