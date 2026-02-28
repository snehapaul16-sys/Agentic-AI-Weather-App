# Agentic-AI-Weather-App
✅ VS Code Online IDE running
✅ Python virtual environment activated (you'll see (.venv) in your prompt)
✅ All required packages installed
✅ AWS credentials configured and tested
✅ Claude 4.5 Sonnet access enabled (enabled by default in an AWS facilitated event)
✅ Working directory created (agentic-ai-workshop)

<img width="953" height="274" alt="python streamlit and aws credentials" src="https://github.com/user-attachments/assets/65759353-1cbe-4739-92ce-fcb0ae18b433" />
The NWS provides free weather data through a two-step API process:

• Points API: https://api.weather.gov/points/{lat},{lon}

Takes latitude/longitude coordinates as input
Returns which NWS forecast office covers that location
Provides the specific grid coordinates for that location
Example: Seattle (47.6062,-122.3321) → SEW office, grid 124,67
• Forecast API: https://api.weather.gov/gridpoints/{office}/{gridX},{gridY}/forecast

Uses the office and grid coordinates from the Points API
Returns detailed weather forecast data in JSON format
Example: gridpoints/SEW/124,67/forecast → Seattle's weather data
• Why Two APIs?: The NWS divides the US into a grid system where each forecast office covers specific grid squares. The Points API tells us which office and grid square to use for any location.

How Our Weather Agent Works
Our weather assistant follows a simple 4-step process: User Input → AI Planning → API Calls → AI Summary → Response

<img width="1043" height="111" alt="connected to claude" src="https://github.com/user-attachments/assets/53ba37cb-a2e8-4786-a349-d0b99479bea9" />

<img width="636" height="495" alt="weather app result part1" src="https://github.com/user-attachments/assets/a3b4657d-65a1-4ab2-b24c-31788ed683db" />
<img width="1054" height="576" alt="result part 2" src="https://github.com/user-attachments/assets/5adf3fdc-b10b-450f-91ec-ecb6b7d68c9d" />
<img width="1075" height="696" alt="part3" src="https://github.com/user-attachments/assets/c30603a6-71b7-4984-be2e-59b57cfac030" />
Web version: visually pleasing forntend using streamlit
<img width="620" height="205" alt="web app" src="https://github.com/user-attachments/assets/8a4d56bf-4bf2-4eba-b860-4047f49d9067" />

<img width="930" height="988" alt="description of austin- streamlit" src="https://github.com/user-attachments/assets/81de9466-5aea-4ee6-8c7e-53d27ea0c4f4" />

 <img width="411" height="845" alt="ans-university of austin" src="https://github.com/user-attachments/assets/0dabc708-8d79-4931-a745-12d199eea768" />

  
  

 <img width="450" height="910" alt="frontend display" src="https://github.com/user-attachments/assets/0fe19c48-6cbe-485c-80a4-89af7a4ca175" />
  






