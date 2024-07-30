1. git clone
2. npm install
3. create .env with the following
   RPC_URL = <ganache rpc url>
   PRIVATE_KEY = <private key of any free account>
   PRIVATE_KEY_PASSPORD= <your password>
4. node encryptKey.js
5. delete PRIVATE_KEY PRIVATE_KEY_PASSPORD from .env
6. PRIVATE_KEY_PASSPORD = <your password> node deploy.js
