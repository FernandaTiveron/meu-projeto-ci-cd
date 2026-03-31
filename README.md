README.md completo (versão limpa)
Projeto CI/CD - Next.js

Este projeto demonstra a implementação de uma pipeline completa de Integração Contínua (CI) e Entrega Contínua (CD) utilizando GitHub Actions e Vercel em uma aplicação Next.js.

Deploy

A aplicação está publicada na Vercel no seguinte link:
https://meu-projeto-ci-cd-three.vercel.app/

Tecnologias utilizadas

Next.js, React, TypeScript, Jest, Testing Library, ESLint, GitHub Actions e Vercel.

Como rodar o projeto localmente

Para clonar o repositório, use:
git clone https://github.com/FernandaTiveron/meu-projeto-ci-cd.git

Depois entre na pasta do projeto e instale as dependências com:
npm install

Para rodar o projeto em ambiente de desenvolvimento:
npm run dev

Testes

Para executar os testes automatizados, utilize:
npm run test

Build do projeto

Para gerar o build de produção:
npm run build

CI/CD (Integração e Entrega Contínua)

Este projeto utiliza GitHub Actions para automatizar o fluxo de CI/CD.

Sempre que há um push ou pull request na branch main, o pipeline executa automaticamente:

Instalação das dependências com npm ci
Verificação de lint com npm run lint
Execução dos testes com npm run test
Build da aplicação com npm run build

Após a execução bem-sucedida do CI, o projeto é automaticamente implantado na Vercel, garantindo entrega contínua.

Estrutura do projeto

/app → páginas da aplicação
/components → componentes reutilizáveis
/tests → testes automatizados
.github/workflows → configuração do pipeline CI/CD

Status do projeto

CI funcionando
Testes automatizados
Build validado
Deploy automático ativo