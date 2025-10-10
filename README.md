![poster](https://github.com/Dayvsontp/newman_serverest/blob/master/Postman/newman-githubActions.png)

## 🤘 Sobre

Repositório do projeto de testes automatizados do site ServeRest, é uma ferramenta de código aberto que auxilia a automação de testes em API's e Web, oferecendo uma abordagem eficaz e altamente confiável.

## 💻 Tecnologias
- Node.js
- Newman
- Github Actions

## 🤖 Pré-requisito
```
node >= 16
```

## 🤖 Como executar

1. Clonar o repositório, instalar as dependências
```
npm install
```

2. Instalar o Newman
```
npm install -g newman
```

3. Executar testes em Headless
```
newman run "local_da_collection" -e "local_do_environment"
```
ou

4. Executar testes no Github Actions
```
* Clicar em Actions, no menu principal do github
* Clicar em Run Postman Collection, no menu lateral esquerdo
* Clicar no event trigger Run workflow e escolha a branch
* Clicar no botão Run workflow
```

<hr>
Boas Práticas
