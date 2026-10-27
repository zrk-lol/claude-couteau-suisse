# 🔪 claude-couteau-suisse

**14 commandes qui rendent Claude meilleur dans tous les domaines** : travail, études, business, code, administratif, vie perso.

Tu tapes `/brief`, `/verifie`, `/decide`… et Claude suit une méthode éprouvée au lieu de répondre au hasard.

<p>
<img src="https://img.shields.io/badge/commandes-14-e10600?style=flat-square&labelColor=111111" />
<img src="https://img.shields.io/badge/Claude_Code-plugin-e10600?style=flat-square&labelColor=111111" />
<img src="https://img.shields.io/badge/claude.ai-compatible-e10600?style=flat-square&labelColor=111111" />
<img src="https://img.shields.io/badge/licence-MIT-9a9aa4?style=flat-square&labelColor=111111" />
</p>

## Les 14 commandes

| Commande | Ce qu'elle fait | Exemple |
|---|---|---|
| `/brief` | Pose les 5 bonnes questions et écrit un brief parfait avant de commencer | `/brief un site pour mon restaurant` |
| `/verifie` | Passe une réponse ou un document au crible : faits, chiffres, hypothèses, confiance | `/verifie` (sur la dernière réponse) |
| `/resume` | Résumé en 1 phrase, 5 points, détaillé, plus les actions à retenir | `/resume compte-rendu.pdf` |
| `/decide` | Matrice de décision pondérée, recommandation, ce qui ferait changer d'avis | `/decide CDI ou freelance` |
| `/plan` | Plan d'action daté, jalons, risques, première action en 10 min | `/plan lancer ma boutique en 6 semaines` |
| `/apprends` | Cours pas à pas avec analogies, quiz et fiche récap | `/apprends Excel, niveau débutant` |
| `/ecris` | E-mail, message ou post en 3 versions (courte, standard, ton adapté) | `/ecris relance facture impayée` |
| `/critique` | Avocat du diable : points faibles classés, objections, version améliorée | `/critique mon business plan` |
| `/explique` | Pour un enfant, un adulte, un expert + idées reçues | `/explique l'inflation` |
| `/brainstorm` | 20 idées triées par impact et effort, top 3 et pari audacieux | `/brainstorm trouver des clients` |
| `/negocie` | Seuils, alternatives, arguments, objections, phrases d'ouverture, simulation | `/negocie augmentation de salaire` |
| `/debug` | Résolution méthodique : symptômes, hypothèses, tests, prévention | `/debug mon wifi coupe le soir` |
| `/compare` | Tableau comparatif selon ton usage, pièges et meilleur choix par profil | `/compare iPhone vs Pixel` |
| `/relis` | Corrige sans changer ton style, avec la liste des changements | `/relis lettre de motivation` |

## Installation

### Claude Code (recommandé)

```
/plugin marketplace add zrk-lol/claude-couteau-suisse
/plugin install couteau-suisse@varhex
```

Les commandes apparaissent quand tu tapes `/`.

### À la main

Copie le dossier `commands/` dans `~/.claude/commands/` (pour tous tes projets) ou dans `.claude/commands/` d'un projet.

### claude.ai et application mobile

Ouvre **[PROMPTS-CLAUDE-AI.md](PROMPTS-CLAUDE-AI.md)** : les 14 commandes en version copier-coller. Astuce : colle-les dans les instructions d'un **Projet** Claude pour les avoir sous la main.

## Pourquoi ça marche

Claude répond mieux quand on lui donne une **méthode** plutôt qu'une question. Chaque commande impose :

- **une structure de réponse** (tableaux, niveaux, étapes) qui évite les pavés ;
- **des garde-fous** : ne pas inventer, signaler l'incertitude, marquer ce qui manque avec `[À COMPLÉTER]` ;
- **une action concrète** à la fin, pour passer de la réponse à l'action.

## Combos utiles

| Situation | Enchaînement |
|---|---|
| Projet flou | `/brief` → `/plan` → `/critique` |
| Info trouvée en ligne | `/resume` → `/verifie` |
| Gros choix | `/compare` → `/decide` |
| Rendez-vous important | `/negocie` → `/ecris` |
| Nouveau sujet | `/explique` → `/apprends` |

---

Fait par **[Varhex by Ȥrk Team](https://varhex.com)** · [TikTok](https://www.tiktok.com/@vertex.code.zrk) · [Instagram](https://www.instagram.com/varhex_by_zrk) · [Discord](https://discord.gg/4qRhB4c5me)

Aussi : [claude-skills-anti-ia](https://github.com/zrk-lol/claude-skills-anti-ia) · [claude-token-saver](https://github.com/zrk-lol/claude-token-saver)
