# FTHTCOIN-WINDOWSCORE
Core wallet for Windows

This is where you can obtain your Fuck Them Heggies Coin Windows Wallet.

First, download the fuckthemheggiescoin-0.21.2.2-win64-setup.exe file.

Once the file has downloaded, right-click and select "Run as administrator."

If you're using Windows 10, you may encounter a warning. Click on "More info" and then select "Run anyway."

The wallet will begin installation.

After the wallet has installed, you will need to add nodes to the configuration file.

Hide the pop-up that appears when you first launch the wallet.

Navigate to Settings, select Options, and then click on "Open Configuration File."

Choose a text editor to modify the file. Notepad will work.

Add the following lines:

addnode=64.227.14.109

Server=1

rpcuser=user

rpcpassword=password

Click save, then close Notepad.

Exit the wallet and restart it.

The wallet will now synchronize with the blockchain.

To start mining, navigate to Help, then Debug Window, and finally Console.

In the command line area at the bottom, type the word "generate" followed by a number (e.g., generate 1).

This command will allow you to mine one block.

Mined coins are not spendable until 101 blocks have been mined. At that point, they will be available to spend.
