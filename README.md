# food-safety-analyzer
Designed a robust AI framework to analyze food ingredients and nutritional values, ensuring safety and healthiness for consumers. The system evaluates food products meticulously and provides actionable insights based on ingredient safety and nutritional content.

How It Works:

Input:
The system takes an image of food ingredient labels or nutritional content. Using Gemini API ('gemini-1.5-flash'), the text data is extracted and encoded into Base64 format for further processing.

Framework:
The extracted information is passed to a set of AI agents built using the CrewAI framework. These agents collaborate to analyze the data in real-time.

Agent Roles:
Ingredient Safety Analysis Agent:
Analyzes every ingredient for harmful substances or violations of food safety regulations.

Nutritional Content Analysis Agent:
Assesses the nutritional values to ensure alignment with healthy dietary guidelines and user-specific needs.

Decision Agent:
Synthesizes the insights from the other agents to deliver:
A verdict (Safe, Unsafe, or Caution)
A rating (out of 10)
A concise summary of findings

Tools:
The agents use WebsiteSearchTool and ScrapeWebsiteTool to dynamically search for relevant information on official and non-official websites, such as allergens, additives, or nutritional benchmarks.

Structured Output:
To ensure consistency, I’ve used Pydantic models to structure the agents' output as JSON. 

Impact:
This project demonstrates the power of AI in promoting informed decisions about food safety and nutrition. By combining intelligent agents, real-time data extraction, and robust tools, we can empower users to make healthier choices effortlessly.

Mentioned the input/output below

 

I’d love to hear your thoughts or suggestions on how to take this project even further! 🙂 

