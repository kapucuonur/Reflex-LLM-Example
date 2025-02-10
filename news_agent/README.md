# AI News Agent using Open AI Swarm and Llama 3.2 running locally

An intelligent research and writing tool built with Reflex, Open AI Swarm and Llama 3.2 running locally using Ollama. This allows users to research a topic and generate a concise, well-structured summary using the advanced AI-powered research and writing agents.

## Features

- Perform in-depth research on any topic
- Utilize multiple AI agents for comprehensive information gathering
- Generate structured, markdown-formatted research outputs
- User-friendly web interface
- Real-time processing with async functionality

## Installation

1. **Clone the repository**:

   ```bash
   git clone
   cd reflex-llm-examples/news_agent
   ```

2. **Set up a virtual environment** (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Pull and Run Llama3.2 using Ollama**:

   ```bash
   # Pull the model
   ollama pull llama3.2
   ```

5. **Run the Reflex application**:  
   Start the Reflex server with:
   ```bash
   reflex run
   ```
