# 13 skills Claude gratuits pour ton Instagram

Les skills de la vidéo [@sosav.ai](https://www.instagram.com/sosav.ai/) « Mon profil a eu 42/100 » : Claude écrit, note et prépare, et rien ne se publie sans toi.

| Skill | Ce qu'il fait |
|---|---|
| `ig-profile` | Note ton profil sur 100 et réécrit ce qui fait perdre des points : nom, bio, lien, épinglés. |
| `ig-reel` | Écrit ton réel à partir d'une idée : accroches notées, texte à dire, texte à l'écran, timing. |
| `ig-viral` | Trouve les réels qui cartonnent dans ta niche, les classe et te dit pourquoi ils marchent. |
| `ig-story` | Écrit tes stories du jour, écran par écran, avec les stickers. |
| `ig-caption` | Écrit la légende et la vérifie avant publication : première ligne, hashtags, appel à l'action. |
| `ig-carousel` | Construit un carrousel : la couverture, le texte de chaque slide, les images à publier. |
| `ig-plan` | Planifie ta semaine : quoi poster, quel format, quand, avec qui interagir. |
| `ig-comment` | Prépare des commentaires chez d'autres créateurs, qui sonnent comme toi. |
| `ig-reply` | Trie les commentaires sous tes posts et prépare les réponses qui valent le coup. |
| `ig-dm` | Écrit tes DM : premier message, proposition de collab, relances. |
| `ig-repurpose` | Transforme une vidéo longue, un podcast ou un article en une semaine de réels et de carrousels. |
| `ig-audit` | Analyse ce que tu as déjà posté : ce qui a marché, pourquoi, et ce qu'il faut arrêter. |
| `ig-human` | Enlève les tics de l'IA d'un texte avant qu'il parte. |

Les skills écrivent, toi tu postes : aucun ne publie ni n'envoie quoi que ce soit à ta place.

## Ce qu'il te faut

- **Claude Code** (abonnement Claude), ou l'appli Claude avec les skills activés
- Rien d'autre : pas de clé, pas de compte à connecter

## Installation

Le plus simple : colle le lien de ce dépôt dans Claude et demande-lui d'installer les skills.

Ou à la main :

```bash
git clone https://github.com/Sosavskaii/skills-instagram-claude.git
```

puis copie les dossiers de `skills/` dans `~/.claude/skills/` (sur Windows : `C:\Users\<toi>\.claude\skills\`). Remplis `templates/voice.md` avec ta façon de parler : les skills s'en servent pour écrire comme toi.

## Utilisation

Tape par exemple `/ig-profile` et colle ton profil, `/ig-reel` avec ton idée, ou `/ig-plan` pour ta semaine.

## Crédits

Ces skills viennent de [instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill) de Jake Schincariol, sous licence MIT (voir `LICENSE`). Le README d'origine, en anglais, est dans `README.en.md`.
