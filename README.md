# Multilingual Assistant 
The Multilingual AI Assistant is a voice-enabled application designed to facilitate seamless communication across multiple languages. Leveraging Google APIs, PaLM2, and Streamlit, this assistant offers real-time speech-to-text and text-to-speech capabilities within an intuitive web interface
# Features
Multilingual Interaction: Communicate effortlessly in various languages, enhancing global accessibility.

Speech Recognition: Utilizes Google Speech-to-Text API to accurately transcribe spoken words.

Natural Language Understanding: Employs PaLM2 for contextual understanding and intelligent responses.

Text-to-Speech Conversion: Converts textual responses back into speech using Google Text-to-Speech API.

User-Friendly Interface: Built with Streamlit, offering a responsive and interactive user experience.
## workflow Diagram
![diagram](https://github.com/Tanujkumar24/Multi-lingual-Ai-Assistant/blob/master/diagram.png)

## Output
![output](https://github.com/Tanujkumar24/Multi-lingual-Ai-Assistant/blob/master/outputImage.png)
![sourcecode](https://github.com/Tanujkumar24/Multi-lingual-Ai-Assistant/blob/master/sourcecode.png)
![aws](https://github.com/Tanujkumar24/Multi-lingual-Ai-Assistant/blob/master/aws_deployement.png)
# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n llmapp python=3.8 -y
```

```bash
conda activate llmapp
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE_API_KEY credentials as follows:

```ini
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# Finally run the following command
streamlit run app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- Google API
- Streamlit
- PaLM2
- s2t
- t2s

### How to Deploy Streamlit app on EC2 instance
### 1. Login with your AWS console and launch an EC2 instance
### 2. Run the following commands
```bash
sudo apt update
```
```bash
sudo apt-get update
```
```bash
sudo apt upgrade -y
```
```bash
sudo apt install git curl unzip tar make sudo vim wget -y
```
```bash
git clone "Your-repository"
```

```bash
sudo apt install python3-pip
```

```bash
pip3 install -r requirements.txt
```

```bash
#Temporary running
python3 -m streamlit run app.py
```
```bash
#Permanent running
nohup python3 -m streamlit run app.py
```

### Note: Streamlit runs on this port: 8501
