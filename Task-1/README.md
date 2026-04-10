# 🚀 GenAI Prompt Templates using LangChain

## 📌 Overview

This project demonstrates how to build modular, reusable, and scalable prompt systems using LangChain.
It replaces hardcoded prompts with structured templates and introduces advanced prompt engineering techniques.

The notebook covers multiple real-world prompt design patterns useful for Generative AI applications.


---

## 🧠 Features

✅ Replace hardcoded prompts with reusable templates

✅ Multi-input dynamic prompt generation

✅ Prompt variation engine (teaching, interview, storytelling)

✅ Chat-based prompt structuring using system & human roles

✅ Clean and modular code design



---

## 🛠️ Tech Stack

Python 🐍

LangChain

Prompt Engineering



---

## ⚙️ Installation

pip install langchain langchain-core


---

## 📖 Tasks Explained

🔹 Task 1: Replace Hardcoded Prompts

Uses PromptTemplate

Eliminates f-strings

Creates reusable prompt functions


PromptTemplate(
    input_variables=["topic"],
    template="Explain {topic} in simple terms for beginners"
)


---

🔹 Task 2: Multi-Input Prompt System

Handles multiple inputs dynamically

Customizes prompts based on:

Topic

Audience

Tone



Example:

Explain AI for beginners in a friendly tone


---

🔹 Task 3: Prompt Variations Engine

Generates prompts in different styles:

Teaching

Interview

Storytelling



prompt_variations = {
    "teaching": "...",
    "interview": "...",
    "storytelling": "..."
}



---

🔹 Task 4: ChatPromptTemplate System

Uses structured chat prompts

Separates:

System messages

Human messages



This is useful for building chatbots and conversational AI systems.


---

## 🎯 Use Cases

AI Chatbots 🤖

Educational tools 📚

Content generation ✍️

Interview preparation systems 🎤

Story generation engines 📖

---

## 🚀 Why This Project?

This project helps you understand:

How to scale prompt engineering

How to avoid hardcoding

How to build production-ready GenAI systems



---
