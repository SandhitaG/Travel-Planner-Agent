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
<img width="1919" height="890" alt="image" src="https://github.com/user-attachments/assets/0f020863-7699-4dab-8df2-f8c1692f2237" />

<img width="1919" height="899" alt="image" src="https://github.com/user-attachments/assets/537b0ab1-5cdf-4d83-b13e-972c4cd065c2" />

<img width="1914" height="894" alt="image" src="https://github.com/user-attachments/assets/0f654812-5625-45b6-8ad4-529d5e3b3fd7" />



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



