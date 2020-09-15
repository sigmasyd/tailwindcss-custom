# iniciar un proyecto con node
---------------------------------
npm init

# instalar tailwindcss
---------------------------------
npm i tailwindcss

# compilar estilos 
---------------------------------
npx tailwindcss build src/estilos.css -o public/estilos.css

# generar archivo de configuracion tailwind.config.js (full: todas las opciones)
---------------------------------
tailwindcss init --full

# generar archivo de configuracion tailwind.config.js basico
---------------------------------
tailwindcss init

# compilar las nuevas configuraciones
---------------------------------
npx tailwindcss build src/estilos.css -o public/estilos.css
