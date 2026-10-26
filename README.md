**English** · [日本語](https://github.com/carlmasters02/carlmasters02/blob/main/README.ja.md) · [Tiếng Việt](https://github.com/carlmasters02/carlmasters02/blob/main/README.vi.md) · [한국어](https://github.com/carlmasters02/carlmasters02/blob/main/README.ko.md) · [中文](https://github.com/carlmasters02/carlmasters02/blob/main/README.zh.md) · [ไทย](https://github.com/carlmasters02/carlmasters02/blob/main/README.th.md) · [Tagalog](https://github.com/carlmasters02/carlmasters02/blob/main/README.tl.md) · [Français](https://github.com/carlmasters02/carlmasters02/blob/main/README.fr.md) · [Deutsch](https://github.com/carlmasters02/carlmasters02/blob/main/README.de.md)

## 👋 Hi, I'm Carl Masters

Cybersecurity student at Temple University Japan.

[![Website](https://img.shields.io/badge/carlmasters.com-000000?style=flat&logo=googlechrome&logoColor=white)](https://carlmasters.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carl-masters-724951297)
![Location](https://img.shields.io/badge/Tokyo,%20Japan-informational?style=flat&logo=googlemaps&logoColor=white)

---

### Focus

I'm a cybersecurity student at Temple University Japan, drawn to the offensive side of the field and to understanding how systems fail in practice rather than in theory. Most of my work involves building security tooling from the ground up. I'd rather decode a protocol byte by byte than reach for a parsing library, and I learn an attack by implementing it against a deliberately vulnerable target instead of just reading about it. The layers that interest me most are the ones where assumptions break down: cryptographic implementations, input and memory handling, and raw network traffic. I care as much about explaining why a flaw exists as about finding it, which is why most of my projects ship with a writeup alongside the code.

---

### Core Languages

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)](https://www.w3schools.com/c/)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://dev.java)

---

### Core Language Projects

Small, self-contained tools that back the languages above with working code. Each one takes a single language and applies it to a real problem, so the proficiency I claim comes with something you can read.

| Project | Purpose | Tech |
| --- | --- | --- |
| [secret-scanner](https://github.com/carlmasters02/secret-scanner) | A CLI tool that scans codebases for hardcoded secrets, pairing regex pattern matching with Shannon entropy analysis to catch high-randomness strings that fixed patterns miss. Built to work through static analysis, file I/O, and CLI design in Python. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) |
| [cryptfile](https://github.com/carlmasters02/cryptfile) | A CLI tool for AES-256-GCM file encryption built on OpenSSL, deriving its key from a passphrase with PBKDF2. Built to work through low-level memory handling, binary file I/O, and cryptographic library integration in C. | [![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black)](https://www.w3schools.com/c/) [![OpenSSL](https://img.shields.io/badge/-OpenSSL-721412?style=flat&logo=openssl&logoColor=white)](https://www.openssl.org/) |
| [tlsprobe](https://github.com/carlmasters02/tlsprobe) | A CLI tool that audits remote TLS endpoints and certificate chains, pairing handshake negotiation with X.509 chain validation and separate legacy-protocol probes to catch deprecated protocols, weak cipher suites, and expiring certificates. Built to work through network socket programming, Public Key Infrastructure (PKI), and CLI design in Java. | [![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat&logo=openjdk&logoColor=white)](https://dev.java) |

---

### Security & Systems Projects

| Project | Purpose | Tech |
| --- | --- | --- |
| [AEGIS-threat-dashboard](https://github.com/carlmasters02/AEGIS-threat-dashboard) | A SOC-style threat operations dashboard with a 3D heatmap globe, built entirely on live public threat intelligence: Cloudflare Radar attack corridors, ransomware.live leak-site victims, CISA KEV with EPSS scores, SANS ISC DShield, and abuse.ch botnet C2 feeds. Nothing is simulated; when a source is down, its panels say so. A zero-dependency Node proxy caches every feed to respect upstream rate limits. Live at [aegisthreatdashboard.com](https://aegisthreatdashboard.com). | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Node.js](https://img.shields.io/badge/-Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)](https://nodejs.org/) [![Cloudflare Workers](https://img.shields.io/badge/-Cloudflare%20Workers-F38020?style=flat&logo=cloudflareworkers&logoColor=white)](https://workers.cloudflare.com/) |
| [network-protocol-analyzer](https://github.com/carlmasters02/network-protocol-analyzer) | A live packet analyzer decoding Ethernet, IPv4, TCP/UDP, and DNS from raw bytes by hand, with no parsing libraries. Streams to a terminal UI, exports PCAP for Wireshark, and flags port scans, DNS tunneling, and ARP spoofing as they happen. | [![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)](https://www.rust-lang.org/) |
| [python-static-analyzer](https://github.com/carlmasters02/python-static-analyzer) | Finds SQL injection and command injection in Python source without running it, using AST parsing plus source-to-sink taint tracking to report the file, the line, and why it is exploitable. Precision and recall benchmarked against labeled vulnerable samples. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [coverage-guided-fuzzer](https://github.com/carlmasters02/coverage-guided-fuzzer) | An AFL-style fuzzer that finds crashes by mutating inputs against coverage feedback rather than guessing blindly, then minimizes each crash to its smallest reproducing case. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black)](https://www.w3schools.com/c/) |
| [Crypto-Attack-Lab](https://github.com/carlmasters02/Crypto-Attack-Lab) | A hands-on lab of classic cryptographic attacks: padding oracle, hash length extension, ECB cut-and-paste, Wiener's attack on RSA, and a timing side channel. Each ships a vulnerable toy implementation, a working exploit, and a writeup of the real-world mistake behind it. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |

---

### Web App Development

| Project | Purpose | Tech |
| --- | --- | --- |
| [FocusHear](https://focus-hear-app.vercel.app/) | A real time assistive communication platform for people with hearing loss. Every captioning app transcribes everyone at once, flooding the user with overlapping voices; FocusHear lets you choose whose voice you hear, with selective listening, a sign language bridge for ASL fingerspelling, and voice-enrolled speaker diarization. Built in 48 hours to take **1st place** at SDGs to Startups 2026, then rebuilt on a GPT-4o and ElevenLabs Scribe pipeline with authenticated accounts, billing, saved voice and face profiles, and a trained ONNX LSTM sign-language model, and taken to an invite-only Build with OpenAI event where it advanced to the first round. Live at [focus-hear-app.vercel.app](https://focus-hear-app.vercel.app/). | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![OpenAI](https://img.shields.io/badge/-GPT--4o-412991?style=flat&logo=openai&logoColor=white)](https://openai.com/) [![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)](https://supabase.com/) [![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat&logo=stripe&logoColor=white)](https://stripe.com/) [![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white)](https://vercel.com/) |
| [NóiFlow AI](https://noiflow-ai.vercel.app/) | A teacher controlled AI workspace for English fluency in Vietnamese classrooms. Teachers create classes with join codes, turn real lesson words into bilingual, reviewable flashcards, generate readings and questions from that vocabulary, and attach spoken response prompts; students then practice flashcards, assignments, and voice tasks with instant AI feedback in one connected loop. Every AI draft stays under teacher review before publishing, with analytics surfacing weak words and skill patterns. Live at [noiflow-ai.vercel.app](https://noiflow-ai.vercel.app/). | [![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)](https://nextjs.org/) [![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white)](https://vercel.com/) |
| [MenYomi](https://github.com/carlmasters02/MenYomi) | Turns a photo of a Japanese restaurant menu into a live bilingual menu. OCR reads each dish and price, then every item gets an English translation, a short description, a cultural note, allergen flags, dietary filters, and spoken Japanese pronunciation. Built solo at the Agent Forge AI Hackathon, integrating six partner platforms (Nosana, Qwen Cloud, GMI Cloud, ai&, Daytona, Qoder) behind a single OpenAI-compatible wrapper. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |

---

### Hackathon Projects

| Project | Purpose | Tech |
| --- | --- | --- |
| [ai-wargame](https://github.com/carlmasters02/ai-wargame) | Two LLM agents fight a turn-based red-vs-blue wargame over a procedurally generated corporate network: a DeepSeek red team hunts the crown-jewel database under fog of war while a Kimi blue team triages noisy alerts. The match plays out live on an interactive network map, a human judge can inject surprise events or swap models mid-game, and every match exports as MITRE ATT&CK and STIX artifacts. Pure simulation: vulnerabilities are abstract game objects, with no exploit code and no real traffic. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)](https://neo4j.com/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [disaster-mutual-aid-matcher](https://github.com/carlmasters02/disaster-mutual-aid-matcher) | Builds and stress-tests individual evacuation plans for residents who need help evacuating, per Japan's evacuation-support mandate. A deterministic solver pairs residents with local helpers and re-plans live as a simulated quake blocks roads, cuts power, and spreads fires; LLMs handle intake parsing, Japanese plan documents, and multilingual dispatches, with Neo4j as the system of record and all inference kept on GPUs in Japan. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)](https://neo4j.com/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |

---

### Templates

| Project | Purpose | Tech |
| --- | --- | --- |
| [python-cli-template](https://github.com/carlmasters02/python-cli-template) | A reusable template for professional repo hygiene: `src/` layout, pytest with coverage, GitHub Actions CI, status badges, a Dockerfile, and semver-tagged releases. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [static-site-template](https://github.com/carlmasters02/static-site-template) | A reusable template for a static website in vanilla HTML/CSS/JS with no backend, with tests, GitHub Actions CI, and a Dockerfile. | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [flask-webapp-template](https://github.com/carlmasters02/flask-webapp-template) | A reusable template for Python + Flask web apps, with tests, GitHub Actions CI, and a Dockerfile. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask&logoColor=white)](https://flask.palletsprojects.com/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [express-webapp-template](https://github.com/carlmasters02/express-webapp-template) | A reusable template for Node + Express web apps with a vanilla HTML/CSS/JS frontend, with tests, GitHub Actions CI, and a Dockerfile. | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Node.js](https://img.shields.io/badge/-Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)](https://nodejs.org/) [![Express](https://img.shields.io/badge/-Express-000000?style=flat&logo=express&logoColor=white)](https://expressjs.com/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [react-express-template](https://github.com/carlmasters02/react-express-template) | A reusable template for a React (Vite) frontend backed by a Node/Express API, with tests, GitHub Actions CI, and a Dockerfile. | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)](https://react.dev/) [![Express](https://img.shields.io/badge/-Express-000000?style=flat&logo=express&logoColor=white)](https://expressjs.com/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |

---

### IoT Projects

| Project | Purpose | Tech |
| --- | --- | --- |
| [g2-vi-en-realtime](https://github.com/carlmasters02/g2-vi-en-realtime) | Live Vietnamese-to-English translation for Even Realities G2 smart glasses, built because the glasses' own Translate app doesn't support Vietnamese. Microphone audio streams over Bluetooth to OpenAI's realtime translation API, and English appears in the heads-up display about a second behind the speaker, with a bilingual transcript saved afterwards. Paired with [g2-relay](https://github.com/carlmasters02/g2-relay), a Cloudflare Worker relay that keeps the API key server-side, since browsers can't set authentication headers on a WebSocket. | [![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/) [![OpenAI](https://img.shields.io/badge/-OpenAI%20Realtime-412991?style=flat&logo=openai&logoColor=white)](https://platform.openai.com/docs/guides/realtime) [![Cloudflare Workers](https://img.shields.io/badge/-Cloudflare%20Workers-F38020?style=flat&logo=cloudflareworkers&logoColor=white)](https://workers.cloudflare.com/) |

---

### Portfolio & Websites

| Project | Purpose | Tech |
| --- | --- | --- |
| [PickYourLinux](https://github.com/carlmasters02/PickYourLinux) | A guide to choosing a Linux distribution. An interactive family tree maps 56 distros back to their Debian, Fedora and Arch roots, and a staged quiz first asks what you're setting up (a desktop, a server, a security toolkit, a privacy system, a gaming handheld or an IoT board), narrows the field at checkpoints, then recommends a specific distro and edition with its reasons, caveats and what to sort out before switching. Built in vanilla HTML, CSS and JavaScript with no build step and no third-party requests. Live at [pickyourlinux.com](https://pickyourlinux.com). | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![D3.js](https://img.shields.io/badge/-D3.js-F9A03C?style=flat&logo=d3&logoColor=white)](https://d3js.org/) |
| [My Personal Portfolio](https://carlmasters.com) | A personal portfolio where I showcase my skills, achievements, and more. Live at [carlmasters.com](https://carlmasters.com). | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |
| [Kady's English Classes](https://kadysenglish.com) | A website designed and built for a freelance English teacher in Vietnam. Live at [kadysenglish.com](https://kadysenglish.com). | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |

---

### Events & Hackathons

| Date | Event | Notes |
| --- | --- | --- |
| October 2026 | Tokyo Agent Hackathon | A one-day open-innovation hackathon hosted by +81 Builders, sponsored by Neo4j and ai&. Entered solo and built [AI Wargame](https://github.com/carlmasters02/ai-wargame), a live red-versus-blue simulation where a DeepSeek attacker and a Kimi defender fight over a procedurally generated corporate network on a Neo4j graph. |
| August 2026 | HITCON 2026 | Two days at Hacks In Taiwan Conference in Taipei, themed “When AI Acts: Hacking the Age of Agentic Systems.” Talks covered AI-driven vulnerability disclosure, agentic SOC automation, embedded hardware research, supply chain provenance, and nation-state tradecraft, closing with Orange Tsai's zero-click Edge sandbox escape. |
| July 2026 | Cursor Tokyo AI Meetup | An evening with the Cursor team at Datadog Japan, covering Cloud Agents and how to structure autonomous coding workflows. |
| July 2026 | Engineering Real World AI with Google and Google DeepMind | Keynote and a Google AI Studio workshop at Google Japan on taking AI systems from prototype to production. |
| July 2026 | Agent Forge AI Hackathon | A one-day hackathon on production-ready AI agents themed around Tokyo and Japanese culture. Entered solo and built [MenYomi](https://github.com/carlmasters02/MenYomi), which turns a photo of a Japanese menu into a bilingual menu with translations and allergen flags. |
| July 2026 | ai& × Moonshot Tokyo Hackathon Night | A single-evening hackathon built around Kimi K2.7 Code running on ai&'s inference platform. |
| July 2026 | Vibe Coders Tokyo: Local Models with Gemma 4 | Running open-weight models on local hardware, and what that changes for cost, latency, and control over your own data. |
| June 2026 | OpenAI × Tokyo AI: Build with OpenAI | Invite-only build event. Brought a rebuilt FocusHear with a production architecture and advanced to the first round. |
| June 2026 | SDGs to Startups Hackathon 2026 | **1st place.** A 48-hour build against UN Sustainable Development Goal 10 with FocusHear, isolating a single voice for people with hearing loss. |
| March 2026 | Builders Weekend 2026 | Shipped TabeTalk with a five-person Temple University Japan team: an AI dining app that identifies who ordered what by voice and splits the check. |
| March 2026 | UI/UX Hackathon | **1st place.** Researched user needs, wireframed, and prototyped an interface, then defended every design decision to the judges. |

---

### 📚 Latest Articles

- [How to Write a Resume That Actually Gets Read](https://carlmasters.com/article-resume.html)
- [Everyday Cybersecurity Habits That Actually Matter](https://carlmasters.com/article-cybersecurity.html)
- [The Privacy Stack: Open Source and Encrypted Alternatives for Every App You Use](https://carlmasters.com/article-privacy.html)

---

### Links

- 🌐 Website: [carlmasters.com](https://carlmasters.com)
- 💼 LinkedIn: [carl-masters](https://www.linkedin.com/in/carl-masters-724951297)
- 🛠️ Developer email: [carl.masters.dev@protonmail.com](mailto:carl.masters.dev@protonmail.com), for bug reports, issues, and questions about my code
- 📧 Professional email: [carl.masters.professional@protonmail.com](mailto:carl.masters.professional@protonmail.com), for professional connections, job inquiries, and internships
