# Astronomical-Identification-ML
As the quantity of astronomical data available continues to exceed the resources available for analysis, recent advances in artificial intelligence encourage the development of automated classification tools. This project, my undergraduate Honors Capstone Project at Seattle Pacific University, develops a framework for training a deep neural network capable of classifying individual astronomical images by describing techniques to extract and label these objects from large images.

The deep neural network does not rely on any particular source of data but to obtain labeled images I used <a href="https://nova.astrometry.com">Astrometry</a> and processed them with <a href="https://www.astromatic.net/software/sextractor/">Source Extractor</a> to produce training data.

Astrometry is of tremendous use for this purpose but the methodologies described herein for processing FITS files with Source Extractor and <a href="https://www.astropy.org">AstroPy</a> are relevant regardless of image source. 

Presently (May 2023), this repository is being configured to include relevant documents and files. Until this is complete, the repo may be incomplete and documentation may not yet be substansive. Please reach out via <a href="https://andrewm.tech#three">andrewm.tech</a> or email me at <a href="mailto:macphersona@spu.edu">macphersona@spu.edu</a> with any questions.

## Academic Presentations
This material has been/will be presented at the following university conferences:

<b>21st Annual Erickson Conference</b><br>
<i>Seattle Pacific University</i><br>
May 5th, 2023

<b>26th Annual Undergraduate Research Symposium</b><br>
<i>University of Washington</i><br>
May 19th, 2023

<b>2nd Annual Honors Research Symposium</b><br>
<i>Seattle Pacific University</i><br>
May 20th, 2023

## Summary Data Flow Chart
![Preprocessing Data Flow](https://user-images.githubusercontent.com/102562791/229910764-7e243235-09e1-4631-baa3-614fc56b4838.png)
---
[![astropy](http://img.shields.io/badge/powered%20by-AstroPy-orange.svg?style=flat)](http://www.astropy.org/)
