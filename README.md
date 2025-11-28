# Contexte

 

C'est votre premier jour au sein du laboratoire d'intelligence artificielle de ModeTrends, l'une des agences de conseil en marketing digital les plus influentes dans l'industrie de la mode. Fondée il y a 15 ans, ModeTrends collabore avec des marques de luxe et des distributeurs de fast fashion dans plus de 30 pays.

 

Face à l'explosion du marketing d'influence, ModeTrends a lancé un projet ambitieux : "Fashion Trend Intelligence". Ce projet vise à développer un système automatisé d'analyse des tendances vestimentaires sur les réseaux sociaux. Son objectif est d'offrir aux marques clientes des informations précises et en temps réel sur les nouvelles modes émergentes, bien avant qu'elles ne deviennent populaires.

 

Pour démarrer ce projet, votre responsable Sophia a présenté cette mission à l'équipe IA lors d'une réunion d'information. Elle a exposé le contexte général, les objectifs et les spécificités techniques de la fonctionnalité de "segmentation de vêtements" que vous allez développer.

 

Vous recevez un mail récapitulatif que Sophia vous a écrit suite à la réunion de présentation :

***

De : Sophia Le Guennec
Envoyé : Hier 16:38
À : Moi
Objet : Récap mission "Fashion Trend Intelligence"
Bonjour,

 

Merci pour ton attention lors de la présentation du projet "Fashion Trend Intelligence". Je voulais, dans ce mail, te faire un récap de ta mission. Comme tu l'as compris, l'objectif global est de concevoir, développer et déployer un système d'analyse qui aura les fonctionnalités suivantes :

- Segmentation vestimentaire : être capable d'identifier et d'isoler avec précision chaque pièce vestimentaire dans une image.

- Analyse stylistique : être capable de classifier les pièces selon leur nature, couleur, texture et style.

- Agrégation de tendances : être capable de compiler ces données sur des milliers de publications pour identifier les tendances émergentes.

Comme tu peux le voir, ce projet est ambitieux et présente plusieurs challenges! Mais ne t'inquiète pas, ton rôle sera de travailler sur la première fonctionnalité, la Segmentation vestimentaire.

 

En ce qui concerne cette fonctionnalité de segmentation, la première étape est d'utiliser un modèle pré-entraîné capable d'identifier les différentes pièces vestimentaires dans une photo comme sur l'illustration ci-dessous. 


![Alt text](https://user.oc-static.com/upload/2025/03/17/17422264494376_Capture%20d%E2%80%99e%CC%81cran%202025-03-17%20a%CC%80%2016.47.04.png)

Pour y arriver, peux-tu évaluer si on peut utiliser les endpoints serverless de Hugging Face et particulièrement le modèle SegFormer-clothes, modèle affiné sur la segmentation vestimentaire ?


Ta première tâche sera donc de tester si le modèle Segformer clothes de Hugging Face peut correctement segmenter les vêtements à partir de quelques images que nous avons annotées (cf les données de test en pièce jointe). Ce n’est pas la panacée, mais ça sera suffisant pour un premier test. Vérifie que lorsque tu envoies une image au service Hugging Face, il te renvoie bien la segmentation correcte des différentes pièces vestimentaires.


Voici le notebook créé par le précédent Data Scientist, peux-tu le reprendre et changer ta clé API et faire tourner le modèle ? 


Ta seconde tâche sera de nous faire un chiffrage approximatif du coût d’utilisation de cette solution avec l’API de Hugging Face. Pourrais-tu évaluer le coût pour 500 000 images sur 30 jours par exemple ?


Tu trouveras un template de présentation en pièce jointe pour présenter les résultats de ton projet à l’équipe ainsi que les données de test.

N’oublie pas de mettre en avant ta capacité à être synthétique et à simplifier ton discours technique si nécessaire. 

 

Bon courage!

 

Sophia 

Directrice IA - ModeTrends

***