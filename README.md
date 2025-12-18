Erronkako repositorioa

git checkout -b feature origin/feature

npm install react-scripts

git checkout -b leprechaun origin/leprechaun

npm install react-icons

npm install react-router-dom



Lo qe hice para crear la pagina en githb:

1. npm install --save-dev gh-pages

2. En tu package.json, agrega la propiedad homepage, por ejemplo:
"homepage": "https://TU_USUARIO.github.io/NOMBRE_DEL_REPO"

3. Dentro de "scripts" de tu package.json, agrega:​​

"predeploy": "npm run build",

"deploy": "gh-pages -d build"
