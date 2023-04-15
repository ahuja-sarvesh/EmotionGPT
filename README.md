# About EmotionGPT
Developed a therapy chatbot system with the help of OpenAl's APIs, HuggingFace Models and a Tensorflow Based ML model for Voice Emotion Detection
<br />
# How to repliacte the project:
-Clone the repository <br />
-Upload it to your google drive, take note of the directory and make sure the model3.h5 Emotion model and .ipynb file are in the same folder.<br />
-Right click on the ```EmotionGPT.ipynb``` file and open it with google colab<br />
-Modify the filepath variable to the location in the drive inside the folder it is present<br />
-Enter you OpenAI API key inside the ```openai.api_key``` variable (**Note: Running this project will incure charges on youer OpenAI account, to know more about the pricing here: https://openai.com/pricing#language-models**)<br />
-Incase you do not have access to the gpt4 api only few people have access to it and you would have to join the waitlist, you can modify the ```model="gpt-4"```under the ```chatgpt_api``` function to ```model="gpt-3.5-turbo"```. The system will behave approximately the same.<br />
-Run the notebook and have fun!<br />
