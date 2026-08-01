# Robin

**Responsable chaîne YouTube [Frandroid](https://www.youtube.com/@Frandroid)** · Développeur d'outils pour production vidéo et systèmes d'IA autonomes.

Depuis 2020, je conçois et maintiens des outils d'automatisation dédiés aux workflows vidéo professionnels : téléchargement de sources, intégration Premiere Pro, dérush automatisé, orchestration multi-agents. Orienté pratique — chaque ligne de code répond à un cas d'usage terrain chez Frandroid ou en prestation.

## Projets publics

**[Robloader](https://github.com/Splainte/Robloader)** — Téléchargeur multi-plateforme (Rust)  
Récupère des vidéos depuis YouTube, TikTok, Instagram, X, Weibo avec filtrages intelligents. Interface native Tauri + WebView, file d'attente, mises à jour in-app silencieuses. Signature cryptographique sur Windows et macOS.

**[Robloader Extension](https://github.com/Splainte/Robloader-Extension)** — Panneau Adobe Premiere Pro  
Intègre Robloader directement dans Premiere : télécharge et importe automatiquement dans des chutiers structurés. CEP (panel COM-based), détection des encodeurs matériels GPU, transcription locale Whisper en parallèle, gestion des fichiers H.264 long-GOP.

**[Sauron](https://github.com/Splainte/Sauron)** — Surveilleur de projet Premiere  
Observe les changements dans une arborescence (add/rename/delete) et les propage automatiquement aux chutiers Premiere via chemins relatifs. Évite la fragilité des symlinks, utilise chokidar côté système et scripting Premiere CEP.

**[StableWarp](https://github.com/Splainte/StableWarp)** — Stabilisation intelligente pour Premiere  
Applique warpstab + ajuste la vitesse de lecture. Architecture CEP avec nid inversé (stabilité à 100%, commande vitesse en surcharge). Exploitation des API Premiere séquence/clip, fin du support CEP prévue septembre 2026.

## Projets privés

**Feedback** — Plateforme de review vidéo (Frame.io-like)  
Centralize le workflow de retour client sur conteneur Docker/Fastify. Freelances et équipe interne déposent/commentent les versions directement via un web client branché au NAS. Remplace le découpage drive/mail/slack par un lien unique par projet.

**Copiteur** — GUI de transfert fichiers (Tauri + rclone sidecar)  
Interface FileZilla-style pour gérer les transferts vers infrastructure distante (NAS Neufsept, seedbox). Drag-and-drop, synchronisation bi-directionnelle, gestion de quotas réseau.

**DropCLI** — Terminal web persistant (node-pty + xterm.js)  
Interface web qui reflète un terminal distant : PTY persistants même après déconnexion, reconnexion auto, sessions multi-utilisateurs. Utilisé en interne pour piloter machine agent IA via navigateur.

## Stack technique

**Langages :** Python · Rust · JavaScript · TypeScript · Java (Android natif)  
**Runtimes & frameworks :** Tauri v2 · Node.js · FastAPI · CEP (Adobe) · UXP  
**Outils & infra :** Ollama · Docker · Playwright · yt-dlp · FFmpeg · Whisper · Claude API  
**Plateformes :** Adobe Creative Suite · Premiere Pro scripting · macOS/Windows/Linux · Android 14+

## Philosophie

Chaque projet cible la friction réelle : pas de MVP académique, mais des solutions rodées qui s'intègrent dans les workflows existants. Documentées pour une prise en main immédiate, testées en conditions réelles avant la livraison.

## Système autonome

Machine agent IA 24/7 sous Linux (Ubuntu Server) avec accès cloud Anthropic. Architecture multi-services pour scrapage, orchestration et analyse : superviseurs systemd, CTL à chaud via Tailscale, dashboards locaux. Permet de valider les outils sur des vraies données Frandroid (volumes, timing, formats réels).
<!-- profil -->
