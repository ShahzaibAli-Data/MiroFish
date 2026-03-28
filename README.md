Here is a clear English translation of your README content focused on setup and usage.

---

MiroFish
A simple and universal swarm intelligence engine that predicts anything

---

Project Overview

MiroFish is a next generation AI prediction engine based on multi agent technology. It extracts seed information from the real world such as breaking news, policy drafts, and financial signals. It then builds a high fidelity parallel digital world.

Inside this world, thousands of agents with independent personalities, long term memory, and behavior logic interact and evolve. You can inject variables from a top level view and simulate future outcomes with precision.

You only need to:
Upload seed material such as reports or stories, and describe your prediction goal in natural language

MiroFish will return:
A detailed prediction report and an interactive digital simulation world

---

Vision

MiroFish aims to create a collective intelligence mirror of reality by capturing how individual interactions lead to group behavior.

At macro level:
A testing lab for decision makers to simulate policies and strategies without risk

At micro level:
A creative sandbox for individuals to explore ideas, stories, and scenarios

---

Workflow

1. Graph construction
   Extract real world data, inject memory, build GraphRAG

2. Environment setup
   Extract relationships, create agents, configure simulation parameters

3. Simulation
   Run parallel simulations, interpret prediction goals, update memory dynamically

4. Report generation
   ReportAgent interacts deeply with the simulation to generate insights

5. Interaction
   Talk with agents or the ReportAgent

---

Quick Start

Method 1. Source Code Deployment

Requirements

* Node.js version 18 or higher
* Python version 3.11 to 3.12
* uv package manager

Check installation:

node -v
python --version
uv --version

---

Step 1. Configure environment variables

Copy the example file:

cp .env.example .env

Edit the .env file and add API keys

Required variables:

LLM_API_KEY=your_api_key
LLM_BASE_URL=[https://dashscope.aliyuncs.com/compatible-mode/v1](https://dashscope.aliyuncs.com/compatible-mode/v1)
LLM_MODEL_NAME=qwen-plus

ZEP_API_KEY=your_zep_api_key

Notes:
You can use any LLM API compatible with OpenAI SDK
Qwen Plus is recommended
Cost can be high, start with less than 40 simulation rounds

---

Step 2. Install dependencies

Install everything:

npm run setup:all

Or step by step:

npm run setup
npm run setup:backend

---

Step 3. Start the services

Run both frontend and backend:

npm run dev

Access:

Frontend
[http://localhost:3000](http://localhost:3000)

Backend API
[http://localhost:5001](http://localhost:5001)

Run separately if needed:

npm run backend
npm run frontend

---

Method 2. Docker Deployment

Step 1. Configure environment variables

cp .env.example .env

Step 2. Start with Docker

docker compose up -d

Ports:

3000 for frontend
5001 for backend

---

Online Demo

You can try the demo here:
[https://666ghj.github.io/mirofish-demo/](https://666ghj.github.io/mirofish-demo/)

---

That is the full setup in clean English. If you want, I can simplify it into a step by step checklist you can follow directly.
