# OhMyFood  
---     
_Projet n°3 de la formation Développeur d'application JavaScript React d'Open Classrooms_  
_Etudiant auteur Christelle Barret, Crazy Beasty_  
---  
## Notice
    
### HTML  
**Input de recherche position** : fichier **index.html, div class : home-form**. Disabled activé sur l'input. Modifier didabled par enable dans l'input pour le rendre actif.
  
### ANIMATIONS 
   
**LOADER**  
- Changer le loader de position (top or in page) :   
Fichier sass/loader.scss  
Afficher le loader_top, commenter l.3 décommenter l.4.  
Afficher le loader_in, décommenter l.3 et commenter l.4.    
- keyframes en bas de page.    
- Loader responsive.   
  
**FAVORIT CHECKBOX**  
- Icon css responsive, fichier sass/default.scss l.174 - 257.  
- Ajustement de position pour home pages, fichier sass/home_pages.scss l.110 - 116.  
- Modification de la taille de l'icon, fichier sass/default.scss, modifier la variable $rule-width l.178.  
- Animation du background : fichier sass/default.scss, animation par transition d'une box-shadow inset l.198 - 199, et transision par la checkbox et hover l.229 - 256 avec modification de la taille de box-shadow.  
- :hover, fichier sass/default.scss l.244 - l.256 est dans une média querie pour déboguer l'activation de la checkbox en version mobile et tablette pour les bases chromnium. 
  
**CALL TO ACTION**    
- Icon css responsive, fichier sass/default.scss l.149 - 172.
- Animation du background : fichier sass/default.  scss, animation par transition de scale, opacity et box-shadow l.162 - 170, transition activé par hover.  
  
**APPARITION DES PLATS DANS LE MENU**    
- Fichier sass/restos_pages.scss.  
- Initialisation de l'animation l.72 - 93 par boucle avec un multiplicateur sur l'indice de la classe afin de provoquer le décallage.  
- Animation l.181 - 190 par changement du scale et de l'opacité.  
  
**ANIMATION DES CHECKBOX DE CHAQUE PLATS DANS LE MENU**    
- Fichier sass/restos_pages.scss.  
- l.94 - 166, animation par transition de la width de .form__card__content et .form__card__content__label.  
- Activation de la transition par hover et check de la checkbox.
- :hover, fichier sass/restos_pages.scss l.154 - l.161 est dans une média querie pour déboguer l'activation de la checkbox en version mobile et tablette pour les bases chromnium.     
  
## Nota Bene  

 



 






