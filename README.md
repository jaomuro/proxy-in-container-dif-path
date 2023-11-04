# Caminhos no Proxy Reverso Nginx
Exemplo simples do funcionamento de um proxy reverso Nginx em Container Docker, que realiza redirecionamentos para serviços que estão estruturados no mesmo docker-compose.yaml. Alcançabilidade garantida por estarem compartilhando a mesma docker network. Redirecionamentos sendo realizados pelo path no domínio e não domínios diferentes.

Para bom funcionamento é necessário um DNS estático configurado, redirecionando as urls para o IP da instância que roda o docker daemon.
