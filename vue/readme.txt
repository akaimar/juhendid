Juhend:
https://www.linkedin.com/learning/vue-js-full-stack-applications-with-firebase/installation-with-vue-cli?contextUrn=urn%3Ali%3AlyndaLearningPath%3A5d94ce0a498e93731fbb8711

#### INSTALL VUE AND CLI ####

$ cd #Mine enda folderisse
$ npm install -g @vue/cli #võimalik, et on vaja panna ette sudo
$ vue create vue-stpas

> Manual features
* Babel * Router * CSS Pre-processors * Linter / Formatter
> use hirtory mode for router? NO
> Sass/SCSS (with node-sass)
> ESLint + Prettier
> Lint on save
> In package.json
> Save? N

$ cd vue-spas


# Mine VSCode-sse
#  Ava fail gitignore ja pane /dist alla
src/db.js

# Ava githubis järgmine link:
# https://gist.github.com/planetoftheweb/c32e93908518eb77dc413ff8f1295d71
# Vajuta nupule "Raw" ja kopeeri npm rida: "npm i --save-dev @fortawesome/fontawesome-free @fortawesome/fontawesome-svg-core @fortawesome/free-solid-svg-icons @fortawesome/vue-fontawesome bootstrap jquery popper.js firebase"
# Mine VSCode terminali ja käivita see käsurealt
$ npm i --save-dev @fortawesome/fontawesome-free @fortawesome/fontawesome-svg-core @fortawesome/free-solid-svg-icons @fortawesome/vue-fontawesome bootstrap jquery popper.js firebase
# see installeerib dependencies jm sodi vt package.json faili ja faili package-lock.json.

### Käivita server ###

$ npm run serve

### MUUD JUHISED ###
# Folderis public me üldiselt midagi ei puutu. Siin asub index.html fail, kus on <div id="app"></div> mida targetime.
# src folderis töötame, siin asub main.js fail, millega me mountime applicationi selle div id peale.  Kõik mida me näeme selles applications, tuleb App.vue failist. Siia me sisestame ka vue librari ja routeri. Et siis erinevaid kompomente kasutada (components kasutast).
# App.vue failis on template, script section ja ka style section. Siin on näha ka template (ülemise menüü) router ligid <router-link to="/">Home</router-link> ja About.
# router.js failis on router.

