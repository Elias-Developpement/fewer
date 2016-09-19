## Les formulaires

Nous allons dès à présent voir comment créer des formulaires en utilisant les composants de Fewer.
Vous pouvez utiliser ces composants en utilisant le préfixe `form-`

Ainsi, vous pouvez créer un formulaire de connexion facilement :
```html
<form>
  <div class="form-champ">
    <label class="form-label">Pseudo : </label>
    <input type="text" class="form-input" placeholder="Pseudo">
  </div>
  
  <div class="form-champ">
    <label class="form-label">Pseudo : </label>
    <input type="password" class="form-input" placeholder="Mot de passe">
  </div>
  
  <div class="form-champ">
    <input type="submit" class="button-bluesky" value="Se connecter">
  </div>
</form>
```

Comme vous pouvez le voir, Fewer est très simple d'utilisation. N'hésitez pas à lire l'annexe où vous retrouverez 
toutes les classes du Framework.
