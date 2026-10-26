[English](https://github.com/carlmasters02/carlmasters02/blob/main/README.md) · [日本語](https://github.com/carlmasters02/carlmasters02/blob/main/README.ja.md) · [Tiếng Việt](https://github.com/carlmasters02/carlmasters02/blob/main/README.vi.md) · [한국어](https://github.com/carlmasters02/carlmasters02/blob/main/README.ko.md) · [中文](https://github.com/carlmasters02/carlmasters02/blob/main/README.zh.md) · [ไทย](https://github.com/carlmasters02/carlmasters02/blob/main/README.th.md) · [Tagalog](https://github.com/carlmasters02/carlmasters02/blob/main/README.tl.md) · **Français**

## 👋 Bonjour, je suis Carl Masters

Étudiant en cybersécurité à Temple University Japan (université Temple, campus du Japon).

[![Site web](https://img.shields.io/badge/carlmasters.com-000000?style=flat&logo=googlechrome&logoColor=white)](https://carlmasters.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carl-masters-724951297)
![Localisation](https://img.shields.io/badge/Tokyo,%20Japon-informational?style=flat&logo=googlemaps&logoColor=white)

*Les dépôts de code, articles et sites liés sont en anglais.*

---

### Domaines d'intérêt

Je suis étudiant en cybersécurité à Temple University Japan, attiré par le versant offensif du domaine et par la compréhension de la façon dont les systèmes échouent en pratique plutôt qu'en théorie. L'essentiel de mon travail consiste à construire des outils de sécurité en partant de zéro. Je préfère décoder un protocole octet par octet plutôt que de me reposer sur une bibliothèque d'analyse, et j'apprends une attaque en l'implémentant contre une cible délibérément vulnérable plutôt qu'en me contentant de lire à son sujet. Les couches qui m'intéressent le plus sont celles où les hypothèses s'effondrent : les implémentations cryptographiques, la gestion des entrées et de la mémoire, et le trafic réseau brut. J'accorde autant d'importance à expliquer pourquoi une faille existe qu'à la trouver, et c'est pourquoi la plupart de mes projets s'accompagnent d'un article explicatif à côté du code.

---

### Langages principaux

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)](https://www.w3schools.com/c/)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://dev.java)

---

### Projets par langage principal

De petits outils autonomes qui appuient les langages ci-dessus avec du code qui fonctionne. Chacun prend un seul langage et l'applique à un problème réel, afin que la maîtrise que je revendique s'accompagne de quelque chose que vous pouvez lire.

| Projet | Objectif | Technologies |
| --- | --- | --- |
| [secret-scanner](https://github.com/carlmasters02/secret-scanner) | Un outil en ligne de commande qui analyse une base de code à la recherche de secrets écrits en dur, en associant la correspondance par expressions régulières à une analyse d'entropie de Shannon pour attraper les chaînes très aléatoires que les motifs figés laissent passer. Écrit pour travailler l'analyse statique, les entrées-sorties fichier et la conception d'interfaces en ligne de commande en Python. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) |
| [cryptfile](https://github.com/carlmasters02/cryptfile) | Un outil en ligne de commande de chiffrement de fichiers en AES-256-GCM bâti sur OpenSSL, dérivant sa clé d'une phrase secrète avec PBKDF2. Écrit pour travailler la gestion mémoire bas niveau, les entrées-sorties de fichiers binaires et l'intégration d'une bibliothèque cryptographique en C. | [![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black)](https://www.w3schools.com/c/) [![OpenSSL](https://img.shields.io/badge/-OpenSSL-721412?style=flat&logo=openssl&logoColor=white)](https://www.openssl.org/) |
| [tlsprobe](https://github.com/carlmasters02/tlsprobe) | Un outil en ligne de commande d'audit des terminaisons TLS distantes et des chaînes de certificats, associant la négociation de la poignée de main, la validation de chaîne X.509 et des sondes distinctes pour les protocoles obsolètes afin de repérer les protocoles dépréciés, les suites de chiffrement faibles et les certificats proches de l'expiration. Écrit pour travailler la programmation réseau par sockets, l'infrastructure à clé publique (PKI) et la conception d'outils en ligne de commande en Java. | [![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat&logo=openjdk&logoColor=white)](https://dev.java) |

---

### Projets sécurité & systèmes

| Projet | Objectif | Technologies |
| --- | --- | --- |
| [AEGIS-threat-dashboard](https://github.com/carlmasters02/AEGIS-threat-dashboard) | Un tableau de bord d'opérations de menaces façon SOC, avec un globe de carte thermique en 3D, bâti entièrement sur du renseignement sur les menaces public et en direct : couloirs d'attaque de Cloudflare Radar, victimes publiées sur les sites de fuite via ransomware.live, CISA KEV avec scores EPSS, SANS ISC DShield et flux de C2 de botnets d'abuse.ch. Aucune donnée n'est simulée : quand une source est indisponible, ses panneaux le disent. Un proxy Node sans aucune dépendance met chaque flux en cache pour respecter les limites de débit des sources. En ligne sur [aegisthreatdashboard.com](https://aegisthreatdashboard.com). | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Node.js](https://img.shields.io/badge/-Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)](https://nodejs.org/) [![Cloudflare Workers](https://img.shields.io/badge/-Cloudflare%20Workers-F38020?style=flat&logo=cloudflareworkers&logoColor=white)](https://workers.cloudflare.com/) |
| [network-protocol-analyzer](https://github.com/carlmasters02/network-protocol-analyzer) | Un analyseur de paquets en direct qui décode Ethernet, IPv4, TCP/UDP et DNS à la main depuis les octets bruts, sans aucune bibliothèque d'analyse. Il diffuse vers une interface en terminal, exporte du PCAP pour Wireshark, et signale les balayages de ports, le tunneling DNS et l'usurpation ARP au moment où ils se produisent. | [![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)](https://www.rust-lang.org/) |
| [python-static-analyzer](https://github.com/carlmasters02/python-static-analyzer) | Détecte les injections SQL et les injections de commandes dans du code source Python sans l'exécuter, grâce à l'analyse de l'AST et au suivi de teinte de la source vers le point sensible, en indiquant le fichier, la ligne et la raison pour laquelle la faille est exploitable. Précision et rappel mesurés sur des échantillons vulnérables étiquetés. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [coverage-guided-fuzzer](https://github.com/carlmasters02/coverage-guided-fuzzer) | Un fuzzer de type AFL qui trouve des plantages en mutant les entrées d'après le retour de couverture de code plutôt qu'au hasard, puis réduit chaque plantage à son plus petit cas reproductible. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black)](https://www.w3schools.com/c/) |
| [Crypto-Attack-Lab](https://github.com/carlmasters02/Crypto-Attack-Lab) | Un laboratoire pratique consacré aux attaques cryptographiques classiques : oracle de remplissage, extension de longueur de hachage, découpage-collage en mode ECB, attaque de Wiener sur RSA, et un canal auxiliaire temporel. Chacune est livrée avec une implémentation jouet vulnérable, un exploit fonctionnel, et un article sur l'erreur bien réelle qui se cache derrière. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |

---

### Développement d'applications web

| Projet | Objectif | Technologies |
| --- | --- | --- |
| [FocusHear](https://focus-hear-app.vercel.app/) | Une plateforme de communication assistée en temps réel pour les personnes malentendantes. Toutes les applications de sous-titrage transcrivent tout le monde à la fois, submergeant l'utilisateur de voix qui se chevauchent ; FocusHear vous laisse choisir quelle voix vous entendez, avec une écoute sélective, une passerelle vers la langue des signes pour la dactylologie ASL, et une séparation des locuteurs fondée sur des voix enregistrées. Construite en 48 heures pour remporter la **1re place** au SDGs to Startups 2026, puis reconstruite sur une chaîne GPT-4o et ElevenLabs Scribe avec des comptes authentifiés, la facturation, des profils vocaux et faciaux enregistrés et un modèle ONNX LSTM de langue des signes entraîné, avant d'être présentée à un événement Build with OpenAI sur invitation où elle a passé le premier tour. En ligne sur [focus-hear-app.vercel.app](https://focus-hear-app.vercel.app/). | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![OpenAI](https://img.shields.io/badge/-GPT--4o-412991?style=flat&logo=openai&logoColor=white)](https://openai.com/) [![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)](https://supabase.com/) [![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat&logo=stripe&logoColor=white)](https://stripe.com/) [![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white)](https://vercel.com/) |
| [NóiFlow AI](https://noiflow-ai.vercel.app/) | Un espace de travail IA contrôlé par l'enseignant pour la fluidité en anglais dans les classes vietnamiennes. Les enseignants créent des classes avec des codes d'invitation, transforment le vocabulaire réel des leçons en cartes mémoire bilingues et révisables, génèrent des lectures et des questions à partir de ce vocabulaire, et ajoutent des consignes de réponse orale ; les élèves s'entraînent ensuite avec les cartes, les devoirs et la voix, avec un retour IA immédiat, dans une boucle connectée. Chaque brouillon d'IA reste soumis à la relecture de l'enseignant avant publication, avec des analyses qui révèlent les mots faibles et les schémas de compétences. En ligne sur [noiflow-ai.vercel.app](https://noiflow-ai.vercel.app/). | [![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)](https://nextjs.org/) [![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white)](https://vercel.com/) |
| [MenYomi](https://github.com/carlmasters02/MenYomi) | Transforme la photo d'un menu de restaurant japonais en menu bilingue en direct. L'OCR lit chaque plat et son prix, puis chaque élément reçoit une traduction anglaise, une courte description, une note culturelle, des alertes allergènes, des filtres alimentaires et la prononciation japonaise lue à voix haute. Réalisé en solo à l'Agent Forge AI Hackathon, en intégrant six plateformes partenaires (Nosana, Qwen Cloud, GMI Cloud, ai&, Daytona, Qoder) derrière une seule couche compatible OpenAI. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |

---

### Projets de hackathon

| Projet | Objectif | Technologies |
| --- | --- | --- |
| [ai-wargame](https://github.com/carlmasters02/ai-wargame) | Deux agents LLM s'affrontent dans un wargame rouge contre bleu au tour par tour sur un réseau d'entreprise généré procéduralement : l'équipe rouge DeepSeek traque la base de données vitale sous le brouillard de guerre tandis que l'équipe bleue Kimi trie des alertes parasitées. Le match se déroule en direct sur une carte réseau interactive, un arbitre humain peut injecter des événements surprises ou changer de modèle en cours de partie, et chaque match s'exporte en artefacts MITRE ATT&CK et STIX. Simulation pure : les vulnérabilités sont des objets de jeu abstraits, sans code d'exploitation ni trafic réel. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)](https://neo4j.com/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [disaster-mutual-aid-matcher](https://github.com/carlmasters02/disaster-mutual-aid-matcher) | Élabore et soumet à des tests de résistance des plans d'évacuation individuels pour les résidents qui ont besoin d'aide pour évacuer, conformément au dispositif japonais d'aide à l'évacuation. Un solveur déterministe apparie les résidents avec des aidants locaux et replanifie en direct tandis qu'un séisme simulé bloque les routes, coupe l'électricité et propage les incendies ; les LLM s'occupent de l'analyse des signalements, de la rédaction des plans en japonais et des messages multilingues, avec Neo4j comme système d'enregistrement et toute l'inférence exécutée sur des GPU au Japon. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)](https://neo4j.com/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |

---

### Modèles

| Projet | Objectif | Technologies |
| --- | --- | --- |
| [python-cli-template](https://github.com/carlmasters02/python-cli-template) | Un modèle réutilisable pour une hygiène de dépôt professionnelle : agencement en `src/`, pytest avec mesure de couverture, intégration continue via GitHub Actions, badges d'état, un Dockerfile et des versions étiquetées en semver. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [static-site-template](https://github.com/carlmasters02/static-site-template) | Un modèle réutilisable pour un site statique en HTML/CSS/JS pur sans backend, avec tests, intégration continue via GitHub Actions et un Dockerfile. | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [flask-webapp-template](https://github.com/carlmasters02/flask-webapp-template) | Un modèle réutilisable pour des applications web Python + Flask, avec tests, intégration continue via GitHub Actions et un Dockerfile. | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask&logoColor=white)](https://flask.palletsprojects.com/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [express-webapp-template](https://github.com/carlmasters02/express-webapp-template) | Un modèle réutilisable pour des applications web Node + Express avec un frontend HTML/CSS/JS pur, avec tests, intégration continue via GitHub Actions et un Dockerfile. | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Node.js](https://img.shields.io/badge/-Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)](https://nodejs.org/) [![Express](https://img.shields.io/badge/-Express-000000?style=flat&logo=express&logoColor=white)](https://expressjs.com/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |
| [react-express-template](https://github.com/carlmasters02/react-express-template) | Un modèle réutilisable pour un frontend React (Vite) adossé à une API Node/Express, avec tests, intégration continue via GitHub Actions et un Dockerfile. | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)](https://react.dev/) [![Express](https://img.shields.io/badge/-Express-000000?style=flat&logo=express&logoColor=white)](https://expressjs.com/) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) |

---

### Projets IoT

| Projet | Objectif | Technologies |
| --- | --- | --- |
| [g2-vi-en-realtime](https://github.com/carlmasters02/g2-vi-en-realtime) | Traduction en direct du vietnamien vers l'anglais pour les lunettes connectées Even Realities G2, créée parce que l'application Translate intégrée aux lunettes ne prend pas en charge le vietnamien. L'audio du micro est diffusé en Bluetooth vers l'API de traduction en temps réel d'OpenAI, et l'anglais s'affiche dans l'affichage tête haute environ une seconde après l'interlocuteur, avec une transcription bilingue enregistrée ensuite. Fonctionne avec [g2-relay](https://github.com/carlmasters02/g2-relay), un relais Cloudflare Worker qui garde la clé d'API côté serveur, car un navigateur ne peut pas ajouter d'en-tête d'authentification à un WebSocket. | [![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/) [![OpenAI](https://img.shields.io/badge/-OpenAI%20Realtime-412991?style=flat&logo=openai&logoColor=white)](https://platform.openai.com/docs/guides/realtime) [![Cloudflare Workers](https://img.shields.io/badge/-Cloudflare%20Workers-F38020?style=flat&logo=cloudflareworkers&logoColor=white)](https://workers.cloudflare.com/) |

---

### Portfolio & sites web

| Projet | Objectif | Technologies |
| --- | --- | --- |
| [PickYourLinux](https://github.com/carlmasters02/PickYourLinux) | Un guide pour choisir une distribution Linux. Un arbre généalogique interactif relie 56 distributions à leurs racines Debian, Fedora et Arch, et un quiz par étapes demande d'abord ce que vous mettez en place (un ordinateur de bureau, un serveur, une boîte à outils de sécurité, un système axé sur la confidentialité, une console portable ou une carte IoT), resserre le choix à chaque point d'étape, puis recommande une distribution et une édition précises, avec les raisons, les mises en garde et ce qu'il faut régler avant de changer. Développé en HTML, CSS et JavaScript natifs, sans étape de build ni requête vers des tiers. | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![D3.js](https://img.shields.io/badge/-D3.js-F9A03C?style=flat&logo=d3&logoColor=white)](https://d3js.org/) |
| [Mon portfolio personnel](https://carlmasters.com) | Un portfolio personnel où je présente mes compétences, mes réalisations et le reste. En ligne sur [carlmasters.com](https://carlmasters.com). | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |
| [Kady's English Classes](https://kadysenglish.com) | Un site conçu et développé pour une professeure d'anglais indépendante au Viêt Nam. En ligne sur [kadysenglish.com](https://kadysenglish.com). | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://www.w3schools.com/html/) [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3schools.com/css/) [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |

---

### Événements & hackathons

| Date | Événement | Notes |
| --- | --- | --- |
| Octobre 2026 | Tokyo Agent Hackathon | Un hackathon d'une journée sur le thème de l'innovation ouverte, organisé par +81 Builders et sponsorisé par Neo4j et ai&. Participation en solo, avec [AI Wargame](https://github.com/carlmasters02/ai-wargame) : une simulation rouge contre bleu en direct où un attaquant DeepSeek et un défenseur Kimi s'affrontent pour un réseau d'entreprise généré procéduralement sur un graphe Neo4j. |
| Août 2026 | HITCON 2026 | Deux jours à la Hacks In Taiwan Conference à Taipei, sur le thème « When AI Acts: Hacking the Age of Agentic Systems ». Les conférences ont couvert la divulgation de vulnérabilités à l'ère de l'IA, l'automatisation d'un SOC par agents, la recherche sur le matériel embarqué, la provenance de la chaîne d'approvisionnement et les méthodes des attaquants étatiques, pour finir sur l'évasion de sandbox zero-click d'Edge par Orange Tsai. |
| Juillet 2026 | Cursor Tokyo AI Meetup | Une soirée avec l'équipe de Cursor chez Datadog Japan, autour des Cloud Agents et de la manière de structurer des flux de développement autonomes. |
| Juillet 2026 | Engineering Real World AI with Google and Google DeepMind | Conférence d'ouverture et atelier Google AI Studio chez Google Japan sur le passage des systèmes d'IA du prototype à la production. |
| Juillet 2026 | Agent Forge AI Hackathon | Un hackathon d'une journée sur les agents d'IA prêts pour la production, sur le thème de Tokyo et de la culture japonaise. Participation en solo, avec [MenYomi](https://github.com/carlmasters02/MenYomi) : une application qui transforme la photo d'un menu japonais en menu bilingue, avec traductions et alertes allergènes. |
| Juillet 2026 | ai& × Moonshot Tokyo Hackathon Night | Un hackathon d'une seule soirée bâti autour de Kimi K2.7 Code tournant sur la plateforme d'inférence d'ai&. |
| Juillet 2026 | Vibe Coders Tokyo: Local Models with Gemma 4 | Faire tourner des modèles à poids ouverts sur du matériel local, et ce que cela change en matière de coût, de latence et de contrôle sur ses propres données. |
| Juin 2026 | OpenAI × Tokyo AI: Build with OpenAI | Événement de développement sur invitation. J'y ai présenté un FocusHear reconstruit avec une architecture de production, qui a passé le premier tour. |
| Juin 2026 | SDGs to Startups Hackathon 2026 | **1re place.** Un développement de 48 heures répondant à l'Objectif de développement durable n° 10 de l'ONU avec FocusHear, qui isole une voix unique pour les personnes malentendantes. |
| Mars 2026 | Builders Weekend 2026 | Livraison de TabeTalk avec une équipe de cinq personnes de Temple University Japan : une application d'IA pour les repas qui identifie à la voix qui a commandé quoi et partage l'addition. |
| Mars 2026 | UI/UX Hackathon | **1re place.** Étude des besoins utilisateurs, wireframes et prototypage d'une interface, puis défense de chaque décision de conception devant le jury. |

---

### 📚 Derniers articles

- [Comment écrire un CV qui est vraiment lu](https://carlmasters.com/article-resume.html)
- [Les habitudes de cybersécurité du quotidien qui comptent vraiment](https://carlmasters.com/article-cybersecurity.html)
- [La pile de la vie privée : des alternatives open source et chiffrées pour chaque application que vous utilisez](https://carlmasters.com/article-privacy.html)

---

### Liens

- 🌐 Site web : [carlmasters.com](https://carlmasters.com)
- 💼 LinkedIn : [carl-masters](https://www.linkedin.com/in/carl-masters-724951297)
- 🛠️ E-mail développeur : [carl.masters.dev@protonmail.com](mailto:carl.masters.dev@protonmail.com), pour signaler des bugs ou des problèmes et poser des questions sur mon code
- 📧 E-mail professionnel : [carl.masters.professional@protonmail.com](mailto:carl.masters.professional@protonmail.com), pour les contacts professionnels, les offres d'emploi et les stages
