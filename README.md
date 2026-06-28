# 🎓 Campus Navigation Bot

[![Python Version](https://img.shields.io/badge/python-3.11%2B-blue)](https://www.python.org) [![Streamlit](https://img.shields.io/badge/UI-Streamlit-red)](https://streamlit.io) [![Gemini AI](https://img.shields.io/badge/AI-Gemini--Flash-orange)](https://deepmind.google/technologies/gemini/)

An interactive campus routing and pathfinding application utilizing OpenStreetMap XML data, NetworkX for graph pathfinding algorithms (BFS, DFS, UCS, A*), and Gemini 2.5 Flash for natural language campus assistance.

## 🚀 Key Technologies
- **Routing Engine**: Python, NetworkX, OSMnx
- **Web Framework**: Streamlit
- **AI Engine**: Google GenAI SDK (Gemini 2.5 Flash)
- **Interactive Mapping**: Folium & streamlit-folium

## 📦 Getting Started & Installation
```bash
# Install dependencies
uv sync

# Configure Gemini API Key
mkdir -p .streamlit
echo 'GEMINI_API_KEY = "your-api-key-here"' > .streamlit/secrets.toml

# Run the application
uv run streamlit run app.py
```

## 📜 License
This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.
