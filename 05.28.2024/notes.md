# REST API

### O que é?

- Uma REST API é uma interface que fornece dados em um formato padronizado com base nas requisições HTTP

### Restrições de uma REST API

- Sobre a relação Cliente-Servidor a interface do usuário não é importante para o Back-End

- Não utiliza sessão (Stateless) -> Nenhum contexto do cliente é salvo no servidor (ex: sessão)

- Cache -> Respostas (responses) devem se auto definir se usam ou não cacher

- Sistema em camadas -> Servidoer intermediários podem ser usados sem que o client saiba

- Interface Uniforme -> Recursos são identificados na requisição, os dados transferidos são desacoplados do schema do banco de dados, também é importante ter mensagens auto-descritivas com links para recursos posteriores para deixar bem organizada e documentada

- Código sob-demanda -> pode ser transferido um código executável

