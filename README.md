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



![1736180505344](https://github.com/user-attachments/assets/91c6b10a-f188-45f2-9559-77aad135564c)
![1736180505355](https://github.com/user-attachments/assets/0bc55814-1b3d-45bf-b120-6b69212e264f)
![1736180506315](https://github.com/user-attachments/assets/176b2e3d-9c38-444d-9b19-bc93331956a2)
![1736180505360](https://github.com/user-attachments/assets/28d66411-c7b0-4b83-8882-66db50edf8d1)
![1736180506396](https://github.com/user-attachments/assets/9a8747b4-e25b-4d3c-b244-7cc95397e269)
![1736180505421](https://github.com/user-attachments/assets/ba55e3c4-1655-4380-88af-69da6e5f668f)

