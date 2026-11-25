# Bastion d'Éther — Jouer en ligne & Téléchargement

Dépôt public de distribution pour **Bastion d'Éther** (version Web instantanée sur GitHub Pages + exécutable Windows autonome pour le Co-op LAN Wi-Fi).

## 🌐 Jouer directement dans le navigateur (Recommandé)

👉 **[JOUER À BASTION D'ÉTHER EN LIGNE (v1.0.0 · f3f2322)](https://damien-16.github.io/towerdef-releases/)**

- **Zéro téléchargement, zéro alerte antivirus** : fonctionne immédiatement dans Chrome, Edge, Firefox ou Safari.
- **Toujours à jour** : Mode Aventure (100 niveaux), Survie Infinie, Mode 3D / HD / Pixel-Art, Arbres Permanents et sauvegardes automatiques dans votre navigateur.

---

## 💻 Téléchargement Windows (Co-op LAN Wi-Fi & Hors-ligne)

👉 **[Télécharger BastionDEther-Windows.zip (v1.0.0 · f3f2322)](https://github.com/Damien-16/towerdef-releases/raw/main/release/BastionDEther-Windows.zip)**  
*(Lien direct .exe : [BastionDEther.exe](https://github.com/Damien-16/towerdef-releases/raw/main/release/BastionDEther.exe))*

- **Aucun prérequis** : pas besoin d'installer Node.js.
- **Solo & Co-op LAN (2–4 joueurs)** : serveur HTTP/WebSocket intégré pour jouer ensemble sur le même Wi-Fi / réseau local.
- **Mises à jour automatiques** : le launcher vérifie automatiquement `release/version.json` et télécharge les patchs (`release/game.zip`).

> 💡 *Comme l'exécutable Windows est compilé sans certificat commercial payant, Windows SmartScreen peut afficher un avertissement : cliquez sur **Informations complémentaires** puis **Exécuter quand même**. Pour éviter tout avertissement, utilisez la version Web ci-dessus !*

---

## Dernière version publiée

- **Version** : `v1.0.0`
- **Build** : `f3f2322`
- **Date de compilation** : `2026-11-25`

### Notes de mise à jour récentes

- `f3f2322` (2026-11-25) — fix: correction des 71 bugs de l'audit complet (gameplay, 3D, UI, LAN, launcher et exe)
- `5dc82a1` (2026-11-24) — docs: ajout de l'audit complet des 71 bugs (BUGS_AUDIT.md) et mise à jour du contexte IA
- `e037d61` (2026-11-24) — Mise à jour des artefacts de release (BastionDEther.exe, game.zip, version.json)
- `25eeb48` (2026-11-23) — Refonte épurée du launcher (sans emoji) et recompilation de BastionDEther.exe
- `ebc35b7` (2026-11-23) — feat: dépôt public séparé pour les releases auto-updater (towerdef-releases)
- `6800deb` (2026-11-23) — feat: ajout du mode 3D Three.js (caméra 3e personne et style semi-pixel)
- `ede0565` (2026-11-23) — chore: filtrage des échanges utiles et sync ai-discussions avant commit
- `6672638` (2026-11-23) — docs: rédaction complète du README
- `07f7204` (2026-11-23) — fix : suppression du node module dans le gitignore
- `119b6a9` (2026-11-22) — Ajout dossier ai-discussions et hooks de sauvegarde/contexte IA automatique
