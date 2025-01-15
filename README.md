# Integração com a API do GitHub

Este código implementa uma função chamada `getApi()`, que faz uma requisição à API pública do GitHub para listar os repositórios de um usuário específico. A função permite que, ao digitar o nome de usuário no campo de entrada, a interface mostre todos os repositórios públicos do usuário, com seus respectivos nomes e links para visualização no GitHub.

## Como Funciona

1. **Captura do Nome do Usuário**: 
   - O nome de usuário do GitHub é obtido a partir de um campo de entrada com o id `#user`.

2. **Requisição à API**:
   - A função faz uma requisição GET à API pública do GitHub para buscar os repositórios do usuário digitado, utilizando a URL `https://api.github.com/users/{user}/repos`.

3. **Exibição dos Repositórios**:
   - A resposta da API é processada e os nomes dos repositórios, juntamente com os links para os repositórios no GitHub, são exibidos em uma lista ordenada dentro de uma `<ul>`. Cada repositório é exibido dentro de um `<li>`, com um link para o repositório.

4. **Tratamento de Erros**:
   - Caso ocorra algum erro (como o nome do usuário ser inválido ou não existir), uma mensagem de erro será exibida na tela informando que houve um problema na busca.



![git](https://github.com/user-attachments/assets/f6a1f98e-7647-4588-a1ca-424bb2d31e45)
