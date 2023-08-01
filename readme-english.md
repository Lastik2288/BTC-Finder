#BTC Finder
# Purpose of the program
If you still do not understand what this program is for, then here is an explanation: In the Electrum Wallet, you can go to the wallet and change the password from it simply by entering a private key that consists of 52 characters, and this program generates this private key, it comes in, looks at the balance and writes it to Money.txt if the balance is greater than 0. It also has some functionality to manage key generation and calculate statistics on generated keys.

- 1 Private key generation: The program is able to generate private keys for Electrum wallets. Private keys are randomly generated combinations of characters from Latin letters and numbers.

- 2 Balance check: The program checks the balance for each generated private key by accessing the Electrum server using the getaddressbalance command. The balance is measured in bitcoins.

- 3 Writing data to a file: If the wallet balance is greater than 0, the program writes the private key and the corresponding balance to the Money.txt file. Each line of the file contains a "Private Key | Balance" pair.

- 4 Commands to control the program: The program provides several commands to control the key generation process:

"start": Starts key generation.
"pause": Pauses key generation until the "start" command is entered or the program terminates.
"stop": Stops key generation and exits the program.

"info": Shows information about the number of generated keys, keys with a balance of 0 and keys with a positive balance.

The program is written in Python on Windows 10.

# INSTRUCTIONS
1. Download and install minimum Python 3.6.x
2. Download and open Electrum and create a wallet. Electrum must be open for the app to work!
3. Move BIT-Finder.exe to any folder convenient for you.
4. Create a settings.txt file in this folder and write the path of the Electrum executable file there. Example: D:\Electrum\electrum-4.4.5.exe.
5. Run the script by clicking 2 times on the .exe file.
6. You can use it when you find the private key from the wallet on which there is a balance, then the private key will be moved to the Money.txt file. You don't need to create it.

# PRICE
For the first 3 buyers, the price of $ 50 will be used to promote the program to such an extent that you will win back the money in a day.
To all those who did not have time to 5000 $ Contact me (Telegram) @abuaue11
Prices are not taken from the air, but with a detailed analysis of the market for such programs.
There are no analogues of this program.

Here are the results of the program, but we are not thieves and we do not steal bitcoins.
