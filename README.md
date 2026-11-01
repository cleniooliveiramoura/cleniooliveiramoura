<div align="center">
  <img src="imagens/Capa_github.png" alt="Header" width="100%"/>
</div>

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=600&height=70&duration=4000&lines=Olá!+👋;Sou+o+Clênio+Oliveira!;AI+Engineer+%26+SaaS+Founder;Arquiteturas+Multiagente+%26+RAG" alt="Typing SVG"/>
</h1>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/clenio-oliveira)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/afonso.clenio/)
[![Genesys](https://img.shields.io/badge/-Genesys_Tecnologia-7928CA?style=flat-square&logo=openai&logoColor=white)](https://genesys.ia.br)
[![Kermartin](https://img.shields.io/badge/-Kermartin_IA-1E3A8A?style=flat-square&logoColor=white)](https://kermartin.ia.br)
[![Profile Views](https://komarev.com/ghpvc/?username=cleniooliveiramoura&color=blue&style=flat-square)](https://github.com/cleniooliveiramoura)

</div>

> ℹ️ Este é meu novo perfil. Meus repositórios foram migrados de [@clenio77](https://github.com/clenio77).

---

## 🚀 Perfil Profissional

**AI Agent Engineer | Arquiteto de Sistemas SaaS | Cientista de Dados**

Especializado no desenvolvimento de ecossistemas inteligentes corporativos e soluções completas ponta a ponta (SaaS). Atuo com foco em modelagem preditiva, engenharia de prompts avançada (Chain-of-Thought) e orquestração de sistemas multiagente autônomos para setores regulados de alta complexidade, como **LegalTech**, **GovTech** e **HealthTech**.

- 🔭 **Fundador**: [Kermartin](https://kermartin.ia.br) (SaaS de análise jurídica com IA) e [Genesys Tecnologia](https://genesys.ia.br) (consultoria que implanta e opera o Kermartin).
- 🎓 **Formação**: Bacharel em Sistemas de Informação (2018).
- 🤖 **Especialidades em IA**: Orquestração Multiagente (CrewAI), RAG, Modelagem Preditiva e Edge AI para processamento local de dados clínicos.
- 🛡️ **Segurança e Conformidade**: Pipelines locais de anonimização sob a LGPD e auditoria de APIs.

---

## 🤖 Arquitetura de Agentes Inteligentes

```mermaid
graph TD
    Input["Fontes de Dados: Diários Oficiais, PJe, Editais, APIs"] --> Scraper["Agentes de Ingestão: Playwright / BeautifulSoup"]
    Scraper --> Clean["Higienização e Anonimização Local (LGPD)"]
    Clean --> RAG["RAG Engine: Vetores de Jurisprudência"]
    RAG --> Orch{"Orquestrador de Agentes"}
    Orch --> Law["Agente Jurídico: Júri / Penal"]
    Orch --> Comp["Agente de Compliance e Editais"]
    Orch --> Clin["Agente Clínico: Auditoria e CoT"]
    Law --> Val["Validador e Human-in-the-Loop"]
    Comp --> Val
    Clin --> Val
    Val --> Action["Action Agents: Alertas e Relatórios FHIR/PDF"]
```

---

## 🏆 Projetos em Destaque

<table>
<tr>
<td width="50%" valign="top">

### ⚖️ [Kermartin IA](https://github.com/cleniooliveiramoura/kermartin)
SaaS de análise jurídica com IA para escritórios brasileiros: Tribunal do Júri e fluxos B2B multimódulo.<br/>
**Stack:** Python · Django · React · Celery · CrewAI<br/>
🌐 [kermartin.ia.br](https://kermartin.ia.br)

</td>
<td width="50%" valign="top">

### 🥊 [Model Arena](https://github.com/cleniooliveiramoura/model-arena)
Federação de sandboxes para comparar modelos e agentes com scoring blindado, scorecard capacidade × segurança e discussão agentic entre modelos.<br/>
**Stack:** Python

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔍 [DeepTrace](https://github.com/cleniooliveiramoura/deep-trace)
Web app + extensão Chrome de fact-checking de vídeos contra desinformação, com Google Gemini multimodal.<br/>
**Stack:** JavaScript · Gemini<br/>
🌐 [deep-trace-analysis.vercel.app](https://deep-trace-analysis.vercel.app)

</td>
<td width="50%" valign="top">

### 🏛️ [CVP-IA — Painel Parlamentar](https://github.com/cleniooliveiramoura/painel-de-gastos-de-parlamentares)
Consulta e auditoria de gastos, votações, proposições e alertas de parlamentares da Câmara e do Senado.<br/>
**Stack:** JavaScript · Supabase · PWA

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [MedGemma Guardian](https://github.com/cleniooliveiramoura/MedGemma-Guardian)
Agente de suporte à decisão clínica e auditoria de prescrições, com privacidade local (Kaggle MedGemma Impact Challenge).<br/>
**Stack:** Python · MedGemma · FastAPI · FHIR

</td>
<td width="50%" valign="top">

### 🎵 [Liturgia Isaías — Caderno da Missa](https://github.com/cleniooliveiramoura/liturgia-isaias)
Repertório litúrgico digital com letras e cifras para as missas.<br/>
**Stack:** Next.js · TypeScript · Tailwind · PWA<br/>
🌐 [liturgia-isaias.vercel.app](https://liturgia-isaias.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ✍️ [ContentOS](https://github.com/cleniooliveiramoura/ContentOS)
Sistema operacional editorial AI-native para produção de conteúdo técnico, integrado a pipelines como o [YouTube Lo-Fi Workflow](https://github.com/cleniooliveiramoura/youtube-lofi-workflow).<br/>
**Stack:** Specs em Markdown · agentes no Cursor · Python

</td>
<td width="50%" valign="top">

### 💬 [KoTauri](https://github.com/cleniooliveiramoura/clenio-kotauri)
Cliente desktop leve para Telegram (Tauri 2 + Telegram Web K) e shell PWA para celular.<br/>
**Stack:** Rust · Tauri 2 · PWA

</td>
</tr>
</table>

---

## 📂 Outros Projetos

**🤖 IA, agentes e automação** —
[ClenioClaw](https://github.com/cleniooliveiramoura/clenioclaw) (assistente pessoal no Telegram) ·
[Hermes](https://github.com/cleniooliveiramoura/hermes) (config do Hermes Agent) ·
[Mentor de Concursos](https://github.com/cleniooliveiramoura/agente_concurseiro) ·
[Agente Social Media](https://github.com/cleniooliveiramoura/agente_social_media) ·
[SocialBot](https://github.com/cleniooliveiramoura/socialbot) ·
[Agente Autônomo](https://github.com/cleniooliveiramoura/agente-autonomo)

**⚖️ LegalTech & GovTech** —
[Genesys](https://github.com/cleniooliveiramoura/genesys) (site e docs da Genesys Tecnologia) ·
[Licita-AI](https://github.com/cleniooliveiramoura/licita-ai) (licitações no Microsoft 365 / Power Platform / Azure Functions) ·
[Licitação AI](https://github.com/cleniooliveiramoura/licitacao-ai) ·
[Advocacia AI](https://github.com/cleniooliveiramoura/escritorio-ai-advocacia)

**📱 Apps, SaaS e ferramentas** —
[Agenda Clinical](https://github.com/cleniooliveiramoura/pscologo-ai) (SaaS para psicólogos) ·
[Carteira Inteligente](https://github.com/cleniooliveiramoura/carteira-inteligente) (investimentos com IA) ·
[Gestor Financeiro](https://github.com/cleniooliveiramoura/gestor-financeiro) ·
[RotaFácil](https://github.com/cleniooliveiramoura/rota-facil) (rotas de entrega) ·
[Fênix PDF](https://github.com/cleniooliveiramoura/Fenix-PDF) ·
[Leitor da Escrivaninha](https://github.com/cleniooliveiramoura/leitor-pdf-livro) (PDF como livro) ·
[SonicStream](https://github.com/cleniooliveiramoura/sonicStream) (extrator de áudio/vídeo PWA) ·
[Portal Jardim Holanda](https://github.com/cleniooliveiramoura/portal-jardim-holanda) (comércio do bairro)

**🌐 Sites para clientes** —
[Borracharia Bodoque](https://github.com/cleniooliveiramoura/bodoqueborrachariamovel) ([no ar](https://bodoqueborrachariamovel.vercel.app)) ·
[Cerimonial Helton Oliveira](https://github.com/cleniooliveiramoura/cerimonial)

**⛪ Igreja e liturgia** —
[Capelania Jesus Bom Pastor](https://github.com/cleniooliveiramoura/capelania) ([no ar](https://capelania.vercel.app)) ·
[Ministério Isaías](https://github.com/cleniooliveiramoura/ministerioisaias) ·
[Comunidade Santo Expedito](https://github.com/cleniooliveiramoura/santoexpedito) ·
[Acalanto Sagrado](https://github.com/cleniooliveiramoura/acalanto-sagrado-legal)

**📊 Ciência de dados e estudos** —
[RiskRating](https://github.com/cleniooliveiramoura/RiskRating) ·
[Recomendação de Filmes](https://github.com/cleniooliveiramoura/movies_recomendation_system) ·
[Prever Salário](https://github.com/cleniooliveiramoura/Prever_salario) ·
[KC House](https://github.com/cleniooliveiramoura/kc_house) ·
[Data Science em Produção](https://github.com/cleniooliveiramoura/DataScienceEmProducao) ·
[Educação Financeira com IA](https://github.com/cleniooliveiramoura/educacao-financeira) ·
[Bootcamp Bradesco GenAI](https://github.com/cleniooliveiramoura/bootcamp-bradesco-dio-genai-dados-cyber) ·
[Seja Data Science](https://github.com/cleniooliveiramoura/sejadatascience)

---

## 🛠️ Stack Tecnológica

<div align="center">

**IA & Orquestração**<br/>
![CrewAI](https://img.shields.io/badge/-CrewAI-FF6B35?style=flat-square&logo=robot&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/-Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Linguagens**<br/>
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)

**Backend & Dados**<br/>
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Frontend & Apps**<br/>
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/-Tailwind-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white)
![Astro](https://img.shields.io/badge/-Astro-BC52EE?style=flat-square&logo=astro&logoColor=white)
![Tauri](https://img.shields.io/badge/-Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)
![PWA](https://img.shields.io/badge/-PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)

**Automação & Infra**<br/>
![Playwright](https://img.shields.io/badge/-Playwright-45ba4b?style=flat-square&logo=playwright&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/-Render-46E3B7?style=flat-square&logo=render&logoColor=white)
![Power Automate](https://img.shields.io/badge/-Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white)

</div>

---

## 💼 Linha do Tempo

```mermaid
timeline
    title Trajetória e Evolução
    2018 : Bacharelado em Sistemas de Informação
    2020 : Machine Learning e Ciência de Dados
    2024 : Sistemas Multiagente (CrewAI) e RAG
    2025 : Fundador do Kermartin e da Genesys Tecnologia
         : Licita-AI (SharePoint / Power Automate / Azure Functions)
    2026 : MedGemma Impact Challenge (Google Health AI)
         : Model Arena, DeepTrace e CVP-IA
```

---

## 📊 Estatísticas do GitHub

<div align="center">
  <img height="180" src="https://github-readme-stats-eight-theta.vercel.app/api?username=cleniooliveiramoura&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="GitHub Stats"/>
  <img height="180" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=cleniooliveiramoura&layout=compact&langs_count=8&theme=tokyonight&hide=html,css" alt="Top Langs"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=cleniooliveiramoura&theme=tokyonight" alt="GitHub Streak"/>
</div>
