## API, REST e RESTFUL

Cliente (client)
Garçon (pedidos, levar seus pedidos, para a cozinha) (API)
cozinha (Server)

Acronimo de Application Programming Interface (Interface de Programação de Aplicações) é basicamente um conjunto de rotinas e padrões estabelecidos por uma aplicação, para que outras aplicações possam utilizar as funcionalidades desta aplicação.

- Responsável por estabelecer comunicação entre diferentes serviços.
- Meio campo entre as tecnologias.
- Intermediador para troca de informações.

## REST
a transferência de dados , geralmente, usando o protocolo HTTP.

### 6 NECESSIDADES (constrains) para ser RESTful

- _Client-server_:
- _Stateless_:
- _Cacheable_:
- _Layered System_:
- _Code on demand (optinal)_:

## RESTFUL

RESTful, é a aplicação dos padrões REST.

## BOAS PRÁTICAS

- Utilizar verbos HTTP para nossas requisições.
- Utilizar plural ou singular na criação dos endpoints? _NÃO IMPORTA!_ use um padrão!!!
- Não deixar barra no final do endpoint
- Nunca deixe o cliente sem resposta!

### VERBOS HTTP

- GET: Receber dados de um Resource.
- POST: Enviar dados ou informações para serem processados por um Resource.
- PUT: Atualizar dados de um Resource.
- DELETE: Deletar um Resource.

### STATUS DAS RESPOSTAS

- 1xx: Informação
- 2xx: Sucesso
   - 200: OK
   - 201: CREATED
   - 204: Não tem conteúdo PUT POST DELETE
- 3xx: Redirection
- 4xx: Client Error
   - 400: Bad Request
   - 404: Not Found!
- 5xx: Server Error
   500: Internal Server Error

https://jsonplaceholder.typicode.com/users