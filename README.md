# Modèle de portfolio BTS SIO

Un portfolio prêt à publier pour l'épreuve E5 du BTS SIO, options SLAM et SISR : accueil, parcours, réalisations professionnelles, tableau de synthèse, veille technologique, projet professionnel et mentions légales. Du HTML et du CSS, sans framework ni installation.

- **Démo :** https://josselyncolombet.github.io/modele-portfolio-bts-sio/
- **Le cours qui va avec :** [construire son portfolio pour l'E5](https://reussirmonbtssio.com/cours/projet-e5/portfolio)

Le contenu d'exemple est le dossier de Camille, étudiante fictive en option SLAM, celle de l'oral blanc E5 du cours. Chaque page de réalisation suit le même plan : contexte, besoin, ton rôle, démarche, difficultés, résultat, compétences, preuves et bilan.

## Le publier

1. Clique sur **Use this template**, puis **Create a new repository**. Donne-lui un nom court, par exemple `portfolio`, et laisse-le **public** : GitHub Pages gratuit l'exige.
2. Dans ton nouveau dépôt : **Settings**, **Pages**, source **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
3. Au bout d'une minute, ton portfolio est en ligne à `https://ton-pseudo.github.io/portfolio/`. C'est cette adresse qui va dans ton tableau de synthèse.

Sans GitHub : **Code**, **Download ZIP**, puis publie le dossier chez l'hébergeur de ton choix.

## Le remplir

| Fichier | Ce que tu y changes |
|---|---|
| `index.html` | Ton nom, ton option, ta session, ton projet en trois lignes, tes liens |
| `parcours.html` | Tes stages ou ton alternance, ta formation |
| `realisations.html` et `realisations/` | Une page par réalisation : copie une page existante pour en ajouter une |
| `competences.html` | Ton tableau de synthèse, avec les mêmes intitulés que tes pages |
| `veille.html` | Ton sujet, tes sources, tes notes datées |
| `projet.html` | Ton projet, tes certifications, ton environnement d'apprentissage |
| `mentions-legales.html` | Ton nom et ton hébergeur |
| `documents/` | Tes preuves en PDF : chaque fichier d'exemple dit ce qu'il faut y mettre |

- Pour mettre ta photo à la place des initiales, suis le commentaire en haut de `index.html`.
- Pour changer la couleur, modifie `--accent` au début de `assets/style.css`.
- Les commentaires `<!-- -->` dans le code t'indiquent ce qu'il faut adapter.

Ne publie rien de confidentiel : anonymise les organisations et demande l'accord de ton tuteur avant de mettre un document en ligne. Le dépôt est public, donc vérifie aussi qu'aucun mot de passe ni aucune clé n'y traîne.

## Avant de déposer ton dossier

- Ouvre ton portfolio en navigation privée, sur un autre ordinateur et sur un téléphone en données mobiles.
- Clique chaque lien : pages, PDF, captures. Aucun ne doit demander de compte.
- Vérifie que chaque ligne du tableau de synthèse mène à la bonne page.
- Ne change plus l'adresse après le dépôt : c'est celle que la commission a dans ton tableau de synthèse.

## Licence

MIT : tu peux tout modifier. Si le modèle t'a servi, garde le lien « Modèle : Réussir mon BTS SIO » en pied de page : il aide d'autres étudiants à le trouver.
