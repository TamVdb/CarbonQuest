# Carbon Quest 🤖

Carbon Quest est un jeu éducatif de plates-formes qui vous invite à explorer les enjeux du Green IT, l’ensemble des pratiques visant à réduire l’impact environnemental des technologies numériques, de leur conception à leur utilisation.

🎯 But du jeu<br />
Votre mission est de grimper jusqu’au sommet de la canopée, tout en répondant correctement à un maximum de questions.

👾 Comment jouer ?<br />
* Utilisez les touches directionnelles et la barre d'espace pour vous déplacer vers le haut de la forêt.
* Rapprochez-vous des esprits de la forêt pour qu'ils vous posent leurs questions.
* Une fois au sommet, vous pourrez consulter vos réponses, voir vos erreurs, et en apprendre davantage sur le Green IT.

💪 Parviendrez-vous à répondre correctement à toutes les questions ?

&nbsp;
## 🌐 Backend et Base de Données

Afin de pouvoir mettre le projet en ligne plus facilement, nous avons développé un backend en Node.js et utilisé une base de données MongoDB.

💻 **Backend initial** : PHP avec une base de données MySQL (administrée via PHPMyAdmin).  
🌍 **Backend actuel** : Node.js avec une base de données MongoDB.  

⚡ _C'est cette version qui est présentée ici et disponible en ligne._

&nbsp;
## 👾 Tester le jeu en ligne
👩‍💻 Enregistrer un nouvel utilisateur <br />
🔓 Se connecter <br />
🎮 Jouer <br />
🤗 Enjoy 

&nbsp;
## 👀 Visuels

![Imgur](https://tinyurl.com/3wzukf3v)
![Imgur](https://tinyurl.com/2s4zdmec)
![Imgur](https://tinyurl.com/33zydzff)
![Imgur](https://tinyurl.com/yk5ppby2)
![Imgur](https://tinyurl.com/2p8na978)


&nbsp;
## ⚙️ Installation
### Backend
Installer les dépendances
```
npm i
```

Créer une base de données `carbonquest` avec MongoDB et une collection `users`

Créer un fichier .env avec les variables suivantes
```
MONGODB_CONNECTION_STRING=MONGODB_CONNECTION_STRING="mongodb://localhost/carbonquest"
API_URL="http://localhost:5173"
``` 

Lancer le serveur
```
npm run dev
```

### Frontend
Installer les dépendances
```
npm i
```

Créer un fichier .env avec la variable suivante
```
VITE_API_URL="http://localhost:3001/"
``` 

Lancer le serveur
```
npm run dev
```

### Tester le jeu
👩‍💻 Enregistrer un nouvel utilisateur <br />
🔓 Se connecter <br />
🎮 Jouer

&nbsp;
## 🔗 Dépendances
### Backend
* Node.js (22.13.0)
* npm
* Express (4.21.2)
* MongoDB (6.12.0)
* Mongoose (8.9.2)
* Nodemon (3.1.9)
* Dotenv (16.4.7)
* Cors (2.8.5)

### Frontend
* Node.js (22.13.0)
* npm
* Vite (5.4.9)
* React (18.3.1)
* Tailwind (3.4.14)
* Axios (1.7.7)
* React Icons (5.4.0)
* React Router Dom (6.27.0)
* React Unity Webgl (9.6.0)
* Zod (3.23.8)
* React Hook Form (7.53.1)


