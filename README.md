# Private Blockchain Application

## How to test your application functionalities?

1. Run your application using the command `node app.js`
   You should see in your terminal a message indicating that the server is listening in port 8000:

   > Server Listening for port: 8000

2. To make sure your application is working fine and it creates the Genesis Block you can use POSTMAN to request the Genesis block:
   ![Request: http://localhost:8000/block/0 ](https://snipboard.io/FC8lZR.jpg)
3. Make your first request of ownership sending your wallet address:
   ![Request: http://localhost:8000/requestValidation ](https://snipboard.io/8NKHWQ.jpg)
4. Sign the message with your Wallet:
   ![Use the Wallet to sign a message](https://snipboard.io/9ut8D2.jpg)
5. Submit your Star
   ![Request: http://localhost:8000/submitstar](https://snipboard.io/b52WLy.jpg)
6. Retrieve Stars owned by me
   ![Request: http://localhost:8000/blocks/<WALLET_ADDRESS>](https://snipboard.io/SngE78.jpg)

7. Validate chain
   ![Request: http://localhost:8000/validatechain](https://snipboard.io/TUpLuA.jpg)
