# EthereumSmartContract-ColinCasey
### GETTING STARTED 
Open a New Admin PowerShell, Cd into project directory 
Cd into "client" directory 
Type "yarn start" 

/* This will start the react application locally */ 

### SMART CONTRACT DEPLOYMENT 

Open a New Admin Powershell, Cd into project directory 
Type "truffle develop" 
This will connect the project to the Existing Truffle Session at localhost:9545 
In the truffle develop powershell, type "compile", then after contracts are compiled, type "migrate"

The "truffle accounts" command will list the available truffle accounts with their corresponding private keys 
Load the private key into MetaMask that corresponds with your truffle account 

## THE CONTRACT ADDRESS
Can be found in the truffle development console by typing "networks"
The corresponding Contract Address will appear, copy this address into app.js
