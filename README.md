# AI-Generated-Text-Detection-using-LLM

This project is finished during April, 2024 - May, 2024 as the final project for the Big Data class by Adjunct Professor Amit Patel at New York University.

## Work distribution:

Danying Xu - llama, chatgpt, bert, 3 baseline models, data processing

Matt Feng - MongoDB, Apache Spark Tool, data processing

John Choi - 

## Instrctuions:

- data_processing & data_preprocessing: put the dataset in your own path and do simple operations according to the codes.

- BERT: to finetune the model, you have to use colab transformer package to connect to hugging face and check GPU capacity to ensure the successful fine-tuning.

- LLaMa: similar to BERT except that the finetuning did not work out due to incapacity of colab's T4 GPU.

- ChatGPT 3.5: to ensure the successful use of Azure OpenAI, apply for right using it on Azure. After this, build a OpenAI project and choose your own model according to their prices. Save the key and path to fill in the relative parts in the codes to run. This does not require GPU on colab or Azure notebook.

