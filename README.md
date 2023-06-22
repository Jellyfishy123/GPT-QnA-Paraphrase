### **Contributors:**
Dang Le Dang Khoa (Software Engineer I'm currently working with for data collection)
<br> Nguyen Tien Dat

### **About:**
We have a new project which is to fine tune and train LLMs on Vietnamese data, with the goal of making a Vietnamese chatbot or LLAMA/ALPACA model trained on Vietnamese dataset. I had to collect data from https://huggingface.co/datasets/commonsense_qa/viewer/default. Khoa provided the starting code for calling ChatGPT using Python using prompt engineering and receiving responses. For every question, I had to use ChatGPT to paraphrase it. Since the whole process is automated, I push the running code onto tmux and it will take approximately 72 hours to finish as there are close to 10,000 questions to paraphrase. All the questions and responses are saved to a text file and used for further training for the Vietnamese LLMs. Furthermore, since I'm using the free API key from OpenAI, I can only make 3 calls per min thus after every prompt, I have to import time and allow the code to sleep for 20s before it makes the next prompt. 
