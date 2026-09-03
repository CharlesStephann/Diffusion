# Projet de diffusion :

Ce projet a pour but d'implémenter un modèle de diffusion probabiliste (DDPM) appliqué à la génération d'images. 
Les trois objectifs majeurs du projets sont :
* l'implémentation d'un pipeline complet : Mettre en place la chaîne de traitement de
bout en bout, incluant le chargement optimisé des données (fichiers .npy), le processus de
bruitage (Forward Process) et l’échantillonnage inverse.
* l'optimisation architecturale : Adapter l’architecture U-Net classique (réduction de la
profondeur et du nombre de canaux) pour obtenir un modèle capable de converger sur CPU
en quelques heures.
* la validation de la génération : Démontrer la capacité du modèle à générer des sprites inédits
mais cohérents, prouvant ainsi que le réseau a appris la structure statistique des données
(forme, palette de couleurs) malgré la simplification du réseau.

Voici le contenu des différents fichiers du projet :
* [`projet_diffusion.ipynb`](`./projet_diffusion.ipynb`) : Code du projet, commentaires expliquant ce qui est réalisé à chaque étape.
* [`lien_datasets.txt`](`./lien_datasets.txt`) : Lien vers le jeu de données utilisé pour ce projet. 
* [`docs`](`docs`) : dossier contenant la documentation, notamment le le rapport du projet, son sujet et les slides du cours sur la diffusion.
* [`figures`](`figures`) : dossier contenant les images illustrant le projet : les sprites inédits générés par le modèle, les sprites fournis par le dataset sur lequel j'ai appliqué un bruit.
