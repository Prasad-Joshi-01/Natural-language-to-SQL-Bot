# Natural-language-to-SQL-Bot

This project focuses on developing a chatbot capable of interpreting natural language prompts and providing corresponding results from a specified database. The chatbot operates by processing user inputs in natural language and generating suitable SQL queries to retrieve information from a database. Additionally, it offers compatibility with various databases by allowing users to provide the database schema as a file rather than a prompt.

## Project Overview

- **Conversion of Data**: The project begins with the conversion of data from an Excel (.xlsx) file into a structured SQL database format. This step ensures that the data is readily accessible and searchable by the chatbot.

- **Schema Understanding**: Understanding the database schema is crucial for effective query generation. The project involves the creation of a schema file that encapsulates the structure of the database. This schema file serves as input for the chatbot, enabling seamless query execution.

## Steps Followed

1. **Data Conversion**: The Excel file containing the dataset is transformed into a SQL database, facilitating efficient data management and retrieval.

2. **Schema Creation**: The database schema is comprehensively understood, and a schema file is generated to be fed directly into the chatbot code. This ensures accurate query formulation based on the database structure.

## Model Used

The chatbot leverages a quantized version of the Llama 2 model from Hugging Face. This model is adept at understanding natural language queries and generating SQL queries tailored to retrieve relevant information from the database.

## Disclaimer

The Llama 2 model utilized in this project is a quantized version obtained from Hugging Face. While efforts have been made to ensure the accuracy and reliability of the chatbot, it is essential to exercise caution and validation, especially in critical applications.

## To implement the task:

1. Ensure that the provided files (data.sqlite, schema.txt, and chatbot.ipynb) are uploaded to the same directory in Google Colab.

2. During execution, remember to update the paths for data.sqlite and schema.txt within the code to match the correct file locations.

3. Change the runtime to T4 GPU for faster execution by navigating to the Runtime menu and selecting "Change runtime type" and then choosing "GPU" and "T4".

4. Run all cells in the notebook either by selecting Runtime -> Run all or by individually executing each cell with Shift+Enter.

In this assignment, I have used the Llama 2 model, specifically the quantized model "TheBloke/Llama-2-13B-chat-GGML," which enables efficient utilization of the model on the T4 GPU.

Another model, "NumbersStation/nsql-llama-2-7B," is also available for this task. NSQL is a family of autoregressive open-source large foundation models (FMs) designed specifically for SQL generation tasks.

The reason for not utilizing the "NumbersStation/nsql-llama-2-7B" model is its computational expense, which exhausts all RAM (GPU) resources during installation(As I am using free Google collab version). Additionally, CPU installation of this model is considerably slower compared to GPU installation.

Thank you for your interest in my project.
