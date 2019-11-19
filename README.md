# Why Azure SignalR Service

#### Handle large-scale client connections without burden of self-hosting:

Managed Scalability - SignalR Service is designed for large-scale real-time applications. SignalR Service allows multiple instances to work together to scale to millions of client connections. The service also supports multiple global regions for sharding, high availability, or disaster recovery purposes. Switching to SignalR Service will remove the need to manage back planes that handle the scales and client connections. The fully managed service also simplifies web applications and saves hosting cost. SignalR Service offers global reach and world-class data center and network, scales to millions of connections, guarantees SLA, while providing all the compliance and security at Azure standard.

Load balancing a large number of persistent WebSocket connections - Load balancing a large number of persistent WebSocket connections becomes a complicated problem to solve as you scale. Common solutions leverage: DNS load balancing, hardware load balancers, and software load balancing. Azure SignalR Service handles this problem for you.

One of the key reasons to use the Azure SignalR Service is simplicity - With Azure SignalR Service, you don't need to handle problems like performance, scalability, availability. These issues are handled for you with a 99.9% service-level agreement.



![alt text](https://docs.microsoft.com/en-us/azure/azure-signalr/media/signalr-overview/managed-signalr-service.png "Managed SignalR")

#### Managing Backplane with Redis

![alt text](https://docs.microsoft.com/en-us/aspnet/core/signalr/scale/_static/redis-backplane.png?view=aspnetcore-3.0 "Managed SignalR")

#### Azure SignalR 

![alt text](https://docs.microsoft.com/en-us/aspnet/core/signalr/scale/_static/azure-signalr-service-multiple-connections.png?view=aspnetcore-3.0 "Managed SignalR")

### Reference
* https://docs.microsoft.com/en-us/azure/azure-signalr/signalr-concept-scale-aspnet-core#why-not-deploy-signalr-myself

# Multiple instances and Disaster Recovery

![alt text](https://docs.microsoft.com/en-us/azure/azure-signalr/media/signalr-concept-disaster-recovery/before-failover.png "")
![alt text](https://docs.microsoft.com/en-us/azure/azure-signalr/media/signalr-concept-disaster-recovery/after-failover.png "")
![alt text](https://docs.microsoft.com/en-us/azure/azure-signalr/media/signalr-concept-disaster-recovery/after-recover.png "")

* https://docs.microsoft.com/en-us/azure/azure-signalr/signalr-howto-scale-multi-instances
* https://docs.microsoft.com/en-us/azure/azure-signalr/signalr-concept-disaster-recovery

# Benchmark and Performance Testing

* https://github.com/Azure/azure-signalr-bench
* https://github.com/aspnet/AspNetCore/tree/master/src/SignalR/perf/benchmarkapps/Crankier

# Performance 

* https://docs.microsoft.com/en-us/azure/azure-signalr/signalr-concept-performance

# Pricing

* 1,000 - Concurrent Connections per Unit 
* 1,000,000 - Messages / Unit / Day
* Messages larger than 2 KB(kilobytes) are counted as multiple messages of 2 KB each.
