# pi-kit
Turn a RaspberryPi 3 B into an Apple HomeKit bridge in order to control RF controlled outlets with Siri.

# Required Materials
<a target="_blank" href="https://www.amazon.com/gp/product/B01CD5VC92/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B01CD5VC92&linkCode=as2&tag=camero013-20&linkId=d57cc185cf9f41625bcf6976d1feb794">Raspberry Pi 3 Model B</a><img src="//ir-na.amazon-adsystem.com/e/ir?t=camero013-20&l=am2&o=1&a=B01CD5VC92" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> - $35.70<br>
<a target="_blank" href="https://www.amazon.com/gp/product/B00DQ2KGNK/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B00DQ2KGNK&linkCode=as2&tag=camero013-20&linkId=f1f978482acbe54ded5dbf80542d48ce">3X RF Controlled Outlets</a><img src="//ir-na.amazon-adsystem.com/e/ir?t=camero013-20&l=am2&o=1&a=B00DQ2KGNK" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> - $19.98 <br>
<a target="_blank" href="https://www.amazon.com/gp/product/B00RFQ11PU/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B00RFQ11PU&linkCode=as2&tag=camero013-20&linkId=9b63367d8ed1b09b9e08e2e5a224063f">RF Transmitter &amp; Receiver Kit</a><img src="//ir-na.amazon-adsystem.com/e/ir?t=camero013-20&l=am2&o=1&a=B00RFQ11PU" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> - $7.91 <br>
<a target="_blank" href="https://www.amazon.com/gp/product/B01GZKOJN2/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B01GZKOJN2&linkCode=as2&tag=camero013-20&linkId=756cff1b2bb2337b673cde28767e642a">Breadboard + Mounting Plate</a><img src="//ir-na.amazon-adsystem.com/e/ir?t=camero013-20&l=am2&o=1&a=B01GZKOJN2" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> - $10.99 <br>
<a target="_blank" href="https://www.amazon.com/gp/product/B008MRZSH8/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B008MRZSH8&linkCode=as2&tag=camero013-20&linkId=5de1ad8851f4482fc38f0d12f5c10df4">Jumper Wires 20cm M/F </a><img src="//ir-na.amazon-adsystem.com/e/ir?t=camero013-20&l=am2&o=1&a=B008MRZSH8" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> - $5.86 <br>
<a target="_blank" href="https://www.amazon.com/gp/product/B004ZIENBA/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B004ZIENBA&linkCode=as2&tag=camero013-20&linkId=482b7a072e66f47d0a7bd9cd046e467c">16GB MicroSD Card + Adapter</a><img src="//ir-na.amazon-adsystem.com/e/ir?t=camero013-20&l=am2&o=1&a=B004ZIENBA" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> - $5.95 <br>
<a target="_blank" href="https://www.amazon.com/gp/product/B01IHU0CEI/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B01IHU0CEI&linkCode=as2&tag=camero013-20&linkId=0f4a3da314c16c300d3213133174b8ef">Micro USB Cable + Wall Adapter</a><img src="//ir-na.amazon-adsystem.com/e/ir?t=camero013-20&l=am2&o=1&a=B01IHU0CEI" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> - $6.99<br>
FREE Borrow a USB Keyboard/Mouse and an HDMI Monitor from a friend or another computer.
FREE Whatever Dumb thing you want to be smart! <br>

# Step 1: Set-Up your Pi
Many of the guides I have found on this subject assume you are a native to RasperryPi and know how to get everything set-up. However, I will not assume that here, and will walk you through the general set-up of a RaspberryPi - so let's get started. <br>
<ul>
  <li>Download the lastest version of the NOOB installer from <a href="http://downloads.raspberrypi.org/NOOBS_latest">here</a></li>
  <li>Insert your microSD card into it's adapter, and insert the whole thing into the SD card reader on your computer. Open up Disk Utility (on Mac) or similar software on Windows. Click to erase and format the disk - select the option FAT.</li>
  <li>Unzip and copy all the files from the NOOB download onto your SD card. Once finished, eject the SD card from your computer - now we are ready to get started on the Pi.</li>
  <li>Remove the microSD card from it's adapter and insert it into the Pi. Now, plug in your USB Keyboard/Mouse, HDMI monitor and the Pi's power cord - it should boot into the installer! Select Raspbian and click install.</li>
</ul>
