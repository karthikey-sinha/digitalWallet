# digitalWallet
A Python-based command-line interface (CLI) application for simulating basic banking operations like wallet creation, money transfers, statements, fixed deposits, and special offers, using modular architecture.

#Features
- Create Wallets with starting balances
- Transfer Money between wallets
- Generate Statements for transaction history
- View Overview of all wallets
- Open Fixed Deposits (FD)
- Apply Offers (like Offer2)
- Supports Command Mode and File Mode


#Usage

1.Setup
Ensure you have Python 3.11 or above installed. 

git clone https://github.com/your-username/digital-wallet-cli.git
cd digital-wallet-cli

2.Run
python main.py

3.File Mode
Provide a command file:
python main.py commands.txtFile Mode:

Command	                                 Example Usage
CreateWallet	                           CreateWallet Alice 1000.00
Overview	                               Overview
TransferMoney                          	 TransferMoney Alice Bob 200.00
Statement	                               Statement Alice
Offer2	                                 Offer2
FD (Fixed Deposit)	                     FD Alice 500.00
exit	                                   exit (to terminate in Command Mode)

#Logs
All errors and actions are logged to logs/app.log.





