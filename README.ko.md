[English](https://github.com/carlmasters02/carlmasters02/blob/main/README.md) · [日本語](https://github.com/carlmasters02/carlmasters02/blob/main/README.ja.md) · [Tiếng Việt](https://github.com/carlmasters02/carlmasters02/blob/main/README.vi.md) · **한국어** · [中文](https://github.com/carlmasters02/carlmasters02/blob/main/README.zh.md) · [ไทย](https://github.com/carlmasters02/carlmasters02/blob/main/README.th.md) · [Tagalog](https://github.com/carlmasters02/carlmasters02/blob/main/README.tl.md) · [Français](https://github.com/carlmasters02/carlmasters02/blob/main/README.fr.md)

## 👋 안녕하세요, Carl Masters입니다

템플대학교 재팬 캠퍼스(Temple University Japan)에서 사이버보안을 공부하고 있습니다.

[![웹사이트](https://img.shields.io/badge/carlmasters.com-000000?style=flat&logo=googlechrome&logoColor=white)](https://carlmasters.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carl-masters-724951297)
![위치](https://img.shields.io/badge/%EB%8F%84%EC%BF%84%2C%20%EC%9D%BC%EB%B3%B8-informational?style=flat&logo=googlemaps&logoColor=white)

*링크된 저장소와 글, 웹사이트는 모두 영어로 되어 있습니다.*

---

### 관심 분야

저는 템플대학교 재팬 캠퍼스에서 사이버보안을 공부하고 있으며, 이 분야의 공격 측면과 시스템이 이론이 아니라 실제로 어떻게 무너지는지를 이해하는 데 끌립니다. 제 작업의 대부분은 보안 도구를 밑바닥부터 만드는 일입니다. 파싱 라이브러리에 기대기보다 프로토콜을 한 바이트씩 직접 해독하는 편을 택하고, 공격 기법은 글로 읽고 마는 대신 의도적으로 취약하게 만든 대상에 직접 구현해 보면서 익힙니다. 가장 흥미로운 계층은 전제가 무너지는 지점입니다. 암호 구현, 입력과 메모리 처리, 그리고 가공되지 않은 네트워크 트래픽이 그렇습니다. 결함을 찾아내는 것만큼이나 그것이 왜 존재하는지 설명하는 일을 중요하게 여기며, 그래서 제 프로젝트는 대부분 코드와 함께 분석 글이 딸려 있습니다.

---

### 주요 언어

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

---

### 주요 언어 프로젝트

위에 적은 언어들을 실제로 돌아가는 코드로 뒷받침하는, 작고 독립적인 도구들입니다. 각각 하나의 언어를 골라 현실의 문제에 적용했기 때문에, 제가 내세우는 숙련도에는 언제나 읽어볼 수 있는 결과물이 따라옵니다.

| 프로젝트 | 목적 | 기술 |
| --- | --- | --- |
| [secret-scanner](https://github.com/carlmasters02/secret-scanner) | 코드베이스를 훑어 하드코딩된 비밀 정보를 찾아내는 CLI 도구로, 정규식 패턴 매칭과 섀넌 엔트로피 분석을 함께 써서 고정된 패턴으로는 놓치는 무작위성 높은 문자열까지 잡아냅니다. Python에서의 정적 분석, 파일 I/O, CLI 설계를 익히려고 만들었습니다. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) |
| [cryptfile](https://github.com/carlmasters02/cryptfile) | OpenSSL을 기반으로 한 AES-256-GCM 파일 암호화 CLI 도구로, PBKDF2를 써서 암호 구절로부터 키를 유도합니다. C에서의 저수준 메모리 처리, 바이너리 파일 I/O, 암호 라이브러리 연동을 익히려고 만들었습니다. | ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) ![OpenSSL](https://img.shields.io/badge/-OpenSSL-721412?style=flat&logo=openssl&logoColor=white) |

---

### 보안 및 시스템 프로젝트

| 프로젝트 | 목적 | 기술 |
| --- | --- | --- |
| [network-protocol-analyzer](https://github.com/carlmasters02/network-protocol-analyzer) | 파싱 라이브러리를 전혀 쓰지 않고 Ethernet, IPv4, TCP/UDP, DNS를 원시 바이트에서 직접 해석하는 실시간 패킷 분석기입니다. 터미널 UI로 스트리밍하고, Wireshark용 PCAP을 내보내며, 포트 스캔과 DNS 터널링, ARP 스푸핑을 벌어지는 그 순간에 잡아냅니다. | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white) |
| [python-static-analyzer](https://github.com/carlmasters02/python-static-analyzer) | 프로그램을 실행하지 않고도 Python 소스에서 SQL 인젝션과 명령어 인젝션을 찾아냅니다. AST 파싱과 소스에서 싱크로 이어지는 오염 추적을 통해 어떤 파일의 몇 번째 줄인지, 왜 악용될 수 있는지까지 보고합니다. 정밀도와 재현율은 라벨이 붙은 취약 샘플로 벤치마크했습니다. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| [coverage-guided-fuzzer](https://github.com/carlmasters02/coverage-guided-fuzzer) | 무작정 찍어보는 대신 커버리지 피드백에 따라 입력을 변형해 크래시를 찾아내는 AFL 방식의 퍼저입니다. 찾아낸 크래시는 재현 가능한 최소 사례로 줄여 줍니다. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) |
| [Crypto-Attack-Lab](https://github.com/carlmasters02/Crypto-Attack-Lab) | 고전적인 암호 공격을 직접 손으로 해보는 실습 랩입니다. 패딩 오라클, 해시 길이 확장, ECB 잘라 붙이기, RSA에 대한 위너 공격, 그리고 타이밍 부채널을 다룹니다. 각 항목마다 취약하게 만든 간단한 구현, 실제로 동작하는 익스플로잇, 그 뒤에 있는 현실의 실수를 짚는 글이 함께 들어 있습니다. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| [python-cli-template](https://github.com/carlmasters02/python-cli-template) | 제대로 된 저장소 관리 습관을 위한 재사용 가능한 템플릿입니다. `src/` 구조, 커버리지를 포함한 pytest, GitHub Actions CI, 상태 배지, Dockerfile, 그리고 semver 태그를 붙인 릴리스를 갖추고 있습니다. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |

---

### 웹 앱 개발

| 프로젝트 | 목적 | 기술 |
| --- | --- | --- |
| [FocusHear](https://focus-hear-app.vercel.app/) | 청각에 어려움을 겪는 사람들을 위한 실시간 의사소통 보조 플랫폼입니다. 기존 자막 앱은 그 자리의 모든 사람을 한꺼번에 받아쓰기 때문에 겹쳐진 목소리가 사용자에게 그대로 쏟아집니다. FocusHear는 누구의 목소리를 들을지 직접 고르게 해 주며, 선택적 청취와 ASL 지문자를 위한 수어 브리지, 음성 등록 기반 화자 분리를 갖추고 있습니다. 48시간 만에 만들어 SDGs to Startups 2026에서 **1위**를 차지했고, 이후 GPT-4o와 ElevenLabs Scribe 파이프라인 위에 인증된 계정, 결제, 저장되는 음성 및 얼굴 프로필, 학습된 ONNX LSTM 수어 모델을 더해 다시 만들었습니다. 이를 초청제 Build with OpenAI 행사에 가져가 1차 라운드를 통과했습니다. [focus-hear-app.vercel.app](https://focus-hear-app.vercel.app/)에서 볼 수 있습니다. | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![OpenAI](https://img.shields.io/badge/-GPT--4o-412991?style=flat&logo=openai&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat&logo=stripe&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white) |

---

### 포트폴리오 및 웹사이트

| 프로젝트 | 목적 | 기술 |
| --- | --- | --- |
| [개인 포트폴리오](https://carlmasters.com) | 제 역량과 성과 등을 소개하는 개인 포트폴리오입니다. [carlmasters.com](https://carlmasters.com)에서 볼 수 있고, 소스는 [My-Personal-Portfolio](https://github.com/carlmasters02/My-Personal-Portfolio)에 있습니다. | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| [Kady's English Classes](https://kadysenglish.com) | 베트남에서 프리랜서로 일하는 영어 강사를 위해 설계하고 만든 웹사이트입니다. [kadysenglish.com](https://kadysenglish.com)에서 볼 수 있습니다. | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |

---

### 행사 및 해커톤

| 날짜 | 행사 | 비고 |
| --- | --- | --- |
| 2026년 7월 | Cursor Tokyo AI Meetup | Datadog Japan에서 Cursor 팀과 함께한 저녁 행사로, Cloud Agents와 자율적인 코딩 워크플로를 어떻게 구성할지를 다뤘습니다. |
| 2026년 7월 | Engineering Real World AI with Google and Google DeepMind | Google Japan에서 열린 기조 강연과 Google AI Studio 워크숍으로, AI 시스템을 프로토타입에서 프로덕션으로 옮기는 방법을 다뤘습니다. |
| 2026년 7월 | Agent Forge AI Hackathon | 도쿄와 일본 문화를 주제로, 실제 운영에 쓸 수 있는 AI 에이전트를 만드는 하루짜리 해커톤. 단독으로 참가했습니다. |
| 2026년 7월 | ai& × Moonshot Tokyo Hackathon Night | ai&의 추론 플랫폼에서 돌아가는 Kimi K2.7 Code를 중심으로 한, 하룻저녁짜리 해커톤. |
| 2026년 7월 | Vibe Coders Tokyo: Local Models with Gemma 4 | 오픈 웨이트 모델을 로컬 하드웨어에서 돌리는 것, 그리고 그것이 비용과 지연 시간, 자기 데이터에 대한 통제권을 어떻게 바꾸는지. |
| 2026년 6월 | OpenAI × Tokyo AI: Build with OpenAI | 초청제 빌드 행사. 프로덕션 아키텍처로 다시 만든 FocusHear를 들고 나가 1차 라운드를 통과했습니다. |
| 2026년 6월 | SDGs to Startups Hackathon 2026 | **1위.** 유엔 지속가능발전목표 10번에 도전한 48시간 빌드로, 청각에 어려움을 겪는 사람을 위해 하나의 목소리만 분리해 내는 FocusHear로 참가했습니다. |
| 2026년 3월 | Builders Weekend 2026 | 템플대학교 재팬 캠퍼스의 5인 팀과 함께 TabeTalk을 완성했습니다. 누가 무엇을 주문했는지 목소리로 알아내고 계산서를 나눠 주는 AI 외식 앱입니다. |
| 2026년 3월 | UI/UX Hackathon | **1위.** 사용자 니즈를 조사하고 와이어프레임과 인터페이스 프로토타입을 만든 뒤, 모든 설계 결정을 심사위원 앞에서 변호했습니다. |

---

### 📚 최신 글

- [실제로 끝까지 읽히는 이력서 쓰는 법](https://carlmasters.com/article-resume.html)
- [정말로 의미 있는 일상의 사이버보안 습관](https://carlmasters.com/article-cybersecurity.html)
- [프라이버시 스택: 당신이 쓰는 모든 앱을 대체할 오픈소스와 암호화 대안](https://carlmasters.com/article-privacy.html)

---

### 링크

- 🌐 웹사이트: [carlmasters.com](https://carlmasters.com)
- 💼 LinkedIn: [carl-masters](https://www.linkedin.com/in/carl-masters-724951297)
