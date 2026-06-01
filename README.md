                    User
                      |
                 API Gateway
                      |
              Agent Orchestrator
                      |
    ------------------------------------------------
    |         |         |         |       |        |
 Planner  Research  Architect  Coder  Reviewer  Tester
    |         |         |         |       |        |
    ------------------------------------------------
                      |
                 Kafka Event Bus
                      |
     -----------------------------------------
     |                |                     |
 PostgreSQL         Redis                Qdrant
     |                |                     |
 Metadata      Shared Memory         Knowledge Base
                      |
                LLM Provider
