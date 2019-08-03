# Geronimo

Application iOS qui a pour but de charger des modèles 3D et de les afficher.



# Fonctionnement

L'utilisation de cette application nécessite l'accés à l'appareil photo afin d'utiliser la réalité augmentée.

1. Une fois l'application lancée, veuillez scannez la pièce afin que celle-ci analyse votre entourage et génère des surfaces planes (rectangle bleu).
2. Une fois des réctangles bleu présent sur l'écran, vous pouvez appuyer afin de positionner le portail à une distance raisonnable.
3. Une fois le portail positionné, appuyez sur le bouton "Deactivate AR Move" puis laissez votre curiosité faire le reste.



# Utilisation

- Effectuer un pincement (pinch) afin de modifier le scale de l'objet présent sur la scène.
- Effectuer un swipe afin de tourner l'objet présent sur la scène.

- Le bouton "Materials" en haut à gauche vous permet d'ouvrir le menu material :
  - Appuyez sur les différentes couleurs de ce menu afin de modifier la couleur de l'objet présent sur la scène.
  

- Le bouton "Deactivate AR Move" / "Activate AR Move" en haut de l'écran permert d'activer/désactiver le repositionnement du portail entier, nécessaire afin d'utiliser les autres fonctionnalités sans bouger l'ensemble.


- Le bouton "Models" en haut à droite de l'écran permet d'ouvrir le menu des models :
  - Appuyez sur le model souhaité afin de le charger sur la scène.
  - Le lien en bas permet d'ajouter un objet 3D à la liste; un accès direct au fichier est nécessaire (exemple: serveur FTP) (cette fonctionnalité ne fonctionne que sur l'éditeur Unity).
  
# Details
  
Les scènes utilisés sont celles-ci:
- Assets/UnityARKitPlugin/Examples/UnityARKitScene/UnityARKitScene.unity (pour la scène avec AR)
- Assets/Scenes/scene_main (pour la scène sans AR)
