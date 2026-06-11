---
title: "Introducing Pedal Builder: From \"What's This Chip?\" to \"It's Done.\""
tagline: "A free, searchable database that maps 2,400+ components to 600+ DIY pedal PCB projects from PedalPCB, AION FX, Madbean and more"

date: 2026-06-11
last_modified_at: 2026-06-11

classes: wide

categories:
  - products
  - tools

tags:
  - pedal-builder
  - pedalpcb
  - aion-fx
  - madbean

header:
  teaser: /assets/images/pedal-builder/builder-home.png
  overlay_image: /assets/images/pedal-builder/builder-home.png
  overlay_filter: 0.8

---

If you've been around here a while, you know I keep reference tables of build docs — the [PedalPCB](/blog/pedalpcb-build-docs/), [Madbean](/blog/madbean-build-docs/), and [PCB Guitar Mania](/blog/pcbguitarmania-build-docs/) posts. I maintained those by hand. Every new board, every changed link, every "Updated:" line at the top — me, squinting at a markdown table.

Those tables just grew up.

**[Pedal Builder](https://builder.pachydermpedals.com)** is a free, searchable database that maps every component to every DIY pedal PCB that uses it — across PedalPCB, AION FX, Madbean, and more. It answers the question every builder with a parts drawer has asked:

> *"I have this chip… what can I build with it?"*

[![The Pedal Builder home page — search a component, finish with a build](/assets/images/pedal-builder/builder-home.png)](https://builder.pachydermpedals.com)

## Why I built it

Like a lot of you, my bench has drawers full of parts left over from past projects and overly optimistic Tayda orders. A tube of TL072s here, a bag of 2N5457s there. The question was never "do I have parts?" — it was "what do these parts add up to?"

Finding the answer meant opening build doc PDFs one at a time and reading the parts list of each. Build docs are great, but they answer the opposite question: they start from the *board* and tell you the *parts*. Nothing started from the *part* and gave you the *boards*.

So now there is. As of today Pedal Builder indexes:

* **2,400+ components**, normalized across sources
* **600+ PCB projects** with full bills of materials
* **300+ commercial base pedals**, cross-referenced to their DIY clones

## Start with a chip

Type in a part number. Here's what `TL072` looks like:

[![Searching TL072 returns 214 PCB projects, each with its reference slots, source link, and build doc](/assets/images/pedal-builder/builder-search-tl072.png)](https://builder.pachydermpedals.com/search?q=TL072)

That one search finds **214 PCB projects** that use a TL072 — and for each one you get the board, the source (PedalPCB, AION FX, Madbean…), the effect type, the exact reference slots on the board (IC1, IC2…), and direct links to the product page and the build doc PDF. The "I have this chip, what can I build?" question, answered in about a second.

## Every board, fully mapped

Each PCB project gets its own page: photo of the board, the commercial pedal it's based on, controls, enclosure size, and the full bill of materials — every component mapped to a real, normalized part record, not just a line of text in a PDF.

[![The Abyss PCB page — based on the EQD The Depths, with a 33-line bill of materials](/assets/images/pedal-builder/builder-pcb-abyss.png)](https://builder.pachydermpedals.com)

And it works in both directions. The **Base Pedals** section lists the commercial pedals these projects are based on, so you can start from "I want a Tube Screamer" instead of "I have a JRC4558" and see how many DIY versions exist of each:

[![The Base Pedals catalog — original commercial pedals cross-referenced to their DIY clones](/assets/images/pedal-builder/builder-base-pedals.png)](https://builder.pachydermpedals.com/base-pedals)

## Free to use — no account needed

Everything above — the search, every component, every BOM, every base pedal — is **free and requires no account**. That part is non-negotiable for me; it's the reference tool I always wanted, and a reference tool you have to log into isn't one.

If you do make a (free) account, you get favorites and a **shopping cart that merges the BOMs of every board in it** into one combined parts list — so you can order parts for three builds in a single Tayda or Mouser order without tab-juggling three PDFs. And for the heavy benchers there's a premium tier coming together that tracks your actual parts inventory, tells you **which boards you can build right now from what's in your drawers**, generates the shopping list for what's missing, and tracks each build from first solder joint to done.

## Go try it

**[builder.pachydermpedals.com](https://builder.pachydermpedals.com)** — search the first chip you can reach from where you're sitting.

It's a living database, and like everything on this site it will have things I got wrong. If a part is mismatched, a build doc link is dead, or your favorite board is missing — let me know. That's half the fun of this hobby: the other half is finally using up those TL072s.
