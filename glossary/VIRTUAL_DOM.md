# Virtual DOM

<<<<<<< HEAD
Virtual DOM section à compléter.

Virtual DOM est une technique et un set de bibliothèques, d'algorithmes nous permettant d'augmenter les performances front end en évitant de travailler directement sur le DOM (Document Object Model), mais sur un objet JavaScript légé qui qui imite l'arbre du DOM.
La technologie a été difficile à implémenter, mais ytiliser ces bibliothèques semble relativement simple et améliore les performances des applications.

## Diverses Bibliothèques et Frameworks
* ReactJS - développé par Facebook
* virtual-dom - par Matt Esch
* Mithril - un framework JavaScript pour générer des applications
* Bobril - framework orienté composant inspiré par Mithril et ReactJS 
* cito.js - framework 
=======
The Virtual DOM is a concept closely associated with React that holds a lightweight, abstracted copy of the [DOM](DOM.md) in memory and doesn't (re)render the elements until the precise moment they are needed. This tremendously helps with page speed, as instead of making the browser render all the components at once, it only needs to do so on the ones that are required at the time, making the usually intensive operations in the virtual DOM first.

When an element in the DOM needs updated, the virtual DOM copy of it is modified first, then it's sent to be rendered in the actual DOM. In React, many smaller read/write operations like this are often batched together.
>>>>>>> 7642a671efd84fb3eb39919482eda60b6a15e355
