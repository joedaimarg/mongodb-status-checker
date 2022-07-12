# mongodb-status-checker

    install dependencies:
        $ npm install

    run the app:
        $ DEBUG=mongodb-status-checker:* npm start
        $ # http://localhost:3991

    enable auto restart:
        $ npm install -g pm2 
        $ DEBUG=mongodb-status-checker:* pm2 start --name dbcheck bin/www
