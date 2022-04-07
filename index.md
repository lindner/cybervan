# CyberVan Project

This repo contains docs and plans on making the ultimate cyber van for
[Neotropolis 2022](https://neotropolis.com) that adheres to the 
[guidelines](docs/neotroplis-policy-2022-v1.0.pdf).

## The Concept

In the dystopian future information is more valuable than ever
but also dangerous to collect.  Going out into the burbclaves requires
stealth and technology.  Everyone can spot a gargoyle a mile away!

Using highly secret holo-skin technology, the CIC Cyber Van can assume the
identity of numerous safe looking vehicles.  But don't be fooled!
They're soaking up all your info to sell to the highest bidder!

In this future world where even your gas is advertiser supported
you will find inserts for videos to play.  You might also be able to
interact with the AI that lives inside and let it trick you into
giving up your information for free.

For CIC agents in the field the Cyber Van offers a way to 
find the latest missions and submit their recon findings.  It
also provides refreshments and a place to avoid paying the 
per-ml piss tax enacted by more modern toilets.   

And of course it's a van, so it'll have lots of candy to lure in
inebriated and stoned ravers and extract even more information.

Check out the [Inspirations](inspiration.md) to get an idea of
what might be possible

## The Parts

The base we will build on is a 2018 RAM [Promaster 1500](https://www.cars.com/research/ram-promaster_1500-2018/)

![Promaster](https://platform.cstatic-images.com/medium/in/v2/stock_photos/70401e3e-a5d6-46eb-8b21-00b4cc88fb62/cc8cb63f-7c66-4ea1-a36f-21397bcef785.png)

The vehicle in hand already a power infrastructure to support night-time usage.

- 200Ah battery
- Solar Panels on roof

The following is a list of items that will be part of the finished project.

- 2x 1000 Lumen Ultra-short-throw projectors, mounted from roof aimed at vehicle.
- Vivid Blue Window tint for headlights and side-windows.
- Hand-made Hex Windshield Cover.
- DMX enabled LED light strip across the top.
- Hand-made Wheel covers that give the appearance of hover.
  - RED LED lighting aimed downwards.
- 6" Yellow/Black hazard tape to go over the bottom black faschia.
- Perforated metal for triangular side windows.
- cheap web cameras aimed at each side recording pixellated video.
- A 25 ft fiberglass antenna/camera mount attached to the trailer hitch.
- Pan/Tilt camera aimed at crowd below.  (maybe a 360?)
  - must have good night vision.
  - must also have good audio pickup for music.
- An Intel NUC with 2x HDMI outputs.
- A raspberry pi.
- A Video archive containing content to stream.
- UV Black lights.

More details on the [Specs](specs.md) page

## Chameleon Skin Howto

A rough sketch on how to make the Van look different

1. Use software like [Madmapper](https://madmapper.com) or [Resolume](https://resolume.com) to build
   a model of the each van side.
2. Make a template for each side of the van.  It'll be 2x1920x1080p.  Basically a double-wide video.
3. A Van **Skin** format can then be used to allow an artist to make different
   van types. 
   a. A basic skin is a static image / single frame looped video.
   b. A more complex van skin will be a longer looped video.
4. Template can contain on-screen elements using green-screens
   a. A 4:3 green screen plays old 80s videos
   b. A 16:9 green screen plays others.
   c. A long-narrow message board could support scrolling text?
   d. Basically color choices could allow for insertion of all kinds of video streams
      for example the 640x480 low res cameras, mast-camera, specific video streams, etc.
5. Some kind of metadata or color scheme to do cool stuff with the DMX controlled LEDs.

## DMX Lighting

LED strips across the top and in the wheel wells (and maybe on the hex
windshield covering) should either use the Van Skin/Theme or when in Music Mode
flash based on amnbient audio.


## More Crazy Ideas

Collecting these over on [Ideas](ideas.md)
