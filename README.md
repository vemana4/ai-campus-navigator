# AI Campus Navigator

[![Python Version](https://img.shields.io/badge/python-3.11%2B-blue)](https://www.python.org) [![Streamlit](https://img.shields.io/badge/UI-Streamlit-red)](https://streamlit.io) [![Gemini AI](https://img.shields.io/badge/AI-Gemini--Flash-orange)](https://deepmind.google/technologies/gemini/)

The AI Campus Navigator is an intelligent, highly interactive routing and pathfinding application explicitly designed to help students, faculty, and visitors seamlessly navigate sprawling, complex university campuses. To achieve millimeter precision, the system natively parses incredibly rich OpenStreetMap (OSM) XML data. It structures this vast geographical information into highly optimized, navigable graph networks using powerful Python libraries like NetworkX and OSMnx, ensuring that every walkway, building entrance, and accessibility ramp is accurately represented in the routing matrix.

Under the hood, the application serves as an advanced sandbox for graph theory and spatial analysis. Users can dynamically toggle between multiple sophisticated graph traversal algorithms to find their optimal route. This includes fundamental approaches like Breadth-First Search (BFS) and Depth-First Search (DFS), up to cost-aware algorithms like Uniform Cost Search (UCS) and the highly optimized, heuristic-driven A* algorithm. This flexibility ensures that the platform can instantly calculate the shortest, fastest, or most accessible paths regardless of campus size or topological complexity.

What truly elevates this application is its seamless integration with the advanced Google Gemini 2.5 Flash AI model. This provides users with a powerful natural language interface, allowing them to ask conversational, context-aware questions about campus locations, historical building information, and optimal paths. Whether a user is looking for the nearest open cafeteria or the most accessible route to a specific lecture hall, the Gemini-powered assistant interprets the request and coordinates with the routing engine to deliver precise, accessible answers through a clean, responsive Streamlit web interface.

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
