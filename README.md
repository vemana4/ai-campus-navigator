# AI Campus Navigator

[![Python Version](https://img.shields.io/badge/python-3.11%2B-blue)](https://www.python.org) [![Streamlit](https://img.shields.io/badge/UI-Streamlit-red)](https://streamlit.io) [![Gemini AI](https://img.shields.io/badge/AI-Gemini--Flash-orange)](https://deepmind.google/technologies/gemini/)

The AI Campus Navigator is an intelligent routing and interactive pathfinding application designed to help students, staff, and visitors seamlessly navigate complex university campuses. By parsing rich OpenStreetMap XML data and structuring it into navigable networks using NetworkX and OSMnx, the application provides precise, turn-by-turn directions. Users can leverage multiple graph traversal algorithms, including Breadth-First Search (BFS), Depth-First Search (DFS), Uniform Cost Search (UCS), and the highly optimized A* algorithm, to find the most efficient routes. Furthermore, the application integrates the advanced Google Gemini 2.5 Flash AI model, offering users a natural language interface where they can ask conversational questions about campus locations, buildings, and optimal paths, all presented in a clean, user-friendly Streamlit web interface.

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
