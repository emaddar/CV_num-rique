
# Emad DARWICH CV digital
Un site Web de CV numérique construit sur la base du contenu de mon CV personnel

Voir la démo en direct ici en utilisant les github pages : [Demo](https://emaddar.github.io/CV_num-rique/)

Ce CV est inspiré de l'[article](https://dev.to/dennisivy11/build-a-digital-resume-host-for-free-559) de Dennis Ivy.

___
## Aperçu du Dark Mode
![dark](./assets/images/dark%20mode%20preview.png)
___
## Aperçu du Light Mode
![dark](./assets/images/light%20mode%20preview.png)
___

## Basculer entre les thèmes de couleurs
Pour basculer entre Dark Mode et Ligth Mode, il faut simplement changer les variables suivantes dans le fichier `main.css` :

### Light Mode :
```css
    --mainTextColor:var(--mainTextColor-light);
    --secondaryTextColor:var(--secondaryTextColor-light);
    --mainLinkColor:var(--mainLinkColor-light);
    --mainBorderColor:var(--mainBorderColor-light);
    --mainBgColor:var(--mainBgColor-light);
    --programTextColor:var(--programTextColor-light);
    --programeBgColor:var(--programeBgColor-light);
    --programeBgColor1:var(--programeBgColor1-light);
```

### Dark Mode :
```css
    --mainTextColor:var(--mainTextColor-dark);
    --secondaryTextColor:var(--secondaryTextColor-dark);
    --mainLinkColor:var(--mainLinkColor-dark);
    --mainBorderColor:var(--mainBorderColor-dark);
    --mainBgColor:var(--mainBgColor-dark);
    --programTextColor:var(--programTextColor-dark);
    --programeBgColor:var(--programeBgColor-dark);
    --programeBgColor1:var(--programeBgColor1-dark);
```