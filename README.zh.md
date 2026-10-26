[English](https://github.com/carlmasters02/carlmasters02/blob/main/README.md) · [日本語](https://github.com/carlmasters02/carlmasters02/blob/main/README.ja.md) · [Tiếng Việt](https://github.com/carlmasters02/carlmasters02/blob/main/README.vi.md) · [한국어](https://github.com/carlmasters02/carlmasters02/blob/main/README.ko.md) · **中文** · [ไทย](https://github.com/carlmasters02/carlmasters02/blob/main/README.th.md) · [Tagalog](https://github.com/carlmasters02/carlmasters02/blob/main/README.tl.md) · [Français](https://github.com/carlmasters02/carlmasters02/blob/main/README.fr.md) · [Deutsch](https://github.com/carlmasters02/carlmasters02/blob/main/README.de.md)

## 👋 你好，我是 Carl Masters

天普大学日本校区（Temple University Japan）网络安全专业学生。

[![网站](https://img.shields.io/badge/carlmasters.com-000000?style=flat&logo=googlechrome&logoColor=white)](https://carlmasters.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carl-masters-724951297)
![所在地](https://img.shields.io/badge/%E4%B8%9C%E4%BA%AC%EF%BC%8C%E6%97%A5%E6%9C%AC-informational?style=flat&logo=googlemaps&logoColor=white)

*文中链接的代码仓库、文章与网站均为英文。*

---

### 关注方向

我是天普大学日本校区的网络安全专业学生，着迷于这个领域的攻击面，也着迷于理解系统在现实中而非理论上是如何失效的。我的大部分工作都是从零开始构建安全工具。比起直接调用解析库，我更愿意一个字节一个字节地把协议拆开；学习一种攻击时，我不满足于只是读懂它，而是在一个刻意留有漏洞的目标上把它实现出来。最吸引我的，是那些假设开始崩塌的层次：密码学的具体实现、输入与内存的处理，以及原始的网络流量。找出一个缺陷固然重要，但解释它为什么存在同样重要，这也是为什么我的项目大多在代码之外还附有一篇分析文章。

---

### 核心语言

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)](https://www.w3schools.com/c/)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://dev.java)

---

### 核心语言项目

一些小而独立的工具，用能跑起来的代码为上面这些语言背书。每个项目都只取一门语言，把它用在一个真实的问题上，这样我所声称的熟练程度背后总有可供阅读的东西。

| 项目 | 用途 | 技术 |
| --- | --- | --- |
| [secret-scanner](https://github.com/carlmasters02/secret-scanner) | 一个扫描代码库中硬编码密钥的命令行工具，将正则模式匹配与香农熵分析结合起来，捕捉固定模式会漏掉的高随机性字符串。写它是为了打磨 Python 中的静态分析、文件 I/O 和命令行设计。 | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) |
| [cryptfile](https://github.com/carlmasters02/cryptfile) | 一个基于 OpenSSL 的 AES-256-GCM 文件加密命令行工具，通过 PBKDF2 从口令派生密钥。写它是为了打磨 C 中的底层内存管理、二进制文件 I/O 以及密码学库的集成。 | [![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black)](https://www.w3schools.com/c/) [![OpenSSL](https://img.shields.io/badge/-OpenSSL-721412?style=flat&logo=openssl&logoColor=white)](https://www.openssl.org/) |
| [tlsprobe](https://github.com/carlmasters02/tlsprobe) | 一个审计远程 TLS 端点与证书链的命令行工具，将握手协商、X.509 证书链验证与专门的旧版协议探测结合起来，找出已弃用的协议、弱密码套件和即将过期的证书。写它是为了打磨 Java 中的网络套接字编程、公钥基础设施（PKI）以及命令行设计。 | [![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat&logo=openjdk&logoColor=white)](https://dev.java) |

---

### 安全与系统项目

| 项目 | 用途 | 技术 |
| --- | --- | --- |
| [AEGIS-threat-dashboard](https://github.com/carlmasters02/AEGIS-threat-dashboard) | 一个 SOC 风格的威胁运营仪表盘，配有 3D 热力图地球，完全基于公开的实时威胁情报构建：Cloudflare Radar 的攻击路径、ransomware.live 的泄露站点受害者、附带 EPSS 评分的 CISA KEV、SANS ISC DShield，以及 abuse.ch 的僵尸网络 C2 数据源。没有任何模拟数据；某个数据源不可用时，对应面板会如实标明。一个零依赖的 Node 代理缓存所有数据源，以遵守上游的速率限制。在线地址：[aegisthreatdashboard.com](https://aegisthreatdashboard.com)。 | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Node.js](https://img.shields.io/badge/-Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)](https://nodejs.org/) [![Cloudflare Workers](https://img.shields.io/badge/-Cloudflare%20Workers-F38020?style=flat&logo=cloudflareworkers&logoColor=white)](https://workers.cloudflare.com/) |
| [network-protocol-analyzer](https://github.com/carlmasters02/network-protocol-analyzer) | 一个实时数据包分析器，完全手写地从原始字节解析 Ethernet、IPv4、TCP/UDP 和 DNS，不依赖任何解析库。它把结果流式输出到终端界面，导出可供 Wireshark 使用的 PCAP，并在端口扫描、DNS 隧道和 ARP 欺骗发生的当下就发出告警。 | [![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)](https://www.rust-lang.org/) |
| [python-static-analyzer](https://github.com/carlmasters02/python-static-analyzer) | 不运行程序就能在 Python 源码中找出 SQL 注入和命令注入，通过 AST 解析加上从源到汇的污点追踪，报告出问题的文件、行号，以及它为什么可被利用。查准率与查全率均在带标注的漏洞样本上做过基准测试。 | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [coverage-guided-fuzzer](https://github.com/carlmasters02/coverage-guided-fuzzer) | 一个 AFL 风格的模糊测试工具，依据覆盖率反馈而不是盲目猜测来变异输入以发现崩溃，再把每个崩溃缩减到能够复现的最小用例。 | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black)](https://www.w3schools.com/c/) |
| [Crypto-Attack-Lab](https://github.com/carlmasters02/Crypto-Attack-Lab) | 一个动手实践经典密码学攻击的实验室：填充预言机、哈希长度扩展、ECB 剪切粘贴、针对 RSA 的 Wiener 攻击，以及一个计时侧信道。每一项都配有一个存在漏洞的玩具实现、一份可运行的利用代码，以及一篇剖析其背后真实工程失误的文章。 | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |

---

### Web 应用开发

| 项目 | 用途 | 技术 |
| --- | --- | --- |
| [FocusHear](https://focus-hear-app.vercel.app/) | 一个面向听障人士的实时辅助沟通平台。现有的字幕应用都是把在场所有人同时转写出来，让用户被层层叠叠的话音淹没；FocusHear 让你自己选择想听谁的声音，具备选择性聆听、用于 ASL 指拼的手语桥接，以及基于声纹注册的说话人分离。它在 48 小时内完成，拿下 SDGs to Startups 2026 **冠军**，随后在 GPT-4o 与 ElevenLabs Scribe 的流水线上重建，加入了带认证的账户体系、计费、可保存的声音与人脸档案，以及一个训练好的 ONNX LSTM 手语模型，并被带到邀请制的 Build with OpenAI 活动上，晋级第一轮。线上地址：[focus-hear-app.vercel.app](https://focus-hear-app.vercel.app/)。 | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![OpenAI](https://img.shields.io/badge/-GPT--4o-412991?style=flat&logo=openai&logoColor=white)](https://openai.com/) [![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)](https://supabase.com/) [![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat&logo=stripe&logoColor=white)](https://stripe.com/) [![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white)](https://vercel.com/) |
| [NóiFlow AI](https://noiflow-ai.vercel.app/) | 一个由教师主导的 AI 工作区，帮助越南课堂提升英语流利度。教师用加入码创建班级，把真实课堂词汇变成可审核的双语闪卡，基于这些词汇生成阅读材料和题目，并附上口语回答提示；学生随后在同一个环环相扣的流程中练习闪卡、作业和语音任务，并获得即时的 AI 反馈。所有 AI 草稿在发布前都要经过教师审核，分析功能还会暴露薄弱词汇和技能模式。线上地址：[noiflow-ai.vercel.app](https://noiflow-ai.vercel.app/)。 | [![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)](https://nextjs.org/) [![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white)](https://vercel.com/) |
| [MenYomi](https://github.com/carlmasters02/MenYomi) | 把日本餐厅菜单的照片变成实时的双语菜单。OCR 读取每道菜和价格，再为每一项加上英文翻译、简短介绍、文化注释、过敏原标记、饮食筛选和日语发音朗读。在 Agent Forge AI Hackathon 上独自完成，把六个合作平台（Nosana, Qwen Cloud, GMI Cloud, ai&, Daytona, Qoder）整合在同一个兼容 OpenAI 的封装层之后。 | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |

---

### 黑客松项目

| 项目 | 用途 | 技术 |
| --- | --- | --- |
| [ai-wargame](https://github.com/carlmasters02/ai-wargame) | 两个 LLM 智能体在一个程序化生成的企业网络上展开回合制红蓝对抗：DeepSeek 红队在战争迷雾中猎取"皇冠明珠"数据库，Kimi 蓝队则在噪声告警中研判分诊。对战在可交互的网络拓扑图上实时展开，人类裁判可以注入突发事件或中途更换模型，每场比赛都能导出为 MITRE ATT&CK 与 STIX 工件。纯模拟运行：漏洞只是抽象的游戏对象，没有任何利用代码，也没有真实流量。 | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)](https://neo4j.com/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [disaster-mutual-aid-matcher](https://github.com/carlmasters02/disaster-mutual-aid-matcher) | 按照日本的个别避难计划制度，为需要帮助避难的居民制定避难方案并进行压力测试。确定性的求解器负责把居民与本地援助者配对，并在模拟地震阻断道路、断电、火势蔓延时实时重新规划；LLM 负责受理信息解析、日文计划书撰写和多语言通知，Neo4j 作为权威数据存储，所有推理都放在日本境内的 GPU 上运行。 | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)](https://neo4j.com/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |

---

### 模板

| 项目 | 用途 | 技术 |
| --- | --- | --- |
| [python-cli-template](https://github.com/carlmasters02/python-cli-template) | 一个可复用的模板，用于建立专业的仓库规范：`src/` 布局、带覆盖率的 pytest、GitHub Actions 持续集成、状态徽章、Dockerfile，以及按语义化版本打标签的发布流程。 | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [static-site-template](https://github.com/carlmasters02/static-site-template) | 一个可复用的模板，用于搭建无后端、纯 HTML/CSS/JS 的静态网站，带测试、GitHub Actions CI 和 Dockerfile。 | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [flask-webapp-template](https://github.com/carlmasters02/flask-webapp-template) | 一个可复用的 Python + Flask Web 应用模板，带测试、GitHub Actions CI 和 Dockerfile。 | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask&logoColor=white)](https://flask.palletsprojects.com/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [express-webapp-template](https://github.com/carlmasters02/express-webapp-template) | 一个可复用的 Node + Express Web 应用模板，配纯 HTML/CSS/JS 前端，带测试、GitHub Actions CI 和 Dockerfile。 | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Node.js](https://img.shields.io/badge/-Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)](https://nodejs.org/) [![Express](https://img.shields.io/badge/-Express-000000?style=flat&logo=express&logoColor=white)](https://expressjs.com/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [react-express-template](https://github.com/carlmasters02/react-express-template) | 一个可复用的模板：React (Vite) 前端搭配 Node/Express API 后端，带测试、GitHub Actions CI 和 Dockerfile。 | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)](https://react.dev/) [![Express](https://img.shields.io/badge/-Express-000000?style=flat&logo=express&logoColor=white)](https://expressjs.com/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |

---

### IoT 项目

| 项目 | 用途 | 技术 |
| --- | --- | --- |
| [g2-vi-en-realtime](https://github.com/carlmasters02/g2-vi-en-realtime) | 为 Even Realities G2 智能眼镜打造的越南语→英语实时翻译，起因是眼镜自带的翻译应用不支持越南语。麦克风音频通过蓝牙流式传输到 OpenAI 的实时翻译 API，英文会在说话者之后约一秒出现在抬头显示中，结束后还能保存双语文字记录。由于浏览器无法为 WebSocket 设置认证请求头，它搭配 [g2-relay](https://github.com/carlmasters02/g2-relay) 使用：一个把 API 密钥留在服务器端的 Cloudflare Worker 中继。 | [![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/) [![OpenAI](https://img.shields.io/badge/-OpenAI%20Realtime-412991?style=flat&logo=openai&logoColor=white)](https://platform.openai.com/docs/guides/realtime) [![Cloudflare Workers](https://img.shields.io/badge/-Cloudflare%20Workers-F38020?style=flat&logo=cloudflareworkers&logoColor=white)](https://workers.cloudflare.com/) |

---

### 作品集与网站

| 项目 | 用途 | 技术 |
| --- | --- | --- |
| [PickYourLinux](https://github.com/carlmasters02/PickYourLinux) | 一份挑选 Linux 发行版的指南。交互式家谱图把 56 个发行版追溯到 Debian、Fedora 和 Arch 三大源头；分阶段的问答会先问你要搭建什么（桌面电脑、服务器、安全工具套件、注重隐私的系统、游戏掌机或 IoT 开发板），在每个检查点缩小范围，最后推荐具体的发行版和版本，并附上理由、注意事项以及切换前需要准备的事项。使用原生 HTML、CSS 和 JavaScript 构建，无需构建步骤，也不向任何第三方发送请求。线上地址 [pickyourlinux.com](https://pickyourlinux.com)。 | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![D3.js](https://img.shields.io/badge/-D3.js-F9A03C?style=flat&logo=d3&logoColor=white)](https://d3js.org/) |
| [我的个人作品集](https://carlmasters.com) | 一个展示我的技能、成果等内容的个人作品集网站。线上地址 [carlmasters.com](https://carlmasters.com)。 | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |
| [Kady's English Classes](https://kadysenglish.com) | 为一位在越南从事自由职业的英语老师设计并搭建的网站。线上地址 [kadysenglish.com](https://kadysenglish.com)。 | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |

---

### 活动与黑客松

| 日期 | 活动 | 说明 |
| --- | --- | --- |
| 2026年10月 | Tokyo Agent Hackathon | 由 +81 Builders 主办、Neo4j 和 ai& 赞助的一日开放创新黑客松。单人参赛，做出了 [AI Wargame](https://github.com/carlmasters02/ai-wargame)：一个实时的红蓝对抗模拟，DeepSeek 攻击方和 Kimi 防守方在 Neo4j 图上争夺一个程序生成的企业网络。 |
| 2026年8月 | HITCON 2026 | 在台北参加了为期两天的 Hacks In Taiwan Conference，主题为 “When AI Acts: Hacking the Age of Agentic Systems”。演讲涵盖 AI 时代的漏洞披露、智能体驱动的 SOC 自动化、嵌入式硬件研究、供应链溯源以及国家级攻击手法，最后以 Orange Tsai 的 Edge 零点击沙箱逃逸收尾。 |
| 2026年7月 | Cursor Tokyo AI Meetup | 在 Datadog Japan 与 Cursor 团队共度的一晚，主题是 Cloud Agents 以及如何组织自主编程的工作流。 |
| 2026年7月 | Engineering Real World AI with Google and Google DeepMind | 在 Google Japan 举行的主题演讲与 Google AI Studio 工作坊，讲的是如何把 AI 系统从原型推向生产。 |
| 2026年7月 | Agent Forge AI Hackathon | 一场为期一天的黑客松，围绕可投入生产的 AI 智能体展开，主题是东京与日本文化。单人参赛，做出了 [MenYomi](https://github.com/carlmasters02/MenYomi)：把日文菜单的照片变成带翻译和过敏原标记的双语菜单。 |
| 2026年7月 | ai& × Moonshot Tokyo Hackathon Night | 一场只有一个晚上的黑客松，围绕运行在 ai& 推理平台上的 Kimi K2.7 Code 展开。 |
| 2026年7月 | Vibe Coders Tokyo: Local Models with Gemma 4 | 在本地硬件上运行开放权重模型，以及这件事如何改变成本、延迟和对自己数据的掌控。 |
| 2026年6月 | OpenAI × Tokyo AI: Build with OpenAI | 邀请制的构建活动。带去了以生产级架构重写的 FocusHear，并晋级第一轮。 |
| 2026年6月 | SDGs to Startups Hackathon 2026 | **冠军。** 一场为期 48 小时、针对联合国可持续发展目标第 10 项的构建赛，作品是为听障人士分离出单一人声的 FocusHear。 |
| 2026年3月 | Builders Weekend 2026 | 与天普大学日本校区的五人团队一起交付了 TabeTalk：一款通过声音识别谁点了什么菜并自动分摊账单的 AI 餐饮应用。 |
| 2026年3月 | UI/UX Hackathon | **冠军。** 调研用户需求，绘制线框图并做出界面原型，然后向评委逐一论证每一个设计决策。 |

---

### 📚 最新文章

- [如何写一份真正会被读完的简历](https://carlmasters.com/article-resume.html)
- [那些真正有用的日常网络安全习惯](https://carlmasters.com/article-cybersecurity.html)
- [隐私工具栈：为你在用的每一个应用找到开源且加密的替代品](https://carlmasters.com/article-privacy.html)

---

### 链接

- 🌐 网站：[carlmasters.com](https://carlmasters.com)
- 💼 LinkedIn：[carl-masters](https://www.linkedin.com/in/carl-masters-724951297)
- 🛠️ 开发者邮箱：[carl.masters.dev@protonmail.com](mailto:carl.masters.dev@protonmail.com)（报告 bug、反馈问题、咨询代码相关问题）
- 📧 工作邮箱：[carl.masters.professional@protonmail.com](mailto:carl.masters.professional@protonmail.com)（职业交流、工作机会、实习咨询）
