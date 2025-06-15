The system uses four agents:

1. **Planner Agent** — Understands user goal and decides agent flow.
2. **Launch Agent** — Fetches next space launch info using SpaceX API.
3. **Weather Agent** — Gets weather details of the launch location using OpenWeatherMap API.
4. **Summary Agent** — Analyzes weather data and summarizes whether the launch might be delayed.

## Tech Stack

- **Google ADK (`google-generativeai[agent]`)**
- **Streamlit UI**
- **Python**
- **OpenWeatherMap API**
- **SpaceX API**
- .env for API keys

 
