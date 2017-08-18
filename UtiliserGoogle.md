# Chercher et trouver sur Google

Voici quelques trucs pour trouver ce dont tu as besoin sur Google:

## Fais simple
Google est très malin. N'utilise que les mots-clef (les mots moins de 3 lettres ne sont pas pris en compte sauf si tu … )

## Cherche en anglais !

## Utilise les guillemets
Quand j'ai un message d'erreur, la première chose que je fais, c'est d'essayer de le comprendre. Mais souvent, je ne sais pas, ou plus, ce que cela veut dire. Alors je la jette dans google, avec des guillemets autour ce qui signifie: "retourne moi les pages qui contiennent EXACTEMENT cette phrase".
par exemple:

```
"Warning: Cannot modify header information - headers already sent by (output started at /path/to/geeklog/public_html/config.php:581) in /path/to/geeklog/public_html/system/lib-sessions.php on line 180"
```

Dans google, je garde la partie non-spécifique à mon code et la mets dans des guillemets : 

```"Cannot modify header information – headers already sent by"```

## Chercher sur un site en particulier
Précède ta recherche par `site :` suivi du nom de domaine. Donc dans le cas précédent, si on veut se restreindre à stackoverflow.com

```
site:stackoverflow.com "Warning: Cannot modify header information - headers already sent by"
```

## Tu veux savoir qui fait un lien vers ton site ?

```
link:tonsite.be
```

## Des sites similaires ?

```
related:pixeline.be
```

## Utilise les opérateurs OR et AND
```
chocolate OR white chocolate
```

## Commence par le mot-clef décrivant la techno afin de limiter les résultats au langage dans lequel tu te trouves

par exemple : 
```
php array push
javascript array push
```

## Une nouvelle techno à apprendre ? Cherche un tutoriel, c'est le plus efficace pour apprendre rapidement le pourquoi, le comment
Notamment, ce qu'il faut installer au départ, à quoi cela sert, etc…
Par ex : 
```
gulp tutorial
php upload tutorial
```

## Rajoute des mots-clef progressivement pour affiner

Par ex: 
```
php array
php array push
php array splice
```

## Pense "langage pro"
Essaye d'utiliser la terminologie d'un site professionnel, donc rédigé avec un niveau de langage professionnel. Pense SEO.

`trouver un taf de dev à bruxelles` —> `web developer job offers Brussels`

## Choisis tes sources et reste-y
Par exemple, la doc officielle de mysql est POURRIE, mais la doc de PHP est super bien fichue. Ainsi, que celle de jQuery. stackoverflow.com est une source très bien pour des problèmes spécifiques.

Par ex :
```
site:stackoverflow.com "array push at specific index"
```

## L'astérisque
astérisque = une "wildcard" = "n'importe quoi à cet endroit".
Très utile pour chercher les paroles d'une chanson.
```
Come * right now * me
```

![Giphy](https://media1.giphy.com/media/vxRJWOAghqjXG/giphy.gif)

Voilà, c'est plus que suffisant pour maîtriser Google. Si tu veux, tu peux aller encore plus loin via ces deux sources :
- [Lifehack: 20 tips to use google search efficiently](http://www.lifehack.org/articles/technology/20-tips-use-google-search-efficiently.html)
- [Google Help: Search](https://support.google.com/websearch/answer/134479?hl=en)  
- [Google Help: Search operators](https://support.google.com/websearch/answer/2466433)  
