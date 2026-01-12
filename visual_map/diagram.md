                                   ┌──────────────────────────────┐
                                   │   Finovia Protocol Notes     │
                                   │  (economic primitives)       │
                                   └──────────────┬───────────────┘
                                                  │
                                                  v
                         ┌────────────────────────────────────────────────────┐
                         │      Core System Architecture Primitives           │
                         └────────────────────────────────────────────────────┘
             ┌──────────────────────┬──────────────────────────┬──────────────────────────┐
             v                      v                          v                          v
┌──────────────────────┐  ┌──────────────────────┐  ┌──────────────────────┐  ┌──────────────────────┐
│ Modular API Router    │  │ SQLite Pipeline      │  │ Celery Automation     │  │ POSOVIA UI Mock      │
│ Tree                  │  │ Template             │  │ Boilerplate           │  │ (operator interface) │
└───────────┬───────────┘  └───────────┬──────────┘  └───────────┬──────────┘  └───────────┬──────────┘
            │                          │                          │                          │
            v                          v                          v                          v
      [ Backend ]               [ Pipelines ]               [ Automation ]              [ UI Layer ]
            \___________________________   |   ______________________________/                |
                                            v                                               v
                                   [ Internal Tools & Systems ]                     [ Selenium Starter ]
