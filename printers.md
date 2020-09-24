# Tested Printers
Please add here printer models you have used with this library and any comments (works / something goes wrong).

This will help to maintain and improve this library and to choose the right printer.

Thank you for your contribution!

## Bluetooth Printers List
| Model | Paper | Library Ver. | Comments |
|---|---|---|---|
| [MUNBYN IMP034-BK](https://images-na.ssl-images-amazon.com/images/I/514cEfTx%2BtL._SL1000_.jpg) | 58mm | 0.1.1 | No issues (Android, iOS) |
| ER-80 |  | 0.1.1 | [No issues](https://github.com/andrey-ushakov/esc_pos_bluetooth/issues/1#issuecomment-597723277) |
| [Seiko RP-D10](https://www.sii.co.jp/sps/eg/product/unit/rpd_series.html) | | | [Printer not listed during scan](https://github.com/andrey-ushakov/esc_pos_printer/issues/48) |
|POS-5802DD (Kkmoon)|58mm|0.2.2|`PosImageFn.bitImageRaster`: align left only ;<br> `PosImageFn.graphics`: doesn't work ;<br> `Ticket.image`: works ;<br> everything else works (Tested on iOS) |
| MHT-P8001, MHT-P26, Jepod JP-81LYA ([#1](https://github.com/andrey-ushakov/esc_pos_bluetooth/issues/1#issuecomment-597723277)) |80mm|0.2.2|All 3 image printing methods doens't work ; <br>bold text: No ; <br>westEur code page: No (Tested on iOS) |
| [NBP4](https://ncts.co/product/ncts-thermal-recipt-printers/) | 79.5± 0.5mm  | 0.2.8 | D/BluetoothLeScanner(24091): could not find callback wrapper;
W/System.err(24091): java.io.IOException: bt socket closed, read return: -1;
E/BluetoothPort(24091): connection device is lost;
W/BluetoothAdapter(24091): getBluetoothService() called with no BluetoothManagerCallback;
I/flutter (24091): Error. Printer connection timeout; (Tested on Android, Soon IOS) |
