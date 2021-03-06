# Lanner FW-8894B &amp; FW-8895B Bios

20 April 2021

## Description
Files for the Lanner FW-8894B &amp; FW-8895B range of appliances.

## Contents
The last AMIBIOS release for the FW-8894B/FW-8895B network appliance. These devices are EOL and the files for it are hard to come by.

The package includes: -
  - the latest Bios available v2.17.1249 dated 03/19/2018
  - a modified Bios based on v2.17.1249 with additional features unlocked

## Package Details

### Bios Information
	Bios Vendor           American Megatrends
	Core Version          5.11
	Compliancy            UEFI 2.4; PI 1.3
	Project Version       0ACFL 0.23 x64
	Build Date and Time   03/19/2018 14:05:24

Modified Bios file includes the following unlocked features under the IntelRCSetup menu: -
- Advanced Power Management Configuration
- Miscellaneous Configuration

These appliances are dual CPU systems with the [Intel E5-2600 v3/v4](https://ark.intel.com/content/www/us/en/ark/products/series/59138/intel-xeon-processor-e5-family.html) (Haswell/Broadwell-EP) family processors with Wellsburg PCH. They utilise features such as Enhanced Intel SpeedStepĀ® Technology and whilst the motherboards support it, the Bios was purposely crippled preventing use of the advanced featureset. Using the standard bios, you will see references on boot that the CPU supports a number of advanced features but which cannot be enabled. A modded bios solves this problem and allows for the OS to throttle the processor frequency to conserve power.

### Screenshots of the Unlocked Menus

Unlocked features in *IntelRCSetup* sub-menu
![Root Menu](https://github.com/ThePopolou/Lanner/blob/main/Screenshots/Screenshot%201.JPG)

Unlocked *Advanced Power Management Configuration* sub-menu
![Advanced Power Management Configuration](https://github.com/ThePopolou/Lanner/blob/main/Screenshots/Screenshot%202.JPG)

Unlocked *Misceallaneous* sub-menu
![Advanced Power Management Configuration](https://github.com/ThePopolou/Lanner/blob/main/Screenshots/Screenshot%203.JPG)

Others are available
