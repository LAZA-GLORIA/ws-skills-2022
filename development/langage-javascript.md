# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ✔️ 
- les normes `ecmascript` ✔️ fonctions fléchées, callback, IIFE, ...
- l'utilisation de l'`asynchrone` ✔️ Je l'utilise tout le temps
    Récupérer la réponse future d'une action (ou promesse) dans un .then ou .catch si elle échoue et gérer les erreurs
    Récuperer une promesse avec async/await, avec await qui suspend l'exécution de la fonction jusqu'à ce que la promesse se réalise, on gère les erreurs avec un try catch
    On peut aussi gérer une fonction asynchrone avec une fonction callback
- les spécifités du mot-clef `this` ❌ Je ne l'utilise pas du tout mais il permet par exemple à une méthode d'accéder à un objet pour éviter de récuperer cet objet directement via la variable externe.

## 💻 Je code en Javascript

### Un exemple de code commenté ❌ / ✔️
Un fonction avec 2 paramètres qui renvoie un nombre aléatoire 
const pickRandom = (array, items) => {
   
   //array ['1', '2', '3', '4', '5', '6', '7', '8', '9', '10']
    //items = 8
    
    const clonedArray = [...array]; //clonedarray ['1', '2', '3', '4', '5', '6', '7', '8', '9', '10'] 
    const randomPicks = []; Je déclare une variable pour récuperer mon résultat

    for (let index = 0; index < items; index++) {
        const randomIndex = Math.floor(Math.random() * clonedArray.length); //Math.random pour trouver un nombre aleatoire entre 0 et 9 car clonedArray.length = 10
        
        randomPicks.push(clonedArray[randomIndex]);   //je push ma valeur dans randompicks
        clonedArray.splice(randomIndex, 1);
    }

    return randomPicks;
}

### Utilisation dans un projet ❌

[lien github](...)

Description :

### J'ai utilisé ce langage en production ❌

[lien du projet](...)

Description :

### J'ai utilisé ce langage en environement professionnel ❌

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

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

