**English** · [日本語](https://github.com/carlmasters02/carlmasters02/blob/main/README.ja.md) · [Tiếng Việt](https://github.com/carlmasters02/carlmasters02/blob/main/README.vi.md) · [한국어](https://github.com/carlmasters02/carlmasters02/blob/main/README.ko.md) · [中文](https://github.com/carlmasters02/carlmasters02/blob/main/README.zh.md) · [ไทย](https://github.com/carlmasters02/carlmasters02/blob/main/README.th.md) · [Tagalog](https://github.com/carlmasters02/carlmasters02/blob/main/README.tl.md) · [Français](https://github.com/carlmasters02/carlmasters02/blob/main/README.fr.md)

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

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

---

### Core Language Projects

Small, self-contained tools that back the languages above with working code. Each one takes a single language and applies it to a real problem, so the proficiency I claim comes with something you can read.

| Project | Purpose | Tech |
| --- | --- | --- |
| [secret-scanner](https://github.com/carlmasters02/secret-scanner) | A CLI tool that scans codebases for hardcoded secrets, pairing regex pattern matching with Shannon entropy analysis to catch high-randomness strings that fixed patterns miss. Built to work through static analysis, file I/O, and CLI design in Python. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) |
| [cryptfile](https://github.com/carlmasters02/cryptfile) | A CLI tool for AES-256-GCM file encryption built on OpenSSL, deriving its key from a passphrase with PBKDF2. Built to work through low-level memory handling, binary file I/O, and cryptographic library integration in C. | ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) ![OpenSSL](https://img.shields.io/badge/-OpenSSL-721412?style=flat&logo=openssl&logoColor=white) |

---

### Security & Systems Projects

| Project | Purpose | Tech |
| --- | --- | --- |
| [network-protocol-analyzer](https://github.com/carlmasters02/network-protocol-analyzer) | A live packet analyzer decoding Ethernet, IPv4, TCP/UDP, and DNS from raw bytes by hand, with no parsing libraries. Streams to a terminal UI, exports PCAP for Wireshark, and flags port scans, DNS tunneling, and ARP spoofing as they happen. | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white) |
| [python-static-analyzer](https://github.com/carlmasters02/python-static-analyzer) | Finds SQL injection and command injection in Python source without running it, using AST parsing plus source-to-sink taint tracking to report the file, the line, and why it is exploitable. Precision and recall benchmarked against labeled vulnerable samples. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| [coverage-guided-fuzzer](https://github.com/carlmasters02/coverage-guided-fuzzer) | An AFL-style fuzzer that finds crashes by mutating inputs against coverage feedback rather than guessing blindly, then minimizes each crash to its smallest reproducing case. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) |
| [Crypto-Attack-Lab](https://github.com/carlmasters02/Crypto-Attack-Lab) | A hands-on lab of classic cryptographic attacks: padding oracle, hash length extension, ECB cut-and-paste, Wiener's attack on RSA, and a timing side channel. Each ships a vulnerable toy implementation, a working exploit, and a writeup of the real-world mistake behind it. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| [python-cli-template](https://github.com/carlmasters02/python-cli-template) | A reusable template for professional repo hygiene: `src/` layout, pytest with coverage, GitHub Actions CI, status badges, a Dockerfile, and semver-tagged releases. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |

---

### Web App Development

| Project | Purpose | Tech |
| --- | --- | --- |
| [FocusHear](https://focus-hear-app.vercel.app/) | A real time assistive communication platform for people with hearing loss. Every captioning app transcribes everyone at once, flooding the user with overlapping voices; FocusHear lets you choose whose voice you hear, with selective listening, a sign language bridge for ASL fingerspelling, and voice-enrolled speaker diarization. Built in 48 hours to take **1st place** at SDGs to Startups 2026, then rebuilt on a GPT-4o and ElevenLabs Scribe pipeline with authenticated accounts, billing, saved voice and face profiles, and a trained ONNX LSTM sign-language model, and taken to an invite-only Build with OpenAI event where it advanced to the first round. Live at [focus-hear-app.vercel.app](https://focus-hear-app.vercel.app/). | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![OpenAI](https://img.shields.io/badge/-GPT--4o-412991?style=flat&logo=openai&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat&logo=stripe&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white) |

---

### Portfolio & Websites

| Project | Purpose | Tech |
| --- | --- | --- |
| [My Personal Portfolio](https://carlmasters.com) | A personal portfolio where I showcase my skills, achievements, and more. Live at [carlmasters.com](https://carlmasters.com), with source at [My-Personal-Portfolio](https://github.com/carlmasters02/My-Personal-Portfolio). | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| [Kady's English Classes](https://kadysenglish.com) | A website designed and built for a freelance English teacher in Vietnam. Live at [kadysenglish.com](https://kadysenglish.com). | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |

---

### Events & Hackathons

| Date | Event | Notes |
| --- | --- | --- |
| July 2026 | Cursor Tokyo AI Meetup | An evening with the Cursor team at Datadog Japan, covering Cloud Agents and how to structure autonomous coding workflows. |
| July 2026 | Engineering Real World AI with Google and Google DeepMind | Keynote and a Google AI Studio workshop at Google Japan on taking AI systems from prototype to production. |
| July 2026 | Agent Forge AI Hackathon | A one-day hackathon on production-ready AI agents themed around Tokyo and Japanese culture. Entered solo. |
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
