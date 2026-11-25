<div align="center">

# `matt1x_` · Matheus Machado

**AI Product Builder & Soluções com IA**  
*Criador do ecossistema **Matt1x / T1x** — apps local-first, automações e sistemas multiagentes construídos em parceria com Inteligência Artificial.*

[![E-mail](https://img.shields.io/badge/Contato-matt1x--t1x%40hotmail.com-FF6B00?style=flat-square&logo=maildotru&logoColor=white)](mailto:matt1x-t1x@hotmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-%40matt1x__channel-18181B?style=flat-square&logo=youtube&logoColor=FF6B00)](https://www.youtube.com/@matt1x_channel)
[![Twitch](https://img.shields.io/badge/Twitch-matt1xchannel-18181B?style=flat-square&logo=twitch&logoColor=FF6B00)](https://www.twitch.tv/matt1xchannel)
[![Kick](https://img.shields.io/badge/Kick-matt1x--23-18181B?style=flat-square&logo=kick&logoColor=FF6B00)](https://kick.com/matt1x-23)

</div>

---

### 🤖 Transparência Primeiro: Como Eu Construo

Eu **não** me apresento como um programador tradicional que decora sintaxe e escreve código manualmente linha por linha.

Eu atuo como **AI Product Builder**: uno **visão de produto, UX, arquitetura de sistemas e orquestração de agentes de IA** para transformar problemas reais em ferramentas, sites e automações que realmente funcionam no mundo real — testadas, empacotadas com instalador, assinadas com `SHA-256` e publicadas.

- **O que eu faço na prática:** diagnóstico do problema, desenho de escopo e interface, orquestração de modelos/agentes de IA (nuvem e local), validação de qualidade (QA/WCAG AA), versionamento e entrega.
- **Filosofia:** **Local-First**, controle total dos dados pelo usuário e evolução contínua em IA aplicada.

---

### 🏗️ Vitrine Técnica Open-Source (Código, Testes & CI)

> Repositórios públicos com foco em **problemas reais de produção**, seguindo o Padrão de Engenharia Matt1x (testes de falha, Docker Compose, GitHub Actions CI e seção explícita de *Limitações Conhecidas*):

| Repositório | Foco de Engenharia | Destaques Técnicos |
| :--- | :--- | :--- |
| **[t1x-inventory-engine](https://github.com/Matt1x-T1x/t1x-inventory-engine)** | Concorrência & Transações | Transações atômicas (`BEGIN IMMEDIATE`), teste real de 10 compras simultâneas (zero overselling), rollback, migrations, OpenAPI, Docker & CI. |
| **[t1x-billing-webhooks](https://github.com/Matt1x-T1x/t1x-billing-webhooks)** | Webhooks & Idempotência | Validação criptográfica HMAC-SHA256 (`timingSafeEqual`), tabela de idempotência (3x reenvio seguro), proteção contra eventos fora de ordem, Docker & CI. |
| **[t1x-ai-support-triage](https://github.com/Matt1x-T1x/t1x-ai-support-triage)** | IA Resiliente & Evals | Saída JSON validada com `Zod`, fallback sem perda de dados (API 503 / JSON quebrado), fila de reprocessamento e **Eval Suite** com dataset rotulado no CI. |

---

### 🚀 Projetos em Destaque (Ecossistema `T1x`)

> *Os códigos-fonte comerciais/proprietários ficam em repositórios privados; abaixo estão as releases públicas oficiais com instaladores verificados.*

#### 💼 Negócios, Automação & Agentes de IA
| Projeto | O que resolve | Plataformas | Releases |
| :--- | :--- | :---: | :---: |
| **[T1x Sell1ng](https://github.com/Matt1x-T1x/t1x-sell1ng-releases)** | Fábrica de sites locais com **esteira de 11 agentes de IA**, WhatsApp Cloud API, LGPD, 17 checks de QA/WCAG AA, deploy Cloudflare Pages e Pix. | Windows · Web | [Releases](https://github.com/Matt1x-T1x/t1x-sell1ng-releases/releases) |
| **[CalculaT1x](https://github.com/Matt1x-T1x/m-calc-releases)** | Sistema desktop 100% local para avaliação, troca, estoque e margem de lucro em revenda Apple. | Windows · macOS | [Releases](https://github.com/Matt1x-T1x/m-calc-releases/releases) |
| **T1x Auto Sales** *(Lab)* | CRM local em SQLite criptografado com rascunhos comerciais SPIN assistidos por IA e propostas HTML. | Windows | *Em preparo* |

#### 🖥️ Ferramentas Desktop & Local-First
| Projeto | O que resolve | Plataformas | Releases |
| :--- | :--- | :---: | :---: |
| **[T1x Legacy](https://github.com/Matt1x-T1x/t1x-legacy-releases)** | Plataforma local-first de memória familiar, história e legado em formato aberto (`Markdown + YAML`). | Windows | [Releases](https://github.com/Matt1x-T1x/t1x-legacy-releases/releases) |
| **[T1x Screen](https://github.com/Matt1x-T1x/t1x-screen-releases)** | Compartilhamento de até 3 telas em 1080p 60fps, câmera e voz — convidados entram pelo navegador sem instalar nada. | Windows · Web | [Releases](https://github.com/Matt1x-T1x/t1x-screen-releases/releases) |
| **[T1x Stream Hub](https://github.com/Matt1x-T1x/t1x-stream-hub-releases)** | Central para lives (Twitch + YouTube) com **AI Chat Shield local**, Voice Macros offline (Vosk), Soundboard e OBS. | Windows | [Releases](https://github.com/Matt1x-T1x/t1x-stream-hub-releases/releases) |
| **[Mus1t1x](https://github.com/Matt1x-T1x/Mus1t1x-releases)** | Estúdio musical com afinador cromático, detecção de acordes por áudio do YouTube, cifras e teleprompter. | Windows | [Releases](https://github.com/Matt1x-T1x/Mus1t1x-releases/releases) |
| **[T1x Client](https://github.com/Matt1x-T1x/tix-client-cs-releases)** | Cliente leve em C# com otimização, configs pro e diagnóstico para CS2 & Deadlock (assinado RSA-SHA256). | Windows | [Releases](https://github.com/Matt1x-T1x/tix-client-cs-releases/releases) |

#### 🧪 Laboratório de IA, Mídia & Games
- **Mente e Corpo:** companheiro digital autônomo com córtex híbrido (`Ollama + Gemini`), memória evolutiva em Markdown, voz neural PT-BR (`edge-tts`) e corpo 3D (`Three.js / .GLB`).
- **T1x AutoRender & T1x Studio:** pipelines 100% locais de vídeo e motion graphics (`Remotion`, `Three.js`, `ComfyUI`, `Ollama`).
- **Games Autorais:** 5 projetos entre **Spawn** (*Sakura Drift Tuning*, *Brewmaster Grid Artesanal*, *In Search of T1x*), **Roblox** (*The Cookie Theft*) e **Unity** (*Sinuca de Buteco*).

---

### 🛠️ Stack & Ferramentas que Orquestro

`Agentes de IA (Gemini · Claude · Antigravity)` · `IA Local (Ollama · ComfyUI · Vosk · edge-tts)` · `Next.js · Tailwind · TypeScript` · `SQLite · Markdown/YAML` · `Cloudflare Pages · GitHub Releases · WhatsApp API` · `Remotion · Three.js`

---

### 🤝 Vamos Trabalhar Juntos?

Estou aberto a **projetos sob demanda (freelance)** e **oportunidades CLT/PJ** em **IA Aplicada, Automação, Agentes e Produto Digital**:

- **Automações & Agentes de IA** (fluxos multiagentes, WhatsApp, integrações e produtividade)
- **Landing Pages & Sistemas Web** (design autoral, acessibilidade WCAG AA e deploy rápido)
- **Ferramentas Internas & Apps Sob Medida** (softwares local-first focados na rotina do negócio)

📩 **E-mail:** `matt1x-t1x@hotmail.com` · 💬 **Discord:** `matt1xchannel`
