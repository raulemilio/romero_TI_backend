/*********Para correr el backend:******************/
dentro de la carpeta backend -> node index.js

/*********paquetes necesarios******************/
npm init
npm install --save express
npm install --save mysql
npm install --save cors
npm install commander
npm install moment --save 

/*********Cuestiones de mySQL:******************/
CREATE USER 'usuario'@'%' IDENTIFIED BY '123';
GRANT ALL PRIVILEGES ON * . * TO 'usuario'@'%';
para poder acceder desde root
ALTER USER 'usuario'@'localhost' IDENTIFIED WITH mysql_native_password BY 'vtwqh7717';
