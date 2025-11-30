# n8n Agents 

This repository contains a collection of workflows, configurations, and reference implementations designed to help you build **Agentic AI systems using n8n**. These files demonstrate how to automate processes, integrate LLMs, and create intelligent agents capable of handling business tasks.

---

## 📁 Repository Structure

Below is a general outline of the types of files included (exact filenames depend on your upload):

### **1. Workflow Files**

Workflows that demonstrate:

* Automated email responses
* RAG-based query answering
* Voice assistant setup
* Tool-based LLM execution
* Multi-step reasoning flows

### **2. Agent Configurations**

Configuration files for:

* Model setup (OpenAI, Cohere, Google Gemini)
* Tool definitions
* Node connections
* Function calling logic

### **3. Prompt Templates**

Reusable prompts for:

* Email writing
* Customer interaction
* RAG queries
* Planning and reasoning

### **4. Support Files**

Additional helper files, including:

* Test data
* Mock webpage text
* Google Sheet sample datasets

---

## 🚀 Features

* Ready-to-use n8n workflow templates
* Modular and scalable agent structure
* Support for LLM tool calling
* Fully customizable nodes and functions
* Example setups for email automation, RAG, and AI assistants

---

## 🧠 What You Can Build with These Files

Using this repo, you can quickly build:

* **AI Email Agent** that reads → understands → drafts → replies.
* **RAG Agent** to answer questions using your documents.
* **Voice Assistant Backend** for any webpage or product.
* **Automation Pipelines** for business tasks.
* **Multi-agent systems** using LLM + n8n.

---

## 📦 Requirements

To fully use these workflows, ensure you have:

* n8n (self-hosted or cloud)
* API access to one of the following:

  * OpenAI
  * Cohere
  * Google Gemini
* Google Sheets access (if using workflow-integrated sheets)

---

## 🛠 Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/n8n-agents
   ```

2. Import the workflow files into your n8n instance.

3. Add API credentials under **n8n → Credentials**.

4. Connect nodes according to the workflow.

5. Run or schedule the flows.

---

## 📘 Webhook Agent

This repository now includes a **Webhook-based Agent** built using n8n. This agent allows external apps, websites, or services to trigger automated LLM workflows via a public webhook.

### 🔗 Live Webhook URL

```
[YOUR_WEBHOOK_URL_HERE](https://ayurvedic-sage-chat.lovable.app)
```

(Replace with your actual webhook link)

### 📄 Workflow JSON File

The webhook workflow is included here:
``

### 🧠 What This Workflow Does

* Listens for incoming webhook requests
* Reads and validates the incoming data
* Passes data into LLM (OpenAI / Cohere / Gemini)
* Generates a structured or natural language response
* Sends automated replies or triggers other flows
* Can be used for chatbots, form submissions, voice apps, or automation

### 📌 Key Features

* Fast, real-time processing
* Fully customizable node pipeline
* Can integrate with Sheets, Email, APIs, or databases
* Supports Agentic reasoning and tool-calling

### 📘 Documentation

Each workflow file is self-contained and documented inside n8n.
Refer to node descriptions and comments in the workflow for understanding logic. Additional documentation for the webhook agent is included inside the JSON workflow.

---

## 🤝 Contributing

Feel free to:

* Add more agent templates
* Improve workflow logic
* Create issues or suggestions

---

## 📬 Contact

If you want help building an advanced n8n agentic system, feel free to reach out.

---

### ⭐ If you find this useful, don’t forget to star the repo!
