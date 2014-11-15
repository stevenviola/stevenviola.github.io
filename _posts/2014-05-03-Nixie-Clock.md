---
layout: post
title: Nixie Clock
---
Completed building a nixie clock with my IN-14 tubes from [a kit](http://www.pvelectronics.co.uk/index.php?main_page=product_info&cPath=21&products_id=79)

One of my tubes was broken (I think the leads were corroded) but still looks good

<iframe width="560" height="315" src="//www.youtube.com/embed/b-54xTTS4fw" frameborder="0" allowfullscreen></iframe>

I replaced the bad tube and now have all 6 digits working. The outcome is looking really great

<iframe width="560" height="315" src="//www.youtube.com/embed/mZ4I35A0rzw" frameborder="0" allowfullscreen></iframe>

I had started to collect Nixie Tubes in 2007 and always wanted to build my own Nixie Clock. I started by getting a [Nixie Clock Controller Chip](http://www.allspectrum.com/store/digit-nixie-tube-clock-controller-chip-p-352.html) but I the chip had some issues initially. I had an error with the hour tens digit. It appeared the pin B (39) and C (40) both output the wrong output. Pin 39 did not output any logic level other than low and pin 40 outputs the inverse of what it should be. I hooked it up to an oscilloscope and had the chip output 0-9. Looking at the output from the scope verified what I was seeing.

({{ site.baseurl }}/images/2014/05/03/nixie_output.jpg)

I was able to return the chip and it turned out both pins 39 and 40 were not functioning properly, and pin 38 appeared to be leaking current and was not functioning perfectly either. I got a replacement chip which worked as expected. Wiring it up was a bit of a mess on the breadboard but after a lot of wiring, it started to come together.

({{ site.baseurl }}/images/2014/05/03/nixie_top.jpg)

When cleaning up some of the wires, it was looking pretty good, although it became apparent using 74141 chip connected to the microprocessor was more complicated and required more wiring, even when laid out on a PCB

({{ site.baseurl }}/images/2014/05/03/nixie_front.jpg)

Overall, I'm really happy with the Nixie Tube kit, and am looking forward to making more clocks in the future 
