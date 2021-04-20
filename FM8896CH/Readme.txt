MB-8896 bios Flash Upgrade Utility
=====================================================
1.Usage:
	Boot to DOS and execute batch file to update bios.

2.Example:
	boot to DOS and type 8896.bat
 	C:\>8896.bat
	C:\>afuefi FM8896CH.3J0 /p /b /n /x /k 
	+---------------------------------------------------------------------------+
	|                 AMI Firmware Update Utility  v3.03.00                     |
	|      Copyright (C)2012 American Megatrends Inc. All Rights Reserved.      |
	+---------------------------------------------------------------------------+
 	Reading flash ............... done
 	- FFS checksums ......... ok
 	Erasing Boot Block .......... done
 	Updating Boot Block ......... done
 	Verifying Boot Block ........ done
 	Erasing Main Block .......... done
 	Updating Main Block ......... done
 	Verifying Main Block ........ done
 	Erasing NVRAM Block ......... done
 	Verifying NVRAM Block ....... done
 	Erasing NCB Block ........... done
 	Updating NCB Block .......... done
 	Verifying NCB Block ......... done


3.Files:
	8896.bat:batch file to update bios.
	AFUEFI.exe:AMI bios flash utility.
	FM8896CH.3J0: Bios binary file.  
	Readme.txt:this file.  	