# Hackintosh - Opencore EFI for Asrock B660M Series


## Specification
| **Component** | **Model** |
| ------------- | --------- |
| CPU | Intel Core i5 12400F |
| Motherboard | Asrock B660M Series | 
| RAM | 16GB (2 x 8GB) Corsair Vengeance RGB @ 2666 CL15 |
| GPU | MSI RX 580 - 8GB  |
| OS Disk (Nvme/Sata3) | Western Digital SN770 1TB |

**macOS version**: Ventura 13.1

**OpenCore version**: 0.8.2  

**SMBIOS**: MacPro7,1

## How to use
  1. Create directory "EFI" in your EFI partition (e.g. pendrive or hard drive)
  2. Clone this repo and paste directiories "BOOT" and "OC" onto created directory
  3. Download [**GenSMBIOS**](https://github.com/corpnewt/GenSMBIOS) to generate unique SMBIOS information. Run it and select **Generate SMBIOS**, as model select **MacPro7,1**.
  4. Boot it!  

## Disclaimer

This documentation is published for the sole purpose of learning and tech enthusiasm and with no guarantees of any kind, I’m not responsible of any harm of any kind or loss of data that may occur.
