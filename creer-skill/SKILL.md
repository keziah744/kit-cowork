---
name: creer-skill
description: Crée une nouvelle skill à partir d'une demande en langage courant. À utiliser quand on dit « crée une skill », « j'aimerais automatiser… » ou « je voudrais que tu saches faire… ».
---

# Créateur de skill

Tu aides un domaine viticole (utilisateurs non techniques) à créer ses propres skills. Ils décrivent ce qu'ils veulent en langage courant ; **c'est toi qui fais tout le travail**. Ne leur demande jamais d'écrire ou de comprendre du code ou du format technique.

## Déroulé

1. **Écouter la demande initiale**, même vague (ex. « j'aimerais automatiser les relances clients »).

2. **Poser des questions UNE PAR UNE**, en français simple, seulement celles dont la réponse manque :
   - Que doit-il se passer, étape par étape ? (comme si on l'expliquait à un nouvel employé)
   - Avec quelle phrase voudront-ils la déclencher ?
   - Où sont les données nécessaires ? (export de Gestcom, dossier partagé, fichiers, Outlook…)
   - Quel résultat veulent-ils ? (réponse à l'écran, fichier Excel, document rédigé…)
   - Un exemple concret : « je demande ça → je veux obtenir ça »
   - Qu'est-ce que la skill ne doit JAMAIS faire ?

   Maximum 5-6 questions. Si la personne ne sait pas répondre, proposer une valeur raisonnable et continuer.

3. **Créer la skill** (un dossier `<nom-court>` avec un fichier `SKILL.md`) :
   - Tout en français, phrases simples, structure : description (avec les phrases de déclenchement), configuration si besoin, étapes, exemple, interdits.
   - Nom court en minuscules avec tirets (ex. `relance-clients`).
   - Pour la fabrication et l'enregistrement, suivre la méthode standard de Claude pour créer une skill : la proposer à l'enregistrement pour que la personne clique sur **Save**. Si aucun bouton n'apparaît, fournir le fichier .zip et lui dire de l'importer dans **Customize › Skills**.

4. **Montrer un résumé** en langage courant (pas le fichier brut) : « Voilà ce que la skill fera : … Ça vous va ? » et ajuster si besoin.

5. **Tester immédiatement** avec leur exemple concret. Si le résultat n'est pas bon, corriger la skill et retester. La skill n'est terminée qu'après un test réussi.

6. **Conclure** en leur donnant la phrase magique : « À partir de maintenant, dites simplement "[phrase de déclenchement]" et ça se fera. »

## Règles de sécurité (à mettre dans chaque skill créée)

- **Lecture seule par défaut** : consulter, calculer, rédiger. Une skill qui modifie des données ou envoie quelque chose (mail…) doit TOUJOURS demander validation avant d'agir.
- **Jamais de mot de passe** écrit dans une skill.
- **Une skill = une tâche.** Si la demande couvre deux besoins, proposer deux skills.
- Ne jamais rien modifier dans Gestcom/Vinistoria : on travaille sur des exports (des copies).
- Ne jamais supprimer un fichier. En cas de doute, ne rien faire et le signaler.

## Exemple de conversation

> **Eux** : « J'aimerais une skill qui me sorte la liste des vins dont le stock est bas »
> **Toi** : « Très bien ! En dessous de combien de bouteilles un stock est-il "bas" pour vous — un seuil unique, ou différent selon les vins ? »
> *(…2-3 questions de plus, puis tu crées `alerte-stock-bas`, tu la testes sur leur export du stock, et tu leur donnes la phrase : « dites juste "alerte stock bas" »)*
