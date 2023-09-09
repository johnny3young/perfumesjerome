#Notas para la app en nodejs y express


Validamos que tengamos instalado Node
PS C:\Users\Black3\Downloads\Web_helios> node -v
v18.12.1

Instalamos Nodemon
PS C:\Users\Black3\Downloads\Web_helios> npm i nodemon
added 92 packages, and audited 93 packages in 2s
12 packages are looking for funding
run `npm fund` for details

found 0 vulnerabilities
npm notice
npm notice New major version of npm available! 8.19.2 -> 10.0.0
npm notice Changelog: https://github.com/npm/cli/releases/tag/v10.0.0
npm notice Run npm install -g npm@10.0.0 to update!
npm notice

Instalamos Express
PS C:\Users\Black3\Downloads\Web_helios> npm i express
up to date, audited 93 packages in 851ms

12 packages are looking for funding
run `npm fund` for details
found 0 vulnerabilities

Instalamos el paquete de dotenv para variables y api
PS C:\Users\Black3\Downloads\Web_helios> npm i dotenv
up to date, audited 93 packages in 1s
12 packages are looking for funding
run `npm fund` for details
found 0 vulnerabilities

Ejecutamos la app para que abra la pagina de forma local por el puerto 9596 configurado en el archivo .env
PS C:\Users\Black3\Downloads\Web_helios> node app.js
webserver activo en el puerto 9596

Nota: para descargar y probar la app se debe reconstruir
los node_modules, con un npm install en la terminal 
```
