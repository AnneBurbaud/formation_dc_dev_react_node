Instructions d'installation
======================

#Windows

1. Installer NodeJS
2. Installer GitKraken
    1. Se rendre sur github.com
        1. Se connecter
        2. Fork le projet Dylfaen/formation_dc_dev_react_node
    1. Se connecter avec Github
    2. Cloner le projet forké sur votre compte depuis github
3. lancer la commande `npm install` dans le répertoire du projet dans `node_src/` et dans `react_src/`
4. Installer mongoDB https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/
5. Lancer la commande en mode administrateur `"C:\Program Files\MongoDB\Server\4.2\bin\mongo.exe"`
6. Lancer MongoDB compass et se connecter au server mongoDB avec `mongodb://127.0.0.1:27017/?compressors=zlib&gssapiServiceName=mongodb`
7. Dans le répertoire du projet modifier `node_src/` pour lancer le serveur sur le port 3001
8. lancer `npm start` dans `react_src/` et dans `node_src/`