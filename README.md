# DevelopSite
该Repo旨在为大家整理出对于开发者来可以学习的站点

## [Kubernetes(K8s)](https://kubernetes.io/)
Kubernetes是容器集群管理系统，是一个开源的平台，可以实现容器集群的自动化部署、自动扩缩容、维护等功能。

[K8s中文社区](https://www.kubernetes.org.cn/)

[K8s中文指南](https://jimmysong.io/kubernetes-handbook/)

## [Istio](https://istio.io/)
Istio 提供一种简单的方式来为已部署的服务建立网络，该网络具有负载均衡、服务间认证、监控等功能，而不需要对服务的代码做任何改动。想要让服务支持 Istio，只需要在您的环境中部署一个特殊的 sidecar 代理，使用 Istio 控制平面功能配置和管理代理，拦截微服务之间的所有网络通信：
- HTTP、gRPC、WebSocket 和 TCP 流量的自动负载均衡。
- 通过丰富的路由规则、重试、故障转移和故障注入，可以对流量行为进行细粒度控制。
- 可插入的策略层和配置 API，支持访问控制、速率限制和配额。
- 对出入集群入口和出口中所有流量的自动度量指标、日志记录和跟踪。
- 通过强大的基于身份的验证和授权，在集群中实现安全的服务间通信。
Istio 旨在实现可扩展性，满足各种部署需求。

[Istio中文教程](https://jimmysong.io/istio-handbook/)

Istio 是由 Google、IBM、Lyft 等共同开源的 Service Mesh（服务网格）框架，于2017年初开始进入大众视野。Kubernetes 解决了云原生应用的部署问题，Istio 解决的是应用的服务（流量）治理问题。


