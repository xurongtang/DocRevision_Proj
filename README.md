# What is this?
A simple project about how to use the OCR and LLM to revist documents, such as your academic papers.

# What you need to prepare.
## API KEY
First, you need to get the API KEY from LLM supplier([Aliyun](https://bailian.console.aliyun.com/) or [DeepSeek](https://platform.deepseek.com/usage)).
Personally, I use Aliyun, so I will show you how to get the API KEY from Aliyun.
Your apikey should be saved in the file "apikey.yaml"

## Python Environment
Second, you need to install the python environment.
The following is key package required
>openAI

>fite (pip install pymupdf)

and there are some basic packages required
>io

>time

>json

>yaml

>PIL (pip install pillow)

>tqdm

## convert your documents to pdf
Finally, you need to convert your documents to pdf.

# Run the project
you can run the project by simply change the path of your documents.

# result
The result is in the folder "{time}_output.txt"

>python solution.py

the result will be in the folder "{time}_output.txt"


# What can you do with this project?
1. you can refine the prompt of the LLM to get better results.
2. you can alter the model of the LLM to get better results.

