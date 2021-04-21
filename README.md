Third project in the Web develop course by OpenClassroom

Ohmyfood: based on a mobile-first website mockup, develop the site with html and css in three versions: mobile, pad and desktop. Ohmyfood is an online meal ordering in gastronomic restaurants to prevent from waiting when arriving on location: the meals are already prepared.
The site has an index page that refers to four restaurants' menus.
As a "favorite" button will later allow to select the restaurant in a favorite list, the :hover and :focus effects on the heart icon are to be displayed: the heart must fill progressively.
Every link has to have :hover effects at least.
The icons are from the font awesome library.

Several visual effects are needed: dishes appear at restaurant's page launch, hearts fill themselves when :hover, a green box with a check icon appears from right when a dish is selected, and a loading spinner for the index page. For further information, report to the creative brief.

No framework is allowed, Sass is on opposite needed.

The site will be displayed on a github page with a scss.file that GitHub will translate for himself (via use of Jekyll) in css.

Locally, the project is developed following the 7-1 pattern files organization in the assets/directory.

The brief:
[Brief créatif - Ohmyfood!.pdf](https://github.com/Kulwch/JulienNanquette_3_06042021/files/6302212/Brief.creatif.-.Ohmyfood.pdf)

Mockups:
[Maquettes Ohmyfood.zip](https://github.com/Kulwch/JulienNanquette_3_06042021/files/6302215/Maquettes.Ohmyfood.zip)

html structure of the restaurants' cards:
```html
<article>
  <h3>(hidden)</h3>
  <a>
    <figure>
      <img/>
      <figcaption>
        <header>
          <h3></h3>
          <p></p>
          <span><i>heart icon(font awesome)empty</i><i><heart icon(font awesome)filled</i></span
        </header>
      </figcaption>
    </figure>
  </a>
</article>
```

The site is then deployed on GitHub pages via the Jekyll convention: the partials are in the _sass directory, and the style.scss file is in assets/css. Github pages will automatically generate the css file for itself to display.
