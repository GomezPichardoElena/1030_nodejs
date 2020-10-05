# Proyecto nodejs

para iniciar el proyecto en nodejs npm init --yes esto nos creara el pacjage.json

vamos a necesitar instalar el mongoosenpm npm install mongoose esto nos creara el package-locj.json y la carpeta node_modules

una forma de instalar typescript como dependencia npm install typescript -D esto añade a la carpeta node_modules la carpteta typescript

inicializamos el poryecto con npx tsc --init esto nos genera el tsconfig.json

 "exclude":[
    "node_modules"
  ]
añadimos esto en el fichero tsconfig para excluir esos ficheros cuando compilemos 

instalar tipos de daros de mongoose:
npm install @types/mongoose

creamos la carpeta src donde iran nuestros programas comenzamos con el index.ts que es el fichero principal de la aplicacion 
para compilar usaremos npm tsc -w, con esto a su vez se creara la carpeta dist

