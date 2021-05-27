---
toc: true
toc_sticky: true
toc_label: "My Table of Contents"
toc_icon: "cog"

# layout: single

title: "Blinking Eye for the Johnny 5 Storm Pedal"
tagline: "Getting the LED to blink like he is fading away."
date: 2021-05-25
last_modified_at: 2021-05-25

header:
  teaser: /assets/images/pedals/119.jpg
  overlay_image: /assets/images/pedals/119.jpg
  overlay_filter: 0.8

author_profile: true
author_profile_end: false

formed:
  - url: /assets/images/blog/clyde/01.jpg
    image_path: /assets/images/blog/clyde/01.jpg
    alt: "placeholder image 1"
    title: ""
  - url: /assets/images/blog/clyde/02.jpg
    image_path: /assets/images/blog/clyde/02.jpg
    alt: "placeholder image 2"
    title: ""
  - url: /assets/images/blog/clyde/03.jpg
    image_path: /assets/images/blog/clyde/03.jpg
    alt: "placeholder image 3"
    title: ""

drying:
  - url: /assets/images/blog/clyde/04.jpg
    image_path: /assets/images/blog/clyde/04.jpg
    alt: "placeholder image 4"
    title: ""
  - url: /assets/images/blog/clyde/05.jpg
    image_path: /assets/images/blog/clyde/05.jpg
    alt: "placeholder image 5"
    title: ""
  - url: /assets/images/blog/clyde/06.jpg
    image_path: /assets/images/blog/clyde/06.jpg
    alt: "placeholder image 6"
    title: ""
  - url: /assets/images/blog/clyde/07.jpg
    image_path: /assets/images/blog/clyde/07.jpg
    alt: "placeholder image 7"
    title: ""
  - url: /assets/images/blog/clyde/08.jpg
    image_path: /assets/images/blog/clyde/08.jpg
    alt: "placeholder image 8"
    title: ""

gallery:
  - url: /assets/images/blog/clyde/09.jpg
    image_path: /assets/images/blog/clyde/09.jpg
    alt: "placeholder image 9"
    title: ""
  - url: /assets/images/blog/clyde/11.jpg
    image_path: /assets/images/blog/clyde/11.jpg
    alt: "placeholder image 11"
    title: ""
  - url: /assets/images/blog/clyde/12.jpg
    image_path: /assets/images/blog/clyde/12.jpg
    alt: "placeholder image 12"
    title: ""
---

So I have been working on my Johnny 5 pedal for a few months. Mostly aesthetics. It is a clone of the Solo Dallas Storm. The [PCB](https://www.pedalpcb.com/product/closedcircuit/) is from PedalPCB and is called the Closed Circuit Booster Limiter. My mind went "Closed Circuit...short circuit...Johnny 5". I found an image I liked on Google Image Search, made a vector representation of it with a few minor modifications and sent if out for printing. Well I just sent of that file for the third time because I made several mistakes with the UV printing that meant it didn't look the way I wanted. This meant I had enclosures to experiment with. 

**Note:** That image was a drawing called "Hey laser lips, your momma was a snowblower." by Alex R. Kirzhner. [This](https://www.facebook.com/690329601012923/photos/pb.690329601012923.-2207520000../1583790585000149/?type=3&theater) is a facebook link to the picture. He also goes by @a_danger_k on Instagram.
{: .notice--info }

[![Johnny5](https://scontent-bos3-1.xx.fbcdn.net/v/t1.18169-9/25507651_1583790585000149_4094225934734760155_n.jpg?_nc_cat=103&ccb=1-3&_nc_sid=973b4a&_nc_aid=0&_nc_ohc=604rZxWeGVwAX9Mr2T7&_nc_ht=scontent-bos3-1.xx&oh=fd254aea28466b772754d94bc01567b3&oe=60D18062)](https://scontent-bos3-1.xx.fbcdn.net/v/t1.18169-9/25507651_1583790585000149_4094225934734760155_n.jpg?_nc_cat=103&ccb=1-3&_nc_sid=973b4a&_nc_aid=0&_nc_ohc=604rZxWeGVwAX9Mr2T7&_nc_ht=scontent-bos3-1.xx&oh=fd254aea28466b772754d94bc01567b3&oe=60D18062)

The first had the LED where the drill template suggested. Nice but nothing really interesting. This is prototype #1. On the second enclosure, aptly named prototype 2 (or should that be johnny 2...hhmmm) I decided to put the LED in the eye socket. Then @gear_ant suggested I get the eye to blink like it does on when he dies in the movie.

Now how can I pass up a macabre idea like that. So I want on a quest for a way to do as @gear_ant suggested. First I tried to use a blinking LED but that really does not have the effect I was looking for. Next I purchased and tried some candle flicker LEDs. But on these the flicker really what not pronounced enough. Finally I decided to try to find a circuit that would work. This lead me to Pulse Width Modulation (PWM) circuits. This is where you blink the led really fast. The faster it blinks the brighter the light, and vice versa. I figured this would help with the dimming.

I settled on [this](https://www.electronicshub.org/pwm-led-dimmer-using-ne555/) circuit. It uses a 555 clock (NE or LM) and a 2n2222 transistor to create a PWM. But is uses a potentiometer to trigger the rate a change with the use of a couple of 1N4148 diodes. This is fine but it is still a manual process. 

Finally I decided to try to use the flicker LED as the trigger for the 555 IC. This worked great. The flicker was random, it did not have a constant brightness like a simple on off and I thought it looked great. I added a trimmer (so it still have a pot) but that is just so I can dial in the perfect brightness. If I ever do a run of these pedals I will have to decide if I want to put in a fixed resistor or let the buyer decide on bot bright his eye will be. I;ll probably leave the trim pot since I like it kind of dim but if you are on a bright stage you won't know that the pedals on.

Now I just need to get pictures and vids of the things I talk about to augment this little story. And since I just ordered the 3rd enclosure today (May 25, 2021). I will have to update with the completed pedal and the flickering eye.