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

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

---

### Projets par langage principal

De petits outils autonomes qui appuient les langages ci-dessus avec du code qui fonctionne. Chacun prend un seul langage et l'applique à un problème réel, afin que la maîtrise que je revendique s'accompagne de quelque chose que vous pouvez lire.

| Projet | Objectif | Technologies |
| --- | --- | --- |
| [secret-scanner](https://github.com/carlmasters02/secret-scanner) | Un outil en ligne de commande qui analyse une base de code à la recherche de secrets écrits en dur, en associant la correspondance par expressions régulières à une analyse d'entropie de Shannon pour attraper les chaînes très aléatoires que les motifs figés laissent passer. Écrit pour travailler l'analyse statique, les entrées-sorties fichier et la conception d'interfaces en ligne de commande en Python. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) |
| [cryptfile](https://github.com/carlmasters02/cryptfile) | Un outil en ligne de commande de chiffrement de fichiers en AES-256-GCM bâti sur OpenSSL, dérivant sa clé d'une phrase secrète avec PBKDF2. Écrit pour travailler la gestion mémoire bas niveau, les entrées-sorties de fichiers binaires et l'intégration d'une bibliothèque cryptographique en C. | ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) ![OpenSSL](https://img.shields.io/badge/-OpenSSL-721412?style=flat&logo=openssl&logoColor=white) |

---

### Projets sécurité & systèmes

| Projet | Objectif | Technologies |
| --- | --- | --- |
| [network-protocol-analyzer](https://github.com/carlmasters02/network-protocol-analyzer) | Un analyseur de paquets en direct qui décode Ethernet, IPv4, TCP/UDP et DNS à la main depuis les octets bruts, sans aucune bibliothèque d'analyse. Il diffuse vers une interface en terminal, exporte du PCAP pour Wireshark, et signale les balayages de ports, le tunneling DNS et l'usurpation ARP au moment où ils se produisent. | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white) |
| [python-static-analyzer](https://github.com/carlmasters02/python-static-analyzer) | Détecte les injections SQL et les injections de commandes dans du code source Python sans l'exécuter, grâce à l'analyse de l'AST et au suivi de teinte de la source vers le point sensible, en indiquant le fichier, la ligne et la raison pour laquelle la faille est exploitable. Précision et rappel mesurés sur des échantillons vulnérables étiquetés. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| [coverage-guided-fuzzer](https://github.com/carlmasters02/coverage-guided-fuzzer) | Un fuzzer de type AFL qui trouve des plantages en mutant les entrées d'après le retour de couverture de code plutôt qu'au hasard, puis réduit chaque plantage à son plus petit cas reproductible. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) |
| [Crypto-Attack-Lab](https://github.com/carlmasters02/Crypto-Attack-Lab) | Un laboratoire pratique consacré aux attaques cryptographiques classiques : oracle de remplissage, extension de longueur de hachage, découpage-collage en mode ECB, attaque de Wiener sur RSA, et un canal auxiliaire temporel. Chacune est livrée avec une implémentation jouet vulnérable, un exploit fonctionnel, et un article sur l'erreur bien réelle qui se cache derrière. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| [python-cli-template](https://github.com/carlmasters02/python-cli-template) | Un modèle réutilisable pour une hygiène de dépôt professionnelle : agencement en `src/`, pytest avec mesure de couverture, intégration continue via GitHub Actions, badges d'état, un Dockerfile et des versions étiquetées en semver. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |

---

### Développement d'applications web

| Projet | Objectif | Technologies |
| --- | --- | --- |
| [FocusHear](https://focus-hear-app.vercel.app/) | Une plateforme de communication assistée en temps réel pour les personnes malentendantes. Toutes les applications de sous-titrage transcrivent tout le monde à la fois, submergeant l'utilisateur de voix qui se chevauchent ; FocusHear vous laisse choisir quelle voix vous entendez, avec une écoute sélective, une passerelle vers la langue des signes pour la dactylologie ASL, et une séparation des locuteurs fondée sur des voix enregistrées. Construite en 48 heures pour remporter la **1re place** au SDGs to Startups 2026, puis reconstruite sur une chaîne GPT-4o et ElevenLabs Scribe avec des comptes authentifiés, la facturation, des profils vocaux et faciaux enregistrés et un modèle ONNX LSTM de langue des signes entraîné, avant d'être présentée à un événement Build with OpenAI sur invitation où elle a passé le premier tour. En ligne sur [focus-hear-app.vercel.app](https://focus-hear-app.vercel.app/). | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![OpenAI](https://img.shields.io/badge/-GPT--4o-412991?style=flat&logo=openai&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat&logo=stripe&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white) |

---

### Portfolio & sites web

| Projet | Objectif | Technologies |
| --- | --- | --- |
| [Mon portfolio personnel](https://carlmasters.com) | Un portfolio personnel où je présente mes compétences, mes réalisations et le reste. En ligne sur [carlmasters.com](https://carlmasters.com), code source sur [My-Personal-Portfolio](https://github.com/carlmasters02/My-Personal-Portfolio). | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| [Kady's English Classes](https://kadysenglish.com) | Un site conçu et développé pour une professeure d'anglais indépendante au Viêt Nam. En ligne sur [kadysenglish.com](https://kadysenglish.com). | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |

---

### Événements & hackathons

| Date | Événement | Notes |
| --- | --- | --- |
| Juillet 2026 | Cursor Tokyo AI Meetup | Une soirée avec l'équipe de Cursor chez Datadog Japan, autour des Cloud Agents et de la manière de structurer des flux de développement autonomes. |
| Juillet 2026 | Engineering Real World AI with Google and Google DeepMind | Conférence d'ouverture et atelier Google AI Studio chez Google Japan sur le passage des systèmes d'IA du prototype à la production. |
| Juillet 2026 | Agent Forge AI Hackathon | Un hackathon d'une journée sur les agents d'IA prêts pour la production, sur le thème de Tokyo et de la culture japonaise. Participation en solo. |
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
