---
toc: true
toc_label: "My Table of Contents"
toc_sticky: true
toc_icon: "cog"

title: Templates
tagline: For creating your pedal art and sending to Tayda for printing..

date: 2021-03-04
last_modified_at: 2021-03-29

author_profile: true
donate: true

header:
  teaser: /assets/templates/templates.jpg
  overlay_image: /assets/templates/templates.jpg
  overlay_filter: 0.8
---

This is the place where I will put templates that I hope will help people build and produce art for their pedals. All you have to do is right lick on the links and "Save link as...".

## Knob Surrounds
<figure  style="width: 200px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/pedalgraphicitems/PedalGraphicItems.jpg"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/pedalgraphicitems/PedalGraphicItems.jpg" alt=""></a>
</figure>

This has a collection of knob surrounds with common knob sizes. You will need to resize the surround for the size of knob you are using.

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/pedalgraphicitems/PedalGraphicItems.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/pedalgraphicitems/PedalGraphicItems.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/pedalgraphicitems/PedalGraphicItems.svg)**

<br>

## Common DIY Pedal Templates

My reason for creating these templates is so that people will have an easier time creating the artwork for their pedals. I also want them to be able to do it without having to pay for Adobe Illustrator. I have been working with others on the [PedalPCB Forum](https://forum.pedalpcb.com/threads/tayda-uv-printing.4245/) to formalize using Affinity Designer and Inkscape to create the art for pedals.

### Template Layout and Use

[Affinity Designer](https://affinity.serif.com/en-us/designer/#buy) is usually $49.99 US. It is currently [March 30, 2021] on sale for $24.99 US. [Inkscape](https://inkscape.org/) is free open source vector graphics software. It's shortfalls are that is does not currently do CMYK or output to PDF. The two together work really well for creating artwork for UV printing at [Tayda Electronics](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html).

#### Layers

The SVG and Affinity Designer files consist of the following layers:

* **hardware:** This has some hardware so you can create a mockup of the completed pedal.
* **GLOSS:** This is the gloss layer you would send to Tayda. CMYK [50,25,25,0]
* **COLOR:** This is the color layer you would send to Tayda.
* **WHITE:** This is the white layer you would send to Tayda. CMYK [25,25,25,25]
* **knobs:** These are circles that are 15mm and 19mm which seem to be the most common knob sizes for this layout of controls.
* **holes:** These are the holes that you would need to drill. The outer layers are for pots the inner for switches. In the LED location they are 3mm and 5mm.
* **background:** This is just a background. I try to set it to an approximation of the enclosure color I will have so I know what it will look like when printed.
* **Drill Template:** This is drill template page that I used to create the template.

#### Usage

I have a [tutorial]({{ site.url }}{{ site.baseurl }}/tutorials/2020-12-27-angry-charles-tutorial/) on how to use the templates. Main points I may not have put in there.

* If you create in Inkscape you will need to open the SVG in Affinity to export to PDF
* Make sure the only viewable layers are WHITE, COLOR, and GLOSS.
  * I recomment always using a gloss layer to protect the artwork. Or clear coat the pedal once you get it back.
* Once you type the correct labels you will need to convert to paths.
* I have added alternate locations for the LEDs to the PedalPCB large and small templates.
* Make sure the GLOSS and WHITE layers use the corret spot colors.
* Convert all color to CMYK.

I'll add more as I realize that I forgot things.

### PedalPCB

PedalPCB has 2 main templates for most of his 125B pedals. They are a wider and a narrower version of the same thing. I call them large and small. I will work on getting templates up for the rest of his builds over time.

#### 125B Large

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/PedalPCB_Standard_Large/PedalPCB_Standard_Large.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Standard_Large/PedalPCB_Standard_Large.png" alt=""></a>
</figure>

This is the starting template I use for many [PedalPCB](https://www.pedalpcb.com) build. This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html) on a 125B enclosure. You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Standard_Large/PedalPCB_Standard_Large.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Standard_Large/PedalPCB_Standard_Large.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Standard_Large/PedalPCB_Standard_Large.svg)**

#### 125B Small

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/PedalPCB_Standard_Small/PedalPCB_Standard_Small.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Standard_Small/PedalPCB_Standard_Small.png" alt=""></a>
</figure>

This is the starting template I use for many [PedalPCB](https://www.pedalpcb.com) build. This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html) on a 125B enclosure. You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Standard_Small/PedalPCB_Standard_Small.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Standard_Small/PedalPCB_Standard_Small.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Standard_Small/PedalPCB_Standard_Small.svg)**

#### Tayda 3 Knob

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/PedalPCB_Tayda_3_Knob/PedalPCB_Tayda_3_Knob.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_3_Knob/PedalPCB_Tayda_3_Knob.png" alt=""></a>
</figure>

This is the starting template for using any of the [Tayda 3 Knob PedalPCB Enclosures](https://www.taydaelectronics.com/hardware/enclosures/drilled-enclosures-for-pedalpcb.html) build. This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html). You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_3_Knob/PedalPCB_Tayda_3_Knob.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_3_Knob/PedalPCB_Tayda_3_Knob.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_3_Knob/PedalPCB_Tayda_3_Knob.svg)**
* **[[AD]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_3_Knob/PedalPCB_Tayda_3_Knob.afdesign)**

#### Tayda 4 Knob

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/PedalPCB_Tayda_4_Knob/PedalPCB_Tayda_4_Knob.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_4_Knob/PedalPCB_Tayda_4_Knob.png" alt=""></a>
</figure>

This is the starting template for using any of the [Tayda 4 Knob PedalPCB Enclosures](https://www.taydaelectronics.com/hardware/enclosures/drilled-enclosures-for-pedalpcb.html) build. This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html). You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_4_Knob/PedalPCB_Tayda_4_Knob.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_4_Knob/PedalPCB_Tayda_4_Knob.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_4_Knob/PedalPCB_Tayda_4_Knob.svg)**
* **[[AD]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_4_Knob/PedalPCB_Tayda_4_Knob.afdesign)**

#### Tayda 5 Knob

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/PedalPCB_Tayda_5_Knob/PedalPCB_Tayda_5_Knob.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_5_Knob/PedalPCB_Tayda_5_Knob.png" alt=""></a>
</figure>

This is the starting template for using any of the [Tayda 5 Knob PedalPCB Enclosures](https://www.taydaelectronics.com/hardware/enclosures/drilled-enclosures-for-pedalpcb.html) build. This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html). You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_5_Knob/PedalPCB_Tayda_5_Knob.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_5_Knob/PedalPCB_Tayda_5_Knob.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_5_Knob/PedalPCB_Tayda_5_Knob.svg)**
* **[[AD]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_5_Knob/PedalPCB_Tayda_5_Knob.afdesign)**

#### Tayda 6 Knob

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/PedalPCB_Tayda_6_Knob/PedalPCB_Tayda_6_Knob.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_6_Knob/PedalPCB_Tayda_6_Knob.png" alt=""></a>
</figure>

This is the starting template for using any of the [Tayda 6 Knob PedalPCB Enclosures](https://www.taydaelectronics.com/hardware/enclosures/drilled-enclosures-for-pedalpcb.html) build. This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html). You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_6_Knob/PedalPCB_Tayda_6_Knob.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_6_Knob/PedalPCB_Tayda_6_Knob.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_6_Knob/PedalPCB_Tayda_6_Knob.svg)**
* **[[AD]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Tayda_6_Knob/PedalPCB_Tayda_6_Knob.afdesign)**

#### Derailer

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/PedalPCB_Derailer/PedalPCB_Derailer.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Derailer/PedalPCB_Derailer.png" alt=""></a>
</figure>

This is the starting template for the [PedalPCB Derailer](https://www.pedalpcb.com/product/derailer/) build. This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html). You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Derailer/PedalPCB_Derailer.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Derailer/PedalPCB_Derailer.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Derailer/PedalPCB_Derailer.svg)**
* **[[AD]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Derailer/PedalPCB_Derailer.afdesign)**

#### Hydra

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/PedalPCB_Hydra/PedalPCB_Hydra.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Hydra/PedalPCB_Hydra.png" alt=""></a>
</figure>

This is the starting template for the [PedalPCB Derailer](https://www.pedalpcb.com/product/hydradelay//) build. This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html). You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Hydra/PedalPCB_Hydra.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Hydra/PedalPCB_Hydra.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Hydra/PedalPCB_Hydra.svg)**
* **[[AD]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Hydra/PedalPCB_Hydra.afdesign)**

#### Parentheses

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/PedalPCB_Parentheses/PedalPCB_Parentheses.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Parentheses/PedalPCB_Parentheses.png" alt=""></a>
</figure>

This is the starting template for the [PedalPCB Derailer](https://www.pedalpcb.com/product/parentheses-fuzz//) build. This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html). You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Parentheses/PedalPCB_Parentheses.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Parentheses/PedalPCB_Parentheses.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Parentheses/PedalPCB_Parentheses.svg)**
* **[[AD]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Parentheses/PedalPCB_Parentheses.afdesign)**

#### Parthenon

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/PedalPCB_Parthenon/PedalPCB_Parthenon.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Parthenon/PedalPCB_Parthenon.png" alt=""></a>
</figure>

This is the starting template for the [PedalPCB Parthenon](https://www.pedalpcb.com/product/parthenon/) build. This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html). You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Parthenon/PedalPCB_Parthenon.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Parthenon/PedalPCB_Parthenon.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Parthenon/PedalPCB_Parthenon.svg)**
* **[[AD]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Parthenon/PedalPCB_Parthenon.afdesign)**

#### Pineapple

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/PedalPCB_Pineapple/PedalPCB_Pineapple.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Pineapple/PedalPCB_Pineapple.png" alt=""></a>
</figure>

This is the starting template for the [PedalPCB Pineapple](https://www.pedalpcb.com/product/pineapple//) build. This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html). You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Pineapple/PedalPCB_Pineapple.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Pineapple/PedalPCB_Pineapple.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Pineapple/PedalPCB_Pineapple.svg)**
* **[[AD]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Pineapple/PedalPCB_Pineapple.afdesign)**

#### Terrarium

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/PedalPCB_Terrarium/PedalPCB_Terrarium.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Terrarium/PedalPCB_Terrarium.png" alt=""></a>
</figure>

This is the starting template for the [PedalPCB Terrarium](https://www.pedalpcb.com/product/pcb351//) build. This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html). You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Terrarium/PedalPCB_Terrarium.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Terrarium/PedalPCB_Terrarium.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Terrarium/PedalPCB_Terrarium.svg)**
* **[[AD]]({{ site.url }}{{ site.baseurl }}/assets/templates/PedalPCB_Terrarium/PedalPCB_Terrarium.afdesign)**

### Madbean Pedals

#### VFE Pedals

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/templates/VFE_125B_Standard/VFE_125B_Standard.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/templates/VFE_125B_Standard/VFE_125B_Standard.png" alt=""></a>
</figure>

This is the starting template I use for my VFE builds from [Madbean Pedals](https://www.madbeanpedals.com/projects/index.html). This includes the WHITE, COLOR and GLOSS layers for [Tayda UV Printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html) on a 125B enclosure. You will need to remove the other layers before sending it to them.

Remember to right click and "Save link as..."

* **[[ZIP]]({{ site.url }}{{ site.baseurl }}/assets/templates/VFE_125B_Standard/VFE_125B_Standard.zip)**
* **[[PDF]]({{ site.url }}{{ site.baseurl }}/assets/templates/VFE_125B_Standard/VFE_125B_Standard.pdf)**
* **[[SVG]]({{ site.url }}{{ site.baseurl }}/assets/templates/VFE_125B_Standard/VFE_125B_Standard.svg)**
* **[[AD]]({{ site.url }}{{ site.baseurl }}/assets/templates/VFE_125B_Standard/VFE_125B_Standard.afdesign)**

