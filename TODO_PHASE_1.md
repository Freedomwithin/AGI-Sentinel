flowchart TD
    A[User / Mission File] --> B[swarm_factory_v4.py]
    B --> C[sovereign_swarm_engine_v4.py]
    C --> D[memories/swarms-v4/<swarm>/shared_blackboard.json]
    D --> E[maya_supervisor.py (hourly audit)]
    D --> F[swarm_watcher.py (detects completion)]
    F --> G[meta_coordinator_v4.py]
    G --> H[VAULT/ledgers/<pillar>_ledger.json]
    H --> I[Future swarms load pillar truths]
    C --> J[Reports: final_reports_jonathon/]
    C --> K[Logs: logs/swarm_*.out]
    
    subgraph LLM Gateway
        L[llm_gateway_v4.py] --> M[Groq 70B (primary)]
        L --> N[Groq 8B (fallback)]
    end
    
    C <--> L
    G <--> L
    E <--> L