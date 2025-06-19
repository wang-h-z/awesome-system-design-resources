# Systems Design Notes

## Scalability

### How can a system grow? 

- More **Users**
- More **Features**
- More **Data**
- More **Complexity**
- More **Geopgraphies**

### How to scale a system? 

1. Vertical Scaling (Scale Up) -> Add more power to exisiting systems (add more RAM, faster CPU or additional storage)

2. Horizontal Scaling (Scale Out) -> Add more machines to your system to spread the workload across multipke servers

3. Load Balancing -> Distribute traffic across multiple servers

4. Caching -> Store frequently accessd data in-memory (Like RAM)

5. Content Delivery Networks (CDNs such as Clouflare)

6. Sharding/Partitioning -> Splitting data or functionality across multiple nodes/servers

7. Asynchronous communication -> defferring long-running or non-critical tasks to background queues or message brokers -> this ensures main application remains reponsive

