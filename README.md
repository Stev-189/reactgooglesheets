# React.JS con Google Sheets como API Rest
## https://www.freecodecamp.org/news/react-and-googlesheets/?fbclid=IwAR0tqM3ANlG-2QKOgHKpK6zqqTKN2lDbbviDEbQZbspyzeAFGuEuEAVxFrg

## https://github.com/nishant-666/React-GoogleSheets
## 01- Primeros pasos
'''
npx create-react-app react-googlesheets
npm install semantic-ui-react semantic-ui-css // es solo estilo se puede hacer con bootstrap
npm install axios
'''
en index.js
import 'semantic-ui-css/semantic.min.css'

## 02- Google Sheets
En Google Sheets creamos una hoja yla primera fila colocamos exactamente los mismos nombres de las variables de objeto state.
nos vamos a compartir obtener enlase y cambiamos el permiso ya cualquier persona con el enlase puede editar.
copiamos enlace.

## 03- https://sheet.best/
creamos una cuenta y agregamos connection con el link de Google Sheets  y la referencias que nos entrega es a la que nos conectamos

## 03-Deploy github
npm install gh-pages --save-dev
en package.json
  "homepage": "https://stev-189.github.io/reactgooglesheets",//nombre del repositorio github
 
y en scripts
"predeploy": "npm run build",
"deploy": "gh-pages -d build",

npm run deploy

#https://stev-189.github.io/reactgooglesheets/ 