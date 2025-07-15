# STABLE_DEFUSSION_MODEL



# 🌍 MultiRAG Vision: Multilingual Text-to-Image Generator

> Generate stunning and hilarious images from text prompts in **any language** using LLM-powered translation and advanced diffusion models.

![demo](https://media.giphy.com/media/l0MYB8Ory7Hqefo9a/giphy.gif)

#🧠 Overview

**MultiRAG Vision** is an AI-powered application that accepts prompts in multiple languages and generates relevant images using text-to-image models like **Stable Diffusion**, **DALL·E**, or **OMINI-Vision**.

It supports:
- 🗣️ Input in over **100+ languages**
- 🎨 High-quality image generation
- 😂 Optional **Funny Prompt Mode** for creativity & humor
- 🤖 Integrated **LangTran** for multilingual understanding

---

#🚀 Features

- 🌐 Multilingual Prompt Support (via LangTran / M2M100 / MarianMT)
- 🖼️ Image Generation with OMINI / Stable Diffusion
- 😂 Funny Prompt Mode (adds humorous twists to input)
- 🧠 Intelligent prompt enhancement via LLMs (GPT, LLaMA, etc.)
- ⚡ Fast and responsive UI with **Gradio** or **Streamlit**



#🛠️ Tech Stack

| Component      | Tool / Model                         |
|----------------|--------------------------------------|
| 🔤 Translation | LangTran / M2M100 / Google Translate |
| 🧠 LLM         | GPT-4 / LLaMA / Gemini                |
| 🎨 T2I Model   | Stable Diffusion / OMINI / DALL·E    |
| 🖥️ Interface   | Streamlit / Gradio                   |
| 🧪 Notebook    | Jupyter (.ipynb)                     |



#🤓 Example Prompts

| Language    | Prompt Input                                      | Output Example                              |
|-------------|---------------------------------------------------|---------------------------------------------|
| English     | A cat playing guitar at a rock concert            | ![img](cat_guitar.png)                      |
| Hindi       | समुद्र के नीचे एक हाथी चाय पी रहा है               | ![img](elephant_tea_underwater.png)         |
| Telugu      | చందమామపై ఒక కుక్క మగధీర పోరాటం చేస్తోంది         | ![img](dog_fight_magadheera.png)            |
| Japanese    | スーツ姿のネコがコーヒーを飲んでいる              | ![img](cat_coffee_suit.png)                 |

---

#🧪 How It Works

1. 🌍 **Input Text Prompt** → (Any language)
2. 🔁 **Translation via LangTran**
3. 🧠 **Prompt Enhancement (Optional)** → via LLM
4. 🎨 **Image Generation** → via T2I models
5. 🎉 **Image Output with Fun Option** (if enabled)

---

#⚙️ Installation

bash
git clone https://github.com/your-username/multirag-vision.git
cd multirag-vision

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py



## 🙌 Acknowledgments

* [Hugging Face Transformers](https://huggingface.co/models)
* [OMINI Vision](https://huggingface.co/OMINI)
* \[LangChain / LangTran]
* [Stability AI](https://stability.ai/)


#🧠 Future Improvements

* 📱 Mobile App Integration
* 🎭 Emotion-based image prompts
* 🗂️ Save image history by user



#💬 Let's Connect

👨‍💻 Created by **[Rapolu Akash](https://www.linkedin.com/in/akash-rapolu-67043a344/)**
📫 Email: [rapoluakash3@gmail.com](mailto:rapoluakash3@gmail.com)
📍 Based in: Hyderabad, India



#⭐️ Give it a Star

If you like this project, please consider giving it a ⭐️ on GitHub to support future updates!


