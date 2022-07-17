---
title: beige-g3-atx-psu-upgrade
date: 2022-07-16T20:32:28-0400
---

Following [this guide](https://forums.macrumors.com/threads/atx-psu-conversion-powermac-g3.1739059/)
I was able to upgrade the loud stock PSU on a Beige Powermac G3 Desktop to a (more) modern
ATX replacement.  Nice and _quiet_.

The tricky thing about the design and orientation of the old PSU within the case is that the
plug socket and fan location is flipped from what you'll find on most readily-available PSUs nowadays.
After some digging I was able to find the [EVGA Supernova 450GM](https://www.evga.com/products/product.aspx?pn=123-GM-0450-Y1)
which ticks all the boxes.  Plug socket fits the cutaway in the rear of the case and the fan
faces downwards towards the motherboard.

![PSU Close Up](https://otosky-notes.s3.us-east-2.amazonaws.com/assets/images/beige_g3_psu_close.jpg)
![Fan on bottom side of PSU](https://otosky-notes.s3.us-east-2.amazonaws.com/assets/images/beige_g3_psu_fan_placement.jpg)
![Case rear cutaway still fits power cord receptacle](https://otosky-notes.s3.us-east-2.amazonaws.com/assets/images/beige_g3_psu_rear_cutaway.jpg)

Note to self when making these repairs: some of the solder joints on these 25 year old machines
will go bad or get loose with ANY sort of flex on the PCB.  I had to reflow all the connections
on the motherboard for the PSU header before the machine would turn on and chime reliably.

![Final top down picture of G3 with PSU installed](https://otosky-notes.s3.us-east-2.amazonaws.com/assets/images/beige_g3_psu.jpg)
