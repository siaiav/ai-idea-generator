# ai-idea-generator

Generate creative ideas for projects, startups, or content — all powered by **TinyLlama (1.1B)** and **Google Colab**, completely free and open-source.

---

## Overview
**AI Idea Generator** is a lightweight NLP project that uses the open-source **TinyLlama-1.1B-Chat** model to generate original, creative ideas based on a user-defined topic.

It runs entirely in **Google Colab Free Tier**, requires no paid APIs, and demonstrates how small language models can still produce meaningful, human-like text.

---

##  Features
- Simple and intuitive input (just enter your topic)
- Generates creative, original ideas
- Runs on free Colab GPU or CPU
- 100% open-source and beginner-friendly
- Built with the Hugging Face `transformers` library

---
## Tech Stack
- Python 3.12+
- Hugging Face Transformers
- TinyLlama-1.1B-Chat
- Google Colab
- Accelerate

## How to Run
1) Open Google Colab.
2) Create a new notebook
3) Copy the code from ai_idea_generator.ipynb into your Colab
4) Add your Hugging Face Access Token
5) In Colab: Runtime → Change runtime type → GPU → Save
6) Run all cells
7) Type your topic and watch the model create ideas for you!

##  Example Usage
```python
💬 Enter topic: startup in psychology
✨ Generated idea:
A digital platform where users interact with an AI life coach, track mood, and get personalized recommendations.

💬 Enter topic: YouTube channel about IT
✨ Generated idea:
A series of short videos where complex tech topics are explained with humor and visuals.


