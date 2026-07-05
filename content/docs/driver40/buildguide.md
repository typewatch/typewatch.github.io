---
title: Build Guide
type: docs
prev: docs/bom/
---

> [!NOTE]
> Before you begin, make sure you have everything you need (tools, parts, guides, snacks) at hand. It'll make the job much easier.

> [!IMPORTANT]
> PCB, case, plate and wiring designs shown here may not represent the newest revisions.

> [!WARNING]
> This project involves wiring. Please be careful when handling electrical equipment, and make sure to properly test your parts before using them.

{{< details title="Tools Required" >}}

- Screwdriver
- Tweezers
- Soldering Iron
- Solder & Flux
- Flashlight
- Magnifying Glass

{{< /details >}}

## PCB

{{% steps %}}

### Step 1

Solder all 40 diodes into their corresponding pads, marked as such:

![diodealignment](/img/docs/driver40/diode-alignment.webp "The line on your diode should face the line on the marking.")

> [!TIP]
> To make installation easier, pre-tin the pads, align the diode, and while holding it down with tweezers, use your iron to reflow each leg into place.

### Step 2

Solder all 40 hotswap sockets into their marked spots, which look like the following:

![hotswapalignment](/img/docs/driver40/switch-footprint.jpeg "The sockets should fit into the hole cutouts on the footprints.")

> [!TIP]
> Same as with the diodes: Pre-tin the pads with as much solder as you can before spilling. Then, align the socket with the holes and pads, and press down on either side with your iron. Hold until the solder melts, and firmly press the socket down into the pad.

### Step 3

Solder headers in place.

![headers](/img/docs/driver40/headers.png "Insert each strip into the corresponding holes, and solder them onto the board through the bottom.")

> [!NOTE]
> Make sure to push them all the way in. If they are misaligned, the MCU will not fit.

### Step 4

Mount the MCU atop the already installed headers, and solder it in place.

> [!CAUTION]
> Make sure to keep the MCU flush with the headers, or you risk cracking it while soldering it in place.

{{% /steps %}}

## Plate Sandwich

## Case Fitting