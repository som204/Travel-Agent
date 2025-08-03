🤖 AI-Powered Travel Planner Agent
<p align="center">
<img src="https://www.google.com/search?q=https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExb21qZzNqZWRobzJ4bnp0dG5odWx6cWJzb2wzZDJzY3lqZ3NqYjZpZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/13GIgrvDY3I9sQ/giphy.gif" alt="AI Travel Planner in action" width="700"/>
</p>

<p align="center">
<em>Tired of juggling a dozen tabs to plan a trip? This AI agent turns hours of stressful planning into a simple, two-minute conversation.</em>
</p>

<p align="center">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/IBM%2520Cloud-Lite%2520Plan-blue" alt="IBM Cloud">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/IBM%2520watsonx.ai-Agent%2520Lab-purple" alt="watsonx.ai">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Model-IBM%2520Granite-informational" alt="IBM Granite">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Python-3.11-blue%3Flogo%3Dpython%26logoColor%3Dwhite" alt="Python">
</p>

📋 Table of Contents
The Problem

The Solution

Key Features

How It Works

Technology Stack

Getting Started

Future Scope

Author

🎯 The Problem
Planning a trip is a fragmented and frustrating experience. Travelers have to manually:

Search across numerous websites for flights, hotels, and activities.

Juggle budgets and conflicting information.

Struggle to build a cohesive plan that makes sense.

The result? Wasted time and unnecessary stress.

💡 The Solution
This AI Travel Planner Agent is a conversational assistant built on IBM watsonx.ai. It leverages a powerful IBM Granite foundation model to act as an intelligent agent that can:

Understand a user's travel request through natural language.

Reason about the necessary steps and tools required to fulfill the request.

Act by connecting to real-time travel APIs to gather live data.

Synthesize all the gathered information into a complete, personalized, and actionable itinerary.

✨ Key Features
🗣️ Conversational Planning: Simply tell the agent what you want, like "Plan a 5-day adventure trip to Costa Rica for under $1500."

✈️ Real-Time Data: Connects to live APIs for up-to-date flight and accommodation pricing and availability.

🗺️ Dynamic Itinerary Generation: Creates detailed day-by-day plans, including suggested activities, tours, and dining options.

❤️ Deep Personalization: Tailors every recommendation to your specific budget, interests (e.g., "art lover," "foodie," "hiker"), and travel style.

⚙️ How It Works
The agent uses a reasoning framework to intelligently orchestrate a series of tasks. Instead of just generating text, it can decide which tool to use, call that tool, and use the output to inform its next step.

graph TD
    A[User] -- "I want to go to Paris" --> B(IBM watsonx Assistant);
    B -- Sends User Request --> C{IBM Agent Lab};
    C -- "How do I plan this?" --> D[IBM Granite LLM];
    D -- "You need flights and hotels. Use your tools." --> C;
    C -- Calls Tool --> E(Flight API);
    C -- Calls Tool --> F(Hotel API);
    E -- Returns Flight Data --> C;
    F -- Returns Hotel Data --> C;
    C -- "Here is the data. Create an itinerary." --> D;
    D -- Generates Itinerary --> C;
    C -- Sends Final Plan --> B;
    B -- Displays to --> A[User];

🛠️ Technology Stack
Component

Technology

Purpose

Cloud Platform

<img src="https://www.google.com/search?q=https://img.shields.io/badge/IBM%2520Cloud-000000%3Fstyle%3Dfor-the-badge%26logo%3Dibm%26logoColor%3Dblue" />

Hosting the entire infrastructure.

AI Environment

<img src="https://www.google.com/search?q=https://img.shields.io/badge/watsonx.ai-000000%3Fstyle%3Dfor-the-badge%26logo%3Dibm-watson%26logoColor%3Dpurple" />

Building, testing, and deploying the agent.

Core Logic

IBM Agent Lab

Orchestrating the agent's reasoning and actions.

Foundation Model

IBM Granite

Powering the agent's NLU and generation.

Conversational Front-End

IBM watsonx Assistant

Providing the user-facing chat interface.

🏁 Getting Started
This agent is deployed on IBM Cloud. To interact with it:

Access the Front-End: Navigate to the chatbot application URL.

Start a Conversation: Describe the trip you want to plan. Be as specific as you like! Mention your destination, budget, duration, interests, and who you're traveling with.

Review Your Plan: The agent will process your request, gather live data, and present you with a personalized itinerary.

🔮 Future Scope
The journey doesn't end here! Future enhancements could include:

Direct Booking: Integrate with payment gateways to book flights and hotels directly.

In-Trip Assistance: Provide real-time alerts for flight delays, gate changes, and weather updates.

Visual Itineraries: Generate a map-based view of the travel plan.

Voice Integration: Enable hands-free planning through a voice-activated assistant.

👤 Author
Som Prasad
