# **Founder Flow – Powered by Langflow and GPT Agents**

FounderFlow is an open-source AI startup builder powered by Langflow and a team of collaborative AI agents. Just input a product idea or customer problem—and watch as specialized agents (CEO, Product Manager, Designer, Engineer, Content Creator, and more) coordinate to generate documents, designs, business models, and landing pages.

Built for speed and validation, this tool simulates an entire startup team to help you ideate, prototype, and launch faster—with market-fit baked in.


## **What This Project Does**
[![Watch the video](https://img.youtube.com/vi/IG7cDP48NU4/maxresdefault.jpg)](https://youtu.be/IG7cDP48NU4)


## 🔧 What it does:
* Uses AI agents connected in Langflow to simulate a full startup team
* Accepts a simple product idea or customer pain point as input

## Generates outputs like:
* Product Requirements Document (PRD)
* User Research Report
* Design Brief
* Landing page
* Business Model Canvas
* Competitor Analysis
* Landing Page with real copy and structure

Outputs are saved into markdown documents or assets (like a landing page).

## 🚀 Why use it:
* Ideal for solo founders, indie hackers, and innovators
* Rapid prototyping and validation loop
* Save hundreds of hours across research, strategy, and product design
* Showcases the power of Langflow for multi-agent orchestration

🧠 No coding required. Just plug in your OpenAI & Tavily (free) key and get building.

---

## **What You’ll Get**

| Asset                                | Description                                                                       |
| --------------------------------------- | --------------------------------------------------------------------------------- |
| **Company Strategy**                    | High-level plan created by the CEO agent to guide all departments.                |
| **Product Requirements Document (PRD)** | A detailed breakdown of the features and user needs for the product.              |
| **User Research Plan & Report**         | A strategy for talking to real users and summarizing findings.                    |
| **Design Brief & Wireframes**           | A short document explaining what needs to be designed, for whom, and why.          |
| **Marketing Strategy**                 | A plan for how to market the product.         
| **Content Pack**                       | A collection of content for the product.
| **Landing Page Copy**                   | Headlines, body copy, and CTAs for a compelling landing page.                     |
| **Competitor Benchmark**                | A brief report comparing your idea to other players in the market.                |
| **Business Model**                      | How the product will make money, who the users are, and what’s needed to operate. |
| **Initial Website/App Design Image**    | A mockup of your product design using DALL·E or design instructions.              |
| **Virtual User Persona Prompts**                | Custom ChatGPT prompts tailored to different users of the product.                |
| **Sales Playbook**                      | Recommended Sales Process
| **Idea Evaluation**                      | Evaluation of the idea
---

## **Examples**

Some example projects are inside the `./examples` folder.

An AI article summarizer app idea is in the `ai_summarizer` folder
An product manager toolkit app idea is in the `product_manager_toolkit` folder

## **How to Use This Project**

### 1. **Install Langflow**

Follow the [Langflow installation guide](https://github.com/langflow-ai/langflow)

Once running, open your browser to:
`http://localhost:7860`

---

### 2. **Get Your OpenAI API Key**

1. Go to [https://platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys)
2. Sign in and click **“Create API key”**
3. Copy the key

### 3. **Get Your Free Tavily Search API Key**

Currently Tavily gives you 1,000 API credits / month

1. Go to [https://tavily.com/](https://tavily.com/)
2. Login or signup and create an API key
3. Copy the key

Now Langflow can use search to do competitor research

---

### 4. **Add Your API Key to Langflow**

Inside Langflow:

* Click the user profile in the top right and select the **gear icon** (Settings) in the sidebar
* Select **"Global Variables"**
* Click **Add New**
* Select **Credential** and enter `OPENAI_API_KEY` as the variable name and your OpenAI API Key as the value
* Click **Add New**
* Select **Credential** and enter `TAVILY_SEARCH_API_KEY` as the variable name and your Tavily API Key as the value

Now Langflow can use GPT-4 and search to run the agents.

---

### 5. **Import the Flow**

Import the Langflow JSON file provided in this repo (e.g. `Product AI Startup.json`):

* Click **“Import Flow”**
* Select the file and open it

You should now see the entire agent-based system ready to use.

---

### 5. **Start the Process**

* Click the **Playground** button in the top right and enter your **product idea** or a **problem users face** in the chat and press **Send**
* Agents will generate documents one by one in your directory and output some results in the chat window. Each one is designed to guide the next agent.

---

## **What You Can Do With It**

* Validate your startup ideas faster
* Use it as an internal builder or AI hackathon project
* Customize the flows to build more advanced agent chains

