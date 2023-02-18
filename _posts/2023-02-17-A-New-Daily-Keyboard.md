---
layout: post
title:  “A New Daily Keyboard? The Crowboard”
date:   2023-02-17 23:18:00 -0800
tags: keyboards
---

I recently built a the Crowboard, from Keyboard Dweebs and it may be my new favorite board.

![ An image of a split unibody keyboard with low profile purple keycaps.]({{ site.baseurl | prepend: site.url }}/images/IMG_2730.png)

The Crowboard is a split unibody keyboard, controlled by the Raspberry Pie Nano. I elected to build mine with Kailh Choc Pro Red switches and MBK legend keycaps.

As a daily corne user, who has become accustomed to the wider arm spacing of a true split keyboard, I was initially skeptical of the unibody design. However the unibody design drew me in as it seemed it might make for a convenient travel board. I was also looking for a board that could be built as a bare PCB as I’ve come to enjoy cáseles low profile keyboards. When I stumbled across the Crowboard at a reasonable price, it checked al of my boxes and I decided it was worth a trial.

The board is fairly simple to construct. 36 diodes, 36 switches and the Pi nano all need to be soldered on. However, the surface mount diodes that were included in my kit are quite small and proved to very frustrating to solder. If I could do it again I would have purchased through hole diodes, which this board can accommodate.

The Pi Nano came pre-flashed with Vial and can be configured through the desktop Vial client or via the Web. I heavily modified the default key map to make use of home row modifiers, a raise layer that includes all of the symbol I use for programming, an arrow cluster, and escape, enter, delete and tab all on the home row.

After a couple days, I’ve found the board quite pleasing to type on. The 35g Choc Pro Reds are some of my favorite switches, and while I might prefer a wider stance, the angle of the alpha keys keeps my wrist mostly comfortable. In particular, I love the spacing between the alpha keys and the thumb clusters. The spacing on my corne is much tighter and I find that my thumbs feel more tense, and when using the inner keys, my thumbs and pointer finger can collide. The extra space provided by the Crowboard has largely alleviated this and my thumbs are much happier.

My primary complaint would be that I’m not sold on the Pi Nano as an MCU. I’m not sure that I see anything that the Pi does significantly better than a pro micro and utilizing the pro micro form factor would allow the option of using the nice!nano for wireless builds, not to mention the ease of finding pro micro equivalents with USB-C.

All in all, I’m quite happy with this board. The price is very reasonable and I’ll likely use it as my main keyboard for the time being, but I will be looking for a similar design that supports a wireless chipset in the near future.  