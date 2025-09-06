📡 RouteLLM Chat App

Inspired by the open-source RouteLLM library
, this app shows how queries can be routed intelligently between different language models for optimal performance and efficiency.

🚀 What is it?

A Streamlit-based chat application that automatically decides which AI model should handle your query. Instead of relying on a single model, it leverages multiple LLMs and dynamically routes tasks to the most suitable one—balancing speed, cost, and quality.

✨ Key Features

💬 Interactive Chat UI – Simple interface for AI conversations

🤖 Smart Model Routing – Queries are sent to the best model depending on complexity

🔀 Hybrid Model Setup – Combines GPT-4 (mini) for complex reasoning with Meta-Llama 3.1 (70B Turbo) for lightweight tasks

📜 Response Transparency – Each answer includes details about which model was used

🗂️ Chat History Tracking – Keeps a full record of messages along with model selections

⚙️ How It Works

Initialization – RouteLLM is configured with two models:

🏋️ Strong model → GPT-4 (mini)

🪶 Efficient model → Meta-Llama 3.1 70B Instruct Turbo

User Input – The user types a query in the chat box.

Routing Logic – RouteLLM evaluates the query’s complexity and selects the optimal model.

Response Generation – The chosen model produces a reply.

Display – The response is shown with the model label for full transparency.

History – The conversation log, including model usage, is stored and displayed.
