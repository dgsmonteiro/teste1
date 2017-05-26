# Teste 1
# Aplicação 1 - Grid usuários
 
Você tem acesso a uma API genérica de usuários, é preciso
 criar uma grid/listagem com as seguintes informações dos usuários:
 
- Número de identificação (ID);
- Primeiro nome e sobrenome, iniciados com letra maiúscula
 e com o sobrenome abreviado
(por ex: Sérgio F.);
- Foto (exibir a imagem, não deixar o caminho do arquivo);
 
Abaixo do grid deverá ter um controle de paginação padrão,
 com funcionalidades de voltar e avançar páginas e links/botões para ir diretamente a uma página específica. Cada página carregará 3 registros de usuários no grid.
 
 
Você poderá acessar os dados no endpoint ->
https://reqres.in/api/
 
**Nesta API a listagem dos usuários é trazida através de um HTTP GET no recurso 'user', passando por querystring o argumento 'page' (tipo inteiro), para controlar as páginas de registros**.
 
É preferível usar a API, porém você pode "mockar" simulando
 os dados de usuários.
