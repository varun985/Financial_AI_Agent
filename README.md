# Phi Data Financial Analyst AI Agent

## Overview
A sophisticated AI-powered financial analysis tool built using the Phi Data framework that combines web search capabilities with financial data analysis. This project implements multiple AI agents working in tandem to provide comprehensive financial insights and market research.

## Features

### Multi-Agent Architecture
- **Finance AI Agent**: Specialized in financial analysis using YFinance tools
  - Real-time stock price tracking
  - Analyst recommendations analysis
  - Stock fundamentals evaluation
  - Company news monitoring
  
- **Web Search Agent**: Provides broader market context and research
  - Web scraping capabilities using DuckDuckGo
  - Source attribution for all information
  - Real-time information gathering

### Interactive Playground Interface
- Local development server with interactive chat interface
- Access through PHI Data playground at localhost
- Real-time streaming responses
- Markdown formatting support
- Visual data presentation using tables

## Technical Stack
- **Framework**: Phi Data
- **Models**: Groq (llama3-groq-70b-8192-tool-use-preview)
- **Tools Integration**:
  - YFinanceTools
  - DuckDuckGo Search
- **Environment Management**: dotenv for secure configuration

## Setup and Configuration
1. Clone the repository
2. Install required dependencies
3. Set up environment variables:
   - `PHI_API_KEY`
   - `OPENAI_API_KEY`
4. Run the playground server

## Usage
```bash
# Start the playground server
python playground.py
Access the interactive interface at localhost:8501 to:

Query financial data
Get stock analysis
Research market trends
View company news
Features
Real-time stock data analysis
Comprehensive market research
Interactive chat interface
Automated financial reporting
Source-attributed information
Table-formatted data presentation
Development
The project is structured with modular agents that can be extended or modified:

Add new tools to existing agents
Create new specialized agents
Customize agent instructions
Modify response formatting
Dependencies
phi.agent
phi.tools
openai
python-dotenv
streamlit (for playground)
Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
MIT
