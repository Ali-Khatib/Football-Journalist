# AI Football Journalist

AI Football Journalist is an AI-powered sports reporting project that generates professional football match reports from real ESPN match data.

The system fetches recent completed matches, extracts key events, adds competition context, identifies standout players, and uses Groq LLMs to write polished football articles through a Gradio interface.

## Features

- Fetches recent completed football matches
- Supports major European leagues and the UEFA Champions League
- Extracts goals, cards, substitutions, and match status
- Adds league table or knockout-stage context
- Identifies standout players
- Generates professional sports articles using Groq
- Provides an interactive Gradio interface

## Tech Stack

- Python
- Gradio
- Groq API
- LangGraph
- LangChain
- ESPN API
- Requests
- BeautifulSoup4
- Trafilatura

## Installation

```bash
pip install -r requirements.txt
