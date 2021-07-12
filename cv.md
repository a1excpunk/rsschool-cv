# Aleksandra Sauri

_Front-end Developer, Based in Tbilisi, Georgia_

## Contact Info

- Tel: `+995558348760`
- [Mail](alexandrasauri19@gmail.com)
- [LinkdIn](https://www.linkedin.com/in/alexandra-sauri-8273ba150/)
- [GitHub](https://github.com/a1excpunk)

## Skills

- HTML
- CSS
- Flex
- Grid
- SCSS
- Responsive Web Design
- JavaScript / ES6
- TypeScript
- VS code
- git
- GitHub
- Angular
- abobe Xd
- REST API
- DevTools

## Experience

- **Contributing Developer** in private project _(Feb 2021 - Apr 2021)_
    - **_Technologies used (by me):_** SCSS, Angular 12, TypeScript.

- Created small components, like: 
    - _forms_
    - _preloaders and placeholders_
    - _animations_
    - _cards_
    - _canvas interactive animations_
    - _carusele_
    - _parallax_
    - _dropdown menu_
    - _price calculator_

#### My Projects
- ⛅ [Weather App](https://a1excpunk.github.io/weatherApp/) ⛅
    - **_Technologies used:_** HTML, CSS, Flex, Grid, JavaScript ES6, third party API.
    <br>
- 🔪 [Tarantino Page](https://a1excpunk.github.io/tribute-page/index.html) 🔪
    - **_Technologies used:_** HTML, CSS, Flex, Animations, audio features, JavaScript ES6, DOM.
    <br>
- 🥗 [Adare Restaurant](https://a1excpunk.github.io/restourant/index.html) 🥗
    - **_Technologies used:_** HTML, CSS, Flex, Grid, Animations, JavaScript ES6.
    <br>
- 🚴 [Bike Repair](https://a1excpunk.github.io/bike-repairs/index.html) 🚴
    - **_Technologies used:_** HTML, CSS, Flex, Grid, Animations.

<br>

##### Code example from latest project
 *creating, randomized, particles on canvas using ES6 classes*

```javascript
class Particle {
    constructor() {
        this.x = mouse.x;
        this.y = mouse.y;
        this.size = Math.random() * 15 + 1;
        this.speedX = Math.random() * 3 - 1.5;
        this.speedY = Math.random() * 3 - 1.5;
        this.color = `hsl(${hue},100%,50%)`;
    }
    update() {
        this.x += this.speedX;
        this.y += this.speedY;
        if(this.size > 0.2){
            this.size = this.size - 0.1;
        }
    }
    draw() {
        ctx.fillStyle = this.color;
        ctx.beginPath();
        ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
        ctx.fill();
    }
}
```

## Languages

- **Georgian:** Native
- **English:** C1
- **Russian:** C1


## Education

- **Bachelor's Degree** in Psychology
[Tbilisi State University](https://www.tsu.ge/en) - Tbilisi, Georgia (_2012 - 2016_)

- **6-week coding course** focused on front-end and JavasCript
[New Horizons Computer Learning Centers](https://www.newhorizons.com/)

- **Javascript Certificate:** fundamentals of web development using Javascript and the HTML DOM
[w3schools](https://certification.w3schools.com/w3certified.asp?id=12861192)

- **6-week coding course** focused on JavasCript and DOM
[Academy Of Digital Industries](https://digitaledu.ge/)