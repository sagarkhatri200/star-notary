# Star Notory
Contract Link(Rinkeby): https://rinkeby.etherscan.io/address/0x13e30e37f2c7b786e5ceda055cec043778e75118
Token Tracker: StarNotary 
Symbol: STAR

# Notes
---------------------------------------
I initially used the starter code, however once completion, i tried upgrading all the dependencies  and make it work using the latest dependencies.
Below are the list of Dependencies

Dependencies
---------------
Truffle v5.4.1 (core: 5.4.1)
Solidity - 0.8.6 (solc-js)
Node v12.18.3
Web3.js v1.4.0
"@openzeppelin/contracts": "^4.2.0"  
"truffle-hdwallet-provider": "^1.0.17"

Steps To run:
----------------------------------------
Use bash for all commands ( latest truffle seems to have problem with powershell)
1) git clone from repo.
2) npm install on the root folder
3) npm install on the /app folder
4) npm uninstall truffle -g
5) npm install truffle@5.4.1 -g
6) truffle compile
7) truffle migrate --reset
8) truffle test
9) In a new bash window,  cd /app   (app folder has the source code)
10) npm run dev (this would boot the app in localhost:8080)
11) You can use rinkeby network to create star and lookup for star using the web @ localhost:8080

Photos are added in the root folder

