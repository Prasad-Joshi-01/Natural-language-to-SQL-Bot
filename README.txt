To implement the task:

1. Ensure that the provided files (data.sqlite, schema.txt, and chatbot.ipynb) are uploaded to the same directory in Google Colab.

2. During execution, remember to update the paths for data.sqlite and schema.txt within the code to match the correct file locations.

3. Change the runtime to T4 GPU for faster execution by navigating to the Runtime menu and selecting "Change runtime type" and then choosing "GPU" and "T4".

4. Run all cells in the notebook either by selecting Runtime -> Run all or by individually executing each cell with Shift+Enter.

In this assignment, I have used the Llama 2 model, specifically the quantized model "TheBloke/Llama-2-13B-chat-GGML," which enables efficient utilization of the model on the T4 GPU.

Another model, "NumbersStation/nsql-llama-2-7B," is also available for this task. NSQL is a family of autoregressive open-source large foundation models (FMs) designed specifically for SQL generation tasks.

The reason for not utilizing the "NumbersStation/nsql-llama-2-7B" model is its computational expense, which exhausts all RAM (GPU) resources during installation(As I am using free Google collab version). Additionally, CPU installation of this model is considerably slower compared to GPU installation.