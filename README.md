# chatPDF-LangChain-HuggingFace-GPT4ALL-ask-PDF-free
Ask PDF NO OpenAI, LangChain, HuggingFace and GPT4ALL

Set an environment variable 
HUGGINGFACEHUB_API_TOKEN='<your_API_TOKEN>'

How to get API_TOKEN
https://huggingface.co/docs/hub/security-tokens

It uses a HuggingFace model for embeddings, it loads the PDF or URL content, cut in chunks and then 
searches for the most relevant chunks for the question and makes the final answer with GPT4ALL.

You can change the HuggingFace model for embedding, if you find a better one, please let us know.

The GPT4ALL is good but slow, if you find a better option, please let us know.
You can download the model from here # https://gpt4all.io/models/ggml-gpt4all-l13b-snoozy.bin

