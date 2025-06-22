## Google Agenet2Agent (A2A Protocol)

### Why A2A?

As agents become more specialized, tasks like planning an international trip require coordinating multiple agents (e.g., for flights, hotels, tours). Without a common protocol, this creates significant engineering hurdles for several key reasons:

    - Lack of Dynamic Discovery: A client agent cannot dynamically find the best service for a job or discover alternatives if a primary agent fails, as connections are often hardcoded.

    - Brittle, Custom Integrations: Each connection requires custom code, leading to a complex architecture that is difficult to scale and maintain.

    - Poor Support for Agentic Workflows: Traditional request-response APIs are ill-suited for the long-running, asynchronous, and multi-turn conversations that are common in agent interactions.

[a2a-actors.png]()