# Consignes de travail sur ce dépôt

Site de l'association Cross Borders (loi 1901), publié sur https://www.crossborders.ngo
(GitHub Pages, branche `main`, domaine déclaré dans `CNAME`).

**À lire aussi avant toute tâche : `JOURNAL.md`** (décisions déjà prises, travail en cours).
À la fin de chaque tâche, ajouter en tête de `JOURNAL.md` une entrée datée de 3 à 6 lignes.

## Comment répondre au président

- En français simple, ton professionnel, réponses courtes.
- Proposer les modifications importantes avant de les appliquer ; les petites corrections se font directement.
- Donner un avis honnête, sans flatterie.
- Tout doit rester gratuit : hébergement GitHub Pages, aucun service ni outil payant.

## Publier

1. `git fetch origin main` et repartir de la version en ligne : une autre conversation peut travailler en même temps. Ne jamais forcer une publication.
2. Site statique écrit à la main, sans générateur : `index.html` (page principale), `galerie/` (musée en 3D), `constellations/` (mots de la rencontre), `mentions-legales.html`.
3. Vérifier les pages modifiées à 390 px et 1280 px, ainsi que les liens et les vidéos.
4. Commit au nom du président : `git -c user.name="Hafid Boutchakkoucht" -c user.email="hafidboutchakkoucht@users.noreply.github.com" commit`. Le message ne contient aucune mention d'outil ou d'assistant, ni co-auteur, ni lien de session.
5. `git push origin main`.

## Où se trouve quoi

| Quoi | Où |
| --- | --- |
| Logos et emblème | `brand/` |
| Photos des activités (nommées lieu-année ou lieu-sujet) | `img/` |
| Vidéos des activités, témoignages, épisodes « Erasmus+ décrypté » | `videos/` |
| Musée virtuel en 3D | `galerie/` |
| Constellations des mots (12 langues) | `constellations/` |

## Contenu

- Siège affiché : Miremont (Haute-Garonne). Coordonnées publiées : courriel et téléphone du président uniquement.
- Ne publier aucune coordonnée d'autres personnes sans leur accord. Photos : uniquement avec l'accord des personnes visibles.
- Le communiqué du président change le 1er de chaque mois : il est préparé, puis publié seulement après validation du président.
- La médiathèque (photos en cascade, vidéos, témoignages) s'enrichit au fil des activités : année, lieu et intitulé du projet pour chaque photo.
- Garder la mention de cofinancement de l'Union européenne et l'avertissement Erasmus+ en pied de page.
- Aucune mention d'un outil ou d'un assistant d'intelligence artificielle sur le site ni dans l'historique.

## Style

Site d'association européenne : vivant mais professionnel, lisible par des jeunes, des familles, des collectivités et des financeurs.
Éviter les tics de gabarit : sections numérotées « 01 / 02 … », mots en italique coloré dans chaque titre, rangées de cases identiques.
