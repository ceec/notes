# notes

#fonts

Using a True Type Fonts .ttf in CSS:

https://stackoverflow.com/questions/4267415/using-true-type-fonts-in-web-applications


HTML5 allows to use TTF fonts in your CSS:
```
@font-face {
  font-family: 'Tagesschrift';
  src: url('tagesschrift.ttf');
}
```
To use it:
```
h1, h2, h3 { font-family: 'Tagesschrift', 'Georgia', serif; }
```
