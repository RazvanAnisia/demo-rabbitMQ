# Description
Small demo repo of how RabbitMQ consumers and senders work with Node.js

# Setup
1.Run 'docker-compose up -d'
This will spin up the RabbitMQ instance so the two node servers will be able to comunicate with it

2. Run 'node receive.js' first - spins up the Node consumer server
3. Run 'node send.js' - spins up the Node sender.
4  Watch the ouput on the receiver after you spin up the sender, and you will see a messaged logged

# Future plans
Maybe create a full fledged Node.js app that uses RabbitMQ to make other services aware of events inside of the web app
