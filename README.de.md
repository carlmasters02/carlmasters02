[English](https://github.com/carlmasters02/carlmasters02/blob/main/README.md) · [日本語](https://github.com/carlmasters02/carlmasters02/blob/main/README.ja.md) · [Tiếng Việt](https://github.com/carlmasters02/carlmasters02/blob/main/README.vi.md) · [한국어](https://github.com/carlmasters02/carlmasters02/blob/main/README.ko.md) · [中文](https://github.com/carlmasters02/carlmasters02/blob/main/README.zh.md) · [ไทย](https://github.com/carlmasters02/carlmasters02/blob/main/README.th.md) · [Tagalog](https://github.com/carlmasters02/carlmasters02/blob/main/README.tl.md) · [Français](https://github.com/carlmasters02/carlmasters02/blob/main/README.fr.md) · **Deutsch**

## 👋 Hallo, ich bin Carl Masters

Cybersecurity-Student an der Temple University Japan (dem japanischen Campus der Temple University).

[![Website](https://img.shields.io/badge/carlmasters.com-000000?style=flat&logo=googlechrome&logoColor=white)](https://carlmasters.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carl-masters-724951297)
![Standort](https://img.shields.io/badge/Tokio,%20Japan-informational?style=flat&logo=googlemaps&logoColor=white)

*Die verlinkten Repositorys, Artikel und Webseiten sind auf Englisch.*

---

### Schwerpunkt

Ich studiere Cybersecurity an der Temple University Japan und interessiere mich vor allem für die offensive Seite des Fachs: dafür, wie Systeme in der Praxis versagen und nicht nur in der Theorie. Den Großteil meiner Arbeit macht das Entwickeln von Sicherheitswerkzeugen von Grund auf aus. Ich dekodiere ein Protokoll lieber Byte für Byte, als zu einer Parsing-Bibliothek zu greifen, und ich lerne einen Angriff, indem ich ihn gegen ein absichtlich verwundbares Ziel implementiere, statt nur darüber zu lesen. Am meisten interessieren mich die Ebenen, auf denen Annahmen zusammenbrechen: kryptografische Implementierungen, die Verarbeitung von Eingaben und Speicher sowie roher Netzwerkverkehr. Mir ist es genauso wichtig zu erklären, warum eine Schwachstelle existiert, wie sie zu finden, weshalb die meisten meiner Projekte neben dem Code eine ausführliche Erläuterung mitbringen.

---

### Kernsprachen

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)](https://www.w3schools.com/c/)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://dev.java)

---

### Projekte zu den Kernsprachen

Kleine, eigenständige Werkzeuge, die die oben genannten Sprachen mit funktionierendem Code belegen. Jedes nimmt eine einzelne Sprache und wendet sie auf ein echtes Problem an, damit die Kenntnisse, die ich angebe, mit etwas einhergehen, das Sie selbst lesen können.

| Projekt | Zweck | Technologien |
| --- | --- | --- |
| [secret-scanner](https://github.com/carlmasters02/secret-scanner) | Ein Kommandozeilenwerkzeug, das Codebasen nach fest eincodierten Geheimnissen durchsucht und dabei Mustererkennung mit regulären Ausdrücken mit einer Shannon-Entropie-Analyse kombiniert, um stark zufällige Zeichenketten zu finden, die feste Muster übersehen. Entwickelt, um statische Analyse, Datei-Ein- und -Ausgabe und CLI-Design in Python zu üben. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) |
| [cryptfile](https://github.com/carlmasters02/cryptfile) | Ein Kommandozeilenwerkzeug zur Dateiverschlüsselung mit AES-256-GCM auf Basis von OpenSSL, das seinen Schlüssel mit PBKDF2 aus einer Passphrase ableitet. Entwickelt, um hardwarenahe Speicherverwaltung, binäre Datei-Ein- und -Ausgabe und die Einbindung einer Kryptografie-Bibliothek in C zu üben. | [![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black)](https://www.w3schools.com/c/) [![OpenSSL](https://img.shields.io/badge/-OpenSSL-721412?style=flat&logo=openssl&logoColor=white)](https://www.openssl.org/) |
| [tlsprobe](https://github.com/carlmasters02/tlsprobe) | Ein Kommandozeilenwerkzeug, das entfernte TLS-Endpunkte und Zertifikatsketten prüft. Es kombiniert die Aushandlung des Handshakes mit der Validierung von X.509-Ketten und separaten Tests auf Altprotokolle, um veraltete Protokolle, schwache Cipher-Suites und bald ablaufende Zertifikate zu erkennen. Entwickelt, um Netzwerkprogrammierung mit Sockets, Public-Key-Infrastruktur (PKI) und CLI-Design in Java zu üben. | [![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat&logo=openjdk&logoColor=white)](https://dev.java) |

---

### Sicherheits- & Systemprojekte

| Projekt | Zweck | Technologien |
| --- | --- | --- |
| [AEGIS-threat-dashboard](https://github.com/carlmasters02/AEGIS-threat-dashboard) | Ein Threat-Operations-Dashboard im Stil eines SOC mit einem 3D-Heatmap-Globus, das vollständig auf öffentlichen Live-Bedrohungsdaten basiert: Angriffskorridore aus Cloudflare Radar, Opfer von Leak-Seiten über ransomware.live, CISA KEV mit EPSS-Werten, SANS ISC DShield sowie Botnet-C2-Feeds von abuse.ch. Nichts ist simuliert: Fällt eine Quelle aus, zeigen ihre Panels das an. Ein Node-Proxy ohne Abhängigkeiten speichert jeden Feed zwischen, um die Ratenbegrenzungen der Quellen einzuhalten. Live unter [aegisthreatdashboard.com](https://aegisthreatdashboard.com). | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Node.js](https://img.shields.io/badge/-Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)](https://nodejs.org/) [![Cloudflare Workers](https://img.shields.io/badge/-Cloudflare%20Workers-F38020?style=flat&logo=cloudflareworkers&logoColor=white)](https://workers.cloudflare.com/) |
| [network-protocol-analyzer](https://github.com/carlmasters02/network-protocol-analyzer) | Ein Live-Paketanalysator, der Ethernet, IPv4, TCP/UDP und DNS von Hand aus rohen Bytes dekodiert, ganz ohne Parsing-Bibliotheken. Er streamt in eine Terminal-Oberfläche, exportiert PCAP für Wireshark und meldet Portscans, DNS-Tunneling und ARP-Spoofing in dem Moment, in dem sie passieren. | [![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)](https://www.rust-lang.org/) |
| [python-static-analyzer](https://github.com/carlmasters02/python-static-analyzer) | Findet SQL-Injection und Command-Injection in Python-Quellcode, ohne ihn auszuführen. Dazu nutzt es AST-Parsing und Taint-Tracking von der Quelle bis zur Senke und meldet die Datei, die Zeile und den Grund, warum die Stelle ausnutzbar ist. Precision und Recall wurden an gekennzeichneten verwundbaren Beispielen gemessen. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [coverage-guided-fuzzer](https://github.com/carlmasters02/coverage-guided-fuzzer) | Ein Fuzzer im Stil von AFL, der Abstürze findet, indem er Eingaben anhand von Coverage-Rückmeldungen mutiert, statt blind zu raten, und anschließend jeden Absturz auf den kleinsten reproduzierbaren Fall reduziert. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black)](https://www.w3schools.com/c/) |
| [Crypto-Attack-Lab](https://github.com/carlmasters02/Crypto-Attack-Lab) | Ein praxisnahes Labor zu klassischen kryptografischen Angriffen: Padding Oracle, Hash Length Extension, ECB-Cut-and-Paste, Wieners Angriff auf RSA und ein Timing-Seitenkanal. Zu jedem gibt es eine verwundbare Spielzeug-Implementierung, einen funktionierenden Exploit und eine Erläuterung des realen Fehlers, der dahintersteckt. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |

---

### Webanwendungsentwicklung

| Projekt | Zweck | Technologien |
| --- | --- | --- |
| [FocusHear](https://focus-hear-app.vercel.app/) | Eine Echtzeit-Kommunikationsplattform zur Unterstützung von Menschen mit Hörverlust. Jede Untertitel-App transkribiert alle gleichzeitig und überflutet die Nutzer mit sich überlagernden Stimmen; bei FocusHear wählen Sie, wessen Stimme Sie hören, mit selektivem Zuhören, einer Brücke zur Gebärdensprache für das ASL-Fingeralphabet und Sprechererkennung anhand registrierter Stimmen. In 48 Stunden gebaut und damit den **1. Platz** bei SDGs to Startups 2026 gewonnen, danach auf einer Pipeline mit GPT-4o und ElevenLabs Scribe neu aufgebaut, mit authentifizierten Konten, Abrechnung, gespeicherten Stimm- und Gesichtsprofilen und einem trainierten ONNX-LSTM-Modell für Gebärdensprache, und schließlich zu einem Build-with-OpenAI-Event nur auf Einladung mitgenommen, wo es die erste Runde erreichte. Live unter [focus-hear-app.vercel.app](https://focus-hear-app.vercel.app/). | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![OpenAI](https://img.shields.io/badge/-GPT--4o-412991?style=flat&logo=openai&logoColor=white)](https://openai.com/) [![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)](https://supabase.com/) [![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat&logo=stripe&logoColor=white)](https://stripe.com/) [![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white)](https://vercel.com/) |
| [NóiFlow AI](https://noiflow-ai.vercel.app/) | Ein von Lehrkräften gesteuerter KI-Arbeitsbereich für flüssiges Englisch in vietnamesischen Klassenzimmern. Lehrkräfte legen Klassen mit Beitrittscodes an, verwandeln echte Vokabeln aus dem Unterricht in zweisprachige, überprüfbare Karteikarten, erzeugen aus diesem Wortschatz Lesetexte und Fragen und fügen mündliche Antwortaufgaben hinzu; die Lernenden üben anschließend mit Karteikarten, Aufgaben und Sprechübungen und erhalten sofort KI-Feedback, alles in einem zusammenhängenden Kreislauf. Jeder KI-Entwurf wird vor der Veröffentlichung von der Lehrkraft geprüft, und Auswertungen zeigen schwache Wörter und Kompetenzmuster. Live unter [noiflow-ai.vercel.app](https://noiflow-ai.vercel.app/). | [![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)](https://nextjs.org/) [![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white)](https://vercel.com/) |
| [MenYomi](https://github.com/carlmasters02/MenYomi) | Verwandelt das Foto einer japanischen Speisekarte in eine zweisprachige Live-Speisekarte. Eine OCR liest jedes Gericht und jeden Preis, danach erhält jeder Eintrag eine englische Übersetzung, eine kurze Beschreibung, einen kulturellen Hinweis, Allergenkennzeichnungen, Ernährungsfilter und eine gesprochene japanische Aussprache. Allein beim Agent Forge AI Hackathon entwickelt, mit sechs Partnerplattformen (Nosana, Qwen Cloud, GMI Cloud, ai&, Daytona, Qoder) hinter einem einzigen OpenAI-kompatiblen Wrapper. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |

---

### Hackathon-Projekte

| Projekt | Zweck | Technologien |
| --- | --- | --- |
| [ai-wargame](https://github.com/carlmasters02/ai-wargame) | Zwei LLM-Agenten tragen ein rundenbasiertes Rot-gegen-Blau-Wargame in einem prozedural generierten Unternehmensnetzwerk aus: Ein DeepSeek-Red-Team jagt im Nebel des Krieges die zentrale Datenbank, während ein Kimi-Blue-Team verrauschte Alarme priorisiert. Das Match läuft live auf einer interaktiven Netzwerkkarte, ein menschlicher Schiedsrichter kann Überraschungsereignisse einspielen oder mitten im Spiel die Modelle tauschen, und jedes Match lässt sich als MITRE-ATT&CK- und STIX-Artefakte exportieren. Reine Simulation: Schwachstellen sind abstrakte Spielobjekte, ohne Exploit-Code und ohne echten Datenverkehr. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)](https://neo4j.com/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [disaster-mutual-aid-matcher](https://github.com/carlmasters02/disaster-mutual-aid-matcher) | Erstellt individuelle Evakuierungspläne für Menschen, die bei einer Evakuierung Hilfe brauchen, und unterzieht sie Belastungstests, gemäß der japanischen Vorgabe zur Evakuierungsunterstützung. Ein deterministischer Solver ordnet ihnen Helfer aus der Nachbarschaft zu und plant live neu, während ein simuliertes Erdbeben Straßen blockiert, den Strom abschaltet und Brände ausbreitet; LLMs übernehmen das Auswerten der Erfassung, japanische Plandokumente und mehrsprachige Einsatzmeldungen, mit Neo4j als maßgeblichem Datensystem und sämtlicher Inferenz auf GPUs in Japan. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)](https://neo4j.com/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |

---

### Vorlagen

| Projekt | Zweck | Technologien |
| --- | --- | --- |
| [python-cli-template](https://github.com/carlmasters02/python-cli-template) | Eine wiederverwendbare Vorlage für professionelle Repository-Hygiene: `src/`-Struktur, pytest mit Coverage, CI mit GitHub Actions, Status-Badges, ein Dockerfile und Releases mit Semver-Tags. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [static-site-template](https://github.com/carlmasters02/static-site-template) | Eine wiederverwendbare Vorlage für eine statische Webseite in reinem HTML/CSS/JS ohne Backend, mit Tests, CI mit GitHub Actions und einem Dockerfile. | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [flask-webapp-template](https://github.com/carlmasters02/flask-webapp-template) | Eine wiederverwendbare Vorlage für Webanwendungen mit Python und Flask, mit Tests, CI mit GitHub Actions und einem Dockerfile. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask&logoColor=white)](https://flask.palletsprojects.com/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [express-webapp-template](https://github.com/carlmasters02/express-webapp-template) | Eine wiederverwendbare Vorlage für Webanwendungen mit Node und Express und einem Frontend in reinem HTML/CSS/JS, mit Tests, CI mit GitHub Actions und einem Dockerfile. | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Node.js](https://img.shields.io/badge/-Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)](https://nodejs.org/) [![Express](https://img.shields.io/badge/-Express-000000?style=flat&logo=express&logoColor=white)](https://expressjs.com/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [react-express-template](https://github.com/carlmasters02/react-express-template) | Eine wiederverwendbare Vorlage für ein React-Frontend (Vite) mit einer Node/Express-API dahinter, mit Tests, CI mit GitHub Actions und einem Dockerfile. | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)](https://react.dev/) [![Express](https://img.shields.io/badge/-Express-000000?style=flat&logo=express&logoColor=white)](https://expressjs.com/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |

---

### IoT-Projekte

| Projekt | Zweck | Technologien |
| --- | --- | --- |
| [g2-vi-en-realtime](https://github.com/carlmasters02/g2-vi-en-realtime) | Live-Übersetzung von Vietnamesisch nach Englisch für die Smart Glasses Even Realities G2, entstanden, weil die Translate-App der Brille kein Vietnamesisch unterstützt. Das Mikrofonaudio wird per Bluetooth an die Echtzeit-Übersetzungs-API von OpenAI gestreamt, und das Englische erscheint etwa eine Sekunde nach dem Sprecher im Head-up-Display; anschließend wird ein zweisprachiges Transkript gespeichert. Ergänzt durch [g2-relay](https://github.com/carlmasters02/g2-relay), ein Relay auf Cloudflare Workers, das den API-Schlüssel auf dem Server hält, da Browser bei einem WebSocket keine Authentifizierungs-Header setzen können. | [![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/) [![OpenAI](https://img.shields.io/badge/-OpenAI%20Realtime-412991?style=flat&logo=openai&logoColor=white)](https://platform.openai.com/docs/guides/realtime) [![Cloudflare Workers](https://img.shields.io/badge/-Cloudflare%20Workers-F38020?style=flat&logo=cloudflareworkers&logoColor=white)](https://workers.cloudflare.com/) |

---

### Portfolio & Webseiten

| Projekt | Zweck | Technologien |
| --- | --- | --- |
| [PickYourLinux](https://github.com/carlmasters02/PickYourLinux) | Ein Leitfaden zur Wahl einer Linux-Distribution. Ein interaktiver Stammbaum führt 56 Distributionen auf ihre Wurzeln Debian, Fedora und Arch zurück, und ein mehrstufiges Quiz fragt zuerst, was Sie einrichten möchten (einen Desktop, einen Server, ein Security-Toolkit, ein auf Privatsphäre ausgerichtetes System, ein Gaming-Handheld oder ein IoT-Board), grenzt die Auswahl an jedem Zwischenstopp weiter ein und empfiehlt dann eine konkrete Distribution und Edition samt Begründung, Hinweisen und dem, was vor dem Umstieg zu erledigen ist. Gebaut mit reinem HTML, CSS und JavaScript, ohne Build-Schritt und ohne Anfragen an Dritte. Live unter [pickyourlinux.com](https://pickyourlinux.com). | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![D3.js](https://img.shields.io/badge/-D3.js-F9A03C?style=flat&logo=d3&logoColor=white)](https://d3js.org/) |
| [Mein persönliches Portfolio](https://carlmasters.com) | Ein persönliches Portfolio, in dem ich meine Fähigkeiten, Erfolge und mehr vorstelle. Live unter [carlmasters.com](https://carlmasters.com). | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |
| [Kady's English Classes](https://kadysenglish.com) | Eine Webseite, die ich für eine freiberufliche Englischlehrerin in Vietnam entworfen und gebaut habe. Live unter [kadysenglish.com](https://kadysenglish.com). | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |

---

### Veranstaltungen & Hackathons

| Datum | Veranstaltung | Notizen |
| --- | --- | --- |
| Oktober 2026 | Tokyo Agent Hackathon | Ein eintägiger Open-Innovation-Hackathon, ausgerichtet von +81 Builders und gesponsert von Neo4j und ai&. Allein teilgenommen und [AI Wargame](https://github.com/carlmasters02/ai-wargame) gebaut: eine Live-Simulation Rot gegen Blau, in der ein DeepSeek-Angreifer und ein Kimi-Verteidiger um ein prozedural generiertes Unternehmensnetzwerk auf einem Neo4j-Graphen kämpfen. |
| August 2026 | HITCON 2026 | Zwei Tage auf der Hacks In Taiwan Conference in Taipeh unter dem Motto „When AI Acts: Hacking the Age of Agentic Systems“. Die Vorträge behandelten KI-gestützte Offenlegung von Schwachstellen, agentenbasierte SOC-Automatisierung, Forschung an eingebetteter Hardware, Herkunftsnachweise in der Lieferkette und die Vorgehensweisen staatlicher Angreifer, zum Abschluss Orange Tsais Zero-Click-Ausbruch aus der Sandbox von Edge. |
| Juli 2026 | Cursor Tokyo AI Meetup | Ein Abend mit dem Cursor-Team bei Datadog Japan über Cloud Agents und darüber, wie man autonome Programmier-Workflows strukturiert. |
| Juli 2026 | Engineering Real World AI with Google and Google DeepMind | Keynote und ein Workshop zu Google AI Studio bei Google Japan darüber, wie KI-Systeme vom Prototyp in die Produktion kommen. |
| Juli 2026 | Agent Forge AI Hackathon | Ein eintägiger Hackathon zu produktionsreifen KI-Agenten rund um Tokio und die japanische Kultur. Allein teilgenommen und [MenYomi](https://github.com/carlmasters02/MenYomi) gebaut, das aus dem Foto einer japanischen Speisekarte eine zweisprachige Speisekarte mit Übersetzungen und Allergenkennzeichnung macht. |
| Juli 2026 | ai& × Moonshot Tokyo Hackathon Night | Ein Hackathon an einem einzigen Abend rund um Kimi K2.7 Code auf der Inferenzplattform von ai&. |
| Juli 2026 | Vibe Coders Tokyo: Local Models with Gemma 4 | Open-Weight-Modelle auf lokaler Hardware betreiben und was das für Kosten, Latenz und die Kontrolle über die eigenen Daten bedeutet. |
| Juni 2026 | OpenAI × Tokyo AI: Build with OpenAI | Build-Event nur auf Einladung. Mit einem neu aufgebauten FocusHear mit Produktionsarchitektur angetreten und die erste Runde erreicht. |
| Juni 2026 | SDGs to Startups Hackathon 2026 | **1. Platz.** Ein 48-Stunden-Build zum UN-Nachhaltigkeitsziel 10 mit FocusHear, das für Menschen mit Hörverlust eine einzelne Stimme herausfiltert. |
| März 2026 | Builders Weekend 2026 | TabeTalk mit einem fünfköpfigen Team der Temple University Japan ausgeliefert: eine KI-App fürs Essengehen, die per Stimme erkennt, wer was bestellt hat, und die Rechnung aufteilt. |
| März 2026 | UI/UX Hackathon | **1. Platz.** Nutzerbedürfnisse erforscht, Wireframes erstellt und eine Oberfläche als Prototyp entwickelt, dann jede Designentscheidung vor der Jury verteidigt. |

---

### 📚 Neueste Artikel

- [Wie man einen Lebenslauf schreibt, der tatsächlich gelesen wird](https://carlmasters.com/article-resume.html)
- [Cybersecurity-Gewohnheiten im Alltag, die wirklich zählen](https://carlmasters.com/article-cybersecurity.html)
- [Der Privatsphäre-Stack: Open-Source- und verschlüsselte Alternativen für jede App, die Sie nutzen](https://carlmasters.com/article-privacy.html)

---

### Kontakt

- 🌐 Webseite: [carlmasters.com](https://carlmasters.com)
- 💼 LinkedIn: [carl-masters](https://www.linkedin.com/in/carl-masters-724951297)
- 🛠️ Entwickler-E-Mail: [carl.masters.dev@protonmail.com](mailto:carl.masters.dev@protonmail.com), für Fehlerberichte, Issues und Fragen zu meinem Code
- 📧 Berufliche E-Mail: [carl.masters.professional@protonmail.com](mailto:carl.masters.professional@protonmail.com), für berufliche Kontakte, Jobanfragen und Praktika
