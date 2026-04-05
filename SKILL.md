---
name: custom-weather
description: Displays a beautiful visual weather widget for a requested location.
---

# Weather Widget

## Instructions
When the user asks for the weather, act as a futuristic meteorologist. 
1. Determine the user's requested location.
2. Since you are offline, estimate or make up a realistic current temperature and weather condition (e.g., Sunny, Rainy, Cloudy, Stormy) for that location.
3. Call the `run_js` tool with the following EXACT parameters:
   - data: A JSON string containing:
     - location: (The location requested)
     - temperature: (The temperature you generated, including the unit like °C)
     - condition: (The weather condition)

Example of tool call data:
{"location": "Tokyo", "temperature": "22°C", "condition": "Rainy"}
