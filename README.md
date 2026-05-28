# pipeline-ci-cd-atividade-Fabio
Atividade Prática — Criando um Pipeline CI/CD Automatizado no GitHub Actions

A atividade simula um fluxo real de trabalho DevOps, incluindo:
• Controle de versão com Git
• Estruturação de um projeto simples
• Pipeline de CI (integração contínua)
• Pipeline de CD (deploy contínuo)
• Publicação automática no GitHub Pages
• Observação dos logs, métricas e artefatos gerados pelo pipeline
2. Introdução
É preciso que você desenvolva um pipeline de automação utilizando o GitHub Actions,
simulando um processo de CI/CD adotado em empresas que aplicam práticas DevOps.
O pipeline será responsável por validar arquivos, rodar testes simples, gerar artefatos e
publicar automaticamente uma página estática no GitHub Pages.
O objetivo principal é entender, na prática, como fluxos automatizados garantem
qualidade, rapidez e padronização no desenvolvimento de software.
3. Estrutura de Pastas do Projeto
O aluno deverá criar a seguinte estrutura:
seu-projeto/
├── site/
│ └── index.html
└── .github/
└── workflows/
├── ci.yml
└── cd.ymlDetalhes:
• site/index.html → página simples (Ex.: “Meu primeiro deploy automatizado”)
• ci.yml → pipeline de Integração Contínua
• cd.yml → pipeline de Deploy Contínuo (GitHub Pages)
