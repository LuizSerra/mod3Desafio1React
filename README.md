<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 07: GoFinances Web
</h3>

<blockquote align="center">“Não espere resultados brilhantes se suas metas não forem claras”!</blockquote>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :rocket: Sobre o desafio

Nesse desafio, você deve continuar desenvolvendo a aplicação de gestão de transações, a GoFinances. Agora você irá praticar o que você aprendeu até agora no React.js junto com TypeScript, utilizando rotas e envio de arquivos por formulário.

## :hammer: Tecnologias
- [React Native](https://reactnative.dev/) 
- [TypeScript](https://www.typescriptlang.org/)
- [Axios](https://www.npmjs.com/package/axios)
- [Styled Components](https://styled-components.com/)
- [Polished](https://github.com/styled-components/polished)
 


### :game_die: Layout da aplicação

O layout pode ser acessado através da página do Figma, no [seguinte link](https://www.figma.com/file/EgOhyj1Inz14dhWGVhRlhr/GoFinances?node-id=1%3A863).

Você precisará uma conta (gratuita) no Figma pra inspecionar o layout e obter detalhes de cores, tamanhos, etc.

## :key: Como rodar esse projeto.

Para clonar e executar este aplicativo, você precisará de  [Git](https://git-scm.com/),  [NodeJs](https://nodejs.org/)  Instalado em seu computador.

O projeto é composto por duas aplicações:

1.  Back-End ([Link do Repositório](https://github.com/LuizSerra/GoStack-FundamentosNode2))

💡  É preciso efetuar o clone e seguir os passos de instalação do  [Repositório da API](https://github.com/LuizSerra/GoStack-FundamentosNode2)

💡  A aplicação precisa que o Back-End esteja sendo executado na porta 3333 para funcionar.

### :sheep: Clonando o repositório.
```
# Clone este repositório
$ git clone https://github.com/LuizSerra/GoStack-GoFinances.git

# Acesse a pasta do projeto no terminal/cmd
$ cd goStack-ConceitosReactNative
```
### :computer: Rodando a aplicação.

```console

# Instale as dependências
$ yarn

# Execute a Aplicação
$ yarn start

# Execute o teste da Aplicação
$ yarn test

# O servidor inciará na porta:3000 - acesse http://localhost:3000
```

### Funcionalidades da aplicação

- **`Listar as transações da sua API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem através de uma tabela, com o campo `title`, `value`, `type` e `category` de todas as transações que estão cadastradas na sua API.

- **`Exibir o balance da sua API`**: Sua página `Dashboard`, você deve exibir o balance que é retornado do seu backend, contendo o total geral, junto ao total de entradas e saídas.

- **`Importar arquivos CSV`**: Na sua página `Import`, você deve permitir o envio de um arquivo no formato `csv` para o seu backend, que irá fazer a importação das transações para o seu banco de dados. O arquivo csv deve seguir o seguinte [modelo](https://github.com/Rocketseat/bootcamp-gostack-desafios/blob/master/desafio-database-upload/assets/file.csv).

### :camera: ScreenCast
![GoFinances](https://github.com/LuizSerra/GoStack-GoFinances/blob/master/GoFinances.gif)

## :computer: Quer contribuir com o Projeto? Saiba como:

-   Faça um  **fork**  do projeto;
-   Crie uma nova branch com as suas alterações:  `git checkout -b my-feature`
-   Salve as alterações e crie uma mensagem de commit contando o que você fez:`git commit -m "feature: My new feature"`
-   Envie as suas alterações:  `git push origin my-feature`

> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions)


## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

Feito com dedicação por Luiz Serra 👋🏽 [Entre em contato](https://www.linkedin.com/in/luizserra)!
