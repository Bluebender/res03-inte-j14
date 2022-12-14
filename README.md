# res03-inte-j14
## Background-theme
```css
body{
  @media (prefers-color-scheme: light){
    background-color: $white;
  }
  @media (prefers-color-scheme: dark){
    background-color: $black;
  }
}
```
## Bouttons
### Bouton bleu
```css
.btn-blue{
    display: inline-block;
    cursor: pointer;
    border-radius: 20px;
    border: none;
    text-decoration: none;
    color: white;
    text-align: center;
    font-size: 1.2rem;
    padding: 10px 20px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
    @media (prefers-color-scheme: light){
      background-color: $lightThemeBlue;
    }
    @media (prefers-color-scheme: dark){
      background-color: $darkThemeBlue;
    }
    &:hover{
        transform: translateY(-2px);
        box-shadow: 2px 4px 10px rgba(0, 0, 0, 0.5);
    }
}
```
### Bouton rouge
```css
.btn-red{
    display: inline-block;
    cursor: pointer;
    border-radius: 20px;
    border: none;
    text-decoration: none;
    color: white;
    text-align: center;
    font-size: 1.2rem;
    padding: 10px 20px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
    @media (prefers-color-scheme: light){
      background-color: $lightThemeRed;
    }
    @media (prefers-color-scheme: dark){
      background-color: $darkThemeRed;
    }
    &:hover{
        transform: translateY(-2px);
        box-shadow: 2px 4px 10px rgba(0, 0, 0, 0.5);
    }
}
```
### Bouton vert
```css
.btn-green{
    display: inline-block;
    cursor: pointer;
    border-radius: 20px;
    border: none;
    text-decoration: none;
    color: white;
    text-align: center;
    font-size: 1.2rem;
    padding: 10px 20px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
    @media (prefers-color-scheme: light){
      background-color: $lightThemeGreen;
    }
    @media (prefers-color-scheme: dark){
      background-color: $darkThemeGreen;
    }
    &:hover{
        transform: translateY(-2px);
        box-shadow: 2px 4px 10px rgba(0, 0, 0, 0.5);
    }
}
```
### Bouton orange
```css
.btn-orange{
    display: inline-block;
    cursor: pointer;
    border-radius: 20px;
    border: none;
    text-decoration: none;
    color: white;
    text-align: center;
    font-size: 1.2rem;
    padding: 10px 20px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
    @media (prefers-color-scheme: light){
      background-color: $lightThemeOrange;
    }
    @media (prefers-color-scheme: dark){
      background-color: $darkThemeOrange;
    }
    &:hover{
        transform: translateY(-2px);
        box-shadow: 2px 4px 10px rgba(0, 0, 0, 0.5);
    }
}
```
