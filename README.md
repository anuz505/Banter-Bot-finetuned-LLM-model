# Banter-Bot 🤖🎭  
*A Finetuned LLaMA 2 Model for Fun, Witty One-Liner Roasts*  

## 📌 Overview  
Banter-Bot is a playful conversational AI designed to deliver **witty one-liner roasts**.  
This project fine-tunes **LLaMA 2** on a custom dataset of roasts collected from Reddit and other sources.  
The result is a lightweight but sharp model specialized in banter, humor, and sarcasm.  

## 🚀 Features  
- Fine-tuned **LLaMA 2** for humor and witty comebacks  
- Dataset built from community-sourced banter examples  
- Training scripts and Jupyter notebook (`finetuning_llama2.ipynb`) included  
- Easily extendable to new datasets and tones  

## 📂 Repository Structure  
├── dataset.ipynb # Data preparation & exploration
├── finetuning_llama2.ipynb # Fine-tuning pipeline for LLaMA 2
├── requirements.txt # Dependencies
└── README.md # Project documentation


## ⚙️ Installation  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/anuz505/Banter-Bot-finetuned-LLM-model.git
cd Banter-Bot-finetuned-LLM-model
pip install -r requirements.txt
```
📌 Example Output

## Input:
```bash
Roast me: I’m addicted to coffee.
```

## Output:
```bash
You don’t run on caffeine, caffeine runs away from you.
```
🔮 Future Work

Deploy as a Discord bot / web app

Add safety filters to avoid harmful outputs

Explore other personalities (compliments, dad jokes, motivational bot)
