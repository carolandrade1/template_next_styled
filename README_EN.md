<table align="right">
 <tr><td><a href="README_EN.md">English</a></td></tr>
 <tr><td><a href="README.md">Português</a></td></tr>
</table>
<br>
<br>

# 📚 Template

The idea of the repository is to serve as a template for new projects. With all the necessary packages and dependencies to start in the best way. The project was created with Next.js and styled-components.

- [Next.js](https://nextjs.org/)

- [Styled-components](https://styled-components.com/)

## 👁‍🗨 CI/CD
CI/CD, continuous integration/continuous delivery, it's a method for frequently delivering applications to customers. For this, automation is applied in the application development stages. The main concepts attributed to this method are continuous integration, delivery and deployment. With CI/CD, it is possible to solve the problems that the integration of new code can cause for the operations and development teams.

- [ESLint](https://eslint.org/)

- [Husky](https://typicode.github.io/husky/#/)

- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

## 🚦 Tests
Software testing is a set of processes with which one intends to validate a system or application, at different times, to verify its correct functioning. They are a series of procedures aimed at finding possible bugs, reporting errors, identifying usability problems, as well as ensuring that all requirements requested by the customer are met.

- [Jest](https://jestjs.io/)

- [Testing Library](https://testing-library.com/)

- [Testing playground](https://testing-playground.com/)


The main.yml file was created to implement the first CI routine. For now only Lint is implemented, but Vercel can be added later.
The repository is using yarn to manage packages, so the routines were built with it.

## 📋 Installation

1. Clone repository

```
git clone https://github.com/carolandrade1/template_next_styled && cd template_next_styled
```

2. Install dependencies

```
yarn install
```

3. Change remote repository URL (if necessary)

3.1. See what is the current repository
```
git remote -v
```
3.2. Change the remote repository URL
```
git remote set-url origin <LinkDoNovoRepositorio>
```
3.3. Check if the change has been made
```
git remote -v
```

4. Run application

```
yarn dev
```

5. Go to http://localhost:3000/ and see the site
