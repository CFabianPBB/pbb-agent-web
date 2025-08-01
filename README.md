# PBB AI Agent Web Interface

A user-friendly web interface for the Performance-Based Budgeting AI Agent.

## Features

- 📊 Upload government position and budget data
- 🤖 AI-powered program analysis and cost prediction
- 💰 Budget optimization recommendations
- 📈 Interactive dashboard with key insights
- 💬 Chat interface for natural language queries

## Quick Start

1. Upload your Excel files (positions & budgets)
2. Click "Run Full Analysis" 
3. Review insights and download reports

## File Requirements

- **Positions File**: Excel with columns: Department, Division, Position Name
- **Budget File**: Excel with columns: Department, Budget

## Local Development

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Deployment

This app is configured for easy deployment to Render.com with automatic builds from GitHub.