---
title: "Client"
date: 2022-10-24T16:06:18+01:00
draft: false
weight: 1
---

Chaque fois que vous passez d'une page à l'autre, en fonction des paramètres que vous avez donnés ou des informations contenues dans la base de données, PHP peut construire une version différente de la même page. Vous voulez que la page elle-même réponde aux événements que vous effectuez pendant que vous y êtes, pour qu'elle se comporte comme un programme à usage général. C'est JavaScript, tous les navigateurs le comprennent. Avec Javascript, vous pouvez gérer tous les événements et faire en sorte que votre page Web agisse de manière dynamique.

Il vous permet de manipuler directement des éléments HTML et de modifier leur état, leur forme, leur couleur, leur position et diverses propriétés. Le code Javascript est intégré dans HTML. Bien sûr, si vous avez généré votre page avec PHP, cela vous permet à son tour de générer du code JavaScript, ce que le navigateur comprend avec HTML. Au final, à l'exécution, l'utilisateur n'interagit directement qu'avec le code écrit en JavaScript.

Avec ces 3 outils, nous pouvons créer un site Web vraiment puissant. Bon disons simplement qu'il faut du temps pour comprendre "l'ordre d'exécution" d'une page web. Si vous remarquez, la communication avec le serveur de base de données... est en PHP. Il est exécuté sur le serveur qui contient la base de données et uniquement via du code PHP, et tout cela est fait avant le chargement de la page dans votre navigateur.

En d'autres termes, JavaScript est aussi agréable et dynamique que vous le souhaitez, mais il ne peut pas communiquer avec la base de données. Si je demande à mon site Web certaines données de ma base de données, en utilisant JavaScript, il ne peut pas me les donner. De cette façon, je ne peux pas mettre à jour dynamiquement mes éléments Web, du moins via la base de données. Une option serait d'appeler une nouvelle page, selon ces paramètres, et tout le processus serait refait, en commençant par créer la nouvelle page avec PHP en fonction de la requête.

Chaque fois que je demande quelque chose à la base de données, Javascript appelle une nouvelle page qui fait le travail en utilisant PHP.