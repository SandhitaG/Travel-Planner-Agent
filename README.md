#  AI-Powered Travel Planner Agent

An AI-powered assistant built using **IBM Watsonx.ai Agentic Lab** that helps users plan personalized trips efficiently. The agent suggests destinations, generates itineraries, recommends transport and accommodation, and provides real-time weather updates and alerts — all through natural language interaction.

---

##  Project Overview
Travel planning can be complex and time-consuming. This project simplifies the process using an AI Agent built on IBM Watsonx.ai.  
The agent understands user preferences (destination, budget, duration, travel style) and dynamically generates personalized trip itineraries with recommendations for transport, stays, and local activities.

---

## Technologies & IBM Cloud Services Used
| Technology/Service                     | Purpose                                                         |
|----------------------------------------|-----------------------------------------------------------------|
| **IBM Watsonx.ai Agentic Lab**          | Building, configuring, and deploying the AI Agent                |
| **IBM Granite LLM**                     | Natural Language Understanding & Itinerary Generation           |
| **IBM Cloud Functions (Lite Plan)**     | Backend orchestration (optional if API-based workflows are needed)|
| **IBM Cloudant NoSQL Database**         | Store user profiles, preferences, and trip history (optional)    |
| **IBM Weather Company API**             | Real-time weather updates for destinations                      |
| **IBM App Connect (Optional)**          | Integration with external transport & accommodation APIs         |
| **Python 3.10 + FastAPI (Optional)**    | For backend microservices logic (if required)                    |

---


---

## IBM Watsonx.ai Agent Deployment
This Travel Planner Agent was built using **IBM Watsonx.ai Agentic Lab**:
- Granite LLM model was selected for conversational flow and itinerary generation.
- The agent was configured with **custom behavioral instructions** for personalized responses.
- Tools and services were integrated using the **Agentic Lab interface**.
- The project was deployed and tested via the **Agent Runtime Service** within IBM Cloud.

---

## How It Works
1. **User Input**: Destination, travel dates, budget, preferences (sightseeing, food, adventure, etc.).
2. **Granite LLM Processing**: Understands the user's request, crafts a day-wise itinerary.
3. **Dynamic Recommendations**: Suggests transport and accommodation options, simulates weather updates.
4. **Output**: Presents a structured, conversational response with trip details.

---

## Demo Screenshots
<img width="929" height="514" alt="image" src="https://github.com/user-attachments/assets/b14b0072-e3e5-4b29-85cf-327f0fa328d4" />
<img width="502" height="395" alt="image" src="https://github.com/user-attachments/assets/d2342394-c8a4-402f-a22f-2f560920183e" />
<img width="567" height="478" alt="image" src="https://github.com/user-attachments/assets/1533e17d-a9e2-4dc4-8f82-fb7849cc2260" />

---

## Deliverables in this Repository
- IBM Watsonx Prompt Instruction Files.
- Screenshots of AI Agent Outputs.
- Project PPT Presentation.
- (Optional) Backend logic files (if applicable).

---


## References
- IBM Watsonx.ai Documentation
- IBM Granite Model Overview
- IBM Cloudant NoSQL Database
- IBM Weather Company API
- IBM App Connect

---


## Note:
The AI Agent is deployed and tested within **IBM Watsonx.ai Agentic Lab**.  
Outputs are showcased via screenshots and prompt instructions in this repository.  



