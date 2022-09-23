# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- Comment développer en utilisant un système de *livereloading* (`nodemon` par exemple) ✔️ 
        installer le paquet npm i nodemon et aller modifier le script dans package.json "start": "nodemon src/index.js" et npm start pour éxecuter l'appli
- La connexion de mon application à une base de données avec et sans ORM/ODM (avec `mongodb` puis `mongoose` par exemple) ✔️
       SGBDR mysql , SQLite  ORM: TypeOrm
- Le développement d'une API REST et GraphQL (avec les packages `express` et `graphql` par exemple) ✔️
        Développer un API REST avec express:  câbler les routes entre les méthodes de requêtes http et les méthodes des contrôleurs, persister les données avec les différentes opérations (create, read, update, delete,...) et communiquer avec la bdd via les rêquetes sql ou via un orm. 
- *Bonus : la manipulation des fichiers système avec `fs` et l'utilisation des streams en NodeJS* ❌

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️
Une méthode editInfos dans un controleur qui permet de modifier les informations d'un utilisateur 

static editInfos = async (req, res) => {
    const { phoneNumber, email } = req.body;
    const id = parseInt(req.params.id, 10);

    models.user
      .updateInfos({ id, phoneNumber, email, city })
      .then(([result]) => {
        if (result.affectedRows === 0) {
          res.sendStatus(404);
        } else {
          res.sendStatus(204);
        }
      })
      .catch((err) => {
        console.error(err);
        res.sendStatus(500);
      });
  };
### Utilisation dans un projet ❌ 

[lien github](...)

Description :

### Utilisation en production si applicable❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description : Google, youtube, ...

## 🚧 Je franchis les obstacles

### Point de blocage ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ 
- J'ai fait une [présentation](...) ❌
