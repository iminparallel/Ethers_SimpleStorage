1. git clone
2. npm install
3. yarn compile
4. create .env with the following
   RPC_URL = <ganache rpc url>
   PRIVATE_KEY = <private key of any free account>
   PRIVATE_KEY_PASSPORD= <your password>
5. node encryptKey.js
6. delete PRIVATE_KEY PRIVATE_KEY_PASSPORD from .env
7. PRIVATE_KEY_PASSPORD = <your password> node deploy.js
