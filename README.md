# Exercice Bootstrap 4 - Layout responsive avancé

Intégrez les maquettes en utilisant la grille Bootstrap.

### Trouver les maquettes

Le fichier se trouve:

- dans l'équipe de votre classe
- dans le projet _FD-03-Bootstrap_

Il se nomme _04 - Bootstrap - Layout responsive avancé_.

### Rendre les colonnes visibles

Afin de rendre les colonnes visibles, vous pouvez utiliser la CSS suivante:

```CSS
.row + .row {
  margin-top: 16px;
}

.row > .col,
.row > [class^=col-] {
  padding-top: 12px;
  padding-bottom: 12px;
  background-color: rgba(86, 61, 124, .15);
  border: 1px solid rgba(86, 61, 124, .2);
}
```

![](_consigne/maquette1@1x.png)
![](_consigne/maquette2@1x.png)
![](_consigne/maquette3@1x.png)
![](_consigne/maquette4@1x.png)
