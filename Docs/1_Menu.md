## Créer un menu

Fewer est un framework relativement flexible. Il peut vous permettre de créer des menus qui s'adapte à la taille de la fenêtre. 
Vous aurez donc un menu différent si vous êtes sur tablette, encore différent si vous êtes sur smartphone.

Pour créer un menu, rien de plus simple. Il suffit de désigner les éléments avec le préfixe `nav-`
```html
<nav class="bg-dark">
  <ul class="nav">
    <li class="nav-li">
      <a class="nav-a" href="#">Accueil</a>
    </li>
    
    <li class="nav-li">
      <a class="nav-a" href="#">Vidéos</a>
    </li>
    
    <li class="nav-li">
      <a class="nav-a" href="#">Tutoriels</a>
    </li>
  </ul>
</nav>
```

Comme vous pouvez le voir, c'est vraiment très simple de créer un menu. Un menu est facilement personnalisable. Si vous voulez
que le menu reste au-dessus de l'écran même lorsque l'on scroll la page, c'est possible :
```html
<nav class="bg-dark fixed">
```

Vous n'avez rien de plus à faire. Pratique non ? Vous verrez que vous pourrez facilement modifier des éléments de cette manière.
