<p align="center">
  <a href="https://adrianmoraisdev.github.io/adrian-higa-portfolio/">
    <img src="assets/neural-header.svg" width="100%" alt="Adrian Higa — Software Engineer .NET & IA. Rede neural animada levando requisito, código e dados até API .NET, testes e deploy."/>
  </a>
</p>

<p align="center">
  <a href="https://adrianmoraisdev.github.io/adrian-higa-portfolio/"><img src="https://img.shields.io/badge/Portf%C3%B3lio-ver_cases-38BDF8?style=for-the-badge&labelColor=0B1222" alt="Portfólio"/></a>
  <a href="https://www.linkedin.com/in/adrianhiga-tech"><img src="https://img.shields.io/badge/LinkedIn-Adrian_Higa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0B1222" alt="LinkedIn"/></a>
  <a href="mailto:adrianmorais.dev@gmail.com"><img src="https://img.shields.io/badge/E--mail-vamos_conversar-A78BFA?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0B1222" alt="E-mail"/></a>
  <img src="https://img.shields.io/badge/Aberto_a-Pleno_%2F_S%C3%AAnior_%C2%B7_Remoto-34D399?style=for-the-badge&labelColor=0B1222" alt="Aberto a posições Pleno e Sênior, remoto"/>
</p>

## Sobre mim

Software Engineer .NET com foco em **IA aplicada**. Sou responsável técnico pelos sistemas de uma
administradora de consórcios de ponta a ponta: arquitetura, desenvolvimento, infraestrutura em nuvem
e segurança. Estruturei um fluxo de engenharia com **agentes de IA (Claude Code e Codex)**, com regras,
revisão humana e testes automatizados, que sustenta **mais de 10 sistemas em produção**.

- 🧠 **IA aplicada:** agentes de IA no desenvolvimento, LLMs com function calling e RAG
- ⚙️ **Backend:** C#, .NET 8/9, ASP.NET Core, EF Core, Dapper, APIs REST
- 🔁 **Eventos e automação:** RabbitMQ, MassTransit, workers, RPA e n8n
- ☁️ **Nuvem e DevOps:** AWS, Linux, Docker, nginx, Cloudflare, CI/CD
- 🛡️ **Segurança:** 2FA, auditoria, CSP, LGPD, varredura contínua de vulnerabilidades

## Como eu entrego com IA

<p align="center">
  <img src="assets/agent-flow.svg" width="100%" alt="Fluxo animado: demanda, briefing, agentes, verificação, revisão humana e produção."/>
</p>

| Princípio | Na prática |
|---|---|
| **Governança em todo repositório** | `AGENTS.md` / `CLAUDE.md` com arquitetura, regras de segurança, proteção contra prompt injection e o que exige aprovação humana |
| **Verificação proporcional** | o agente só declara pronto o que foi testado: comportamento alterado, autorização, isolamento e regressão |
| **Custo sob controle** | contexto enxuto e leitura seletiva; medi e reduzi o custo de tokens por entrega |
| **Segurança antes de velocidade** | segredos fora do contexto, homologação antes de produção, ações externas com confirmação |

## Cases

Sistemas corporativos apresentados sem telas, nomes de clientes ou endereços. Cada case tem página com arquitetura, decisões e resultado.

| Case | O que resolve | Destaque |
|---|---|---|
| [**Plataforma comercial e API central**](https://adrianmoraisdev.github.io/adrian-higa-portfolio/cases/plataforma-comercial/) | Simulação de planos, comissões, campanhas e assinatura digital em uma API única | ~300 endpoints · 307 testes · deploy sem queda |
| [**Automação orientada a eventos**](https://adrianmoraisdev.github.io/adrian-higa-portfolio/cases/automacao-orientada-a-eventos/) | Cadastros no ERP legado e sincronização de vendas sem trabalho manual | RabbitMQ · DLQ · idempotência |
| [**Apuração de assembleias ao vivo**](https://adrianmoraisdev.github.io/adrian-higa-portfolio/cases/assembleias-ao-vivo/) | Sorteio e lances calculados em tempo real, exportados no formato do ERP | .NET 9 · regras no domínio · 73 testes |
| [**Painéis executivos e de vendas**](https://adrianmoraisdev.github.io/adrian-higa-portfolio/cases/paineis-executivos/) | Resultado e metas para diretoria, gerentes e equipes, do celular ao telão | 2FA · CSP · containers somente leitura |
| [**Infraestrutura em nuvem e DevSecOps**](https://adrianmoraisdev.github.io/adrian-higa-portfolio/cases/infraestrutura-devsecops/) | Ambiente de produção configurado do zero e operado sem time dedicado | AWS · Cloudflare · Trivy + CISA KEV |
| [**Agente de atendimento com LLM**](https://adrianmoraisdev.github.io/adrian-higa-portfolio/cases/agente-atendimento-llm/) | Assistente que consulta catálogo, pedidos e políticas sem inventar números | function calling · RAG · 3 provedores |
| [**Acervo e integração de assinatura digital**](https://adrianmoraisdev.github.io/adrian-higa-portfolio/cases/assinatura-digital/) | Cópia fiel dos contratos desde 2021 e migração de plataforma com segurança | somente leitura garantida por teste |
| [**EngPav: diário de obra com 3D**](https://adrianmoraisdev.github.io/adrian-higa-portfolio/cases/engpav/) | Relatório diário de pavimentação offline, com a rua em 3D | Electron · React 19 · three.js |

## Repositórios públicos

- 🤖 [**emporio-musica-agent**](https://github.com/adrianmoraisdev/emporio-musica-agent): agente de atendimento com LLM, function calling multi-provedor e RAG BM25 (Python, 40 testes)
- 🌐 [**adrian-higa-portfolio**](https://github.com/adrianmoraisdev/adrian-higa-portfolio): este portfólio, em Next.js com exportação estática e deploy no GitHub Pages
- 🏗️ [**EngPav-releases**](https://github.com/adrianmoraisdev/EngPav-releases): instaladores do EngPav com atualização automática

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=cs,dotnet,py,ts,react,nextjs,electron&theme=dark" alt="C#, .NET, Python, TypeScript, React, Next.js, Electron"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=mysql,sqlite,rabbitmq,docker,linux,aws,nginx,cloudflare,githubactions,bitbucket,git&theme=dark" alt="MySQL, SQLite, RabbitMQ, Docker, Linux, AWS, nginx, Cloudflare, GitHub Actions, Bitbucket, Git"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Claude_Code-agentes-D97757?style=flat-square&logo=anthropic&logoColor=white&labelColor=0B1222" alt="Claude Code"/>
  <img src="https://img.shields.io/badge/Codex-agentes-10A37F?style=flat-square&logo=openai&logoColor=white&labelColor=0B1222" alt="Codex"/>
  <img src="https://img.shields.io/badge/LLMs-function_calling-A78BFA?style=flat-square&labelColor=0B1222" alt="LLMs com function calling"/>
  <img src="https://img.shields.io/badge/RAG-BM25-38BDF8?style=flat-square&labelColor=0B1222" alt="RAG"/>
  <img src="https://img.shields.io/badge/SQL_Server-T--SQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white&labelColor=0B1222" alt="SQL Server"/>
  <img src="https://img.shields.io/badge/Trivy-DevSecOps-1904DA?style=flat-square&logo=aqua&logoColor=white&labelColor=0B1222" alt="Trivy"/>
</p>

## Trajetória

| Período | Cargo | Empresa |
|---|---|---|
| mai. 2024 — atual | Analista de TI Pleno · Software Engineer .NET & IA | Consórcio Guerra Brasil |
| jun. 2023 — abr. 2024 | Desenvolvedor Backend .NET | Ololu Plataforma Digital |
| jul. 2021 — mai. 2023 | Estagiário de Tecnologia · .NET Core e C# | Ololu Plataforma Digital |

---

<p align="center">
  <b>Procurando alguém que entregue .NET e IA em produção?</b><br/>
  <a href="https://www.linkedin.com/in/adrianhiga-tech">LinkedIn</a> ·
  <a href="mailto:adrianmorais.dev@gmail.com">adrianmorais.dev@gmail.com</a> ·
  <a href="https://adrianmoraisdev.github.io/adrian-higa-portfolio/">Portfólio</a>
</p>
