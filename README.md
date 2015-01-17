# MediumFox #

Live theme preview available at [AdrianArtiles.com](http://AdrianArtiles.com).

This is a theme for [Octopress](http://Octopress.org). Inspired by Medium and FoxSlide and leveraging the latest [Bootstrap](http://getbootstrap.com/), and is a very clean, focused, and unique theme.

Note** I'm not sure how actively the original repo is being maintained, but this fork is being actively updated.

## Installation ##

````
$ cd yourOctopress
$ git submodule add https://github.com/sevenadrian/MediumFox .themes/MediumFox
$ git submodule update --init
$ rake install['MediumFox']
$ rake generate
````

## Alternate Installation Without Git Submodule ##
````
$ cd yourOctopress
$ git clone https://github.com/sevenadrian/MediumFox .themes/MediumFox
$ rake install['MediumFox'] # for zsh, use: rake install\['MediumFox'\]
$ rake generate
````

## Customization ##
You can change the main intro hero, the following landing row, and footer in the following locations;  
hero: `source/_includes/custom/hero.html`  
landing row: `source/_includes/custom/home_landing_row.html`  
footer: `source/_includes/custom/footer.html`  

You can change the background image used behind the hero by replacing the image in `source/images/background.jpg`

## Pull-Requests Welcomed! ##

This is a first draft and can definitely be improved on. Pull requests are very much welcomed and desired!
