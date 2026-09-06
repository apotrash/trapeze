# Trapèze

Application macOS de transcription et de synthèse vidéo. Vos vidéos, vos
transcriptions et vos résumés restent sur votre ordinateur.

Ce dépôt ne sert qu'à la distribution : le code source n'y figure pas.
**[Télécharger la dernière version](../../releases/latest)**

## Installation

1. Téléchargez le fichier `.dmg`, ouvrez-le, glissez Trapèze dans Applications.
2. Lancez l'application. Elle est signée et notarisée par Apple : aucun
   avertissement de sécurité.
3. Saisissez votre code d'activation, au format `XXXX-XXXX-XXXX-XXXX`.

L'activation contacte nos serveurs une seule fois. Ensuite, Trapèze vérifie sa
licence hors ligne : ni panne de réseau ni déplacement ne vous bloquent.

## Ce qu'il faut sur votre Mac

Trapèze s'appuie sur des outils installés localement.

| Pour | Outil |
| --- | --- |
| Ouvrir et préparer vos vidéos | `ffmpeg`, `ffprobe` |
| Importer depuis un lien | `yt-dlp` |
| Écrire le texte de ce qui est dit | `whisper.cpp` et son fichier de modèle |

Le guide affiché au premier lancement vérifie réellement ce qui est présent et
vous dit ce qui manque.

### Pour les résumés

Trapèze n'inclut aucun abonnement d'intelligence artificielle : il utilise le
vôtre, avec son outil officiel.

- **Codex** — le CLI Codex et un abonnement ChatGPT.
- **Claude** — le CLI Claude et un abonnement Anthropic.

Sans fournisseur configuré, la transcription fonctionne ; le résumé non.

## Vos données

La bibliothèque, les transcriptions et les résumés restent sur votre Mac. Vos
fichiers vidéo d'origine ne sont jamais modifiés.

Si vous demandez un résumé, la transcription est envoyée au fournisseur que
vous avez choisi, avec votre propre compte, et traitée selon ses conditions.

L'activation ne transmet que votre code et une empreinte anonyme de votre
machine — un hachage, jamais l'identifiant matériel lui-même.

## Configuration requise

macOS sur puce Apple Silicon.
