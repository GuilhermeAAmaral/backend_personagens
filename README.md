README

Título: API Personagens 

Descrição: API desenvolvida em Node e Typescript com endpoints de criação, listagem e exclusão de personagens aleatórios

Endpoints: Cadastro, listagem e exclusão dos personagens

Rotas: 

//-------------------------------------------------------------------------------------------------------------------------------

Criar personagem

Método: Post

URL: http://localhost:3003/criarPersonagem

body: {
    "name": "Homem Aranha",
    "gender": "MALE",
    "description": "universo marvel"
}

//-------------------------------------------------------------------------------------------------------------------------------

Buscar todos os personagens

Método: GET

URL: http://localhost:3003/criarPersonagem

//-------------------------------------------------------------------------------------------------------------------------------

Excluir personagem

Método: Delete

URL: http://localhost:3003/deletarPersonagem/:id

Path Params: id

//-------------------------------------------------------------------------------------------------------------------------------

Buscar filmes que o personagem participou

Método: GET

URL: http://localhost:3003/filme/:id/Personagem

Path Params: id


Ferramentas, dependências e libs instaladas: Node, Typescript, Express, My SQL

Para rodar o projeto localmente: Faça o clone do repositorio, navegue até a pasta destino, utilize o comando npm install, rode o servidor com o comando npm run start e faça as requisições via Postman ou app de preferência.

 
