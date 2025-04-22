# RestroBot
RestroBot : A Capstone Project for Google GenAI course
In this project, I developed RestroBot, a conversational agent system designed to facilitate natural language ordering for food from menu. The solution integrates three key Generative AI capabilities:

Conversational Agent (GenAI Capability #1) – A natural language interface that allows users to interact with the system to place orders or ask questions, simulating a human-like concierge experience.

Function Calling (GenAI Capability #2) – The bot utilizes function calling to interact with structured tools like the live food menu and back-end ordering systems, enabling dynamic and contextual responses based on user input.

Grounded Search Methodology (GenAI Capability #3) – RestoBot uses a grounding technique to ensure accurate and relevant answers to user queries by referencing a well-defined menu and operational constraints.

RestroBot offers a looping chat interface for customers, allowing ongoing interaction where users can place, modify, or inquire about order seamlessly. The system is structured as a graph of nodes representing various functional parts—such as the live resturant menu and a back-room ordering system—to simulate real-world workflow integration.

IMPORTANT!
The app built in this notebook takes user input using a text box (Python's input). These are commented-out to ensure that you can use the Run all feature without interruption. Keep an eye out for the steps where you need to uncomment the .invoke(...) calls in order to interact with the app.
