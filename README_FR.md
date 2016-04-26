The tricky thing here is that a leap year in the Gregorian calendar occurs:

```plain
on every year that is evenly divisible by 4
  except every year that is evenly divisible by 100
    unless the year is also evenly divisible by 400
```

For example, 1997 is not a leap year, but 1996 is.  1900 is not a leap
year, but 2000 is.

If your language provides a method in the standard library that does
this look-up, pretend it doesn't exist and implement it yourself.

## Notes

For a delightful, four minute explanation of the whole leap year
phenomenon, go watch [this youtube video][video].

[video]: http://www.youtube.com/watch?v=xX96xng7sAE



Ce qui est délicat ici, c'est qu'une année bissextile dans le calendrier grégorien se produit:

`` `plain
pour chaque année qui est divisible par 4
   sauf les années qui sont divisibles par 100
     à moins que l'année ne soit aussi divisible par 400
`` `

Par exemple, 1997 n'est pas une année bissextile, mais 1996 l'est, 1900 est pas une année bissextile, mais 2000 l'est !

Si votre language fournit une méthode dans la bibliothèque standard qui fait ce calcul, ignorez le.

## Remarques

[Vidéo]: http://www.youtube.com/watch?v=xX96xng7sAE
