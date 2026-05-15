# Guide Administrateur MalihaGroup

Ce guide vous explique comment gérer votre plateforme via le nouveau panneau d'administration.

## 1. Connexion à l'administration
L'interface d'administration est accessible à l'adresse : `votre-site.netlify.app/admin`

1.  Rendez-vous sur `/admin`.
2.  Connectez-vous avec vos identifiants Netlify Identity (configurés sur votre tableau de bord Netlify).
3.  Une fois connecté, vous accédez au tableau de bord Decap CMS.

## 2. Publier un Article de Blog
1.  Dans la barre latérale gauche, cliquez sur **Blog**.
2.  Cliquez sur **New Blog** (en haut à droite).
3.  Remplissez les champs : Titre, Date, Image de couverture, Description courte.
4.  Rédigez votre article dans l'éditeur Markdown (Corps de l'article).
5.  Cliquez sur **Publish** pour mettre en ligne.

## 3. Ajouter de la Musique (MP3)
1.  Cliquez sur **Musique** dans le menu.
2.  Cliquez sur **New Musique**.
3.  Entrez le titre et l'artiste.
4.  Téléchargez le fichier **MP3** via le champ "Fichier MP3".
5.  Ajoutez une image de pochette.
6.  **Publish**.

## 4. Gérer la Galerie (Photos/Vidéos)
1.  Cliquez sur **Galerie**.
2.  Choisissez le type (Photo ou Vidéo).
3.  Téléchargez votre fichier.
4.  Ajoutez une description.
5.  **Publish**.

## 5. Modifier la Page d'Accueil & SEO
1.  Allez dans **Paramètres du site**.
2.  Choisissez **Page d'accueil** pour modifier les textes du Hero (titre, sous-titre, bouton).
3.  Choisissez **SEO** pour modifier le titre de l'onglet, la description Google et les mots-clés.
4.  Enregistrez les modifications.

## 6. Workflow de Mise à Jour
Chaque fois que vous cliquez sur **Publish** dans l'admin :
1.  **Decap CMS** crée un commit automatique sur votre dépôt **GitHub**.
2.  **Netlify** détecte le changement et lance un **Rebuild**.
3.  Votre site est mis à jour automatiquement en quelques secondes.

---
*Note : Pour l'Assistant IA, assurez-vous d'avoir configuré vos clés API dans les variables d'environnement Netlify si vous souhaitez activer les réponses réelles.*
