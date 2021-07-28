//COMO EMPEZAR A COMPILAR EN SASS//
1. ABRIR LA CONSOLA EN ESTA CARPETA CON CTRL+Ñ
    A. npm install node-SASS nodemon
    npm install -D node-sass nodemon
    B. npm init
 2. ABRIR EL ARCHIVO PACKAGE-JSON Y EDITARLO
    A. A CONTINUACION DE && EXIT 1" COLOCAR UNA , ENTER Y PEGAR EL SIGUIENTE TEXTO:

    "build-css": "node-sass --include-path scss scss/main.scss css/stylr.css",
    "watch-css": "nodemon -e scss -x \"npm run build-css\""   

3. CREAR LAS CARPETAS CON SUS RESPECTIVOS ARCHIVOS
    A.SCSS/MAIN.SCSS
    B.CSS/STYLE.CSS

4. EN LA CONSOLA CORRER EL COMANDO
    A. npm:  run build-CSS //por unica vez
    B. npm:  run watch-css

5. CADA VEZ QUE SE QUIERA SEGUIR COMPILANDO EN SASS
    A. ABRIR LA CONSOLA CTRL Ñ
    B. npm run watch-CSS

//FIN

C:\Users\Leandro\Desktop\TP CODER\html\SASSCODER