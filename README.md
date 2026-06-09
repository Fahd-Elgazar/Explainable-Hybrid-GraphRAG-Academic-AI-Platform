### System Architecture

The Explainable Hybrid GraphRAG Academic AI Platform follows a layered architecture designed to provide grounded, explainable, and academically verified responses. A React frontend communicates with a Node.js orchestration layer that coordinates intelligent routing, hybrid retrieval, conversation memory, and response generation.

The Brain Router analyzes incoming queries and dynamically selects the most appropriate execution path. Information is retrieved from both a Neo4j Knowledge Graph and a Qdrant Vector Database, then merged through an Evidence Fusion Engine to combine structural and semantic knowledge.

Response generation is performed using Gemini as the primary large language model, while a reliability layer provides automatic failover to local Ollama models during service degradation. Conversation memory, decision-support services, and observability components work together to deliver accurate, explainable, and resilient academic assistance.
