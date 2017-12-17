# Botschmiede Backend

Instructions to deploy the software (Tested on Ubuntu 16.04 and Windows 10):

1. Install latest stable docker version (Tested with v.17.11.0-ce, v.1.13.1)
2. Install latest stable docker-compose version (Tested with v.1.17.0 and v.1.8.0)
3. Move to the 'SEP_Frontend' directory and place your server ip with port (Default Port 3000) in the settings.json file (Important!!)
4. Move to the 'Deployment-Hufflepuff' directory and update the .env file with your LiveEngage data (Important!!)
5. Run the following docker-compose command: <code>docker-compose up</code>
6. Build Welcome-Bot image with curl: <code>curl -X POST http://localhost:3000/image/create -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"type" : "Welcome_Bot"}'</code>
7. Build FAQ-Bot image with curl: <code>curl -X POST http://localhost:3000/image/create -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"type" : "FAQ_Bot"}'</code>
8. Connect to the server via a browser (Tested with Chrome) and Login with your LiveEngage ID (Important for Chat) and some random user data 

