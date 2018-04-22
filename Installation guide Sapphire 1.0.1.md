This guide will explain how to install Sapphire 1.0.1. Please follow this guide step by step, only then your installation will be succesfull.
Please report any bugs to the slack in the #support channel.
***

1.	First we will have download sapphire, select the download for the OS you are using.:
	https://drive.google.com/drive/folders/1PL9RRzseJnt4v82vEAszB3bCgWE_RanM

>If you never had any other ECC wallet and this is your first then please skip to step 8. 
    If your already had another ECC wallet on your pc and want to reuse the wallet.dat file (because you have coins on the addresses) follow from here: 

2.	Go to:
***
On Windows:
	`C:\Users\<USER>\AppData\Roaming\eccoin`

***
On Linux:
`home/<USER>/.eccoin`
***
On Mac
`~/Library/Application Support/eccoin`
***
>If you cant find the folder AppData this is because it is hidden by default. 
>For windows go to the windows search option and type %appdata%, this will show you the folder. 
>For Mac go to finder type shift + command + g and then type  ~/Library

	
3.	Delete every file and folder you see, EXCEPT FOR THE wallet.dat file (this file gives you acces to the coins in your addresses).

4.	Download the bootstrap from https://drive.google.com/uc?id=1lJNcrJ5ry4Efbn6eDzGZCyo-itoQycZI&export=download this will increasy the sync speed for sapphire a lot.
	Depending on your setup it can take anyware from 4hours to 8+ to catch up to 100%.
	
5.	Unzip the downloaded bootstrap.zip file.

6.	Copy the bootstrap.dat file (there are 4 files in the bootstrap.zip but we only need the bootstrap.dat file)

7.	Place this file inside of the eccoin.
	Now there should be 2 files inside of the eccoin folder, the wallet.dat file and the bootstrap.dat file.

8.	Run the downloaded sapphire setup.

9.	Now you will see the ECC logo with the message "Hello, we are getting a few things ready".
	Sapphire is downloading the daemon, this a ~20mb file so depeding on your network speed it can take a little time.
	
10. After when its done downloading the daemon, sapphire will check if your wallet.dat file is encrypted.
	If it is you can continue, if not please encrypt it.

11. Now you can select your theme, which ever you like.

12. When done selecting the theme click the arrow and you will see the home screen of sapphire.

13. If done correctly you will now see in the bottom left the syncing progress. 

14. The installation is done.

>Note: 	If you run a fresh install of sapphire, so you never had any other ECC wallet on your system, and see that the syncing progress is slow. You can add the bootstrap file to speed up the process.
>- Stop sapphire, 
>- Download the bootstrap from https://drive.google.com/uc?id=1lJNcrJ5ry4Efbn6eDzGZCyo-itoQycZI&export=download ,
>- Unzip the downloaded bootstrap.zip file.
>- Copy the bootstrap.dat file (there are 4 files in the bootstrap.zip but we only need the bootstrap.dat file)
>- Place this file inside of the C:\Users\<USER>\AppData\Roaming\eccoin folder. 
	>Or ~/Library/Application Support/eccoin for mac
>- Run sapphire again, it will first look like the syncing is stuck because it is checking the already downloaded blocks before importing the bootstrap.dat file.