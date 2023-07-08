## [10-Bit-Colors and more:](https://www.quora.com/How-is-10-bit-colour-depth-represented-in-hex-if-a-normal-6-digit-hex-code-can-supprort-only-up-to-16777216-colours-while-10-bit-colour-have-1-073-741-824-colours)


## Step 1: Calculate colors-amount by channel/color (RGB):
* for 8-bit color => 2^8 = 256 dec., to represent them in "only" 2 hex.-digits, we have a max of `FF` hex. = 255 dec.
* for 10-bit color => 2^10 = 1024 dec. = 400 hex., we need here 3 hex.-digits, but 3 full hex-digits is `FFF` = 4095 dec.
* for 12-bit color = 2^12 = 4096 dec., to represent them in "only" 3 hex.-digits, we have a max of `FFF` hex. = 4095 dec.
* for 16-bit color => 2^16 = 65536 dec. = 10000 hex., to represent them in "only" 4 hex.-digits, we have a max of `FFFF` hex. = 65535 dec.
* for 24-bit color => 2^24 = 16777216 dec. = 1000000 hex., to represent them in "only" 5 hex.-digits, we have a max of `FFFFF` hex. = 16777215 dec.
* for 32-bit color => 2^32 = ca. 4,3 G dec. = 100000000 hex., to represent them in "only" 6 hex.-digits, we have a max of `FFFFFF` hex. = ca. 4,3 G dec.


## Step 2: [Calculate colors-amount in total, all 3 channel/colors toghether:](https://www.quora.com/How-is-10-bit-colour-depth-represented-in-hex-if-a-normal-6-digit-hex-code-can-supprort-only-up-to-16777216-colours-while-10-bit-colour-have-1-073-741-824-colours)

* for 8-bit colors => 256^3 = ca. 1,68 M dec., to represent them in "only" 6 hex.-digits, we have a max of `FFFFFF` RGB-value = 16777215 dec. = `RRGGBB`
* for 10-bit colors => 1024^3 = ca. 1 G dec. = 40000000 hex., but 9 full hex.-digits (FFFFFFFFF) is to much, hence `400400400` max. RGB-value = `RRRGGGBBB`
* for 12-bit colors = 4096^3 = ca. 68,72 G dec., to represent them in "only" 9 hex.-digits, we have full 9 hex.-digits -1 = `FFFFFFFFF` RGB-value = `RRRGGGBBB`
* for 16-bit colors => 65536^3 = ca. 281 T dec., to represent them in "only" 12 hex.-digits, we have full 12 hex.-digits -1 = `Fx12` RGB-value = `Rx4,Gx4,Bx4`
* for 24-bit colors => 16777216^3 = ca. 4,7 Z dec., to represent them in "only" 15 hex.-digits, we have full 15 hex.-digits -1 = `Fx15` RGB-value = `Rx5,Gx5,Bx5`
* for 32-bit colors => ca. 4,3 G^3 = ca. 80x10^27 dec., to represent them in "only" 18 hex.-digits, we have full 18 hex.-digits -1 = `Fx18` RGB-value = `Rx6,Gx6,Bx6`


## Note-s:
* Is not recommended to see 10-bit videos, pictures, etc. on 8-bit monitors, you loss quality.
* 10-bit-videos are to test 3-D-TV/Video but also 2-D-videos are available on the Web.
* VLC don't support 10-bit, use "KMPlayer", "SMPlayer"
* 10-bit graphics can be done with "krita", "DaVinci-Resolve", "Inkscape"
* Gimp don't support 10-bit too.
* [Krita](https://docs.krita.org/en/general_concepts/colors/bit_depth.html) works with 8-16 & 32-bit coding.


## (my own) Considerations:
* The 10-bit technology is an "intermediate step" to 12-bit.
* People buying 10-bit display need "material" for playing with.
* Some works are already done in the devepolment `*.svg` (scalable vector graphic) is the magic word.
* Web- & App-developer are late even with scalable "icons", I mean you have full-HD on smart-phone by 5-7 inches and 4-8 K on 28-43 inch display.

