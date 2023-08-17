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
Afficher le loader_top, commenter l.2 décommenter l.3.  
Afficher le loader_in, décommenter l.2 et commenter l.3.    
- keyframes en bas de page.    
- Loader responsive.   
  
**FAVORIT CHECKBOX**  
- Icon css responsive, fichier sass/default.scss l.174 - 245.  
- Ajustement pour home pages, fichier sass/home_pages.scss l.109 - 114.  
- Modification de la taille de l'icon, fichier sass/default.scss, modifier la varible $rule-width l.175.  
- Animation du background : fichier sass/default.  scss, animation par transition d'une box-shadow inset l.197 - 198, et transision par la checkbox et hover l.224 - 242 avec modification de la taille de box-shadow.  
  
**FAVORIT CHECKBOX**    
- Icon css responsive, fichier sass/default.scss l.148 - 170.
- Animation du background : fichier sass/default.  scss, animation par transition de scale, opacity et box-shadow l.162 - 168, transition activé par hover.  
  
**CARD MENU APPARITION**    
- Fichier sass/restos_pages.scss.  
- Initialisation de l'animation l.71 - 92 par boucle avec un multiplicateur sur l'indice de la classe afin de provoquer le décallage.  
- Animation l.180 - 189 par changement du scale et de l'opacité.  
  
**CARD MENU CHECKBOX**    
- Fichier sass/restos_pages.scss.  
- l.93 - 166, animation par transition de la width de .form__card__content et .form__card__content__label.  
- Activation de la transition par hover et check de la checkbox.     
  
## Nota Bene  

### comentaires SASS  

  
NB: Gérer l'apparence des puce liste ol dans index.html.

 






