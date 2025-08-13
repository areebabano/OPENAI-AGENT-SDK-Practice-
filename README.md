# OPENAI-AGENT-SDK
# 🤖 Agent Runner in Google Colab — Human-Friendly Guide

This mini-project shows how to build **AI Agents** in Google Colab that can perform specific jobs.  
We made:
- **Math Agent** → Solves math questions
- **Cooking Agent** → Suggests recipes from your ingredients

---

## 📚 Key Components — Explained Simply

| Command / Function | What It Does | Real-World Analogy |
|--------------------|--------------|--------------------|
| `!pip install -Uq openai-agents` | Installs the AI agent toolkit. | Installing WhatsApp before you can chat. |
| `nest_asyncio` | Lets async code run in Colab without crashing. | Widening the road so two cars can drive together. |
| `Agent` | An AI helper with a specific job. | Hiring a teacher for only math. |
| `Runner` | Runs your agent and delivers answers. | Pressing "Call" to speak to your helper. |
| `AsyncOpenAI` | Connects to AI API in async mode. | Talking to multiple people at once. |
| `OpenAIChatCompletionsModel` | Decides which AI model to use. | Choosing if your helper speaks like a scientist or chef. |
| `set_tracing_disabled` | Turns off debug logging. | Switching off CCTV for privacy. |
| `userdata.get("GEMINI_API_KEY")` | Safely gets your API key. | Unlocking a vault without showing the key. |
| `input()` | Gets user input. | Asking: “What ingredients do you have?” |

---

## 🛠 How It Works
1. Install `openai-agents`.
2. Allow async code in Colab with `nest_asyncio`.
3. Get your API key from `userdata`.
4. Connect to Gemini AI with `AsyncOpenAI`.
5. Create an **Agent** with a name and role.
6. Use **Runner** to ask questions.
7. Show results to the user.

---
