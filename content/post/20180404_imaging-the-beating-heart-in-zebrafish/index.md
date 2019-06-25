---
title: "Imaging the Beating Heart in Zebrafish"
subtitle: ""
summary: ""
authors: ["chas"]
tags: ["3Rs","phototoxicity","interdisciplinarity","microscopes","zebrafish"]
categories: ["my research","research"]
date: 2018-04-04T17:12:05+01:00
featured: false
draft: false
slug: "imaging-the-beating-heart"
---
2018 has been a busy year so far (and I expect it will stay that way) but I’ve finally made time to write another blog post (and also to move my blog into my personal website). Given that so far this year I’ve spoken about my current research - imaging the beating zebrafish heart - to audiences of academics, the public & students I thought it was about time to do a blog post summarising said research. Hopefully this short post will provide you with an idea of what we’re trying to achieve, why and how we’re going about it (although I've kept off too much detail for now).

<!--more-->

## The Challenge of a Beating Heart

Here at the University of Glasgow I am working with <a href="https://www.gla.ac.uk/schools/physics/staff/jonathantaylor/" target="_blank" rel="noopener noreferrer">Dr Jonathan Taylor</a> on techniques for imaging the living, beating heart in zebrafish. This work is part of a <a href="https://www.bhf.org.uk/research-projects/development-and-optimisation-of-synchronised-3d-invivo-imaging-of-the-embryonic-and-juvenile-zebrafish-heart" target="_blank" rel="noopener noreferrer">British Heart Foundation</a> funded collaboration between us and a team of biologists at the University of Edinburgh. Our collaborators are interested in quantifying how the heart responds to injury, which in turn can be used to develop drugs that improve the natural injury response. Eventually, the fundamental research being carried out in the zebrafish can be translated to other model organisms and may, after much validation, be trialled in humans. At a conference I attended earlier in the year, one speaker gave the (uncited) statistic that 22 out of 24 drugs developed in the zebrafish have been successfully translated to humans despite the differences between a fish heart and a human heart.


So that’s why our collaborators are interested in imaging the heart, but what are the challenges? Well, the primary challenge is that the living, beating heart is doing just that – beating. Generally, 3D fluorescence microscope images are built up by collecting several 2D images at different depths in the sample. The constant motion of the heart means that, in order to capture 3D fluorescence images of the heart, one must either be able to capture an entire 3D image very quickly, quicker than most fluorescence microscopes can achieve, or one could slow down, stop or pace the heart so that each 2D fluorescence plane can be captured at the exact same ‘phase’ or point in the heart beat cycle.

## Prospective Optical Gating

Unfortunately, intervening in the heart beat with drugs or electricity then starts to alter heart function and shape and may, over prolonged periods, introduce damage to the heart and other tissues in the fish. If we’re interested in imaging injury response we need to avoid accidental injury caused by our imaging. In other organisms, such as mice and humans, an echocardiogram (ECG) signal can be used to capture synchronised images in a technique known as gating [1].

Unfortunately, attaching an ECG to a 3 mm long zebrafish embryo is challenging and very invasive. The approach we take at Glasgow is to use an non-invasive and gentle infrared video of the heart; this is the optical aspect of the approach. Using the concepts of gating with this optical source of information we can ‘computationally freeze’ the heart [2]. We use real-time computer algorithms to predict, this is the prospective bit, when to capture each 2D fluorescence image at a specific target phase. We are able to do this without the use of drugs or electrical stimulation. This allows the heart to continue beating completely naturally whilst we build up synchronised 3D snapshots (one 2D fluorescence images per heartbeat) of the heart at a target phase. Below you can see an example of a 3D taken with and without the synchronisation provided by our optical gating approach.

<div style="text-align: center; margin: auto;">
  <img class="size-medium wp-image-911" src="https://www.chasnelson.co.uk/wp-content/uploads/2018/04/synced-285x300.jpg" alt="Synchronised 3D Imaging Captured During the Constant Beating of the Heart" style="width:45%" srcset="https://www.chasnelson.co.uk/wp-content/uploads/2018/04/synced-285x300.jpg 285w, https://www.chasnelson.co.uk/wp-content/uploads/2018/04/synced.jpg 315w" sizes="(max-width: 285px) 85vw, 285px" /> <img class="size-medium wp-image-910" src="https://www.chasnelson.co.uk/wp-content/uploads/2018/04/notsynced-286x300.jpg" alt="Unsynchronised 3D Imaging Clearly Showing Scrambling of Information by the Constant Beating of the Heart" style="width:45%" srcset="https://www.chasnelson.co.uk/wp-content/uploads/2018/04/notsynced-286x300.jpg 286w, https://www.chasnelson.co.uk/wp-content/uploads/2018/04/notsynced.jpg 316w" sizes="(max-width: 286px) 85vw, 286px" /><br /> Synchronised 3D Imaging of the Heart (from [1])
</div>

This approach actually has additional benefits. Not only can synchronised 3D images be collected without intervening in the heart’s natural processes but by ‘computationally freezing’ the heart, we are able to track the true motion of injury response cells, such as as macrophages. If we were to naively capture a constant video of the beating heart, any macrophages in our images would be constantly moving in and out with the heartbeat. By freezing the heart, this high frequency in-out motion is removed and we are able to track the motion of cells across the surface of the heart.

## The 3Rs

Part of the work that I've been focussing on during my time at Glasgow is to help improve the system so that instead of only being able to capture short timelapse videos, e.g. one 3D stack ever two minutes for half an hour to an hour, we able to capture timelapse videos over timescales relevant to development and injury-response, e.g. 12+ hours.

A standard approach to this would be to injure a batch of fish and image different fish at different timepoints throughout the injury-response process. Each fish might then be killed so that imaging becomes a simple process; however, this leads to a drop in blood pressure and a change in heart and blood vessel shape.

Alternatively, the heart might be imaged in the living fish; however, common imaging approaches other than the optical gating described above often cause a response in the heart such as a change in heart rate. We've even seen a macrophage, i.e. injury, response to one alternative imaging approiach. As such, these approaches can't be used at several timepoints in a single fish as the imaging itself could be inducing an injury response - the very thing we're trying to measure.

By improving our optical gating approach so that timelapse images can be taken over 24 hours or more (see \[3] for the technical detail) we've developed a system that can reduced the numbers of animals needed in an experiment and refined the experiment by minimising invasiveness and possible injury. These are two of the 3Rs, the guiding principles of using animals in research [4\] (see [my earlier post](https://www.chasnelson.co.uk/2017/11/10/better-imaging-of-living-animals-and-the-3rs/)).

## The 3Ps

Finally, this approach has benefits in terms of phototoxicity, photodamage and photobleaching (the 3Ps). By only capturing one 2D fluorescence image per heartbeat we reduce the amount of light being applied to our fish in comparison to high-speed, constant imaging. This reduces the effects of phototocixity and photodamage, which often manifest as a change in heart rate or, in extreme cases, the recruitment of macrophages and other injury response cells.

Further, if the fluorophore being imaged is particularly susceptible to photobleaching, an often dramatic loss of brightness, then the low-light nature of our system will reduce the impact this has on imaging. Thus allowing imaging for longer with minimal changes in intensity of signal.

### The Beat Goes On...

With recent improvements in our algorithms we are now able to capture images of a computationally frozen heart for over 24 hours. This allows our collaborators to count and track macrophages and neutrophils for several hours after an induced injury. We are also able to follow morphological changes throughout heart development in zebrafish embryos. Our collaborators are now using these technologies to allow quantified, high resolution imaging of heart injury response. Hopefully this will lead to new discoveries in cardiac repair that, after further research, might make their way in to humans.

In the future we hope to improve this system further, combining state-of-the-art optics and computational approaches to improve the system robustness, temporal and spatial quality and further reduce the amount of light being pumped into the system.

P.S. We are currently putting this work together as a new paper which we hope to submit in the coming months – expect pretty pictures and videos.

### References

  1. See this article for great descriptions of gating in CT imaging <a href="http://xrayphysics.com/cardiac_ct.html" target="_blank" rel="noopener noreferrer">http://xrayphysics.com/cardiac_ct.html</a>.
  2. Taylor, J.M., Saunter, C.D., Love, G.D., Girkin, J.M., Henderson, D.J. and Chaudhry, B., 2011. Real-time optical gating for three-dimensional beating heart imaging. _Journal of biomedical optics_, _16_(11), p.116021. <a href="https://dx.doi.org/10.1117/1.3652892" target="_blank" rel="noopener noreferrer">https://dx.doi.org/10.1117/1.3652892</a> (available at <a href="http://dro.dur.ac.uk/8939/1/8939.pdf" target="_blank" rel="noopener noreferrer">http://dro.dur.ac.uk/8939/1/8939.pdf</a>).
  3. <div class="gs_citr" tabindex="0">
      Nelson, C.J., Buckley, C., Mullins, J.J., Denvir, M.A. and Taylor, J., 2018, February. Imaging the developing heart: synchronized time-lapse microscopy during developmental changes. In <i>Three-Dimensional and Multidimensional Microscopy: Image Acquisition and Processing XXV</i> (Vol. 10499, p. 104991F). International Society for Optics and Photonics. <a href="https://dx.doi.org/10.1117/12.2290191" target="_blank" rel="noopener noreferrer">https://dx.doi.org/10.1117/12.2290191</a> (available at <a href="https://arxiv.org/pdf/1802.05663.pdf" target="_blank" rel="noopener noreferrer">https://arxiv.org/pdf/1802.05663.pdf</a>).
    </div>

  4. NC3RS (<a href="https://nc3rs.org.uk/" target="_blank" rel="noopener noreferrer">https://nc3rs.org.uk/</a>).
