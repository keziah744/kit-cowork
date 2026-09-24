# Kit atelier Claude Cowork

Le matériel de l'atelier : une skill à installer, des consignes prêtes à coller et des fichiers de démonstration.

**Tout récupérer :** bouton vert **Code** › **Download ZIP**, puis clic droit sur le fichier téléchargé › **Extraire tout**.

| Fichier | À quoi il sert |
|---|---|
| [`guide-cowork.pdf`](guide-cowork.pdf) | **Le mode d'emploi à imprimer** (3 pages) : utiliser Cowork, créer une skill, planifier une tâche, brancher Outlook, les bonnes règles, et quoi faire si ça ne marche pas. |
| [`creer-skill.zip`](creer-skill.zip) | La skill « créer une skill en parlant ». À importer dans Cowork (voir plus bas). |
| [`creer-skill/SKILL.md`](creer-skill/SKILL.md) | Le contenu de cette skill, à lire pour savoir ce qu'elle fait. |
| [`consigne-veille-hebdo.txt`](consigne-veille-hebdo.txt) | La consigne de la veille hebdomadaire, à coller dans une tâche planifiée. |
| [`stock-exemple.xlsx`](stock-exemple.xlsx) | Un faux export de stock (12 vins fictifs), si le vrai export n'est pas prêt. |
| [`demo-classement/`](demo-classement) | Le dossier test du classement des pièces : 6 pièces fictives dans « À classer », dont 2 pièges. |
| [`demo-classement-corrige.txt`](demo-classement-corrige.txt) | La phrase de départ à coller et le résultat attendu. |

## Installer la skill creer-skill

1. Dans Claude Desktop, onglet **Cowork** : **Customize** › **Skills** › **+**.
2. Choisir `creer-skill.zip`, puis vérifier que la skill est activée.

Lien direct du fichier : https://github.com/keziah744/kit-cowork/raw/main/creer-skill.zip

Sur un abonnement Team, l'administrateur doit d'abord autoriser les skills pour l'organisation.

## Lancer la skill

Le plus sûr : écrire « Utilise la skill creer-skill : je veux créer une skill qui… », ou taper `/` dans la zone de message et choisir creer-skill.

Sans le nom, Claude peut prendre sa méthode générale de création de skill, qui marche aussi mais qui est plus technique.

## Créer la veille hebdomadaire

1. **Scheduled** › **New task** › **Set up manually**.
2. Fréquence : chaque semaine, le lundi à 8 h. Ne choisir **aucun dossier** : la tâche tourne alors même quand le PC est éteint.
3. Coller la consigne de `consigne-veille-hebdo.txt`, enregistrer, puis la lancer une fois pour voir le résultat.

## Démo du classement des pièces

1. Dans Cowork, choisir le dossier **demo-classement** (pas le dossier du kit entier, sinon Claude verrait le corrigé).
2. Coller la phrase de départ de `demo-classement-corrige.txt`.
3. Comparer avec le résultat attendu. Pour recommencer, re-télécharger le kit.

*Tous les documents, sociétés et chiffres de démonstration sont fictifs.*
