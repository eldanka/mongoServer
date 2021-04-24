# nodeServer
My first NodeJS Server
Simple node server with MongoDB on localhost:5000
<h2>Installed additional content:</h2>
<h3>*dependencies (commands used for installation):</h3>
    body-parser: ^1.19.0 (npm install body-parser)</br>
    express: ^4.17.1 (npm install express)</br>
    helmet: ^4.5.0 (npm install helmet --save)</br>
    lodash: ^4.17.21 (npm install lodash)</br>
    mongoose: ^5.12.5 (npm install mongoose)</br>
<h3>*devDependencies (commands used for installation):</h3> 
    babel-core: ^6.26.3</br>
    babel-loader: ^7.1.5</br>
    babel-preset-env: ^1.7.0</br>
    babel-preset-stage-2: ^6.24.1</br>
    (npm install babel-core, babel-loader, babel-preset-env, babel-preset-stage-2)</br>
    nodemon: ^2.0.7 (npm install nodemon --save-dev)</br>
    webpack: ^5.35.0</br>
    webpack-cli: ^4.6.0</br>
    webpack-node-externals: ^3.0.0</br>
    (npm install webpack webpack-cli webpack-node-externals --save-dev)</br>
<h2>scripts:</h2>
    start: nodemon</br>
    build: webpack --mode=production"</br>
    test: echo \"Error: no test specified\" && exit 1</br>
<h2>Needed Tools</h2>
    MongoDB</br>
    Robo3T</br>
    Postman</br>
# Discription
- MongoDB database created with Robo3T menagement tool
- two collections: students & courses
- students with keys: firstName, lastName, yearOfBirth, address, etc
- courses with keys: name, points
- created API services and CRUD for database manipulating
- test API with Postman
