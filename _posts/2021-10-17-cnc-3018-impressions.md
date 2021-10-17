---
layout: post
title: "CNC 3018 (Pro) First Impressions"
date:   2021-10-17 19:30:00 +0100
categories: [CNC]
image: /images/2021-10-17-IMG_4914.jpg
---

Since starting with 3D printing a few months ago, I've been interested in exploring hobbyist CNC machines and ended up ordering one.

## Background
I started reading around and searching various online marketplaces and kept coming across the CNC 3018 specification. CNC 3018 refers to the 300x180mm bed size and these machines have no set manufacturer or even design.

Despite this, they generally share similar parts and construction of aluminium extrusions and bakelite plastic. I chose to buy my CNC machine from [AliExpress](https://www.aliexpress.com/item/4000577587076.html) and it arrived in a week.

## Construction
To my surprise, the machine came completely unassembled and was just a box of parts. Fortunately, using the included instructions it took under two hours to go from this to a fully assembled machine. I haven't included any build steps in this post as there are plenty of amazing guides online already.

### Before
![CNC Machine Parts](/images/2021-10-17-IMG_4910.jpg)

### After
![CNC Machine](/images/2021-10-17-IMG_4919.jpg)

## End Mills
My CNC 3018 came with 10x 60° V bits, which are mainly intended for engraving. As I was intending to do more milling than engraving, I chose to switch these out for some more traditional [flat-ended tools](https://www.amazon.co.uk/gp/product/B08X2BN3V1). These machines typically use a 3.175mm (1/8 inch) ER11 collet and replacement end mills are readily available.

Although sets of these bits are available cheaply, it may be most cost effective to invest in higher quality end mills of the sizes you require. I chose to use the 1/16 inch bit predominately, due to it being a good compromise between speed and quality.

## Design
After completing the build, I started looking into design software to start testing the CNC. I eventually settled on [Easel](https://www.inventables.com/technologies/easel), a cloud-based offering from Inventables.

I designed a small sign with varying cut depths, from light engraving to a full cut through the 10mm pine (any wood could be used but I bought some cheap floorboards from the local DIY shop).

![Easel CAD Software](/images/2021-10-17-Easel.png)


## Testing
Although Easel supports carving directly, this requires the Pro plan, so I exported my design as gcode. I then used [candle](https://github.com/Denvi/Candle) to move the spindle to the XYZ0 position and run the job.

Aside from some light sanding, the sign came out perfectly on the first attempt. Coming from 3D printing with its endless calibrations and levelling, this is especially refreshing.

![CNC Product](/images/2021-10-17-IMG_5178.jpg)

I tried this simple design style a couple of times. In this second example it's clear that the 1/16 inch bit was too big!

![CNC Product 2](/images/2021-10-17-c89a37d5c.jpg)


## Conclusion
For the low price these machines sell for, they offer incredible value for money. Once you get past the assembly stage, the CNC is easy to operate and maintain. Saying this, certain features such as endstops and network connectivity are lacking, but I'll be addressing these shortfalls in future articles.