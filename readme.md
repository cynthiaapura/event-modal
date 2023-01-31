# Création d'une fenêtre modale en HTML et CSS

[Lien vers la page](https://cynthiaapura.github.io/event-modal/)


Exemple de CSS pour la mise en page pour l'ouverture d'une fenêtre modale
```css
.modal-parent{
    position: fixed;
    top: 0;
    left: 0;
    height: 100vh;
    width: 100vw;
    background-color: rgb(111, 8, 8, 0.3); 
    z-index: -1;
    backdrop-filter: blur(.3rem); /* blur est l'arrière plan */
    opacity: 0;
    transition: all .6s ease-in-out;
}
.appear-modal:target{
    opacity: 1;
    z-index: 1;
}```