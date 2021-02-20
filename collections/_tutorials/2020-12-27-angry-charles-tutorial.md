---
toc: true
toc_label: "My Table of Contents"
toc_icon: "cog"
title: Creating a PDF for Tayda UV Printing
header:
    teaser: /assets/images/2020-12-27-angry-charles-tutorial/Complete_graphics.jpg
excerpt: I go over using the opensource Inkscape and the $49.99 US Affinity Designer to create PDF for UV printing at Tayda Electronics.
---

# Tayda UV Printing #

**Warning:** I have not gotten this to work exporting from Affinity Designer with multiple layers. I have successfully printed the enclosure for the [Purple](/pedals/2020-12-24-074/) which only has a color layer on a white background. I cannot get it either use the Roland swatches or export the WHITE and GLOSS layers. As of Febuary 19, 2021 I have received information from Hugo that the Affinity exported files wouldn't work with the added features. I have downloaded the free trial if Illustrator and have worked from the SVG created in Inkscape and have resubmitted the files. I will keep you posted. 
{: .notice--danger}

## Intro ##

If you are like me, this is a hobby. As such I want to spend as much money as I can on parts and not on software. Because of this I do not want to invest in **Abobe Illistrator** ($59 a month US) but I would still like to get the professional look of UV printing. With help from the members on PedalPCB's forum I have come up with this less expensive approach.

I have been using [Inkscape](https://inkscape.org/release/inkscape-1.0.1/) to create my graphics and make [templates](/assets/resources/PedalPCB_6_Knob_Type_1_Clean.svg) for pedals. I then get them prepared and ready to print using [Affinity Designer](https://affinity.serif.com/en-us/designer/) which as of this writing is $49.99 US for a perpetual license.

## The Template ##

![Template](/assets/images/2020-12-27-angry-charles-tutorial/ALL_Drill_Guide.jpg)

I have created templates for each of PedalsPCB's main pedal formats. For this one I am using the 6 knob type 1 template. This is the wider spacing of the 2 knobs. The font I used is Eurostile-Bold. I believe I read on the diystompboxes forum that it was the font used by MXR and I am a fan. Lets go over the layers.

### Tayda-125B-Template ###

![Tayda-125B-Template](/assets/images/2020-12-27-angry-charles-tutorial/Tayda-125B-Template.jpg)

This layer is where I imported the drill guide form the PDF to ensure that I aligned all the elements correctly. I am using the file sizes from the [Tayda UV printing](https://www.taydaelectronics.com/hardware/enclosures/enclosure-uv-printing-service.html) page.  

**Info:** This layer is not included in the final export. 
{: .notice--info}

### Enclosure ###

![Enclosure](/assets/images/2020-12-27-angry-charles-tutorial/Enclosure.jpg)

I have a rectangle that is the size of the enclosure on this level. I fill it with the *color* of the enclosure that i want to print on. This enables me to see what the finished enclosure might look like. 

**Info:** This layer is not included in the final export. 
{: .notice--info}

### Hole Sizes ###

![Hole Sizes](/assets/images/2020-12-27-angry-charles-tutorial/Hole_Sizes.jpg)

I use this layer as a guide to show me how big the holes will be once I drill. I have two options for where to place my LED. The LED holes are without bevels. Just 3mm and 5mm holes.  

**Info:** This layer is not included in the final export. 
{: .notice--info}

### Knob Placement ###

![Knob Placement](/assets/images/2020-12-27-angry-charles-tutorial/Knob_Placement.jpg)

I created this layer to get an idea of how much space is taken up by the knobs. I wanted to make sure that the labels and graphics would look good with the knob sizes chosen. Here I have included 19mm ann 15mm knob outlines as a guide. 

**Info:** This layer is not included in the final export. 
{: .notice--info}

### COLOR ###

![COLOR](/assets/images/2020-12-27-angry-charles-tutorial/COLOR.jpg)

### WHITE, GLOSS-M, GLOSS-V, EMBOSS ###

These layers are left blank. From what I can tell the white layer will be printed first, then color, then the over layers (EMBOSS or either GLOSS layer). The over and under layers work like the color layer but they only have a single color. In Inkscape this can be any color as we will have to change the color to the roland swatch in Affinity Designer.

# Step by Step Guide #

So how do I use this template. Well I will go over create the pdf file for a pedal. I am not going to go over how to create the art. I will save that for another lengthy tutorial. For this demonstration I will be creating the UV print file for the [PedalPCB Angry Charles](https://www.pedalpcb.com/product/angrycharles/).

## 1. Create your SVG File ##

### Open the Template ###

![ALL](/assets/images/2020-12-27-angry-charles-tutorial/ALL.jpg)

I start with opening the template and making sure that I can see all the layers that importand to me. Here I have the `Enclosure`, `Hole Sizes`, `Knob Placement`, and `COLOR` layers visible. I also change the template color to the powder color of the enclosure I will be purchasing.

### Remove Elements ###

![ALL_Remove_Elements](/assets/images/2020-12-27-angry-charles-tutorial/ALL_Remove_Elements.jpg)

I then remove any elements that will not be a part of the final pedal. Here I removed the upper middle knob and label and replaced it with the LED.

### Update Labels ###

![ALL_Update_Labels](/assets/images/2020-12-27-angry-charles-tutorial/ALL_Update_Labels.jpg)

I then need to update all the labels while they are still text. I can rename them, change the font and font size, and reposition them.

### Text to Paths ###

At his point I will need to change all the text objects to Paths. 

![ALL_text_objects](/assets/images/2020-12-27-angry-charles-tutorial/ALL_text_objects.jpg)

When they are selected you can see that they are of type `Text`.

![ALL_text_objects_2](/assets/images/2020-12-27-angry-charles-tutorial/ALL_text_objects_2.jpg)

We will then choose `Path > Object to Path`.  

![ALL_text_objects_3](/assets/images/2020-12-27-angry-charles-tutorial/ALL_text_objects_3.jpg)

This converts the `Text` objects to `Group` objects containing the path for each letter.

### Add Graphics ###

![Complete_graphics](/assets/images/2020-12-27-angry-charles-tutorial/Complete_graphics.jpg)

At this point you are able to create and position your graphics for the pedal. 

Here I just blatantly ripped off the design by JHS. **_I would advise doing something original_** but this was the easiest for me to produce for the demonstration.
{: .notice--warning}

As you can see I only use the `COLOR` layer at this point.

### Duplicate to WHITE and EMBOSS-M Layers ###

![duplicate_1](/assets/images/2020-12-27-angry-charles-tutorial/duplicate_1.jpg)

Select everything on the color layer and `right-click > Duplicate` or `CTRL + d` to duplicate all items.

![duplicate_2](/assets/images/2020-12-27-angry-charles-tutorial/duplicate_2.jpg)

Then `right-click > Move to Layer...`. You should not have to select again as the duplicates should be selected.

![duplicate_3](/assets/images/2020-12-27-angry-charles-tutorial/duplicate_3.jpg)

Choose layer `WHITE`. This will make everything that was selected in your `COLOR` layer now be in the `WHITE` layer as well. This is important when you are printing on a colored enclosure to ensure that your art shows up, or it you can to print white. Do not put white items in the `COLOR` layer.

I repeat step `1f` for the overlayer that I want as well. Only duplicate and move the items that you want in gloss or embossed.
{: .notice--info}

### Save ###

**Save your SVG file NOW** and throughout. If you are anything like me you may crash or freeze `Inkscape`. I try to save after every action. 
{: .notice--warning}

I try to have only the `WHITE`, `COLOR`, and `GLOSS-M` (`GLOSS-V`,`EMBOSS`) layers visible when saving. 

## 2. Create PDF for Tayda ##

### OPEN in Affinity Designer ###

![affinity_open](/assets/images/2020-12-27-angry-charles-tutorial/affinity_open.jpg)

Open the saved SVG file in Affinity Designer.

#### Rolad Swatches ####

Make sure that you have the Roland swatches imported into Affinity Designer. You can download them [here](/assets/resources/Roland%20VersaWorks.ase).

**Note:** Danbieranowski on the PedalPCB Forum put up a [post](https://forum.pedalpcb.com/threads/tayda-uv-printing-roland-swatches-for-affinity.5699/) on how to [import the Roland swatch into Affinity Designer](https://support.retrosupply.co/article/100-how-to-import-an-affinity-swatch-palette#:~:text=Open%20Affinity%20Designer%20or%20Affinity,and%20toggle%20to%20Import%20Palette).
{: .notice--info}

### Update WHITE Layer ###

![affinity_RDG_White](/assets/images/2020-12-27-angry-charles-tutorial/affinity_RDG_White.jpg)

In the `WHITE` layer you will want to select everything and change the color to `RDG_WHITE`. Be sure to watch your fill and stroke. You will not want to create fills or strokes that weren't originally there.

### Update GLOSS-M Layer ###

![Affinity_Gloss_Fill](/assets/images/2020-12-27-angry-charles-tutorial/Affinity_Gloss_Fill.jpg)

You will repeat this process with the GLOSS or EMBOSS layers. Use the color `RDG_GLOSS` for any of the over layers.

### Export to PDF ###

![Affinity_Export_Explained](/assets/images/2020-12-27-angry-charles-tutorial/Affinity_Export_Explained.jpg)

You are now ready to export your PDF file. In the menu bar go to `File > Export ...`. This will oprn the export dialog box. Make sure you choose PDF. Set your DPI (I chose 600 here but it is **unverified** I know 400 DPI works) and make sure the `Don't export layers hidden by Export Persona` is checked. Click the `Export` button.

### Check PDF ###

You will want to make sure that it exported properly. I am in the process of verifying multiple layers. Currently I know this works for the color layer. I open the PDF file in adobe and in affinity to ensure that the 3 layers are there.

![Affinity_exported_pdf](/assets/images/2020-12-27-angry-charles-tutorial/Affinity_exported_pdf.jpg)

![affinity_pdf_open](/assets/images/2020-12-27-angry-charles-tutorial/affinity_pdf_open.jpg)

![affinity_pdf_opened_detail](/assets/images/2020-12-27-angry-charles-tutorial/affinity_pdf_opened_detail.jpg)

I hope this works for anyone that tried it. Let me know how it goes. You can contact me at pandemicpedals@gmail.com.
