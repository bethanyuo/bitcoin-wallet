# Bitcoin Wallet
Set up a Bitcoin wallet. Install several NuGet packages, write the source code for different functionalities and in the end, send and receive coins in your wallet.

## NuGetPackages
* NBitcoin
* Qbitninja.Client
* HBitcoin

## Network
Bitcoin TestNet

## Create the Repo

1. Created the empty repo in github.
2. Clone the empty repo to my local box.
3. Run `dotnet new console`
4. Run `dotnet run` – This should run the code and print out "Hello World!"
5. Copy the Program.cs code from the exercise template directory to the Program.cs in the project.

## Program Options
* `Create` – this creates a .JSON file through which different wallet address pairs may be accessed. To create it the user must choose a name and a password. A mnemonic phrase will be displayed on the screen as well as the address public-private keys. This information should be documented and kept in a safe place as it will come in handy afterwards; 
* `Recover` – with this functionality a user may recreate lost .JSON file. For the fail to ne the correct one the user must have the password and mnemonic phrase; 
* `Balance` – shows the current balance of all wallets for certain .JSON file; 
* `History` – this shows the transaction ID of incoming and outgoing coins. It is going to be used when sending coins, since they must be send using the received coins’ transaction ID (why this is so will become obvious in a short while); 
* `Receive` – shows 10 public addresses for selected .JSON file where the user may receive Bitcoins; 
* `Send` – used to send Bitcoins to other address. Here the needed information is the name of the .JSON file, the wallet address from which the coins are send, its private key, the transaction ID through which the coins were received beforehand, the address to which the coins are to be send, the amount to be send, the amount to be got back and finally a short message; 
* `Exit` – kills the program. 

## Module
MI2: Module 5: E1
