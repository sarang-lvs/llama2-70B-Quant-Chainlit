# Welcome to the CPU Chatbot! 🤖🤖

Hi there! This is a **PoC for building a chatbot using Open Source Large Language Model such as Llama2 70B (Quantized) on a CPU**.

The data used for training is a sustainability report from Microsoft for FY 2022. Original report here: [Microsoft 2022 Environmental Sustainability Report](https://aka.ms/SustainabilityReport2022).

## Notes:

- This was developed using Llama2 7B Quantized model in conjunction with LangChain and FAISS.
- This enitre solution runs on a CPU architecture and needs at least 16GB of memory free to run the model.
- LLMs like Llama2 need large computing power (read - GPUs, TPUs etc.), so a technique called quantization is used instead, which reduces the size and precision, but makes it possible to run the model on a regular laptop CPU.
- Chainlit is a web framework used for creating this bot.

## Usage

- To run this, clone the repo and download the 'LLama2 7B Quantized model on your local disk. The size of the model file '.bin' is around 8 GB.
- Place the model '.bin' file (example - 'llama-2-7b-chat.ggmlv3.q8_0.bin') in your project directory.
- In the 'data' folder, replace the PDF with the files of your choice
- Run 'ingest.py' first, and then 'model.py'

## Useful Links 🔗

- [Chainlit Documentation](https://docs.chainlit.io) 📚
- [Llama2 7B Quantized Model- download from here](https://huggingface.co/TheBloke/Llama-2-7B-GGML) **Code will not work without this!**
- [LangChain](https://www.langchain.com/)
- [FAISS](https://engineering.fb.com/2017/03/29/data-infrastructure/faiss-a-library-for-efficient-similarity-search/)

## SCreenshots

![First screen](image.png)