# Why Azure SignalR Service

One of the key reasons to use the Azure SignalR Service is simplicity. With Azure SignalR Service, you don't need to handle problems like performance, scalability, availability. These issues are handled for you with a 99.9% service-level agreement.

Also, WebSockets are typically the preferred technique to support real-time content updates. However, load balancing a large number of persistent WebSocket connections becomes a complicated problem to solve as you scale. Common solutions leverage: DNS load balancing, hardware load balancers, and software load balancing. Azure SignalR Service handles this problem for you.



![alt text](https://docs.microsoft.com/en-us/azure/azure-signalr/media/signalr-overview/managed-signalr-service.png "Managed SignalR")

## Reference
* https://docs.microsoft.com/en-us/azure/azure-signalr/signalr-concept-scale-aspnet-core#why-not-deploy-signalr-myself

# Multiple instances

https://docs.microsoft.com/en-us/azure/azure-signalr/signalr-howto-scale-multi-instances
