## Google Agenet2Agent (A2A Protocol)

### Why A2A?

- Lack of Dynamic Discovery: A client agent must have the network address and API specifications of a remote agent hardcoded. It cannot dynamically discover new agents or find alternatives if a primary agent is unavailable.

- Brittle, Custom Integrations: Each connection requires custom code to translate between the two agents. This creates a "spaghetti architecture" where every new agent added to the system may require N-1 new integrations, a model that is neither scalable nor maintainable.

- Inability to Handle Stateful, Long-Running Tasks: Traditional request-response APIs are ill-suited for the complex, long-running, and often asynchronous tasks that agents perform. There is no standard way to track the progress of a task, handle multi-turn conversations, or receive updates.