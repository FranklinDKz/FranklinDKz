<h1 align="center">Franklin · DK RP</h1>

<p align="center">
  <b>Desenvolvedor Full Stack</b><br/>
  Técnico em Informática (Instituto Federal, 2º ano) · Brasil 🇧🇷
</p>

<p align="center">
  <a href="https://discord.gg/TyttP5qAMZ"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>
  <a href="https://www.youtube.com/@dkfivemrp"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Aberto%20a-Est%C3%A1gio%20%7C%20J%C3%BAnior%20%7C%20Freelance-16a34a?style=for-the-badge" />
</p>

---

## 👋 Sobre

Desenvolvo e publico software que outras pessoas usam: **plataforma web com pagamentos e painel administrativo, APIs com migrations e testes, aplicativos desktop para Windows e sistemas de licenciamento**. Boa parte do meu trabalho vem do ecossistema **FiveM**, onde mantenho uma comunidade, uma loja e produtos digitais com clientes reais, o que me ensinou a lidar com suporte, deploy, segurança e manutenção de verdade.

Procuro **estágio ou vaga júnior** como desenvolvedor Full Stack.

---

## 🚀 Projetos em destaque

### 🌐 [ScR Community](https://github.com/FranklinDKz/scr-community-fivem) · [site no ar](https://scr-community.dk-rp.workers.dev)
Plataforma web completa para distribuir resources, vender bases e prestar suporte.
`TypeScript` `Cloudflare Workers` `D1 (SQL)` `R2` `Vite`
- API serverless no **Cloudflare Workers**, banco **D1** com **migrations versionadas** e arquivos privados no **R2**
- Login por e-mail/senha e por **Discord**, sessão persistente, perfil e **painel administrativo**
- **Checkout com confirmação no servidor** antes de liberar acesso, e downloads protegidos com limite diário
- Testes (`core.test.ts`) e **CI no GitHub Actions**

### ☕ [Sala Livre](https://github.com/FranklinDKz/sala-livre)
Agenda de salas que impede reservas em conflito.
`Java 21` `Spring Boot` `Flyway` `H2` `Docker`
- Regra de negócio testada: sem sobreposição, janela de horário, blocos de 30 min
- **Transação com bloqueio de linha** para evitar condição de corrida em reservas simultâneas
- API REST com `400/404/409` coerentes, migrations Flyway, Dockerfile e **CI**

### 🐍 [Bancada](https://github.com/FranklinDKz/bancada-service-desk)
Ordens de serviço de TI com painel web e API em Python.
`Python` `API REST (docs em /docs)` `SQLite` `Docker`
- Filtros, busca, exportação CSV, seed de dados e **testes automatizados com CI**

### 🛠️ [DK Game Optimizer](https://github.com/FranklinDKz/dk-game-optimizer)
Aplicativo desktop para Windows 10/11 com ajustes de jogos e manutenção.
`C#` `.NET` `PowerShell`
- Detecção de hardware, **ações com prévia do comando, confirmação, log e backup** de valores do Registro para reversão
- Limpeza segura (ignora arquivos recentes/bloqueados e pastas fora da lista permitida)
- Projeto de testes e **pipeline de build**

### 🎮 [GRW DK RP Panel](https://github.com/FranklinDKz/GRW-DKRP-Panel)
Painel Windows em PT-BR para Ghost Recon Wildlands (solo/offline): manipulação de memória com verificação de assinatura antes de qualquer patch, instalador e releases. Licença GPL-3.0 com código-fonte de dependências incluído.
`C#` `PowerShell`

---

## 🔒 Trabalho em repositórios privados

Além dos projetos públicos, mantenho código comercial privado, entre eles:

- **Plataforma de licenciamento:** API de licenças, painel web e bot de Discord para entregas
- **Instalador desktop em Electron:** login por licença, checagem de IP, download com retomada, instalador NSIS e versão portable
- **Scanner desktop de bases FiveM:** analisa Lua, SQL, cfg e arquivos de streaming, procura falhas de segurança e malware e gera relatórios em `.txt`, `.md` e `.pdf`
- **ScR Stream:** transmissão de tela e áudio para calls do Discord
- **Bases FiveM multi-framework** e documentação técnica das bases

Posso apresentar o código e a arquitetura em entrevista.

---

## 🧰 Stack

**Linguagens**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

**Back-end & Front-end**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Dados**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Cloudflare D1](https://img.shields.io/badge/Cloudflare%20D1-F38020?style=flat-square&logo=cloudflare&logoColor=white)

**Infra & Ferramentas**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)

**Game engines:** Unity · Unreal Engine (estudo)

---

## ⚙️ Práticas de engenharia

- **Migrations versionadas** (Flyway, Wrangler/D1) em vez de banco alterado à mão
- **Testes automatizados e CI** nos projetos públicos
- **Segredos fora do Git** (`.dev.vars.example`, variáveis de ambiente)
- **Validação no servidor**: pagamento, licença e acesso nunca dependem do cliente
- **Docker** e documentação de execução local passo a passo, com README em PT-BR e EN
- Uso IA como assistente, mas **reviso, testo e respondo pelo código e pela arquitetura**

---

## 🔐 Infra, redes e segurança

Deploy em **Cloudflare, Google Cloud, VPS Linux/Windows, Render, Railway** e outros. DNS e domínios, variáveis de ambiente, banco remoto, autenticação e controle de acesso, proteção de APIs, ofuscação de código, análise de vulnerabilidades, fundamentos de TCP/IP, HTTP/HTTPS e DNS.

---

## 🎓 Formação & Conquistas

- 🎓 **Técnico em Informática**, Instituto Federal (2º ano)
- 🥇 **1º lugar**, evento acadêmico FAPAZ, projeto **E-Lixo Zero**
- 🌎 XI Bienal · SIAI 2025 e 2026
- 📖 One Way / Monkey Academy
- 🖥️ Base em hardware e suporte: montagem, manutenção e diagnóstico de PCs, notebooks e consoles

---

## 📊 GitHub

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=FranklinDKz&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=FranklinDKz&layout=compact&theme=github_dark&hide_border=true" />
</p>

---

<p align="center"><i>Construindo, aprendendo e melhorando um projeto por vez.</i></p>
