#ChatGLM + VITS + SadTalker

## base on chatGLM-6B-int4/vits/SadTalker

### This project is open source and commercial use is strictly prohibited.

- This project is based on Tsinghua University open source model chatGLM-6B and vits framework

   - Main references https://github.com/ruoqiu6/chat-with-Elysia2.0.git and https://github.com/OpenTalker/SadTalker

   - The chatGLM-6B model is open sourced by Tsinghua University. When using it, please pay attention to the corresponding usage instructions and strictly abide by the usage regulations.

     - Model download link [Click here](https://huggingface.co/THUDM) Please read the instructions carefully to download the corresponding model according to your own hardware configuration.
     - After downloading the model, please place the model and response files in the ./chatglm-model path
     - For the parameter download method, please refer to the video [here](https://space.bilibili.com/3493270982232856)
     - Emotion settings and pre-prompt settings are temporarily maintained as default.json by the original author and can be modified by yourself.

   - The vits model comes from the up owner "saya is sleeping", commercial use is strictly prohibited
     - After downloading, please place the model and configuration files in the ./model-vits path
     - There are multiple models internally, you can choose according to your own needs. The selection parameters can be modified in self.speaker_choice in soundmaker.py

   - Sadtalker model download reference https://github.com/OpenTalker/SadTalker
     - Model download: bash scripts/download_models.sh

- When deploying the project by yourself, use the following command to install the module. Note: the torch installed by pip may be the CPU version. Please follow the installation method on the torch official website to install the corresponding cuda version. If module compatibility issues occur, please use python3.9.6
  
   pip install -r requirements.txt

- When running the project, use
   python main.py can be run

After running the main file, fill in the questions in order, provide pictures of people, generate dialogues, and generate dialogue videos.

The full text of the model, including parameters, is available at the link: https://pan.baidu.com/s/1JPsijA4muq8rGsxUykrfrg?pwd=2zot
Extraction code: 2zot

- Demo video reference

https://github.com/hhhwmws0117/GLM-VITS-SadTalker/issues/1#issue-1754902198


refer to:
[0]https://github.com/hhhwmws0117/GLM-VITS-SadTalker

[1]https://github.com/ruoqiu6/chat-with-Elysia2.0.git

[2]https://github.com/THUDM/ChatGLM-6B

[3]https://github.com/datawhalechina/prompt-engineering-for-developers

[4]https://github.com/imClumsyPanda/langchain-ChatGLM

[5]https://github.com/OpenTalker/SadTalker

[6]https://huggingface.co/spaces/zomehwh/vits-uma-genshin-honkai