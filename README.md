### AI Travel Planning Web Application using LangGraph
This project showcases a real-world Multi-Agent AI system powered by LangGraph.
The system leverages four specialized AI agents that collaborate to generate a complete travel itinerary automatically.


## Core Functionality

✈️ Flight Search Agent
🏨 Hotel Search Agent
🗓️ Itinerary Planning Agent
🧠 Memory using PostgreSQL
🌐 Real-time API Integration
💻 Streamlit Web Interface

## Frameworks & Tools
-LangGraph
-LangChain
-Groq
-Llama 3.3 70B
-PostgreSQL
-Streamlit
-Tavily API
-AviationStack API

#Step 1: Create Python Environment

Open the terminal inside the project folder and run:
python -m venv langgraph_env3

Now activate the environment:
Windows:  langgraph_env3\Scripts\activate

#Step 2: Install Dependencies

Run the following command:

AI-Travel-Planning-System-using-LangGraph
/README.md
codewithaarohi
codewithaarohi
update
ff6c064
 · 
last month
AI-Travel-Planning-System-using-LangGraph
/README.md

Preview

Code

Blame
156 lines (84 loc) · 2.63 KB
AI Travel Planning System using LangGraph
This project is a Real-World Multi-Agent AI System built using LangGraph.

The system uses 4 AI agents that work together to plan a complete trip automatically.

Features
✈️ Flight Search Agent
🏨 Hotel Search Agent
🗓️ Itinerary Planning Agent
🤖 Final Response Agent
🧠 Memory using PostgreSQL
🌐 Real-time API Integration
💻 Streamlit Web Interface
Tech Stack
LangGraph
LangChain
Groq
Llama 3.3 70B
PostgreSQL
Streamlit
Tavily API
AviationStack API
Step 1: Create Python Environment
Open the terminal inside the project folder and run:

	python -m venv langgraph_env3
Now activate the environment:

Windows
	langgraph_env3\Scripts\activate
YouTube Tuturial (Hindi) - https://youtu.be/ctHby5vhDqg
YouTube Tuturial (English) - https://youtu.be/_5XF5CCnbDk
Step 2: Install Dependencies
Run the following command:

	pip install langgraph langchain langchain-openai langchain-groq langchain-community 
  pip install langchain-tavily psycopg[binary] psycopg_pool python-dotenv tavily-python requests streamlit
  pip install -U "psycopg[binary,pool]"  langgraph-checkpoint-postgres

