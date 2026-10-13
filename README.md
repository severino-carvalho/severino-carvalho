<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <img alt="Severino Carvalho — Desenvolvedor Full Stack" src="./assets/banner-light.svg" width="100%">
</picture>

<br>

<a href="https://severinocarvalho.dev"><img src="https://img.shields.io/badge/severinocarvalho.dev-1A1F2B?style=flat-square&logo=googlechrome&logoColor=white" alt="Site"></a>
<a href="https://www.linkedin.com/in/severino-carvalho/"><img src="https://img.shields.io/badge/LinkedIn-AD4A26?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:severinocarvalho14@gmail.com"><img src="https://img.shields.io/badge/Email-1A1F2B?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/numbers-dark.svg">
  <img alt="3+ anos em produção · 3 sistemas corporativos · Back, Web e Mobile ponta a ponta" src="./assets/numbers-light.svg" width="100%">
</picture>

</div>

## Sobre mim

Desenvolvedor Full Stack com experiência construindo sistemas que resolvem problemas reais, do back-end ao mobile. Na **IDUS**, digitalizo processos do setor de **óleo e gás** que antes viviam em planilhas e papel, entregando sistemas usados no dia a dia da operação.

- Desenvolvedor Full Stack na **IDUS** desde abr/2023
- Cursando **Bacharelado em Tecnologia da Informação** na UFRN
- Código que se lê: Clean Code, funções pequenas e Code Review

## Como eu trabalho

- **Ponta a ponta**: entendo o problema inteiro, da modelagem do banco até a tela que o usuário toca. Isso evita decisões de front-end que não fazem sentido para o back-end, e vice-versa.
- **Aprender fazendo**: testo uma tecnologia construindo algo com ela antes de confiar nela num projeto sério.
- **Código que se lê**: prefiro nomes claros e funções pequenas a comentários explicando código confuso.

## Stack

**Back-end**

<img src="https://skillicons.dev/icons?i=java,spring,nodejs,nestjs,express,rabbitmq" alt="Java, Spring, Node.js, NestJS, Express, RabbitMQ">

**Front-end & mobile**

<img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,tailwind" alt="React, React Native, Next.js, TypeScript, JavaScript, Tailwind">

**Dados & infra**

<img src="https://skillicons.dev/icons?i=postgres,mysql,docker,git,github" alt="PostgreSQL, MySQL, Docker, Git, GitHub">

Também: Spring Security · JPA/Hibernate · JWT/OAuth2 · REST APIs · React Native · Realm (offline-first)

## Destaques técnicos

- **Offline-first no mobile**: app React Native com Realm, que funciona sem conexão e sincroniza quando a rede volta.
- **Mensageria entre microsserviços**: integração assíncrona com RabbitMQ.
- **Segurança**: autenticação e autorização com Spring Security, JWT e OAuth2.
- **Digitalização de processos**: planilhas e papel substituídos por fluxos automatizados, com modelagem em PostgreSQL e JPA/Hibernate.

## Arquitetura que costumo construir

```mermaid
flowchart LR
    mobile["App React Native<br/>(Realm, offline-first)"] -- sync --> api["API Spring Boot"]
    web["Web React + TypeScript"] --> api
    api -- "JWT / OAuth2" --> auth["Spring Security"]
    api --> db[("PostgreSQL")]
    api -- eventos --> mq{{"RabbitMQ"}}
    mq --> ms["Microsserviços"]
```

## Experiência

**Desenvolvedor Full Stack · IDUS** · _Natal, RN · abr/2023 até hoje_

- **Digitalização de processos para o setor de óleo e gás**: sistema em produção que troca planilhas e papel por fluxos automatizados. APIs REST, modelagem de banco de dados, integração entre módulos e módulos mobile em React Native.
- **Sistema de monitoramento de alarmes industriais**: atuação desde o início do projeto, cuidando de interfaces, APIs REST, modelagem de dados e integração entre microsserviços via mensageria.

## Formação

| Curso | Instituição | Período |
| --- | --- | --- |
| Bacharelado em Tecnologia da Informação | UFRN | 2026 até hoje |
| Técnico em Programação para Internet | IMD/UFRN | 2020 a 2022 |
| Técnico em Informática | IFRN, Campus João Câmara | |

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/severino-carvalho/severino-carvalho/output/snake-dark.svg">
  <img alt="Animação de contribuições" src="https://raw.githubusercontent.com/severino-carvalho/severino-carvalho/output/snake.svg">
</picture>

---

<div align="center">

Tem um projeto em mente ou quer trocar uma ideia? **[Fale comigo](mailto:severinocarvalho14@gmail.com)** · Veja mais em **[severinocarvalho.dev](https://severinocarvalho.dev)**

</div>
