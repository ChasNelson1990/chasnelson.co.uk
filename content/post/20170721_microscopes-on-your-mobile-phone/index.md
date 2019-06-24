---
title: "Microscopes on Your Mobile Phone"
subtitle: ""
summary: ""
authors: ["chas"]
tags: ["microscopes"]
categories: ["outreach","research"]
date: 2017-07-21T15:30:09+01:00
featured: false
draft: false
slug: "mobile-phone-microscopes"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
Many modern microscopes can be large, highly technical and expensive pieces of equipment. This is most evidenced when you consider that, when funding such equipment at UK universities and research institutes, many funding bodies stipulate a requirement for sharing across multiple research groups or institutes. However, as developers of new microscopy technology a focus on such fancy and costly microscopes should not be at the detriment of the continued research into miniaturisation, cheaper manufacturing and improved transportable microscopes.

<!--more-->

## Why Do We Need Small and Cheap Microscopes?

But, why do we need small, cheap and transportable microscopes? Surely the exciting microscopy is done with powerful lasers, fancy optics and performed by Nobel Prize winners? Whilst some of the most beautiful and scientifically revealing images are indeed captured by some of the larger and fancier equipment out there, some of the most important applications of imaging technologies are in healthcare, particularly in the developing world.

These parts of the world are often very well connected by satellite and mobile networks and smart phones sales are surprisingly high. So, we have a problem of expensive and cumbersome microscopes... and a solution of one of the most powerful devices we've ever come up with: a pocket-sized computer with a digital camera sensor and and high quality lens. A perfect pairing I'd say!

## But How Good Can They Be?

Suprisingly good! We're obviously not the first people to ask that question and so I point you to this (open access) research article comparing smartphone microscopy and conventional microscopy in dermatology: <a href="https://dx.doi.org/10.5858/arpa.2014-0593-OA" target="_blank" rel="noopener">https://dx.doi.org/10.5858/arpa.2014-0593-OA</a> [1]. Obviously, the paper is quite technical but their abstract conclusion sums it up nicely:

> Mobile phone–based microscopy has excellent performance characteristics for the inexpensive diagnosis of nonmelanoma skin cancers in a setting where a traditional microscope is not available.

Basically, whilst smartphone microscopes won't surpass dedicated microscopes they workswell enough to be a reliable tool for microscopy and a cheap alternative too.

## Who Designs Microscopes for Mobile Phones?

There's quite a few research papers on mobile phone microscopes and plenty of open source projects trying to design equipment that can be cheaply produced, often 3D printed, for poorer regions of the Earth. As much of this research is open access, I'm just going to provide a short list of a few companies, papers and repositories for you to browse at your own leisure (in no particular order):

  * Foldscope [2] is a low-cost, paper-based microscope that has been used for education and research across the globe. As well as their main website, which has an imaging community, see their Wikipedia page for examples of its use <a href="https://en.wikipedia.org/wiki/Foldscope" target="_blank" rel="noopener">https://en.wikipedia.org/wiki/Foldscope</a>.
  * A cheap adapter for most smartphones sold by the Science Museum (<a href="https://www.sciencemuseumshop.co.uk/exhibition-ranges/wonderlab-collection/wonderlab-matter/smartphone-microscope.htm" target="_blank" rel="noopener">https://www.sciencemuseumshop.co.uk/exhibition-ranges/wonderlab-collection/wonderlab-matter/smartphone-microscope.htm</a>) can be a great way to introduce microscopy as fun family activity for investigating nature from rocks to insects.
  * The Smartphone Microscope [3] is designed to be an easy to build and cheap platform to turn any smartphone into a fairly robust microscope. The designs for the original version are available on Instructables [4] and they also sell pre-fabricated versions. Keep an eye out for version 2.0, coming soon!
  * A recent preprint article (open access) reported a simple, 3D printed adapter for smartphones that uses the internal camera flash as an illumination source [5].
  * And, last but not least, my favourite portable microscope is a smartphone-driven Lego Lightsheet Microscope!! The website it currently under construction but hopefully they'll put all the details up soon at <a href="http://legolish.org/" target="_blank" rel="noopener">http://legolish.org/</a>. (We might be planning to build this at work.)

There are more out their and there is an increasing movement for creating cheaper, open access, open source, research-quality tools. For example, the recent PLoS Biology (open access) paper on FlyPi, the low-cost, 3D-printable behavioural biology set-up by the Baden lab. See <a href="https://dx.doi.org/10.1371/journal.pbio.2002702" target="_blank" rel="noopener">https://dx.doi.org/10.1371/journal.pbio.2002702</a> for the paper and <a href="https://open-labware.net/projects/flypi/" target="_blank" rel="noopener">https://open-labware.net/projects/flypi/</a> for the dedicated Open Labware page.

### References

  1. Richard R. Jahan-Tigh, Garrett M. Chinn, and Ronald P. Rapini, 2016. A Comparative Study Between Smartphone-Based Microscopy and Conventional Light Microscopy in 1021 Dermatopathology Specimens. _Archives of Pathology & Laboratory Medicine_ Vol. 140, No. 1, pp. 86-90.
  2. Foldscope: <a href="https://microcosmos.foldscope.com" target="_blank" rel="noopener">https://microcosmos.foldscope.com</a>
  3. The Smartphone Microscope: <a href="http://thesmartphonemicroscope.com/" target="_blank" rel="noopener">http://thesmartphonemicroscope.com/</a>
  4. $10 Smartphone to Digital Microscope Conversion!: <a href="http://www.instructables.com/id/10-Smartphone-to-digital-microscope-conversion/" target="_blank" rel="noopener">http://www.instructables.com/id/10-Smartphone-to-digital-microscope-conversion/</a>
  5. <div class="highwire-cite-title">
      <div class="highwire-cite-title">
        <div class="highwire-cite-authors">
          <span class="highwire-citation-authors"><span class="highwire-citation-author first"><span class="nlm-given-names">Antony</span> <span class="nlm-surname">Orth</span></span>, <span class="highwire-citation-author"><span class="nlm-given-names">Emma</span> <span class="nlm-surname">Wilson</span></span>, <span class="highwire-citation-author"><span class="nlm-given-names">Jeremy</span> <span class="nlm-surname">Thompson</span></span>, <span class="highwire-citation-author"><span class="nlm-given-names">Brant C.</span> <span class="nlm-surname">Gibson, 2017 (preprint). </span></span></span>A dual-mode mobile phone microscope using integrated and ambient light. <em><span class="highwire-cite-metadata-journal highwire-cite-metadata">bioRxiv </span></em><span class="highwire-cite-metadata-pages highwire-cite-metadata">162008; </span><span class="highwire-cite-metadata-doi highwire-cite-metadata"><span class="doi_label">doi:</span> </span><a href="https://dx.doi.org/10.1101/162008" target="_blank" rel="noopener">https://dx.doi.org/10.1101/162008</a>.
        </div>
      </div>
    </div>
