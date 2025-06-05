# SmartDine: AI-Powered Restaurant Assistant

SmartDine is an advanced, agentic Retrieval-Augmented Generation (RAG) system designed to simulate a restaurant waiter. Built using LangChain, LangGraph, and OpenAI's GPT models, this project showcases how Generative AI can enhance user experience in daily-life scenarios such as dining and customer support.

---

## 🚀 Project Objective

To build an intelligent, conversational restaurant assistant that:

* Answers customer queries about the menu.
* Recommends dishes based on user input.
* Provides friendly and context-aware responses.
* Retrieves accurate menu-related content from a custom knowledge base.

---

## 📊 Tech Stack

| Technology | Purpose |
| ---------- | ------- |
|            |         |

| **Python**           | Primary language                       |
| -------------------- | -------------------------------------- |
| **LangChain**        | LLM orchestration and tool integration |
| **LangGraph**        | Workflow and agent logic management    |
| **OpenAI GPT**       | Language understanding and generation  |
| **FAISS/ChromaDB**   | Vector store for retrieval             |
| **Jupyter Notebook** | Development & experimentation          |

---

## 💡 Key Features

### 1. Agentic Workflow (LangGraph)

* Multi-step dialogue management
* Branching logic and tool usage decisions

### 2. Retrieval-Augmented Generation (RAG)

* Semantic search of custom documents (e.g., menu, FAQs)
* Injects relevant context into GPT prompt for grounded answers

### 3. Prompt Engineering

* Custom prompts to emulate a friendly, helpful restaurant waiter
* Ensures consistent tone and persona

### 4. Memory & Context Handling

* Maintains conversation history
* Personalized and continuous interactions

---

## 🛍️ Use Case: Daily Restaurant Assistant

**SmartDine** can be used by:

* Restaurants wanting a virtual assistant on their kiosk/web platform
* Food delivery services adding GenAI chat support
* Digital menu providers aiming to add interactivity
* Smart devices (voice assistants) for dining experiences

---

## 📅 Sample Interaction

**User:** What’s special in the vegan section today?

**SmartDine:** Today’s vegan special is the Grilled Tofu Bowl with quinoa, fresh veggies, and house-made tahini dressing. Would you like a recommendation for something spicy?

---

## 🔧 How It Works

1. **User Input:** Text or voice query from customer
2. **Intent Detection:** GPT interprets user intent
3. **Knowledge Retrieval:** Relevant docs retrieved using embeddings
4. **Response Generation:** Context + intent combined and passed to GPT
5. **Output:** Friendly, coherent waiter-style response

---

## 🔢 Setup Instructions

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/smartdine-agent.git
cd smartdine-agent
```

2. **Create virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Add your API keys**

* Create a `.env` file with:

```
OPENAI_API_KEY=your_key_here
```

5. **Run the notebook or script**

```bash
jupyter notebook Agentic_RAG.ipynb
```

---

## 🚀 Future Enhancements

* Voice integration with Whisper or Google STT
* Multilingual support for global audiences
* Integration with live menu APIs
* Real-time user feedback loop

---

## 👥 Author

**Saurabh Kumar**
Generative AI Engineer
[LinkedIn](https://www.linkedin.com/in/saurabh-kumar-7a92a616b/) | [GitHub](https://github.com/Raj-saurabh)

---

## ✅ License

This project is open-source and available under the [MIT License](LICENSE).
