---
title: "Let There be Light... but Not Too Much"
subtitle: "Phototoxicity in Microscopy"
summary: "An essential aspect to microscopy is light. Early microscopes used ambient light or used mirrors to reflect light, either from the sun or a candle, onto the sample of interest. With the inventions [1] of the electric light bulb additional, artificial light sources could be used and the light from lamps could be focussed onto samples with much greater control."
authors: ["chas"]
tags: ["microscopes","photoxicity"]
categories: ["academia","my research","research"]
date: 2017-08-11T18:19:14+01:00
featured: false
draft: false
slug: "phototoxicity"
---
## Light is an Essential Aspect of Microscopy

An essential aspect to microscopy is light. Early microscopes used ambient light or used mirrors to reflect light, either from the sun or a candle, onto the sample of interest. With the inventions [1] of the electric light bulb additional, artificial light sources could be used and the light from lamps could be focussed onto samples with much greater control.

<!--more-->

Fluorescent proteins (see 2008 on my <a href="https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1xVUEF-BWrs088M4WRcu-JL0D6xp1qHZZRX8OiOUQqfk&font=Default&lang=en&initial_zoom=2&height=650" target="_blank" rel="noopener">interactive timeline</a>) brought a new round of light technologies to microscopy, with one of the most common light sources for confocal microscopes being the mercury arc lamp. Combined with appropriate filters, the mercury lamp, along with xenon and tungsten lamps, provides a powerful light source suitable for exciting low quantum yield [2] fluorescent proteins.

Recently, LED light sources have begun to take over from arc lamps. Their mass production driven by consumer technology has made them cheap, easy to get hold of and remarkably reliable. LEDs can be found in single, narrowband set-ups, i.e. able to excite only specific fluorescent molecules, or in broadband, i.e. white, forms that can be combined with filters for greater flexibility.

But, one of the most important light sources in modern, state-of-the-art microscopy is the LASER. LASERs, or _Light Amplification by Stimulated Emission of Radiation_ devices, are extremely clever pieces of equipment (and a full description of them is technically beyond this blog). Essentially a laser amplifies an initial light source through stimulating the release of photons of a known length from an excited medium, or dye. Lasers have many benefits for microscopy including their known and very narrowband spectrum, i.e. very specific wavelengths are produced, and their coherence, which allows tight focussing and control of the spatial structure of the light.

## Light vs. Biologists: Round One!

So, as microscopy technology has developed we've moved to stronger, more specific and more focussed light sources. And this has, in turn, allowed us to get clearer, higher resolution images and is now allowing optical microscopy to near the resolutions achieved by electron microscopy. But using light has its costs and, as microscopists and biologists, it's very important for us to keep these costs in mind.

I think it's fair to say that a lot of biology doesn't really like light. Obviously, there are systems that have developed to exploit the energy provided by the suns light, e.g. photosynthesis, but light, and the energy contained, causes lots of problems to our cells. For example, if you sunbathe without protection the energy from UV rays, which are just a wavelength of light, cause damage to your DNA, which you cells must correct. A combination of mutations caused by UV and various causes, along with genetic predisposition, can lead to skin cancers [3]: a clear negative effect of light on biology.

In fact, all light has an effect on biological tissue, especially at shorter wavelengths (green and blue visible light, UV light). Unfortunately, until very recently, producing bright blue, green and yellow fluorescent proteins has been significantly easier than developing bright far-red and near-infrared proteins. As such, a significant amount of microscopy in recent years has been firing damaging light on our samples.

## Biologists vs. Light: Round Two!

All is not lost. Although the damage light causes during microscopy can be severe, most microscopy is done at low light levels, often the lowest that allow us to see the biology of interest. Further, a dialogue has recently opened up in the community as to the best ways to measure, record and publish how we are using light and the effect this might have on the biology concerned [4].

This dialogue is extremely important but it must be a discussion that transcends disciplinary boundaries (transdisciplinary) and manufacturers and developers of microscope technologies must be as aware of and as open about the problems of light damage (photodamage/photoxicity) as biologists.

## Biologists vs. Light: Round Three! A Knockout...?

Well, no. But with some clever design and thinking microscopists can develop systems that minimise the energy transferred to our samples from light. For example, in my current <a href="https://www.chasnelson.co.uk/research/" target="_blank" rel="noopener">research</a>, we are using a low intensity, infrared LED for constant imaging of zebrafish hearts. This light has a minimal to negligible effect on the fish.

We're able to use this low-damage imaging to trigger the capture of fluorescent images at very precise times, i.e. at specific points within the heartbeat. These fluorescent images, individually, also have a minimal effect on the fish's health and stress levels. We are then able to computationally build a 3D image of the beating zebrafish heart and monitor the changes over hours and days to understand development, healing and regeneration.

Alternative approaches to the problem of capturing images at specific points in the heartbeat have been to capture lots of fluorescent images at a high rate and computationally work out which ones were actually at the point you wanted afterwards. This is not only inefficient with your data but taking large numbers of these fluorescent images within a short timespan can have serious effects on heart and immune system activity.

## Biologists vs. Light: The Fight Continues

### References

  1. <a href="https://en.wikipedia.org/wiki/Incandescent_light_bulb#History" target="_blank" rel="noopener">https://en.wikipedia.org/wiki/Incandescent_light_bulb#History</a>
  2. <a href="https://en.wikipedia.org/wiki/Quantum_yield" target="_blank" rel="noopener">https://en.wikipedia.org/wiki/Quantum_yield</a>
  3. <a href="http://www.cancerresearchuk.org/about-cancer/causes-of-cancer/sun-uv-and-cancer/how-the-sun-and-uv-cause-cancer" target="_blank" rel="noopener">http://www.cancerresearchuk.org/about-cancer/causes-of-cancer/sun-uv-and-cancer/how-the-sun-and-uv-cause-cancer</a>
  4. Unfortunately neither of these are fully Open Access, sorry.
      1. Laissue, P. Philippe, Rana A. Alghamdi, Pavel Tomancak, Emmanuel G. Reynaud, and Hari Shroff, 2017. Assessing phototoxicity in live fluorescence imaging. _Nature Methods_ Vol. 14, no. 7, pp. 657-661. <a href="https://dx.doi.org/10.1038/nmeth.4344" target="_blank" rel="noopener">https://dx.doi.org/10.1038/nmeth.4344</a> (or available here <a href="https://publications.mpi-cbg.de/Laissue_2017_6887.pdf" target="_blank" rel="noopener">https://publications.mpi-cbg.de/Laissue_2017_6887.pdf</a>)
      2. Icha, J., Weber, M., Waters, J. C. and Norden, C., 2017. Phototoxicity in live fluorescence microscopy, and how to avoid it. _BioEssays_ Vol. 39, 1700003. <span class="article-header__meta-info-data"><a href="https://dx.doi.org/10.1002/bies.201700003" target="_blank" rel="noopener">https://dx.doi.org/10.1002/bies.201700003</a></span>
