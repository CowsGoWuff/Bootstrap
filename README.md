    1. Stop/shutdown your wallet client if it is running.
    2. Navigate to your GenesisX data directory as shown below:

# Your GenesisX data directory stores your blockchain, configuration, wallet, and masternode data.  By default, they are located in the following locations for each OS type:

## Windows
Go to Start > Run > %APPDATA%\GenesisX
(or just enter the above path in explorer)

or C:\Users\%username%\AppData\Roaming\GenesisX

(Hidden folder "AppData" - [How to view hidden folders on Windows](https://www.howtogeek.com/howto/windows-vista/show-hidden-files-and-folders-in-windows-vista/))


## OSX (MacOS)
Open a finder window, then select the "Go" dropdown menu. In this menu please press the "Go to Folder..." option. In the window that opens type: ~/Library/Application Support/GenesisX and press enter. If the folder cannot be found please repeat the steps and enter: ~/.genesisx

~/Library/Application\ Support/GenesisX
(/Users/YourUserName/Library/Application\ Support/GenesisX)

## MacOS High Sierra Only

~/.genesisx

(/Users/YourUserName/.genesisx)


    3. Delete ONLY the 4 folders and 2 files shown below
    (blocks, chainstate, sporks, zerocoin, banlist.dat, and peers.dat) folders from your data directory.
    (Do NOT delete backups or wallet.dat)
    4. Download the latest bootstrap from here
    5. Extract the bootstrap zip file you just downloaded and you will see a file called "bootstrap.zip"
    6. Place the "bootstrap.zip" file in your data directory
    7. Start your wallet client.
