1. **Event-Driven Computing:**
    
    - Serverless architecture responds to events, automatically triggering the execution of functions in response to specific events or requests.
2. **No Server Management:**
    
    - Eliminates the need for managing servers. Cloud providers handle infrastructure, scaling, and maintenance, allowing developers to focus on code.
3. **Scalability:**
    
    - Scales dynamically based on demand. Resources automatically scale up or down, ensuring efficient utilization and cost-effectiveness.
4. **Statelessness:**
    
    - Functions are stateless and ephemeral, promoting simplicity and ease of scaling. State is typically managed externally, often using cloud-based storage services.
5. **Microservices:**
    
    - Encourages a [[Microservices|microservices]] architecture, where applications are composed of small, independent functions that communicate through [[API|APIs]].
6. **Cost Efficiency:**
    
    - Billed based on actual usage, reducing costs during periods of inactivity. Resource allocation is automatic and tied to execution time.
7. **Fast Deployment:**
    
    - Rapid deployment of functions allows for quick development cycles and easier updates, fostering agility and faster time-to-market.
8. **Event Sources:**
    
    - Integrates with various event sources, such as databases, storage, or APIs, allowing seamless connectivity with different services within the ecosystem.
9. **Security Responsibilities:**
    
    - Cloud providers handle underlying security, but developers must implement security measures within the application code and configurations.
10. **Use Cases:**
    
    - Ideal for event-driven applications, microservices, and scenarios with variable workloads. Commonly used for web applications, APIs, and backend services.
11. **Cold Start Latency:**
    
    - Functions may experience initial latency (cold start) when triggered for the first time or after being idle, impacting response times.
12. **Monitoring and Logging:**
    
    - Requires robust monitoring and logging tools for tracking function execution, performance, and identifying potential issues.