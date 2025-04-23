
🛍️ SalesBot: AI Clothing Store Assistant

SalesBot is a locally-hosted AI chatbot designed to simulate a helpful assistant in a clothing store. It gently encourages customers to explore discounted items, especially hats, and is powered by a local LLM via Ollama.

🚀 Features

1.💬 Natural language interaction with a clothing store assistant

2.🧠 Intelligent responses using a local Ollama model (llama3.2)

3.🛒 Promotes items on sale (e.g., hats at 60% off)

4.🖥️ Simple and beautiful Gradio UI for seamless chatting

📦 How It Works

The chatbot:

Uses a predefined system prompt to behave like a store assistant

Runs a local Ollama model for fast and private LLM inference

Interacts with users through a Gradio interface

🧑‍💻 Getting Started

Prerequisites

1.Python 3.8+

2.Ollama installed and running locally

3.llama3.2 model downloaded in Ollama

Install Dependencies

bash
Copy code

pip install gradio requests

Run the App

Make sure Ollama is running:

bash
Copy code

ollama run llama3.2

Then start the chatbot:

bash
Copy code

python salesbot.ipynb  # Or run all cells in Jupyter
🧠 Example Prompt Handling

👒 If a user says: "I'm looking for a hat", the bot promotes hat sales.

👞 If a user asks about shoes, it mentions they're not on sale but redirects attention to hats.

🚫 If a user mentions belts, the bot clarifies that belts aren't sold and promotes other items.



📄 License
This project is open source and available under the MIT License.
