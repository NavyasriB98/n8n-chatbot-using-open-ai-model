# n8n-chatbot-using-open-ai-model
AI Chatbot Workflow with OpenAI and Memory
This project sets up a basic AI chatbot using OpenAI's language model and a memory module to maintain conversation context. The workflow is built in a visual environment and uses trigger-based flow to handle incoming messages, process them with an AI model, and retain relevant memory.

**Workflow overview:**
When Chat Message Received
         ↓
     AI Agent
   ↙       ↘
Model     Memory

**nodes Description**
When Chat Message Received
Type: Trigger Node

Function: Activates the chatbot when a message is received.

AI Agent
Type: Main Processing Node

Function: Acts as the brain of the chatbot.

Takes user inputs.

Uses an LLM (GPT-mini via OpenAI) to generate responses.

Interacts with memory for contextual awareness.

OpenAI Chat Model
Model Used: gpt-mini

Function: Powers the chatbot's language understanding and generation capabilities.

Simple Memory
Type: Memory Module

Function: Stores conversational context within the configured context length.

![image](https://github.com/user-attachments/assets/5ef4117d-d04d-4ed3-8ccb-fb396caa77aa)


