---
toc: true
toc_label: "My Table of Contents"
toc_sticky: true
toc_icon: "cog"

title: Create a 3PDT Breakout PCB for Manufacture
tagline: The next step in pedal building is creating your own boards,

date: 2021-07-02
last_modified_at: 2021-07-02

author_profile: true
donate: true

header:
  teaser: /assets/images/tutorial/3pdt/banner.png
  overlay_image: /assets/images/tutorial/3pdt/banner.png
  overlay_filter: 0.8

schematic:
  - url: /assets/images/tutorial/3pdt/01.png
    image_path: /assets/images/tutorial/3pdt/01.png
    alt: "create project"
    title: "Create Project"
  - url: /assets/images/tutorial/3pdt/02.png
    image_path: /assets/images/tutorial/3pdt/02.png
    alt: "create scheamtic"
    title: "Create Schematic"
  - url: /assets/images/tutorial/3pdt/03.png
    image_path: /assets/images/tutorial/3pdt/03.png
    alt: "choose switch"
    title: "Choose Switch"

board:
  - url: /assets/images/tutorial/3pdt/06.png
    image_path: /assets/images/tutorial/3pdt/06.png
    alt: "create board"
    title: "Board Created"
  - url: /assets/images/tutorial/3pdt/07.png
    image_path: /assets/images/tutorial/3pdt/07.png
    alt: "layout"
    title: "Board Layout"
  - url: /assets/images/tutorial/3pdt/08.png
    image_path: /assets/images/tutorial/3pdt/08.png
    alt: "Ratsnest"
    title: "Ratsnest"

panel:
  - url: /assets/images/tutorial/3pdt/12.png
    image_path: /assets/images/tutorial/3pdt/12.png
    alt: "panel board"
    title: "Panel Board"
  - url: /assets/images/tutorial/3pdt/13.png
    image_path: /assets/images/tutorial/3pdt/13.png
    alt: "panel ratsnest"
    title: "Panel Ratsnest"
  - url: /assets/images/tutorial/3pdt/14.png
    image_path: /assets/images/tutorial/3pdt/14.png
    alt: "cam profile"
    title: "choose cam profile"

cam:
  - url: /assets/images/tutorial/3pdt/15.png
    image_path: /assets/images/tutorial/3pdt/15.png
    alt: "cuts and dimensions"
    title: "Dimensions and Vcuts"
  - url: /assets/images/tutorial/3pdt/16.png
    image_path: /assets/images/tutorial/3pdt/16.png
    alt: "top copper"
    title: "Top Copper"
  - url: /assets/images/tutorial/3pdt/17.png
    image_path: /assets/images/tutorial/3pdt/17.png
    alt: "bottom copper"
    title: "Bottom Copper"

jlcpcb:
  - url: /assets/images/tutorial/3pdt/jlcpcb.png
    image_path: /assets/images/tutorial/3pdt/jlcpcb.png
    alt: "jlcpcb order page"
    title: "JLCPCB Order Page"
  - url: /assets/images/tutorial/3pdt/jlcpcb2.png
    image_path: /assets/images/tutorial/3pdt/jlcpcb2.png
    alt: "jlcpcb options"
    title: "JLCPCB Options"
  - url: /assets/images/tutorial/3pdt/jlcpcb3.png
    image_path: /assets/images/tutorial/3pdt/jlcpcb3.png
    alt: "jlcpcb price"
    title: "JLCPCB Price"
---

So I have been building pedals for a little over a year. In that time I have always hand wired my switches unless the breakout boards were supplied with the circuit.

I felt it was time to take the next step and create my own PCBs. I have breadboarded a few circuits and I want to put a few into production. As a test I created my own breakout board for the 3PDT. I usually see them for $1 a board. So I did a little digging around, found some [information on panelizing](https://maker.pro/pcb/tutorial/how-to-panelize-your-pcbs-in-eagle-using-v-grooves) your layouts using a [Sparkfun ULP for panelization](https://github.com/sparkfun/SparkFun_Eagle_Settings/blob/master/ulp/SparkFun-Panelizer.ulp) and got to work.

## Setup

The links above are to an article I found on panelizing. Use that tutorial to setup Eagle so that you can panelize your circuits. You should also go to the JLCPCB  article on installing the [CAM settings](https://support.jlcpcb.com/article/137-how-to-generate-gerber-and-drill-files-in-autodesk-eagle) for them in Eagle as well.

The rest of the article is based on thiese already being done.

## Create Schematic

{% include gallery id="schematic" %}

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/04.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/04.png" alt=""></a>
</figure>

The first thing you want to do is create a project in Eagle and create a schematic. I chose the 3PDT stomp under switches because it has the large circular holes. I also used square pads for all the pads here so that I had more metal surface to solder to. The boards I show later use the round pads.

## Create Board

{% include gallery id="board" %}

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/05.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/05.png" alt=""></a>
</figure>

I create my board by first clicking on the green and gray "SCH/BRD" button to auto create the board. I then layout the parts. I use 12mil for my airwires. I also use the pentagon to create my ratsnest. I put all my traces on the bottom of the board. This one can be done on a single layer. Also you can delete the yellow board outline and create your own on the dimension layer.

<figure  class="align-center">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/09.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/09.png" alt=""></a>
</figure>

## Panelizing

Once you have the board you would like to panelize you will need to:

1. close the schematic
2. select the entire board
3. copy it
4. click on the ULP button

<figure  style="width: 220px" class="align-left">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/09.5.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/09.5.png" alt=""></a>
</figure>

At this point the ULP dialog will pop up. You will need to hit the browse button and choose the Sparkfun Panelizer ULP that you installed earlier. This will allow all your panels to have the same label names for components. It also tiles your layout on the panel.

<figure  style="width: 120px" class="align-right">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/10.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/10.png" alt=""></a>
</figure>
<figure  style="width: 120px" class="align-right">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/11.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/11.png" alt=""></a>
</figure>

For JLCPCB the settings are:

* must be smaller than 100mm X 100mm [3.937X3.937 inches]
* gaps are 0.4mm X 0.4mm [0.01575 X 0.01575 inches], this leave space for the vcuts
* check ad V-score Lines and Text and Top Stencil
* Hit generate and click through diolog boxes.

{% include gallery id="panel" %}

Once the paneling is done you will need to rerun the ratsnest to get your ground plain. This is important or your board will not work correctly. I had this problem with the first one I did.

## CAM Processor

{% include gallery id="cam" %}

<figure  class="align-center">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/18.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/18.png" alt=""></a>
</figure>

When you open the cam processor you will want to make sure each level has what you want on it.Make sure you add the correct layers to the silkscreen top. I sometimes have to check this several times. Here the panelizer put the correct labels on 125 _tNames and I put the "Pandemic Pedals" on 51 tDocu. 

When you are satisfied click on "Process Job" and save the resulting zip file.

This is the directory and all files created in this process.

<figure  class="align-center">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/19.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/19.png" alt=""></a>
</figure>

## JLCPCB

The JLCPCB price for panel by customer for 5, 100mm by 100mm boards is $8 us. This design gets 20 boards per panel. I also make sure that I do the surface finish of LeadFree HASL-RoHS. And I have the confirm the production file. The total with shipping is 12.94 and takes about 2 - 3 weeks to arrive. You can get it much quicker if you want to pay $5 more for the shipping.

For anyone who wants to make this the way it is you can right click and download the zip file [here](/assets/resources/3PDT_Stomp-Panel_2021-07-02.zip).

These are images of what I have setup and the price.

**Note**: Make sure that the ground plain and everything looks right in the board image.
{: .notice--warning}

{% include gallery id="jlcpcb" %}

## Boards

These are the finished boards from the first batch. I believe the second is better with the name in a better spot and no outline of the stomp.

<figure  class="align-center">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/boards.jpg"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/tutorial/3pdt/boards.jpg" alt=""></a>
</figure>

