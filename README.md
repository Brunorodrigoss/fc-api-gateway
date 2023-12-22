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
