Third project in the Web develop course by OpenClassroom

 ==> Project basics:

Ohmyfood: based on a mobile-first website mockup, develop the site with html and css in three versions: mobile, pad and desktop. Ohmyfood is an online meal ordering in gastronomic restaurants to prevent from waiting when arriving on location: the meals are already prepared.
The site has an index page that refers to four restaurants' menus.
As a "favorite" button will later allow to select the restaurant in a favorite list, the :hover and :focus effects on the heart icon are to be displayed: the heart must fill progressively.
Every link has to have :hover effects at least.
The icons are from the font awesome library.

Several visual effects are needed: dishes appear at restaurant's page launch, hearts fill themselves when :hover, a green box with a check icon appears from right when a dish is selected, and a loading spinner for the index page. For further information, report to the creative brief.

No framework is allowed, Sass is on opposite appreciated.
The brief:
[Brief créatif - Ohmyfood!.pdf](https://github.com/Kulwch/JulienNanquette_3_06042021/files/6302212/Brief.creatif.-.Ohmyfood.pdf)

Mockups:
[Maquettes Ohmyfood.zip](https://github.com/Kulwch/JulienNanquette_3_06042021/files/6302215/Maquettes.Ohmyfood.zip)


==> Environment: 

Locally, the project has been developed following the 7-1 pattern files organization in the assets/ directory. The IDE used is Visual Studio Code with extensions: Live server, and Prettier for preview and formatting. DevTools from Chrome and Firefox Dev editions have been used, and the html and css passed through W3C validator. A 'develop' branch has been created to work the project. A git merge is made near the end on 'main' branch.

==> Prerequisites:

- The css file is compiled using Sass (https://sass-lang.com/) from the main file named "styles.scss". To use Sass compilation, you must install Sass on your computer, and then use the script in the package.json file. The script will let you define the output file of the compiled css.
- Moreover, to avoid compatibility problems with navigators (like the 'background-clip: text' on Chrome) I also used autoprefix to add prefix on properties. There again, you have to use the script in the package.json file.



==> Deployment: 

The site is then deployed on GitHub pages via the Jekyll convention: the partials are in the sass directory, and the styles.scss file import all rules. The sass compilation translate it in styles.css which is set to output in assets/css. You may have to use a -config.yml to change the sass directory if you want.
The deployment is based on the 'main' branch. You don't have to push the css file, pushing package.json;  and sass + assets directories will be sufficient: Jekyll will generate the css file.

!Important!
To make the deployment, you have to add a YAML front-end matter: two lines of --- at the beginning of your styles.scss file when pushing on the repo.
