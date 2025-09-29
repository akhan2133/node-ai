# NodeAI – Multi-Vendor Robotics Orchestration

NodeAI is building a unified dashboard and orchestration engine for fleets of robots across multiple vendors and environments.
Today, most integration windows are vendor-locked or require sending sensitive data overseas. NodeAI provides a vendor-agnostic, on-premise solution that helps vendors deploy robotics faster, safer, and more reliably.  

### Key Highlights
- **API Gateway + Adapters:** Single entrypoint with clean contracts; plug-in adapters for ROS, simulators, and vendor SDKs.
- **Planner Core:** Mission and policy engine that coordinates multiple robots/vendors together.
- **On-Prem Containers:** Each service ships as a container; customers keep their data local.
- **Extensible:** New vendors can be integrated by adding a lightweight adapter, without touching core logic.

### Architecture (at a glance)
- **Frontend:** Calls NodeAI through a typed API client.
- **API Gateway:** Exposes schemas/contracts (OpenAPI).
- **Planner:** Core domain logic for missions/policies.
- **Adapters:** ROS and simulation connectors, extendable for new vendors.
- **Deployment:** Per-service Dockerfiles, orchestrated via docker-compose.

### Access
The full implementation is hosted in a **private GitHub repository**.  
- I can provide a **demo** on request.
- Please feel free to reach out if you'd like to discuss the details or see the project in action.  

### Contact
📧 aka306@sfu.ca  
🔗 [LinkedIn](https://www.linkedin.com/in/asfand-khan-a03888275/)  
