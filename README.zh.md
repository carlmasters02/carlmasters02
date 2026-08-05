[English](https://github.com/carlmasters02/carlmasters02/blob/main/README.md) · [日本語](https://github.com/carlmasters02/carlmasters02/blob/main/README.ja.md) · [Tiếng Việt](https://github.com/carlmasters02/carlmasters02/blob/main/README.vi.md) · [한국어](https://github.com/carlmasters02/carlmasters02/blob/main/README.ko.md) · **中文** · [ไทย](https://github.com/carlmasters02/carlmasters02/blob/main/README.th.md) · [Tagalog](https://github.com/carlmasters02/carlmasters02/blob/main/README.tl.md) · [Français](https://github.com/carlmasters02/carlmasters02/blob/main/README.fr.md)

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

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

---

### 核心语言项目

一些小而独立的工具，用能跑起来的代码为上面这些语言背书。每个项目都只取一门语言，把它用在一个真实的问题上，这样我所声称的熟练程度背后总有可供阅读的东西。

| 项目 | 用途 | 技术 |
| --- | --- | --- |
| [secret-scanner](https://github.com/carlmasters02/secret-scanner) | 一个扫描代码库中硬编码密钥的命令行工具，将正则模式匹配与香农熵分析结合起来，捕捉固定模式会漏掉的高随机性字符串。写它是为了打磨 Python 中的静态分析、文件 I/O 和命令行设计。 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) |
| [cryptfile](https://github.com/carlmasters02/cryptfile) | 一个基于 OpenSSL 的 AES-256-GCM 文件加密命令行工具，通过 PBKDF2 从口令派生密钥。写它是为了打磨 C 中的底层内存管理、二进制文件 I/O 以及密码学库的集成。 | ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) ![OpenSSL](https://img.shields.io/badge/-OpenSSL-721412?style=flat&logo=openssl&logoColor=white) |

---

### 安全与系统项目

| 项目 | 用途 | 技术 |
| --- | --- | --- |
| [network-protocol-analyzer](https://github.com/carlmasters02/network-protocol-analyzer) | 一个实时数据包分析器，完全手写地从原始字节解析 Ethernet、IPv4、TCP/UDP 和 DNS，不依赖任何解析库。它把结果流式输出到终端界面，导出可供 Wireshark 使用的 PCAP，并在端口扫描、DNS 隧道和 ARP 欺骗发生的当下就发出告警。 | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white) |
| [python-static-analyzer](https://github.com/carlmasters02/python-static-analyzer) | 不运行程序就能在 Python 源码中找出 SQL 注入和命令注入，通过 AST 解析加上从源到汇的污点追踪，报告出问题的文件、行号，以及它为什么可被利用。查准率与查全率均在带标注的漏洞样本上做过基准测试。 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| [coverage-guided-fuzzer](https://github.com/carlmasters02/coverage-guided-fuzzer) | 一个 AFL 风格的模糊测试工具，依据覆盖率反馈而不是盲目猜测来变异输入以发现崩溃，再把每个崩溃缩减到能够复现的最小用例。 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) |
| [Crypto-Attack-Lab](https://github.com/carlmasters02/Crypto-Attack-Lab) | 一个动手实践经典密码学攻击的实验室：填充预言机、哈希长度扩展、ECB 剪切粘贴、针对 RSA 的 Wiener 攻击，以及一个计时侧信道。每一项都配有一个存在漏洞的玩具实现、一份可运行的利用代码，以及一篇剖析其背后真实工程失误的文章。 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| [python-cli-template](https://github.com/carlmasters02/python-cli-template) | 一个可复用的模板，用于建立专业的仓库规范：`src/` 布局、带覆盖率的 pytest、GitHub Actions 持续集成、状态徽章、Dockerfile，以及按语义化版本打标签的发布流程。 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |

---

### Web 应用开发

| 项目 | 用途 | 技术 |
| --- | --- | --- |
| [FocusHear](https://focus-hear-app.vercel.app/) | 一个面向听障人士的实时辅助沟通平台。现有的字幕应用都是把在场所有人同时转写出来，让用户被层层叠叠的话音淹没；FocusHear 让你自己选择想听谁的声音，具备选择性聆听、用于 ASL 指拼的手语桥接，以及基于声纹注册的说话人分离。它在 48 小时内完成，拿下 SDGs to Startups 2026 **冠军**，随后在 GPT-4o 与 ElevenLabs Scribe 的流水线上重建，加入了带认证的账户体系、计费、可保存的声音与人脸档案，以及一个训练好的 ONNX LSTM 手语模型，并被带到邀请制的 Build with OpenAI 活动上，晋级第一轮。线上地址：[focus-hear-app.vercel.app](https://focus-hear-app.vercel.app/)。 | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![OpenAI](https://img.shields.io/badge/-GPT--4o-412991?style=flat&logo=openai&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat&logo=stripe&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white) |

---

### 作品集与网站

| 项目 | 用途 | 技术 |
| --- | --- | --- |
| [我的个人作品集](https://carlmasters.com) | 一个展示我的技能、成果等内容的个人作品集网站。线上地址 [carlmasters.com](https://carlmasters.com)，源码在 [My-Personal-Portfolio](https://github.com/carlmasters02/My-Personal-Portfolio)。 | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| [Kady's English Classes](https://kadysenglish.com) | 为一位在越南从事自由职业的英语老师设计并搭建的网站。线上地址 [kadysenglish.com](https://kadysenglish.com)。 | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |

---

### 活动与黑客松

| 日期 | 活动 | 说明 |
| --- | --- | --- |
| 2026年7月 | Cursor Tokyo AI Meetup | 在 Datadog Japan 与 Cursor 团队共度的一晚，主题是 Cloud Agents 以及如何组织自主编程的工作流。 |
| 2026年7月 | Engineering Real World AI with Google and Google DeepMind | 在 Google Japan 举行的主题演讲与 Google AI Studio 工作坊，讲的是如何把 AI 系统从原型推向生产。 |
| 2026年7月 | Agent Forge AI Hackathon | 一场为期一天的黑客松，围绕可投入生产的 AI 智能体展开，主题是东京与日本文化。单人参赛。 |
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
