# Using Deep Neural Networks to Classify Astronomical Images
As the quantity of astronomical data available continues to exceed the resources available for analysis, recent advances in artificial intelligence encourage the development of automated classification tools. This project, my undergraduate Honors Capstone Project at Seattle Pacific University, develops a framework for training a deep neural network capable of classifying individual astronomical images by describing techniques to extract and label these objects from large images.

The deep neural network does not rely on any particular source of data but to obtain labeled images I used <a href="https://nova.astrometry.com">Astrometry</a> and processed them with <a href="https://www.astromatic.net/software/sextractor/">Source Extractor</a> to produce training data.

Astrometry is of tremendous use for this purpose but the methodologies described herein for processing FITS files with Source Extractor and <a href="https://www.astropy.org">AstroPy</a> are relevant regardless of image source. 

Presently (May 2023), this repository is being configured to include relevant documents and files. Until this is complete, the repo may be incomplete and documentation may not yet be substansive. Please reach out via <a href="https://andrewm.tech#three">andrewm.tech</a> or email me at <a href="mailto:macphersona@spu.edu">macphersona@spu.edu</a> with any questions.

## Academic Presentations
This material was presented at the following university conferences. A slideshow recording of the Erickson conference is currently available and recordings of the others are being made available shortly.

:star:<a href="https://sitecoremaster.spu.edu/-/media/academics/college-of-arts-sciences/erickson/2023/Erickson-2023-awardees.ashx"> Award Winner - Top Oral Presentation</a> :star:<br>
<b>21st Annual Erickson Conference</b><br>
<i>Seattle Pacific University</i><br>
May 5th, 2023<br>
<a href="https://youtu.be/vKQuGpHbEUY">Video Link</a>

<b>26th Annual Undergraduate Research Symposium</b><br>
<i>University of Washington</i><br>
May 19th, 2023

<b>2nd Annual Honors Research Symposium</b><br>
<i>Seattle Pacific University</i><br>
May 20th, 2023<br>
<a href="https://spu.hosted.panopto.com/Panopto/Pages/Viewer.aspx?pid=2ceddffc-c8ac-414c-b525-b0150113e61e&id=600f5f55-6473-4288-b58d-b015011f1b67&advance=true">Video Link</a>

## Repository Guide
This repository accompanies the academic paper <i>Using Deep Neural Networks to Classify Astronomical Images</i> by Andrew Macpherson available in the Seattle Pacific University Digitial Commons. It is intended to provide access to files referenced in the paper and many proper descriptions are given in the paper. Nonetheless, a brief outline of the repository contents is as follows:

📁Appendixes - Contains appendixes that are not given in the paper, namely Appendixes C, D, & E. These contain basic information for objects in the New General Catalog, Henry Draper Catalog, and Index Catalog.<br>
📁Data - Contains sample raw astronomical images in FITS format. These sample files were used to create labeled images</br>
📁Images - Contains labeled cutouts from sample FITS files.<br>
📁Presentations - Contains recordings of presentations to university conferences.<br>
📁config - Contains configuration files for Source Extractor, modified as described in the paper to adjust the appropriate parameters and extract relevant data.<br>

## Summary Data Flow Chart
![Preprocessing Data Flow](https://user-images.githubusercontent.com/102562791/229910764-7e243235-09e1-4631-baa3-614fc56b4838.png)
---
[![astropy](http://img.shields.io/badge/powered%20by-AstroPy-orange.svg?style=flat)](http://www.astropy.org/)
