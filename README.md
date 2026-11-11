<!-- Perfil bilíngue / Bilingual profile. Texto simples, sem imagens. -->

# João Pedro Panza Mainieri

```console
$ whoami
joão pedro · AI Resident @ Instituto Eldorado
engenharia de software @ PUC-Campinas · Campinas, BR

$ cat foco.txt
agentes que executam ações, não só conversam:
tool calling · MCP · RAG · voz
```

[Português](#português) · [English](#english) · [LinkedIn](https://linkedin.com/in/joao-pedro-panza-mainieri) · [E-mail](mailto:joaopedro.mainieri@gmail.com)

---

## Português

### Sobre

Sou residente de IA no Instituto Eldorado (Residência em IA, PUC-Campinas) e curso Engenharia de Software na PUC-Campinas. Gosto de construir agentes de IA que fazem algo útil: chamam ferramentas, lembram do contexto, consultam documentos e, quando faz sentido, conversam por voz. Também desenvolvo aplicações web e mobile completas, como freelancer.

Falo português (nativo) e inglês (Cambridge B2). Sou cidadão brasileiro e italiano.

### Projetos de IA em destaque

#### [aprendendo-agentes-ia](https://github.com/Jp-mainieri/aprendendo-agentes-ia)
**Em andamento · Residência em IA**

Trilha de estudo que constrói o mesmo agente em três níveis (SDK puro, LangChain e LangGraph) e termina em um agente de suporte com memória de longo prazo, RAG e aprovação humana antes de abrir um chamado.

- **IA:** tool calling, memória, embeddings, RAG com Chroma, LangGraph
- **Stack:** Python, Groq, LangChain, LangGraph

#### [neuramarket](https://github.com/Jp-mainieri/NeuraMarket)
**2º lugar · NeuraLake Launch Hackathon (19 e 20/09/2026)**

Marketplace em que agentes de IA contratam outros agentes, com o pagamento liberado só depois que um verificador confere a entrega. Créditos simulados.

- **IA:** servidor MCP próprio com 24 ferramentas, agentes sobre a API da NeuraLake, worker de navegador
- **Stack:** React, TanStack Start, Supabase, Playwright
- **Meu papel:** ideia, produto, arquitetura e desenho dos agentes. A implementação foi feita com Claude e Codex.
- [Demo online](https://market-agent-sync.lovable.app) · [Vídeo](https://github.com/Jp-mainieri/NeuraMarket/blob/main/docs/demo.mp4)

#### [finn](https://github.com/Jp-mainieri/finn)
**MVP em uso pessoal**

Assistente de voz para o carro: o motorista chama "Finn" e agentes de Spotify e Waze executam a ação, sem tirar as mãos do volante.

- **IA:** LLM com tool calling, orquestrador multiagente, A2A, wake word, STT e TTS. Não usa MCP.
- **Stack:** Next.js, TypeScript, NeuraLake, Groq, Porcupine
- **Meu papel:** projeto individual
- [Vídeo](https://github.com/Jp-mainieri/finn/blob/main/docs/demo.mp4)

#### [relay](https://github.com/Jp-mainieri/relay)
**Protótipo de hackathon · AI Tinkerers & OpenAI**

Agente de passagem de turno: confere se o checklist crítico foi dito e avisa por voz, uma única vez, se algo ficou faltando. As falas vêm de transcrições, sem microfone.

- **IA:** LLM com Structured Outputs, evidência literal para cada item, memória longitudinal
- **Stack:** Python, FastAPI, Next.js
- [Vídeo](https://github.com/Jp-mainieri/relay/blob/main/docs/demo.mp4)

#### [devready](https://github.com/juninhos-comunidade/devready)
**2º lugar · Hackathon Comunidade Juninhos & Nortjobs**

Plataforma de preparação para entrevistas de tecnologia: analisa a vaga, cruza com o currículo e o GitHub e monta treino e trilha de estudo.

- **IA:** Groq (análise da vaga, treino e extração do currículo)
- **Stack:** Next.js, Prisma, PostgreSQL
- **Meu papel:** autenticação, cadastro, upload do PDF, extração de competências e análise do GitHub (projeto em equipe)

#### [vizioai](https://github.com/Jp-mainieri/VizioAI)
**Protótipo de hackathon · Google DeepMind & AI Tinkerers (IA para impacto social)**

Extensão do Chrome para navegar por voz, pensada para pessoas cegas: o Gemini interpreta a página e executa a ação.

- **IA:** Gemini 2.5 Flash, ações em JSON, voz
- **Stack:** JavaScript, Chrome Manifest V3

### Dados e machine learning

- [emotional-dataset-pt-br](https://github.com/Jp-mainieri/emotional-dataset-pt-br): tradução do GoEmotions para português (54.263 comentários), com um pipeline de tradução por LLM.
- [Olimpo (residenciaIA-1-fakenews)](https://github.com/Jp-mainieri/residenciaIA-1-fakenews): detecção de fake news com SVM e atributos do spaCy. Minha parte foi o aprendizado supervisionado.

### Ferramentas

- [hacka-crawl](https://jp-mainieri.github.io/hacka-crawl/): radar de hackathons abertos no Brasil, cruzado com os meus projetos.

### Outros projetos

| Projeto | O que é |
|---|---|
| [devberry](https://devberry.com.br) | plataforma no estilo Duolingo para aprender a programar, no ar com usuários reais (Java e Python) |
| mesclainvest | plataforma de negociação de tokens, como líder técnico (Flutter e Firebase) |
| fast-attendance | chamada por QR code rotativo e áudio quase ultrassônico, em equipe de 5 (Spring Boot e Next.js) |
| [velpi](https://velpi.vercel.app) | catálogo no WhatsApp para pequenos vendedores (Next.js, sem backend) |
| [cli-pirates](https://github.com/Jp-mainieri/CLI-PIRATES) | combate naval em tempo real no terminal, em Python puro |

### Hackathons

| Evento | Projeto | Resultado |
|---|---|---|
| NeuraLake Launch Hackathon | neuramarket | 2º lugar |
| Hackathon Comunidade Juninhos & Nortjobs | devready | 2º lugar |
| Hackathon Global AI Tinkerers & OpenAI | relay | participação |
| AI Tinkerers & Google DeepMind (IA para impacto social) | vizioai | participação |
| Don't Skip Challenge | Burger Manager | participação |
| weHandle / Liga de TI PUC-Campinas | trustcheck | participação |

### Tecnologias

| Área | Ferramentas |
|---|---|
| IA | agentes com LLM, tool calling, MCP, RAG, LangGraph, LangChain, voz, Gemini, Groq |
| Web | TypeScript, Next.js, React |
| Mobile | Flutter, Dart, PWA |
| Backend | Python, FastAPI, Java, Spring Boot |
| Infra | Firebase, Docker, Vercel, Cloudflare |

---

## English

### About

I am an AI resident at Instituto Eldorado (Residência em IA, PUC-Campinas) and a Software Engineering student at PUC-Campinas. I like building AI agents that do something useful: they call tools, remember context, search documents and, when it makes sense, talk by voice. I also build complete web and mobile applications as a freelancer.

I speak Portuguese (native) and English (Cambridge B2). I am a Brazilian and Italian citizen.

### Featured AI projects

#### [aprendendo-agentes-ia](https://github.com/Jp-mainieri/aprendendo-agentes-ia)
**Work in progress · AI Residency**

A study path that builds the same agent at three levels (raw SDK, LangChain and LangGraph) and ends with a support agent that has long-term memory, RAG and human approval before opening a ticket.

- **AI:** tool calling, memory, embeddings, RAG with Chroma, LangGraph
- **Stack:** Python, Groq, LangChain, LangGraph

#### [neuramarket](https://github.com/Jp-mainieri/NeuraMarket)
**2nd place · NeuraLake Launch Hackathon (Sep 19-20, 2026)**

A marketplace where AI agents hire other agents, and payment is released only after a verifier checks the delivery. Credits are simulated.

- **AI:** a custom MCP server with 24 tools, agents on the NeuraLake API, a browser worker
- **Stack:** React, TanStack Start, Supabase, Playwright
- **My role:** idea, product, architecture and agent design. Implementation was done with Claude and Codex.
- [Live demo](https://market-agent-sync.lovable.app) · [Video](https://github.com/Jp-mainieri/NeuraMarket/blob/main/docs/demo.mp4)

#### [finn](https://github.com/Jp-mainieri/finn)
**MVP in personal use**

A voice assistant for the car: the driver says "Finn" and Spotify and Waze agents carry out the request, hands-free.

- **AI:** LLM with tool calling, multi-agent orchestrator, A2A, wake word, STT and TTS. It does not use MCP.
- **Stack:** Next.js, TypeScript, NeuraLake, Groq, Porcupine
- **My role:** solo project
- [Video](https://github.com/Jp-mainieri/finn/blob/main/docs/demo.mp4)

#### [relay](https://github.com/Jp-mainieri/relay)
**Hackathon prototype · AI Tinkerers & OpenAI**

A shift-handoff agent: it checks whether the critical checklist was spoken and alerts by voice, once, if something was missed. Speech comes from transcripts, with no microphone.

- **AI:** LLM with Structured Outputs, literal evidence for each covered item, longitudinal memory
- **Stack:** Python, FastAPI, Next.js
- [Video](https://github.com/Jp-mainieri/relay/blob/main/docs/demo.mp4)

#### [devready](https://github.com/juninhos-comunidade/devready)
**2nd place · Comunidade Juninhos & Nortjobs Hackathon**

An interview-prep platform for tech jobs: it analyzes the job posting, matches it against the resume and GitHub, and builds practice and a study plan.

- **AI:** Groq (job analysis, practice generation and resume extraction)
- **Stack:** Next.js, Prisma, PostgreSQL
- **My role:** authentication, signup, PDF upload, skills extraction and GitHub analysis (team project)

#### [vizioai](https://github.com/Jp-mainieri/VizioAI)
**Hackathon prototype · Google DeepMind & AI Tinkerers (AI for social impact)**

A Chrome extension for voice browsing, designed for blind users: Gemini interprets the page and performs the action.

- **AI:** Gemini 2.5 Flash, JSON actions, voice
- **Stack:** JavaScript, Chrome Manifest V3

### Data and machine learning

- [emotional-dataset-pt-br](https://github.com/Jp-mainieri/emotional-dataset-pt-br): Portuguese translation of GoEmotions (54,263 comments), with an LLM translation pipeline.
- [Olimpo (residenciaIA-1-fakenews)](https://github.com/Jp-mainieri/residenciaIA-1-fakenews): fake news detection with an SVM and spaCy features. My part was supervised learning.

### Tools

- [hacka-crawl](https://jp-mainieri.github.io/hacka-crawl/): a radar of open hackathons in Brazil, matched against my projects.

### Other projects

| Project | What it is |
|---|---|
| [devberry](https://devberry.com.br) | a Duolingo-style platform for learning to code, live with real users (Java and Python) |
| mesclainvest | a token trading platform, as technical lead (Flutter and Firebase) |
| fast-attendance | class attendance with rotating QR codes and near-ultrasound audio, in a team of 5 (Spring Boot and Next.js) |
| [velpi](https://velpi.vercel.app) | a WhatsApp catalog for small sellers (Next.js, no backend) |
| [cli-pirates](https://github.com/Jp-mainieri/CLI-PIRATES) | real-time naval combat in the terminal, in plain Python |

### Hackathons

| Event | Project | Result |
|---|---|---|
| NeuraLake Launch Hackathon | neuramarket | 2nd place |
| Comunidade Juninhos & Nortjobs Hackathon | devready | 2nd place |
| AI Tinkerers & OpenAI Global Hackathon | relay | participant |
| AI Tinkerers & Google DeepMind (AI for social impact) | vizioai | participant |
| Don't Skip Challenge | Burger Manager | participant |
| weHandle / Liga de TI PUC-Campinas | trustcheck | participant |

### Technologies

| Area | Tools |
|---|---|
| AI | LLM agents, tool calling, MCP, RAG, LangGraph, LangChain, voice, Gemini, Groq |
| Web | TypeScript, Next.js, React |
| Mobile | Flutter, Dart, PWA |
| Backend | Python, FastAPI, Java, Spring Boot |
| Infra | Firebase, Docker, Vercel, Cloudflare |

---

[LinkedIn](https://linkedin.com/in/joao-pedro-panza-mainieri) · [E-mail](mailto:joaopedro.mainieri@gmail.com) · [devberry.com.br](https://devberry.com.br)
