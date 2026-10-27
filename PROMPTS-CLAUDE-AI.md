# Couteau suisse Claude — version claude.ai et application mobile

Pas de Claude Code ? Copie un bloc ci-dessous dans Claude, remplace `[…]` par ta demande.

## /brief — Transforme une demande floue en brief complet avant de commencer

```text
Tu vas transformer cette demande en brief précis avant de produire quoi que ce soit : [ce que tu veux faire]

1. Reformule la demande en une phrase.
2. Pose **au maximum 5 questions**, uniquement celles dont la réponse change vraiment le résultat (objectif, public, contraintes, format, délai, budget, ce qui existe déjà). Propose une réponse par défaut pour chacune entre parenthèses.
3. Attends les réponses. Si l'utilisateur répond « défaut », prends tes propositions.
4. Écris le brief final :
   - **Objectif** (mesurable si possible)
   - **Pour qui**
   - **Livrable** (format exact, longueur)
   - **Contraintes** et ce qu'il ne faut pas faire
   - **Critères de réussite** (3 à 5 points vérifiables)
5. Demande : « Je lance avec ce brief ? »
```

## /verifie — Vérifie une réponse, un document ou une affirmation avant de t'y fier

```text
Vérifie ceci de façon critique : [texte, fichier ou rien pour la dernière réponse]
(Si rien n'est fourni, vérifie ta dernière réponse.)

Produis un tableau :

| Affirmation | Type (fait / chiffre / opinion / hypothèse) | Fiabilité (solide / à vérifier / douteux) | Pourquoi | Comment vérifier |

Puis :
- **Ce qui manque** pour conclure.
- **Hypothèses cachées** sur lesquelles tout repose.
- **Erreurs probables** (calculs, dates, noms, logique) avec la correction.
- **Niveau de confiance global** sur 10, justifié en une phrase.

Ne présente jamais un point « à vérifier » comme certain. Si tu n'as pas accès à une source, dis-le.
```

## /resume — Résume n'importe quel contenu en 3 niveaux, avec les actions à retenir

```text
Résume : [texte, fichier, URL ou sujet]

Rends exactement ce format :

**En une phrase :** l'idée principale.

**En 5 points :** les éléments essentiels, un par ligne, sans répétition.

**En détail :** une synthèse structurée par sous-titres, pour quelqu'un qui n'a pas lu l'original.

**À retenir / à faire :** décisions, dates, chiffres, actions concrètes (avec qui et quand si c'est indiqué).

**Ce que le texte ne dit pas :** les questions importantes laissées sans réponse.

N'ajoute aucune information absente de la source. Cite les chiffres exactement.
```

## /decide — Aide à prendre une décision avec une matrice pondérée

```text
Aide-moi à décider : [la décision et les options]

1. Liste les options (ajoute « ne rien faire / attendre » si pertinent, et une option à laquelle je n'ai peut-être pas pensé).
2. Propose 4 à 6 critères avec un poids (total 100). Demande si je veux ajuster les poids, sinon continue.
3. Tableau : options × critères, note de 1 à 5, score pondéré.
4. **Recommandation** en une phrase, avec la raison principale.
5. **Ce qui me ferait changer d'avis** : les 2 ou 3 informations qui inverseraient le résultat.
6. **Le test le moins cher** pour réduire l'incertitude avant de décider.
7. Le pire scénario de l'option recommandée et comment le limiter.

Pour les sujets médicaux, juridiques ou financiers importants, rappelle de valider avec un professionnel.
```

## /plan — Transforme un objectif en plan d'action concret et daté

```text
Construis un plan d'action pour : [objectif + délai]

- **Objectif reformulé** : précis, mesurable, avec une date.
- **Étapes** en tableau : n°, action concrète (un verbe), durée estimée, échéance, livrable, dépendance.
- **Jalons** : 3 moments où l'on vérifie qu'on est sur la bonne voie, avec le critère de vérification.
- **Risques** : les 3 plus probables, et la parade pour chacun.
- **La première action à faire dans les 10 prochaines minutes.**

Si le délai est irréaliste, dis-le et propose une version réduite qui tient dans le délai.
```

## /apprends — Apprends n'importe quel sujet pas à pas, avec quiz et exercices

```text
Apprends-moi : [sujet + ton niveau]

1. Demande mon niveau et mon objectif si je ne les ai pas donnés (une seule question).
2. Donne une **carte du sujet** : 5 à 7 notions, dans l'ordre où les apprendre.
3. Enseigne **une notion à la fois** :
   - explication courte avec un exemple concret ;
   - une analogie de la vie quotidienne ;
   - l'erreur la plus fréquente sur cette notion ;
   - **une question de quiz**. Attends ma réponse avant de continuer.
4. Corrige ma réponse avec bienveillance, réexplique autrement si je me trompe.
5. Après la dernière notion : un mini-exercice pratique et une fiche récapitulative d'une page.
```

## /ecris — Rédige un e-mail, un message ou un post, dans le ton voulu

```text
Rédige : [à qui, pourquoi, ton]

Règles :
- Commence par l'essentiel. Une demande claire, une seule si possible.
- Phrases courtes, pas de formules creuses (« je me permets de », « n'hésitez pas »).
- Adapte le ton au destinataire (client, patron, ami, administration).

Donne **3 versions** :
1. **Courte** (3–4 lignes)
2. **Standard**
3. **Plus chaleureuse** ou **plus ferme** selon le contexte

Ajoute un **objet** pour les e-mails. Signale toute info manquante avec `[À COMPLÉTER]` au lieu de l'inventer.
```

## /critique — Joue l'avocat du diable sur une idée, un texte ou un projet, puis l'améliore

```text
Critique sans complaisance : [ce qu'il faut critiquer]

1. **Ce qui marche** (2–3 points, brièvement).
2. **Points faibles**, classés du plus grave au moins grave, chacun avec : le problème, pourquoi c'est un problème, une correction concrète.
3. **Les objections** que poserait une personne sceptique (client, investisseur, prof, jury), et la meilleure réponse.
4. **Ce qui manque complètement.**
5. **Version améliorée** (ou plan de réécriture si c'est trop long).

Sois direct. Pas de compliment gratuit.
```

## /explique — Explique n'importe quoi simplement, puis en profondeur

```text
Explique : [concept ou question]

1. **Pour un enfant de 12 ans** : 3–4 phrases, une analogie concrète.
2. **Pour un adulte curieux** : le fonctionnement réel, un exemple chiffré ou concret.
3. **Pour un expert** : les nuances, limites, débats ou cas particuliers.
4. **Les 3 idées reçues** les plus courantes sur le sujet, et pourquoi elles sont fausses.
5. **Pour aller plus loin** : les mots-clés exacts à chercher.

Si une partie relève de l'incertitude scientifique ou de l'opinion, signale-le.
```

## /brainstorm — Génère beaucoup d'idées puis les trie par impact et effort

```text
Brainstorm sur : [problème ou objectif]

1. Génère **20 idées** variées : évidentes, originales, radicales, gratuites, ce que ferait un concurrent, l'inverse de l'habitude.
2. Tableau : idée, impact (1–5), effort (1–5), coût approximatif.
3. **Top 3 « gains rapides »** (fort impact, faible effort).
4. **1 pari audacieux** qui vaut la peine d'être testé.
5. Pour le n°1 : comment le tester en moins d'une semaine.
```

## /negocie — Prépare une négociation : salaire, prix, contrat, conflit

```text
Prépare la négociation : [situation, ce que tu veux]

- **Mon objectif idéal**, **mon point acceptable**, **mon seuil de rupture**.
- **Ma meilleure alternative** si ça échoue (et comment la renforcer avant de négocier).
- **Ce que veut probablement l'autre partie**, ses contraintes et son alternative.
- **Mes 5 arguments** classés par force, avec une preuve pour chacun.
- **Les objections probables** et une réponse pour chacune.
- **Ce que je peux céder** qui me coûte peu mais compte pour l'autre.
- **Les 3 premières phrases** pour ouvrir la discussion.
- Propose ensuite une **simulation** : tu joues l'autre partie, je réponds.
```

## /debug — Résout méthodiquement un problème, technique ou non

```text
Aide-moi à résoudre : [ce qui ne marche pas]

1. **Symptômes** : reformule précisément ce qui se passe, ce qui était attendu, depuis quand, ce qui a changé.
2. Pose les questions manquantes (3 maximum) si c'est bloquant.
3. **Hypothèses** classées de la plus probable à la moins probable, avec pour chacune un indice qui la confirmerait.
4. **Tests** : pour chaque hypothèse, le test le plus simple et rapide à faire, dans l'ordre.
5. Une fois la cause trouvée : la correction, puis **comment éviter que ça revienne**.

Un test à la fois. Ne propose pas de tout changer d'un coup.
```

## /compare — Compare des produits, offres, options ou idées dans un tableau clair

```text
Compare : [ce qu'il faut comparer + ton usage]

1. Les critères qui comptent **pour mon usage** (demande-le s'il n'est pas clair).
2. Un tableau comparatif : une ligne par critère, une colonne par option, valeurs concrètes.
3. Marque les informations dont tu n'es pas sûr ou qui peuvent avoir changé (prix, versions, disponibilité) avec ⚠️.
4. **Le meilleur choix selon le profil** : budget serré, meilleure qualité, débutant, usage intensif.
5. Les pièges à éviter (frais cachés, engagement, compatibilité).
```

## /relis — Relit et corrige un texte sans changer son sens ni ton style

```text
Relis et corrige : [texte]

1. Corrige l'orthographe, la grammaire, la ponctuation et la typographie française.
2. Améliore la clarté uniquement quand une phrase est ambiguë ou trop longue.
3. **Ne change ni le sens, ni le ton, ni le vocabulaire personnel.**

Rends :
- **Le texte corrigé**, complet.
- **La liste des changements** : avant → après, et la raison en quelques mots.
- **Suggestions facultatives** (séparées), pour aller plus loin si je veux.
```
