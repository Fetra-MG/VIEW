# Rambeso — structure du site

## Arborescence

```
index.html                 Page d'accueil (CSS et JS inclus dans le fichier)
produit/index.html          Page hub du catalogue (message "bientot disponible")
produit/template.html       Gabarit a dupliquer pour chaque nouveau produit
images/logo-rambeso.webp    Logo (a placer ici, deja reference par le code)
images/preview.avif         Image d'arriere-plan (a placer ici, deja referencee)
```

Chaque page HTML est autonome : le style et les scripts sont integres
directement dans le fichier, donc un simple double-clic sur index.html
(une fois le dossier images/ en place a cote) suffit pour previsualiser
le site dans un navigateur.

## Ajouter un nouveau produit plus tard

1. Copier `produit/template.html`.
2. Le renommer avec le nom du produit, par exemple `produit/sac-a-dos-urbain.html`.
   Ce nom devient l'adresse propre du produit.
3. Remplir les zones marquees `[A REMPLIR]` dans le fichier copie.
4. Ajouter une carte vers cette page depuis `produit/index.html` quand le produit est pret a etre publie.

Chaque produit garde ainsi sa propre page et son propre lien, sans jamais modifier l'architecture existante.

## Police

Le logo utilise Momo Trust Display (Google Fonts) pour les titres et le nom
de la marque. Outfit est utilise pour le texte courant. Les deux sont
charges depuis Google Fonts dans chaque page.
