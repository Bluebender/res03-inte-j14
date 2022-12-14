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
## Header
```html
<script src="https://kit.fontawesome.com/dbf8b52bf4.js" crossorigin="anonymous"></script>

<header>
    <figure>
        <img src="assets/images/logo.jpg" alt="logo"/>
    </figure>
    <nav>
        <h2 class="hidden">Menu de navigation</h2>
        <ul>
            <li><a href="">Home</a></li>
            <li><a href="">Photos</a></li>
            <li><a href="">Articles</a></li>
            <li><a href="">Contact</a></li>
        </ul>
    </nav>
    <ul>
        <li><a href=""><span class="fa-brands fa-facebook-f" alt="facebook"></span></a></li>
        <li><a href=""><span class="fa-brands fa-twitter"></span></a></li>
        <li><a href=""><span class="fa-brands fa-instagram"></span></a></li>
        <li><a href=""><span class="fa-solid fa-basketball"></span></a></li>
    </ul>
</header>
```
```css
body > header{
    background-color: grey;
    display: grid;
    grid-template-columns: 0.1fr 0.1fr 0.1fr 0.8fr 0.4fr 0.2fr 0.1fr;
    grid-template-rows: 10vh;
    box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
    > figure{
        grid-column: 2 / 3;
        height: 100%;
        > img{
            height: 100%;
        }
    }
    > nav{
        grid-column: 4 / 5;
        display: flex;
        > ul{
            width: 100%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            > li{
                padding: 5px 0;
                > a{
                    font-size: 1.4rem;
                    text-decoration: none;
                    color: black;
                }
                &:hover{
                    transform: translateY(-4px);
                    border-bottom: 4px solid black;
                }
            }
        }
    }
    > ul{
        grid-column: 6 / 7;
        display: flex;
        justify-content: space-between;
        align-items: center;
        > li{
            > a{
                font-size: 1.4rem;
                text-decoration: none;
                color: black;
            }
            &:hover{
                transform: translateY(-4px);
                > a{
                    color: white;
                }
            }
        }
    }
}
```
