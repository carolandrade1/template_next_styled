<table align="right">
 <tr><td><a href="README_EN.md">English</a></td></tr>
 <tr><td><a href="README.md">Português</a></td></tr>
</table>
<br>
<br>

# 📚 Repositorio Base

A ideia do repositorio é servir de base para novos projetos. Com todos os pacotes e depencias necessarias para iniciar da melhor forma. O projeto foi criado com Next.js e styled-components.

- [Next.js](https://nextjs.org/)

- [Styled-components](https://styled-components.com/)

## 👁‍🗨 CI/CD
CI/CD, continuous integration/continuous delivery, é um método para entregar aplicações com frequência aos clientes. Para isso, é aplicada a automação nas etapas do desenvolvimento de aplicações. Os principais conceitos atribuídos a esse método são integração, entrega e implantação contínuas. Com o CI/CD, é possível solucionar os problemas que a integração de novos códigos pode causar para as equipes de operações e desenvolvimento.

- [ESLint](https://eslint.org/)

- [Husky](https://typicode.github.io/husky/#/)

- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

## 🚦 Testes
Testes de software é um conjunto de processos com os quais se pretende validar um sistema ou aplicação, em momentos diferentes, para verificar seu correto funcionamento. São uma série de procedimentos que visam encontrar possíveis bugs, reportar erros, identificar problemas de usabilidade, bem como assegurar que todos os requisitos solicitados pelo cliente sejam atendidos.

- [Jest](https://jestjs.io/)

- [Testing Library](https://testing-library.com/)

- [Testing playground](https://testing-playground.com/)


O arquivo main.yml foi criado para implementar a primeira rotina de CI. Por enquanto somento o Lint está implementado, mas o Vercel pode ser adicionado posteriormente.
O repositorio está utilizando o yarn para administrar os pacotes, por isso as rotinas foram montadas com ele.

## 📋 Instalação Base

1. Clonar repositorio

```
git clone https://github.com/carolandrade1/template_next_styled && cd template_next_styled
```

2. Instalar dependências

```
yarn install
```

3. Trocar URL do repositorio remoto (caso necessário)

3.1. Ver qual o repositorio atual
```
git remote -v
```
3.2. Mudar a URL do repositorio remoto
```
git remote set-url origin <LinkDoNovoRepositorio>
```
3.3. Verifique se a mudança foi realizada
```
git remote -v
```

4. Rodar aplicativo

```
yarn dev
```

5. Acesse http://localhost:3000/ e navegue pelo site