# pipeline-ci-cd-atividade-Fabio

## Atividade Prática — Criando um Pipeline CI/CD Automatizado no GitHub Actions

Esta atividade simula um fluxo real de trabalho DevOps, incluindo:

* Controle de versão com Git
* Estruturação de um projeto simples
* Pipeline de CI (Integração Contínua)
* Pipeline de CD (Deploy Contínuo)
* Publicação automática no GitHub Pages
* Observação dos logs, métricas e artefatos gerados pelo pipeline

---

## Introdução

O objetivo desta atividade é desenvolver um pipeline de automação utilizando **GitHub Actions**, simulando um processo de **CI/CD** adotado em empresas que aplicam práticas DevOps.

O pipeline é responsável por:

* Validar arquivos do projeto
* Executar testes simples
* Gerar artefatos
* Publicar automaticamente uma página estática no **GitHub Pages**

Com isso, é possível compreender na prática como fluxos automatizados garantem:

* Qualidade
* Rapidez
* Padronização no desenvolvimento de software

---

## Estrutura de Pastas do Projeto

```text
seu-projeto/
├── site/
│   └── index.html
└── .github/
    └── workflows/
        ├── ci.yml
        └── cd.yml
```

---

## Detalhes dos Arquivos

### `site/index.html`

Página HTML simples utilizada para publicação automática no GitHub Pages.

Exemplo:

```html
<h1>Meu primeiro deploy automatizado</h1>
```

---

### `ci.yml`

Pipeline de **Integração Contínua (CI)** responsável por:

* Validar a estrutura do projeto
* Verificar se o arquivo `index.html` existe
* Executar testes simples automatizados

---

### `cd.yml`

Pipeline de **Deploy Contínuo (CD)** responsável por:

* Publicar automaticamente a aplicação
* Realizar deploy no **GitHub Pages**
* Disponibilizar a página após cada atualização no repositório

---

## Tecnologias Utilizadas

* Git
* GitHub
* GitHub Actions
* GitHub Pages
* HTML5

---

## Resultado Esperado

Ao realizar um `push` no repositório:

1. O pipeline de CI será executado automaticamente
2. Os testes e validações serão realizados
3. O deploy será publicado automaticamente no GitHub Pages
4. A aplicação ficará disponível online

---
