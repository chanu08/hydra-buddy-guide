# 🏯 Hydra-Buddy: The Hyderabad Local Guide

> **Week 5 Challenge:** The Local Guide
> **Theme:** Building a context-aware AI that understands local culture and slang.

![License](https://img.shields.io/badge/License-MIT-green) ![Built With](https://img.shields.io/badge/Built%20With-Kiro-purple) ![Context](https://img.shields.io/badge/Context-Aware-orange)

## 📖 Overview
**Hydra-Buddy** is not your average AI assistant. It is a hyper-local guide designed specifically for **Hyderabad, India**.

Unlike generic LLMs that sound robotic and recommend tourist traps, Hydra-Buddy speaks the local **"Dakhni"** dialect (slang) and knows the *real* food spots. It uses a custom knowledge base to differentiate between a "good" biryani and a "commercial" one.

## 🧠 The "Brain" (Custom Context)
The core of this project is the `product.md` file. Instead of hard-coding logic, I created a knowledge base that teaches Kiro:
* **Persona:** Sarcastic, helpful, and uses slang like *"Hau"* (Yes), *"Nakko"* (No), and *"Light lo"* (Ignore it).
* **Anti-Patterns:** Explicit rules to avoid suggesting over-hyped places (e.g., "Do NOT suggest Paradise").
* **Local Wisdom:** Traffic advice specific to Hitech City and Old City.

## ✨ Features
* **🗣️ Local Lingo:** The AI responds with authentic Hyderabadi slang.
* **🥘 Curated Food Guide:** Recommends local favorites like *Bawarchi* and *Ram ki Bandi* instead of generic chains.
* **🚦 Traffic Smarts:** Knows when to avoid specific areas based on local rush hour trends.

## 🛠️ How Kiro Accelerated Development
This project was built in under an hour using **Kiro IDE**.
1.  **Context Injection:** I simply provided the `product.md` file and told Kiro, *"Read this and become this persona."* Kiro instantly adopted the tone without complex prompting.
2.  **UI Generation:** Kiro generated the "Biryani Orange" themed chat interface to match the local vibe.
3.  **Logic Parsing:** Kiro wrote the JavaScript to parse the markdown context and simulate the AI's decision-making process.

*(The full conversation history and context generation are included in the `.kiro` folder of this repository.)*

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/chanu08/hydra-buddy-guide.git](https://github.com/chanu08/hydra-buddy-guide.git)
    ```
2.  **Open the App:**
    * Navigate to the folder.
    * Open `index.html` in your web browser.
3.  **Start Chatting:**
    * Try asking: *"Where should I eat Biryani?"* or *"How is the traffic?"*

## 📂 Project Structure
* `index.html` - The main application and chat interface.
* `product.md` - **The Brain.** Contains the dictionary, rules, and local context.
* `.kiro/` - Contains the Kiro chat history and context files.

---
*Submitted for the AI for Bharat Week 5 Hackathon.*
