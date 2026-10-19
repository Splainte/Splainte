# Robin

**Responsable chaîne YouTube [Frandroid](https://www.youtube.com/@Frandroid)** · Développeur d'outils pour production vidéo et systèmes d'IA autonomes.

Je conçois et maintiens des outils d'automatisation dédiés aux workflows vidéo professionnels : téléchargement de sources, intégration Premiere Pro, sous-titrage, dérush automatisé, transferts de fichiers, orchestration d'agents IA. Orienté pratique — chaque ligne de code répond à un cas d'usage terrain chez Frandroid ou en prestation.

## Projets publics

**[Robloader](https://github.com/Splainte/Robloader)** — Téléchargeur vidéo multi-plateforme (Tauri + Rust)  
Récupère des vidéos depuis YouTube, TikTok, Instagram, X et Weibo en un clic. Interface native Windows/macOS, file d'attente, cookies du navigateur pour la 4K et les contenus restreints, mises à jour in-app. Disponible en français et en anglais.

**[Copiteur](https://github.com/Splainte/Copiteur)** — Client de transfert SFTP (Tauri + rclone)  
Double explorateur façon FileZilla, motorisé par rclone : parallélise même un seul gros fichier pour tenir 100+ Mo/s depuis un NAS ou un serveur. Glisser-déposer dans les deux sens, file d'attente avec reprise automatique après coupure réseau, mises à jour signées. Windows et macOS, en français ou en anglais.

**[Coquille](https://github.com/Splainte/Coquille)** — Sous-titrage augmenté par IA pour Premiere Pro  
Transcrit la séquence, corrige le jargon tech (noms de produits, anglicismes, homophones) sans toucher au timing, découpe en lignes équilibrées et insère une vraie piste de sous-titres. Glossaire et règles par média, suggestions de l'IA validées une par une.

**[Robloader Extension](https://github.com/Splainte/Robloader-Extension)** — Robloader dans un panneau Premiere Pro  
Colle une URL : la vidéo est téléchargée, préparée et importée automatiquement dans le chutier `ELEMENTS/Robloader` du projet ouvert. Transcodage H.265 pour éviter les artefacts de décodage de Premiere, extraction d'un segment, yt-dlp mis à jour tout seul.

**[Sauron](https://github.com/Splainte/Sauron)** — Import automatique dans Premiere  
Surveille une arborescence de dossiers et reproduit les ajouts, renommages et suppressions dans des chutiers miroirs de Premiere, via chemins relatifs.

**[StableWarp](https://github.com/Splainte/StableWarp)** — Stabilisation + vitesse pour Premiere  
Applique Stabilisation de déformation et changement de vitesse sur un même plan, ce que Premiere refuse nativement : le plan est stabilisé à 100 % dans une séquence imbriquée, la vitesse est appliquée par-dessus.

## Projets privés

**Derusher** — Dérush automatique dans Premiere  
Détecte silences et mauvaises prises (transcription + LLM) pour pré-monter les rushes.

**DropCLI** — Interface web miroir de Claude Code (node-pty + xterm.js)  
Terminaux persistants même après déconnexion, reconnexion automatique, vue chat mobile. Sert à piloter la machine agent IA depuis n'importe quel navigateur.

**Feedback** — Plateforme de review vidéo façon Frame.io  
Un lien unique par projet pour que monteurs externes et équipe déposent et commentent les versions, branché directement sur le NAS.

**Catapulte** — Mise en ligne YouTube automatisée  
Upload via l'API YouTube, transcription locale et génération assistée du titre, de la description et des tags.

## Stack technique

**Langages :** Python · Rust · TypeScript · JavaScript (React) · Java (Android natif)  
**Runtimes & frameworks :** Tauri v2 · Node.js · FastAPI · CEP (Adobe) · UXP  
**Outils & infra :** rclone · Docker · Playwright · yt-dlp · FFmpeg · Whisper · Claude API  
**Plateformes :** Adobe Creative Suite · Premiere Pro scripting · macOS/Windows/Linux · Android 14+

## Philosophie

Chaque projet cible la friction réelle : pas de MVP académique, mais des solutions rodées qui s'intègrent dans les workflows existants. Documentées pour une prise en main immédiate, testées en conditions réelles avant la livraison.

<!-- profil -->
