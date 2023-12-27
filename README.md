Team Topologies -  Matthew Skelton and Manuel Pais

https://github.com/devfullcycle/FC3-admin-catalogo-de-videos-api-gateway

https://pantsel.github.io/konga/

docker-compose -f kong-compose.yml up

Downstream(User/Api) -> Proxy(Kong) -> Upstream (Backend)

Plugins:
    - response-transformer
        https://docs.konghq.com/hub/kong-inc/response-transformer/configuration/
    
    - request-transformer
        https://docs.konghq.com/hub/kong-inc/request-transformer/configuration/
    
    - rate-limiting
        https://docs.konghq.com/hub/kong-inc/rate-limiting/
    
    - correlation-id
        https://docs.konghq.com/hub/kong-inc/correlation-id/

    - basic-auth
        https://docs.konghq.com/hub/kong-inc/basic-auth/

    - key-authentication
        https://docs.konghq.com/hub/kong-inc/key-auth/


Konga Config:
![Konga Services](images/konga-services.png)
![Konga Service Bets part 1](images/konga-service-bets-1.png)
![Konga Service Bets part 2](images/konga-service-bets-2.png)
![Konga Service Bets Routes](images/konga-service-bets-routes.png)

![Konga Services Bets Plugins](images/konga-service-bets-plugins.png)

![Konga Services Bets Plugin Zipkin part 1](images/konga-service-bets-plugins-zipkin-1.png)
![Konga Services Bets Plugin Zipkin part 2](images/konga-service-bets-plugins-zipkin-2.png)

![Konga Services Bets Plugin TCP Log](images/konga-service-bets-plugins-tcp-log.png)

![Konga Services Bets Plugin Rate Limiting part 1](images/konga-service-bets-plugins-rate-limiting-1.png)
[Konga Services Bets Plugin Rate Limiting part 2](images/konga-service-bets-plugins-rate-limiting-2.png)
[Konga Services Bets Plugin Rate Limiting part 3](images/konga-service-bets-plugins-rate-limiting-3.png)

[Konga Services Bets Plugin Response Transformer part 1](images/konga-service-bets-plugins-response-transformer-1.png)
[Konga Services Bets Plugin Response Transformer part 2](images/konga-service-bets-plugins-response-transformer-2.png)

![Konga Services Bets Plugin Key Auth](images/konga-service-bets-plugins-key-auth.png)

![Konga Services Bets Eligible Consumers](images/konga-service-bets-plugins-key-auth.png)

![Konga Routes](images/konga-routes.png)
![Konga Route create_bet part 1](images/konga-route-create-bet-1.png)
![Konga Route create_bet part 2](images/konga-route-create-bet-2.png)
![Konga Route create_bet part 3](images/konga-route-create-bet-3.png)

![Konga Consumers](images/konga-consumers.png)
![Konga Consumer Auth Basic details](images/konga-consumer-auth-basic-details.png)
![Konga Consumer Auth Basic credentials](images/konga-consumer-auth-basic-credentials.png)

![Konga Consumer Auth Api Key details](images/konga-consumer-auth-api-key-details.png)
![Konga Consumer Auth Api Key credentials](images/konga-consumer-auth-api-key-credentials.png)

![Konga Plugins](images/konga-plugins.png)
![Konga Plugin Correlation ID](images/konga-plugin-correlation-id.png)
![Konga Plugin Prometheus](images/konga-plugin-prometheus.png)

![Konga Connections](images/konga-connections.png)