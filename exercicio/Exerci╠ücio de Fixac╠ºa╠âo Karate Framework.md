![Logo Raroacademy QA](../logo.jpeg)

# Exercício de fixação Karate Framework


1. Crie um repositório de git seguindo os passos abaixo:
    1. Acesse a página de criação de um novo repoistório no [Github](https://github.com/new). Caso ainda não possua uma conta do Github, [crie sua conta](https://github.com/join).
    2. Configure o nome do repositório como ``exercicio1-karate``;
    3. Defina o tipo de visualização do repositório como ``Public``;
    4. Clique em ``Create repository``;
    5. Crie uma nova pasta com o nome ``exercicio1-karate`` em qualquer local de sua preferência em seu sistema operacional;
    6. Abra esta pasta com o editor de texto ``VsCode``;
    7. Execute o comando ``git init`` para inicializar o repositório;
    8. Execute o comando ``git branch -M main`` para definir a branch padrão do repositório;
    9. Execute o comando ``git remote add origin https://github.com/SEU_NOME_DE_USUARIO_DO_GITHUB/exercicio1-karate.git`` para definir o repositório onde suas alterações serão salvas.

2. Crie um arquivo ``.feature`` e documente a funcionalidade de Gestão/Controle de Pet do [Swagger Petstore](https://petstore.swagger.io/#/) utilizando o Karate Framework.

    2.1. Crie um Cenário que envie uma requisição para a rota [POST /pet/{petId}](https://petstore.swagger.io/#/pet/updatePetWithForm) utilizando o Karate. Seu teste deve verificar se o response code é igual a ``200``;

    2.2. Crie um cenário que envie uma requisição para a rota [GET /pet/findByStatus](https://petstore.swagger.io/#/pet/findPetsByStatus), buscando os pets com status ``available`` ou ``pending``  e verifique se o response code é igual a ``200``.

3. Salve e faça commit das suas mudanças.
    1. ``git add .``
    2. ``git commit -m "primeiro exercício karate"``<br>

4. Atualize o repositório do Github com suas alterações: 
    <br>Caso seja seu primeiro push: `` git push --set-upstream origin main`` 
    <br>Caso já tenha feito um push neste repositório e branch anteriormente: ``git push``
