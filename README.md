# brainwallet - What this script does
This Python script generates Bitcoin addresses from a wordlist of brain wallet passphrases. It then checks the balances of the wallets generated from the passphrases in the wordlist. This script helps you find brain wallet addresses that contain Bitcoin balance in them.


# Install
Install the required libraries using pip:
```pip install ecdsa base58 requests colorama```

Put a list of passphrases you want process in passphrases.txt. Example:
```
mysecretpassphrase1
anotherpassphrase
yetanotherpassphrase
```

# Run the Script
```Python brain_wallet_checker.py```

The script will generate addresses from ```passphrases.txt``` and check the balances of the wallets created. If the script finds a wallet address with balance more than zero, the passphrase, along with the private key and address, will be written to ```wallets_with_balance.txt```

# Sample output
```
Passphrase: mysecretpassphrase1
Private Key: 4a8a08f09d37b73795649038408b5f33f2e3d8c9
Bitcoin Address: 1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa
Balance: 0.0 BTC
Status: DEAD

Passphrase: anotherpassphrase
Private Key: 5f4dcc3b5aa765d61d8327deb882cf99
Bitcoin Address: 1dice8EMZmqKvrGE4Qc9bUFf9PX3xaYDp
Balance: 0.1 BTC
Status: ACTIVE!
```

# Donations
If you found this script useful and would like to support its development, feel free to donate to my BTC address: bc1qhx4pdfxfrr5z7whg9zx96502uq5kvanpj4nfsx
It would be very appreciated 😊
