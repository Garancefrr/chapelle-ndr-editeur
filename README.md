# Chapelle Notre-Dame de Réconciliation — Éditeur Instagram

Éditeur visuel pour créer et exporter les publications Instagram de la
**Chapelle Notre-Dame de Réconciliation** (Lille). Tout fonctionne dans le
navigateur, sans installation et sans connexion internet.

🔗 **Site en ligne :** https://garancefrr.github.io/chapelle-ndr-editeur/

---

## Utilisation

1. Ouvrez le site (ou le fichier `index.html` par double-clic).
2. Choisissez un type de post dans les onglets du haut :
   - **Événement** — concerts, conférences, expositions
   - **Chantier** — avancée de la restauration
   - **Programme** — le programme du mois
   - **Anecdote** — récits historiques de la chapelle
   - **⚙ Réglages** — couleurs de la charte (appliquées à tous les visuels)
3. Pour chaque type, **3 designs** sont disponibles (boutons Design A / B / C).
4. Modifiez les textes, dates et photos dans le panneau de gauche ;
   la prévisualisation se met à jour en direct.
5. Cliquez sur **↓ Télécharger PNG** pour obtenir le visuel prêt à publier
   (1080×1080 px, ou 1080×1350 px pour le Programme).

Votre travail est sauvegardé automatiquement dans le navigateur.

---

## Fonctions utiles

- **Photos** : importez une image, puis **glissez-la** sur la prévisualisation
  pour la recadrer et utilisez la **molette** pour zoomer. Boutons *Recentrer*
  (photo entière) et *Adapter* (remplit le cadre).
- **Programme** : glissez la poignée **⋮⋮** pour réordonner les événements.
  Au-delà de 5 événements, le Design A se découpe en plusieurs **planches**
  (un PNG par planche) à publier en **carrousel** Instagram.
- **Couleurs** : l'onglet *Réglages* permet de changer la palette de marque ;
  le changement s'applique partout en direct.

---

## Mettre le site à jour

Le site est un **fichier unique** `index.html` — tout (code, polices, images)
est intégré dedans, aucune dépendance externe.

Pour publier une nouvelle version :

1. Remplacez le fichier `index.html` dans ce dépôt
   (**Add file → Upload files**, puis **Commit changes**).
2. GitHub Pages se met à jour automatiquement en ~1 minute.

---

## Hébergement (GitHub Pages)

Déjà configuré, mais pour mémoire :

1. **Settings → Pages**
2. **Source** : `Deploy from a branch`
3. **Branch** : `main` · dossier `/ (root)` → **Save**

Le fichier `.nojekyll` (vide) à la racine évite que GitHub modifie le HTML.

---

*Association des Amis de la Chapelle Notre-Dame de Réconciliation
— 28 rue de Canteleu, 59000 Lille*
