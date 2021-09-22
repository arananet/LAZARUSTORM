# LAZARUSTORM
External CPU adapter for A500, specially designed for Pistorm. This board distribution is based on my LAZARUS BOARD and not based on someone's else design.

# Images

<img src="https://github.com/arananet/LAZARUSTORM/blob/main/images/1.png?raw=true" width="700">

# Jumper settings
In order to use this adapter, you will need to set some jumpers. On the A500 side, there is a jumper called JP6 near the edge port that must be shorted, there are some revisions that will have this directly and others like the rev6a that must be shorted. Check the next image as a guide.

<img src="https://github.com/arananet/LAZARUSTORM/blob/main/images/rev6ajp6.png?raw=true" width="300">

Stock jumper settings for the LAZARUSTORM adapter, tested with two 68000 cpu's are: VPAJP 1-2 and BRJP open.

# PCB information

This is 4-layer board. Use your favorite pcb manufacturer to build this pcb using the gerbers available on the gerbers folder. Recommended PCB manufacturers: ALLPCB, JLCPCB and PCBWAY.

Layers order:

L1: copper_top_l1.gbr

L2 (VCC): copper_inner_l2.gbr

L3 (GND): copper_inner_l3.gbr

L4: copper_bottom_l4.gbr


PCB Thickness: 1.6mm.

# Bom

In order to build your adapter, check the bill of material:

| Part          | Value                   | Package                        |
| ------------- | ----------------------- | ------------------------------ |          
| C1       		| 100NF SMD CAPACITOR     | 0805                       |
| C2       		| 22UF SMD CAPACITOR     | 0805                       |
| R1     		| 220OHM RESISTOR          | 0805                   |
| R2      		| 1K RESISTOR            | 0805                           |

1 PCS of 86-PIN (2X43) 2.54 EDGE CONNECTOR (find them on aliexpress or ebay)

2 PCS of 1x40 male to female pins.

https://es.aliexpress.com/item/32854325182.html?spm=a2g0o.detail.1000060.2.350fada9Xv7nRh&gps-id=pcDetailBottomMoreThisSeller&scm=1007.13339.169870.0&scm_id=1007.13339.169870.0&scm-url=1007.13339.169870.0&pvid=9b1afe58-2a7a-4338-a981-ace8b2a98808&_t=gps-id:pcDetailBottomMoreThisSeller,scm-url:1007.13339.169870.0,pvid:9b1afe58-2a7a-4338-a981-ace8b2a98808,tpp_buckets:668%230%23131923%230_668%230%23131923%230_668%23888%233325%2314_668%23888%233325%2314_668%232846%238115%232000_668%235811%2327180%2341_668%232717%237567%23940_668%231000022185%231000066059%230_668%233468%2315613%23444_668%232846%238115%232000_668%235811%2327180%2341_668%232717%237567%23940_668%233164%239976%2356_668%233468%2315613%23444

# Update
22-09-2021 - Update info about jumper settings.
29-07-2021 - Initial release.

# Note

This is a work in progress, more testing needs to be done, but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board. USE AT YOUR OWN RISK!

If you like the project or want to support it, you can buy me a beer or a KO-FI :) 
[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H51MPWG)

# License

ATTENTION: This is for eBay sellers: this project was made for the retro community and not for resale on eBay. So only retro hardware forums and individual people can build this project. IT'S NOT FOR EBAY SALE.

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
