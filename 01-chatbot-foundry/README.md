# 🤖 AI Chatbot with Azure AI Foundry

This project is a basic multi-turn chatbot built using **Azure AI Foundry Prompt Flow** and **GPT-4**.

## 💡 Features

- Prompt Flow UI with user input
- GPT-4-powered completions
- Optional evaluation using Azure Foundry tools
- Deployable as a managed REST endpoint

## 🚀 How to Run

1. Create a new Foundry project: `basic-chatbot`
2. Add `user_input` and `prompt` nodes
3. Use prompt:  
   > You are a helpful assistant. Answer the user input clearly.  
   > {{ user_input }}
4. Test & evaluate grounding
5. Deploy to REST endpoint (optional)

## 🔍 Sample Output

User: "What is Azure AI Foundry?"  
Bot: "Azure AI Foundry is Microsoft’s integrated platform to build, evaluate, and deploy generative AI applications..."

## 📸 Screenshots

![Flow UI](../screenshots/flow-ui.png)
