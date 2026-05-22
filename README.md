This is a command-line AI assistance specfically designed to be a Gardening assisitant.
It features layered guardrails to keep conversations safe and orderly according to defined topic. However topic can be dynamically changed if desired so AI can assist outside of gardening parameters.
The Chatbot uses embedding-based topic validation with Ada-002, filtering responses before replying. 
The chatbot maintains conversation history for natural multi-turn interactions and uses Azure OpenAI for chat generation, while gracefully handling deployment and configuration issues so the app stays usable even when services are misconfigured.


