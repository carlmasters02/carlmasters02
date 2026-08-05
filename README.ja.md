[English](https://github.com/carlmasters02/carlmasters02/blob/main/README.md) · **日本語** · [Tiếng Việt](https://github.com/carlmasters02/carlmasters02/blob/main/README.vi.md) · [한국어](https://github.com/carlmasters02/carlmasters02/blob/main/README.ko.md) · [中文](https://github.com/carlmasters02/carlmasters02/blob/main/README.zh.md) · [ไทย](https://github.com/carlmasters02/carlmasters02/blob/main/README.th.md) · [Tagalog](https://github.com/carlmasters02/carlmasters02/blob/main/README.tl.md) · [Français](https://github.com/carlmasters02/carlmasters02/blob/main/README.fr.md)

## 👋 こんにちは、Carl Masters です

テンプル大学ジャパンキャンパス（Temple University Japan）でサイバーセキュリティを学んでいます。

[![ウェブサイト](https://img.shields.io/badge/carlmasters.com-000000?style=flat&logo=googlechrome&logoColor=white)](https://carlmasters.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carl-masters-724951297)
![所在地](https://img.shields.io/badge/%E6%9D%B1%E4%BA%AC%E3%80%81%E6%97%A5%E6%9C%AC-informational?style=flat&logo=googlemaps&logoColor=white)

*リンク先のリポジトリ、記事、ウェブサイトはすべて英語です。*

---

### 関心分野

テンプル大学ジャパンキャンパスでサイバーセキュリティを学んでいます。関心があるのは攻撃側の視点と、システムが理論上ではなく実際にどう壊れるのかを理解することです。取り組みの多くは、セキュリティツールをゼロから作ることに費やしています。パーサーライブラリに頼るよりもプロトコルを 1 バイトずつ自分で解析したいですし、攻撃手法は読んで終わりにせず、意図的に脆弱にしたターゲットに対して実装することで学びます。最も興味を惹かれるのは、前提が崩れる層です。暗号の実装、入力とメモリの扱い、そして生のネットワークトラフィック。欠陥を見つけることと同じくらい、それがなぜ存在するのかを説明することを大切にしています。だからこそ、私のプロジェクトはほとんどがコードと一緒に解説記事を用意しています。

---

### 主要言語

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

---

### 主要言語のプロジェクト

上に挙げた言語を、実際に動くコードで裏付ける小さな独立したツール群です。それぞれ一つの言語を取り上げて現実の課題に応用しているので、私が掲げるスキルには必ず読めるコードが伴っています。

| プロジェクト | 概要 | 技術 |
| --- | --- | --- |
| [secret-scanner](https://github.com/carlmasters02/secret-scanner) | コードベースをスキャンしてハードコードされた秘密情報を検出する CLI ツール。正規表現によるパターンマッチングと Shannon エントロピー解析を組み合わせ、固定パターンでは見逃すランダム性の高い文字列も捉えます。Python での静的解析、ファイル I/O、CLI 設計を身につけるために作りました。 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) |
| [cryptfile](https://github.com/carlmasters02/cryptfile) | OpenSSL を用いた AES-256-GCM ファイル暗号化の CLI ツール。鍵は PBKDF2 でパスフレーズから導出します。C における低レベルなメモリ管理、バイナリファイル I/O、暗号ライブラリの統合を身につけるために作りました。 | ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) ![OpenSSL](https://img.shields.io/badge/-OpenSSL-721412?style=flat&logo=openssl&logoColor=white) |

---

### セキュリティ・システム系プロジェクト

| プロジェクト | 概要 | 技術 |
| --- | --- | --- |
| [network-protocol-analyzer](https://github.com/carlmasters02/network-protocol-analyzer) | Ethernet、IPv4、TCP/UDP、DNS を生のバイト列から手作業でデコードする、パースライブラリを一切使わないライブパケットアナライザ。ターミナル UI にストリーミング表示し、Wireshark 用に PCAP を出力、ポートスキャン・DNS トンネリング・ARP スプーフィングをリアルタイムで検知します。 | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white) |
| [python-static-analyzer](https://github.com/carlmasters02/python-static-analyzer) | Python のソースコードを実行せずに SQL インジェクションとコマンドインジェクションを検出。AST 解析とソースからシンクへのテイント追跡により、ファイル・行番号・なぜ悪用可能なのかまで報告します。適合率と再現率はラベル付きの脆弱サンプルでベンチマーク済みです。 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| [coverage-guided-fuzzer](https://github.com/carlmasters02/coverage-guided-fuzzer) | 当てずっぽうではなくカバレッジのフィードバックに基づいて入力を変異させ、クラッシュを発見する AFL 方式のファザー。見つけたクラッシュは再現可能な最小ケースまで縮小します。 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) |
| [Crypto-Attack-Lab](https://github.com/carlmasters02/Crypto-Attack-Lab) | 古典的な暗号攻撃を手を動かして学ぶラボ。パディングオラクル、ハッシュ長延長攻撃、ECB カット＆ペースト、RSA に対する Wiener の攻撃、タイミングサイドチャネルを収録。それぞれに脆弱な実装、動作する攻撃コード、その背景にある現実の設計ミスの解説が付いています。 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| [python-cli-template](https://github.com/carlmasters02/python-cli-template) | きちんとしたリポジトリ運用のための再利用可能なテンプレート。`src/` レイアウト、カバレッジ付き pytest、GitHub Actions による CI、ステータスバッジ、Dockerfile、semver タグ付きリリースを備えています。 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |

---

### Web アプリ開発

| プロジェクト | 概要 | 技術 |
| --- | --- | --- |
| [FocusHear](https://focus-hear-app.vercel.app/) | 聴覚に困難を抱える人のためのリアルタイム支援コミュニケーションプラットフォーム。既存の字幕アプリはその場の全員を一度に文字起こしするため、重なり合う声がユーザーに押し寄せてしまいます。FocusHear は誰の声を聞くかを選べるようにし、選択的リスニング、ASL 指文字のための手話ブリッジ、音声登録による話者ダイアライゼーションを備えています。48 時間で構築して SDGs to Startups 2026 で **優勝**、その後 GPT-4o と ElevenLabs Scribe のパイプライン上に、認証付きアカウント、課金、音声・顔プロファイルの保存、学習済み ONNX LSTM 手話モデルを加えて作り直し、招待制の Build with OpenAI イベントに持ち込んで一次選考を通過しました。公開先は [focus-hear-app.vercel.app](https://focus-hear-app.vercel.app/)。 | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![OpenAI](https://img.shields.io/badge/-GPT--4o-412991?style=flat&logo=openai&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat&logo=stripe&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white) |

---

### ポートフォリオ・ウェブサイト

| プロジェクト | 概要 | 技術 |
| --- | --- | --- |
| [個人ポートフォリオ](https://carlmasters.com) | スキルや実績などを紹介する個人ポートフォリオ。公開先は [carlmasters.com](https://carlmasters.com)、ソースは [My-Personal-Portfolio](https://github.com/carlmasters02/My-Personal-Portfolio) にあります。 | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| [Kady's English Classes](https://kadysenglish.com) | ベトナムでフリーランスの英語講師をしている方のために設計・構築したウェブサイト。公開先は [kadysenglish.com](https://kadysenglish.com)。 | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |

---

### イベント・ハッカソン

| 日付 | イベント | 内容 |
| --- | --- | --- |
| 2026年7月 | Cursor Tokyo AI Meetup | Datadog Japan で開かれた Cursor チームとの夜。Cloud Agents と、自律的なコーディングワークフローの組み立て方がテーマでした。 |
| 2026年7月 | Engineering Real World AI with Google and Google DeepMind | Google Japan での基調講演と Google AI Studio ワークショップ。AI システムをプロトタイプから本番へ持っていく方法について。 |
| 2026年7月 | Agent Forge AI Hackathon | 東京と日本文化をテーマにした、本番投入できる AI エージェントのための一日ハッカソン。ソロで参加しました。 |
| 2026年7月 | ai& × Moonshot Tokyo Hackathon Night | ai& の推論プラットフォーム上で動く Kimi K2.7 Code を軸にした、一晩限りのハッカソン。 |
| 2026年7月 | Vibe Coders Tokyo: Local Models with Gemma 4 | オープンウェイトのモデルをローカルのハードウェアで動かすこと、そしてそれがコスト・レイテンシ・自分のデータに対する統制をどう変えるか。 |
| 2026年6月 | OpenAI × Tokyo AI: Build with OpenAI | 招待制のビルドイベント。本番向けアーキテクチャで作り直した FocusHear を持ち込み、一次選考を通過しました。 |
| 2026年6月 | SDGs to Startups Hackathon 2026 | **優勝。** 国連持続可能な開発目標 10 に挑む 48 時間のビルド。聴覚に困難を抱える人のために特定の声だけを取り出す FocusHear で臨みました。 |
| 2026年3月 | Builders Weekend 2026 | テンプル大学ジャパンキャンパスの 5 人チームで TabeTalk を開発。誰が何を注文したかを音声から判別し、会計を割り勘にする AI 外食アプリです。 |
| 2026年3月 | UI/UX Hackathon | **優勝。** ユーザーニーズを調査し、ワイヤーフレームからインターフェースのプロトタイプまで作成した上で、すべての設計判断を審査員に対して説明しました。 |

---

### 📚 最新の記事

- [実際に読んでもらえる履歴書の書き方](https://carlmasters.com/article-resume.html)
- [本当に意味のある、日々のサイバーセキュリティ習慣](https://carlmasters.com/article-cybersecurity.html)
- [プライバシースタック：日常的に使うあらゆるアプリのオープンソース・暗号化された代替手段](https://carlmasters.com/article-privacy.html)

---

### リンク

- 🌐 ウェブサイト: [carlmasters.com](https://carlmasters.com)
- 💼 LinkedIn: [carl-masters](https://www.linkedin.com/in/carl-masters-724951297)
