On-The-Air--web
===============

Our new little website for OTA -- www.ontheair.co

`bower install & npm install`

`gulp serve` for your duties in /app.

`gulp wiredep` to... wire deps separately, and `watch` to use livereload on /dist.

`gulp build` will run tests (which btw, plz don't forget to write) and compile everything into /dist. 

in /dist, `divshot push development (or staging, or production)` to deploy. pushing to development first, then running `divshot promote` is recommended. scope the divshot docs for more info.
