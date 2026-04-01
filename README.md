# Kalenjin–Kiswahili Speech & Translation AI

This project demonstrates an end-to-end **Natural Language Processing (NLP)** and **Text-to-Speech (TTS)** pipeline using a **Kalenjin–Kiswahili parallel corpus**. It showcases how to load linguistic datasets, generate speech, perform simple translations, and create basic AI-generated videos.

---

## Project Overview

This notebook (`pochon.ipynb`) walks through a multi-stage AI workflow:

- Loading and exploring a bilingual dataset  
- Generating speech using AI models  
- Translating between Kiswahili and Kalenjin  
- Creating simple videos from audio + images  

The project demonstrates **AI applications for African languages**, including:
- Language preservation  
- Voice assistants  
- Education tools  
- Accessibility technologies  

---

## Tech Stack

- **Python**
- **Transformers (Hugging Face)** – NLP & TTS models  
- **PyTorch** – GPU acceleration  
- **Pandas** – Data handling  
- **SoundFile** – Audio processing  
- **MoviePy** – Video generation  

---

## Installation

```bash
pip install transformers datasets soundfile accelerate -q
pip install pandas pyarrow rustbpe tiktoken -q
pip install moviepy -q
