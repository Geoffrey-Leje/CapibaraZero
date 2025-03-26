# CapibaraZero

## Resources

**[STL](/STL/)**

**material**

- [Buttun](https://
fr.aliexpress.com
/item/32963848918.html?spm=a2g0o.order_list.order_list_main.5.22665e5b7eGzIE&gatewayAdapt=glo2fra)
- [IR module](https://
fr.aliexpress.com
/item/1005006385368806.html?spm=a2g0o.order_list.order_list_main.5.d9695e5b2jyo4A&gatewayAdapt=glo2fra)
- [ESP32-S3](https://
fr.aliexpress.com
/item/1005006418608267.html?spm=a2g0o.order_list.order_list_main.17.22665e5b7eGzIE&gatewayAdapt=glo2fra)
- [Battery LiPo 3.7V 1500mAh](https://
fr.aliexpress.com
/item/1005008347608135.html?spm=a2g0o.order_list.order_list_main.23.22665e5b7eGzIE&gatewayAdapt=glo2fra)
- [RFID PN532 + Badge](https://
fr.aliexpress.com
/item/1005007492284526.html?spm=a2g0o.order_list.order_list_main.11.d9695e5b2jyo4A&gatewayAdapt=glo2fra)
- [Screen LCD TFT IPS 1.9"](https://
fr.aliexpress.com
/item/1005007923886006.html?spm=a2g0o.order_list.order_list_main.35.22665e5b7eGzIE&gatewayAdapt=glo2fra)
- [Charge card and display battery]()
- [Wireless module SX1278/433 MHz (SX1276)](https://
fr.aliexpress.com
/item/32828673632.html?spm=a2g0o.order_list.order_list_main.47.22665e5b7eGzIE&gatewayAdapt=glo2fra)
- [Resistence 10K](https://
fr.aliexpress.com
/item/1005006427040577.html?spm=a2g0o.order_list.order_list_main.53.22665e5b7eGzIE&gatewayAdapt=glo2fra)
- [Regulator 3v3](https://
fr.aliexpress.com
/item/1005006884309456.html?spm=a2g0o.order_list.order_list_main.17.d9695e5b2jyo4A&gatewayAdapt=glo2fra)
- [SD Reader](https://
fr.aliexpress.com
/item/1000001126728.html?spm=a2g0o.order_list.order_list_main.23.35f95e5bjPqLRG&gatewayAdapt=glo2fra)

**Links**

- [Capibarazero.com - docs](https://capibarazero.com/)
- [GitHub](
https://github.com/
CapibaraZero)

python3 -m esptool --chip esp32s3 --port UPLOAD_PORT --baud 460800 --before default_reset --after hard_reset write_flash -z --flash_mode dio --flash_freq 80m --flash_size detect 0x0000 bootloader.bin 0x8000 partitions.bin 0xe000 boot_app0.bin 0x10000 firmware.bin
