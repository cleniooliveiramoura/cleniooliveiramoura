<div align="center">
  <img src="imagens/Capa_github.png" alt="Header" width="100%"/>
</div>

<h1 align="center">Clênio Oliveira</h1>

<p align="center"><b>AI Agent Engineer e fundador do Kermartin</b>: construo sistemas multiagente, RAG e SaaS para LegalTech, GovTech e HealthTech, do protótipo à produção.</p>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/clenio-oliveira)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/afonso.clenio/)
[![Kermartin](https://img.shields.io/badge/-Kermartin_IA-1E3A8A?style=flat-square&logoColor=white)](https://kermartin.ia.br)
[![Profile Views](https://komarev.com/ghpvc/?username=cleniooliveiramoura&color=blue&style=flat-square)](https://github.com/cleniooliveiramoura)

</div>

<p align="center"><sub>Novo perfil: repositórios migrados de <a href="https://github.com/clenio77">@clenio77</a>.</sub></p>

---

## 🚀 Sobre

- 🔭 Fundador do [Kermartin](https://kermartin.ia.br), SaaS de análise jurídica com IA.
- 🎓 Bacharel em Sistemas de Informação (2018).
- 🤖 Orquestração multiagente (CrewAI), RAG, modelagem preditiva e Edge AI.
- 🛡️ Anonimização local sob a LGPD e auditoria de APIs.

---

## 🔨 Construindo agora

- 🏪 **Portal do comércio do Jardim Holanda** (Uberlândia): site estático em Astro alimentado por planilha, com coleta de dados em Python.
- 🛞 **Landing pages de alta conversão para Google Ads**, como a [Borracharia Bodoque](https://bodoqueborrachariamovel.vercel.app).
- 📖 **Leitor da Escrivaninha**: leitor de PDF em formato de livro, 100% no navegador e PWA.

<sub>Repositórios privados; links apenas para o que está no ar.</sub>

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

### ⚖️ [Kermartin IA](https://kermartin.ia.br)
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
<img src="https://raw.githubusercontent.com/cleniooliveiramoura/deep-trace/HEAD/assets/og-banner.png" alt="DeepTrace" width="100%"/><br/>
Web app + extensão Chrome de fact-checking de vídeos contra desinformação, com Google Gemini multimodal.<br/>
**Stack:** JavaScript · Gemini<br/>
🌐 [deep-trace-analysis.vercel.app](https://deep-trace-analysis.vercel.app)

</td>
<td width="50%" valign="top">

### 🎵 [SonicStream](https://github.com/cleniooliveiramoura/sonicStream)
Extrator de áudio (MP3) e vídeo (MP4) self-hosted, com fila em threads e PWA responsivo.<br/>
**Stack:** Python · FastAPI · yt-dlp · FFmpeg · Docker

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [MedGemma Guardian](https://github.com/cleniooliveiramoura/MedGemma-Guardian)
Agente de suporte à decisão clínica e auditoria de prescrições, com privacidade local (Kaggle MedGemma Impact Challenge).<br/>
**Stack:** Python · MedGemma · FastAPI · FHIR

</td>
<td width="50%" valign="top">

### ⛪ [Liturgia Isaías — Caderno da Missa](https://liturgia-isaias.vercel.app)
Repertório litúrgico digital com letras e cifras para as missas.<br/>
**Stack:** Next.js · TypeScript · Tailwind · PWA<br/>
🌐 [liturgia-isaias.vercel.app](https://liturgia-isaias.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💬 [KoTauri](https://github.com/cleniooliveiramoura/clenio-kotauri)
Cliente desktop leve para Telegram (Tauri 2 + Telegram Web K) e shell PWA para celular.<br/>
**Stack:** Rust · Tauri 2 · PWA

</td>
</tr>
</table>

---

## 📂 Outros Projetos

**⚖️ GovTech & LegalTech:** CVP-IA (auditoria de gastos parlamentares) · Licita-AI (licitações no Microsoft 365)<br/>
**📱 Apps e SaaS:** Agenda Clinical (SaaS para psicólogos) · Carteira Inteligente (investimentos com IA) · RotaFácil (rotas de entrega)<br/>
**⛪ Igreja e comunidade:** [Capelania Jesus Bom Pastor](https://capelania.vercel.app) · Ministério Isaías

<sub>Repositórios privados; os links levam aos sites no ar.</sub>

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
    2025 : Fundador do Kermartin
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
