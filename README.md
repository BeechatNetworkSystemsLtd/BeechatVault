# Beechat Vault
## _OSHW NFC tag-based cold wallet, to store private keys and other sensitive data_

![BNSLTD](https://beechat.network/wp-content/uploads/2021/02/powered-by-1.png)
![License](https://img.shields.io/badge/License-GPLv2-blue)

## Introduction

Beechat Vault tag is an NFC tag consisting of:
* High efficiency multi-layer custom NFC 13.56 MHz antenna,
* M24SR64-Y ST-Microelectronics IC,
* Super small 9.7mm x 9.7mm x 1.4mm size.

The idea arose as we needed a low-cost way to store many private keys, securely. Our post-quantum private keys are very large (>1KiB) so we couldn't use common tags on the market (such as NTAG213). With the Beechat Vault tag, we can store 2 post-quantum keypairs, or 256 Bitcoin/Ethereum private keys protected with AES-128.


[Access Beechat Vault datasheet](https://github.com/BeechatNetworkSystemsLtd/BeechatVault/raw/main/Beechat_Vault-NA_V2_P-Specification_sheet.pdf)
-------------------

__Features__ 

Feature Name | Value |
| ------ | ------ | 
|Read range | 20 mm | test | 
|Dimensions | 9.7mm x 9.7mm x 1.4mm | 
|Data retention | 200 years | 
|Storage capacity | 8 KiB | 
|Password size | 128-bit | 



Image
-------------------
![image](https://raw.githubusercontent.com/BeechatNetworkSystemsLtd/BeechatVault/main/vault-render.png)
_Beechat Vault Revision 1.0 pictured above_

License Information
-------------------

The hardware is released under the [GNU General Public License, version 2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html).

Distributed as-is; no warranty is given.
