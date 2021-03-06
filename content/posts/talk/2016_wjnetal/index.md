---
title: "Application of High-Speed Level Set Segmentation to Light Sheet Fluorescence Microscopy"
event: Light Sheet Fluorescence Microscopy Conference
location: Sheffield, UK
date: 2016-09-01
all_day: true
publishDate: 2020-04-17T15:16:36.964564Z
authors: ["chas", "Chris G. Willcocks", "Philip T. G. Jackson", "P. Philippe Laissue", "Boguslaw Obara"]
abstract: "Light sheet fluorescence microscopy produces large, detailed 3D images of biological samples, but these images are often heavily afflicted by structured noise caused by optical effects such as attenuation, refraction and shadowing. Local Gaussian distribution fitting (LGDF) energy is a powerful variational level set framework, ideally suited to these challenges for its ability to segment image objects with inhomogeneous intensity. However, as with most level set methods, LGDF is computationally intensive, and existing CPU implementations take several hours to segment modestly sized 3D images. We present a powerful software package that implements LGDF energy minimisation efficiently on the GPU, running in seconds rather than hours on most 3D images. It is able to segment multiple objects in real-time, at subpixel accuracy despite uneven background, severe noise, and objects with blurred and/or broken boundaries. The speed of our algorithm makes real-time interaction with datasets possible, allowing the user to select individual objects, correct errors and tune parameters  instantaneously (or: without delay). Our method utilises three intuitive and tunable parameters, each relating to tangible properties of the final segmentation, and a combination of optional, interactive brushes to edit and constrain segmentation in 3D. Here we demonstrate application of our high-speed, three-dimensional image segmentation framework to a range of complex and large light sheet fluorescence microscopy images. We show accurate and high-quality three-dimensional segmentations that are captured in real-time using modern GPU technologies."
tags: ["oral"]

featured: false

url_slides:
url_code:
url_pdf:
url_video:
url_poster:
url_dataset:

slides: ""
projects: []
---

