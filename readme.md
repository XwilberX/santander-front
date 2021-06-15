# Iniciar proyecto de git
git init

# Preparar archivos que se convertiran en commit
git add .

## EL punto es para agregar todos los archivos modificados

# Crear commit con su mensaje
git commit -m "aqui va el mensaje"

# Agregar remoto "solo la primera vez"
git remote add origin https://github.com/XwilberX/santander-front.git

# Enviar commits al servidor de GitHub
git push -u origin master