# fast-windows-10-pre-install-guide
fast windows 10 pre-install guide


## Index
1. [Backup Important Files](#backup-important-files)
2. [Backup License Keys](#backup-license-keys)
3. [Create Windows 10 Installer](#create-windows-10-installer)
4. [Update BIOS](#update-bios)
5. [Unbind Windows License](#unbind-windows-license)

## <a name="backup-important-files">Backup Important Files</a>
### Usefull tools
- Navigation and file finding software
	- [Explorer++](https://explorerplusplus.com/)
	- [SwiftSearch](https://sourceforge.net/projects/swiftsearch/)
- File compression software
	- [7-Zip](https://www.7-zip.org/)
- Temporary storage
	- High capacity USB or DVD
	- External hard drive
	- High capacity cloud storage
	
## <a name="backup-license-keys">Backup License Keys</a>
### Usefull tools
- License key finding software
	- `slmgr /dlv`
	- `slmgr /dlv all`
	- [Belarc Advisor](https://www.belarc.com/products_belarc_advisor)
	- [Magical Jelly Bean Keyfinder](https://www.magicaljellybean.com/keyfinder/)
	- [WinKeyFinder](https://www.winkeyfinder.com/)
- Key recording tools
	- Windows ***screenshot*** or ***snipping tool***
	- Phone camera
- Key storage
	- [Private Imgur album](https://imgur.com) (account required for private albums)
	- Phone storage

## <a name="create-windows-10-installer">Create Windows 10 Installer</a>
### Usefull tools
- [Windows 10 install tool](https://www.microsoft.com/en-ca/software-download/windows10)
- USB or DVD with a cpacity of at least 8GB (All data will be lost)

## <a name="update-bios">Update BIOS</a>
### Usefull tools
- Windows ***system information***

## <a name="unbind-windows-license">Unbind Windows License</a>
Simply open the command prompt and run the command `slmgr /upk`
To check if it was properly unbound, go to windows search and search `Activation` to see the status
