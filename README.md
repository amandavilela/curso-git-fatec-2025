# Aprendendo git
Repo para o mini-curso de git ministrado no dia 06/10/2025 na Semana da Tecnologia da Fatec Sorocaba.

Instrutores: [Amanda Vilela](https://github.com/amandavilela) & [Felipe Bernardes](https://github.com/felipebernardes)

Slides em: 


## tl;dr

### Instalando o git

https://git-scm.com/book/pt-br/v1/Primeiros-passos-Instalando-Git

### Configurando seu usuário
```
git config --global user.name "Seu nome"
git config --global user.email nome@email.com
```

### Criando um repositório no github

Leia mais detalhes sobre configuração de repositórios [aqui](https://help.github.com/articles/create-a-repo/)

### Clonando um repositório

```
git clone <endereço>
```

### Commitando coisas

Após finalizar seu trabalho é hora de realizar um commit, o primeiro passo é adicionar os arquivos para o commit

```
git add arquivo1.js arquivo2.js
```

Após adicionar os arquivos o commit pode ser feito:

``` 
git commit -m "Sua bonita e explicativa mensagem de commit"
```
*Não se esqueça de escrever uma mensagem bem explicativa com mais ou menos 50 caracteres

### Enviando commits

Para enviar seus commits para o servidor remoto, utilize o push

```
git push origin master
```

Origin = repostório remoto

Master = branch para onde os commits serão enviados

### Forkando um repositório

Para forkar um repositório, clique no botão Fork no canto direito da tela:

<img width="1413" height="412" alt="image" src="https://github.com/user-attachments/assets/76af97f4-dd30-4550-b5b3-e9669eedbd33" />

Uma cópia do repositório será feita para o seu perfil do github, após isso, basta clonar o repostório e enviar seus commits.

### Fazendo um Pull Request

Após enviar os commits para o respositório forkado é possível fazer um pull request, ou seja solicitar que suas modificações sejam enviadas para o repositório.

Para realizar um pull request, no seu repositório, clique na segunda aba __Pull Resquests__;

Clique no botão __New Pull Request__;

O GitHub automaticamente encontrará as diferenças entre o seu repositório e o repositório principal. Basta preencher um título e uma descrição de acordo com as recomendações do repositório principal e clicar no botão __Create new pull request__.

## Aprendendo mais

- Assista [essa playlist](https://www.youtube.com/playlist?list=PLInBAd9OZCzzHBJjLFZzRl6DgUmOeG3H0)

- Leia a [documentação oficial do git](https://git-scm.com/)

- [Ajuda GitHub](https://help.github.com/)

- Aprendendo a escrever [documentos markdown](www.markdowntutorial.com/)
