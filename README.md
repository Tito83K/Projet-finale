# 🌐 Mon Site Web – Projet BTS CIEL

Bienvenue sur le dépôt GitHub de mon site web réalisé dans le cadre de mon projet de cours en **BTS CIEL** au lycée Saint-Éloi.

---

## 🔧 Technologies utilisées

- **HTML5**  
- **CSS3**  
- Pas de JavaScript – tout est fait en HTML et CSS uniquement.

---

## ✨ Fonctionnalités principales

### 🎞️ Parallaxe
Effet de défilement fluide où le fond bouge plus lentement que le contenu, pour une sensation de profondeur.

### 📸 Carrousel d’images
Un diaporama d’images fonctionnel et responsive uniquement en CSS.

---

## 📁 Structure du projet

```bash
/
├── index.html
│    ├── présentation et intérêt
│    ├── Parallaxe
├── style.css
├── voyage.html
│   ├── Milan
│   ├── Crète
│   ├── Carrousel
├── bonplan.html
├── apropos.html
│   ├── Video.mp4
├── contact.html
├── Medias/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
└── README.md
```
## CODES HTML
#### Voici quelque-uns des codes html utilisé pour ce site
### index.html
```html  index.html

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vie2Rêve</title>
    <link rel="stylesheet" href="style.css">
    <link rel="image" href="/Medias/">
</head>
<body>
<a href="indexanglais.html">EN</a>
  <div class="header">
    <img src="Medias/logo.png" alt="Logo" class="logo">
    <nav>
      <ul>
        <li><a href="">Accueil</a></li>
        <li><a href="voyage.html">Voyages</a></li>
        <li><a href="Bonplans.html">Bons Plans</a></li>
        <li><a href="apropos.html">A propos</a></li>
        <li><a href="contact.html">Contact</a></li> 
      </ul>
    </nav>
  </div>

<div class="parallax">
    <div class="parallax parallax1"><strong>Je partagerai sur ce blog tout les voyages que j'ai effectuer en vous <br>proposant des bon-plan (Vols/Hotel/Restaurant...)</strong></div></div>
  
    <div class="content">
      <h1>Pourquoi ce site ?</h1>
      <p>Vous allez pouvoie retrouver l'enssemble des voyages que j'ai effectuer afin de vous donner des idées en vous recontant mes ressentit avec toute ma franchise.</p>
    </div>
  
    <div class="parallax parallax2">Trouver votre prochaine destination et projeter vous dans vos futurs vouyages<BR>en vous inspiant de ma propre expérience pour créé les votres</div>
  
    <div class="content">En espérant vous avoir aider à trouver votre bonheur.<br>
      Bon voyage !!
    </div>
  
    <footer>
      <div class="footer-content">
        <p>2025 Lycée Saint Eloi</p>
      </div>
    </footer>


    </body>
    </html>
```
### voyage.html
```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vie2Rêve</title>
    <link rel="stylesheet" href="style.css">
    <link rel="image" href="/Medias/">
</head>
<body>
    <a href="voyageanglais.html">EN</a>
    <div class="header">
        <img src="Medias/logo.png" alt="Logo" class="logo">
    <nav>
        <ul>
          <li><a href="Index.html">Accueil</a></li>
          <li><a href="voyage.html">Voyages</a></li>
          <li><a href="Bonplans.html">Bons Plans</a></li>
          <li><a href="apropos.html">A propos</a></li>
          <li><a href="contact.html">Contact</a></li> 
        </ul>
    </nav>
    </div>
    <div class="hautpage">  
        <div class="carousel">
            <div class="carousel-track">
            <div class="slide"><img src="Medias/duomo.jpeg" alt="Image 1"></div>
            <div class="slide"><img src="Medias/gallerie.jpeg" alt="Image 2"></div>
            <div class="slide"><img src="Medias/gucci.jpeg" alt="Image 3"></div></div>
        </div>
        <div class="textcar"><h1>Milan (Italie) </h1><br><p>Capitale italienne de la mode et du design,<br> Milan offre un subtil mélange de modernité et de tradition.<br> Le temps d’un week-end, flânez dans les galeries de la Galleria Vittorio Emanuele II,<br> admirez la majestueuse cathédrale Duomo,<br> ou explorez les œuvres de Léonard de Vinci au musée des Sciences et des Techniques.<br>

Milan est la destination parfaite pour combiner culture, shopping et bien-être en quelques jours.</p></div>
    </div>    
    <div class="hautpage">  
        <div class="carousel">
            <div class="carousel-track">
            <div class="slide"><img src="Medias/Matala.jpeg" alt="Image 1"></div>
            <div class="slide"><img src="Medias/pay2gr.jpeg" alt="Image 2"></div>
            <div class="slide"><img src="Medias/titoanna.jpeg" alt="Image 3"></div></div>
        </div>
        <div class="textcar"><h1>Crête (Grèce)</h1><br><p>Explorez une Crète authentique<br> En partant vers ses villages perchés et ses îles secrètes comme Gavdos ou Loutro.<br> Chaque excursion vous plonge dans un mode de vie préservé :<br> Repas faits maison <br>Artisanat local<br> Raki partagé sous les oliviers.<br> Loin du tourisme de masse, vous découvrirez une culture fière et chaleureuse,<br> au rythme des montagnes et de la mer.</p> </div>
    </div> 
  
      <footer>
        <div class="footer-content">
          <p>2025 Lycée Saint Eloi</p>
        </div>
      </footer>
```
### apropos.html
```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>À propos – BTS CIEL Saint Éloi</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <a href="aproposanglais.html">EN</a>
    <div class="header">
        <img src="Medias/logo.png" alt="Logo" class="logo" />
        <nav>
            <ul>
                <li><a href="Index.html">Accueil</a></li>
                <li><a href="voyage.html">Voyages</a></li>
                <li><a href="Bonplans.html">Bons Plans</a></li>
                <li><a href="#">À propos</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </div>

    <main class="content">
        <section class="about-me">
            <h1>À propos de moi</h1>
            <p>Je m'appel Tito FEDELE et je suis étudiant en BTS CIEL au lycée Saint Éloi. Ce site est un projet de cours.</p>
        </section>
    </main>
    <video autoplay muted loop id="background-video">
    <source src="Medias/Musique de méditation - Nature, Paysages apaisants • 15 minutes .mp4" type="video/mp4" />
  </video>

    <footer>
        <div class="footer-content">
            <p>2025 Lycée Saint Éloi</p>
        </div>
    </footer>
</body>
</html>
```
## CSS
#### Voici maintenant le code css utilisé pour ce site
### style.css
```css
body
{
    background-color: rgb(32, 87, 129) ;
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size: 100% 100%;
    object-fit: cover;
    scroll-behavior: smooth;
    
}

.hautpage
{
  display: flex;
  flex-direction: row;
}

.carousel {
  width: 400px;
  height: 600px;
  overflow: hidden;
  position: relative;
  border-radius: 10px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
  margin-left: 0;
}


.carousel-track {
  display: flex;
  width: 300%;
  height: 100%;
  animation: scroll 9s infinite;
}
.textcar{
  color: #f0f0f0;
  margin-right: 0%;
  margin-top: 0%;
  font-size:larger;
  text-align: center;
}

.slide {
  width: 100%;
  flex-shrink: 0;
}

.slide img {
  width: 400px;
  height: 600px;
  object-fit: cover;
  display: block;
}

@keyframes scroll {
  0%    { transform: translateX(0%); }
  33%   { transform: translateX(0%); }
  36%   { transform: translateX(-100%); }
  66%   { transform: translateX(-100%); }
  69%   { transform: translateX(-200%); }
  100%  { transform: translateX(-200%); }
}

.titre{
  text-align: center;
  color:rgb(246, 248, 213);
  top: 30px;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  
}

nav{
  width: 100%;
  margin: 0 auto;
  background-color:rgb(152, 210, 192);
  position: sticky;
  top: 0px;
  z-index: 0;
}

nav ul{
  list-style-type: none;
}

nav ul li{
  float: left;
  width: 20%;
  text-align: center;
  position: relative;
}

nav ul::after{
  content: "";
  display: table;
  clear: both;
}

nav a{
  display: block;
  text-decoration: none;
  color: rgb(32, 87, 129);
  border-bottom: 2px solid transparent;
  padding: 10px 0px;
}

nav a:hover{
  color: orange;
  border-bottom: 2px solid gold;
}

.footer-content{
  background-color: rgb(152, 210, 192);
  color: rgb(32, 87, 129);
  width: auto ;
  height: 20px;
}

.parallax {
  height: 100vh;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  text-align: center;
}

.parallax1 {
  background-image: url('Medias/Fond.jpg');
  text-align: center;
  line-height: 250px;
  color: #f0f0f0;
  font-size: 2rem;
}


.parallax2 {
  background-image: url('Medias/ile.jpg');
  text-align: center;
  line-height: 150px;
  color: #f0f0f0;
  font-size: 3rem;
}

.content {
  height: auto;
  background-color:rgb(152, 210, 192);
  text-align: center;
  font-size: 2rem;
  vertical-align: middle;
}

.logo
{
  width: 400px;
  height: auto;
  align-items: center;
  margin-left: 450px;

}
.container {
  display: flex;
  justify-content: center;
  gap: 40px;
  align-items: flex-start;
  max-width: 1000px;
  margin: auto;
}

form {
  background-color: rgb(70, 161, 186);
  padding: 20px;
  border-radius: 10px;
  max-width: 400px;
  margin-left: 50px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

label {
  display: block;
  margin-top: 15px;
  margin-bottom: 5px;
  font-weight: bold;
}

input, textarea {
  width: 100%;
  padding: 8px;
  border-radius: 5px;
  border: 1px solid #ccc;
  box-sizing: border-box;
}

button {
  margin-top: 20px;
  padding: 10px;
  width: 100%;
  background-color: #007BFF;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 1rem;
  cursor: pointer;
}

button:hover {
  background-color: #0056b3;
}

.texteform {
  display: flex;
  justify-content: center;
  gap: 40px;
  align-items: flex-start;
  max-width: 1000px;
  margin: auto;
}
.bon-plan {
    background-color: #d0f0e0; /* Vert doux pastel */
    border-left: 8px solid #1d4e89; /* Bande colorée à gauche */
    padding: 30px;
    margin: 40px auto;
    width: 80%;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    border-radius: 10px;
    font-family: 'Segoe UI', sans-serif;
}

.bon-plan h1 {
    color: #1d4e89;
    text-align: center;
    font-size: 2em;
    margin-bottom: 20px;
    font-weight: 700;
}

.bon-plan p {
    font-size: 1.1em;
    text-align: center;
    margin-bottom: 20px;
}

.bon-plan ul {
    list-style-type: disc;
    padding-left: 30px;
}

.bon-plan li {
    font-size: 1.05em;
    line-height: 1.6;
    margin-bottom: 12px;
}

.bon-plan strong {
    color: #0b3d91;
}

video{
  width: 600px;
  height: 400px;
  align-items: center;
  margin-left: 300px;
}
```

