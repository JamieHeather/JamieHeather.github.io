---
layout: default
modal-id: 5
date: 2015-10-13
img: pcr.png
alt: image-alt
project-date: October 2015
journal: Scientific Reports
doi: <a href="http://dx.doi.org/10.1038/srep14629">10.1038/srep14629</a>
authorship: Mid
article: Research
topic: Bioinformatics | Modelling
description: <a href="https://github.com/JamieHeather/JamieHeather.github.io/raw/master/_pdfs/Best_2015_SciRep_PCR_stochasticity.pdf">Download pdf</a><p>This was the third paper I contributed to in my time at UCL. This paper was primarily the work of Katharine Best on the analysis side, and Theres Oakes on the wet lab side (although I did a little of both). However, as I described in a [blog-post I wrote on this paper previously](http://jamimmunology.blogspot.com/2015/11/heterogeneity-in-polymerase-chain-reaction.html), my major contribution to this work was in making the initial observations which sparked off this project.<p> This paper uses data produced from the TCR sequencing platform I was instrumental in developing at UCL, in which random barcodes (or unique molecular indexes, UMIs) are added to TCR cDNA molecules prior to amplification and sequencing. This allows us to correct for sequencing and PCR errors and duplication. However, as we started to develop protocols to do so, we noticed that the degree to which different TCR molecules were amplified in a PCR was not consistent (at least not for rare sequences), in a manner that seeemed to be length and nucleotide sequence independent. As this was followed up, it turned that even different molecules of the <i>same</i> TCR were amplified to different extents. Katharine did some excellent modelling on this phenomenon to rule out a number of explanation; the model which best fits the data suggests a system in which there initially some variation in efficiency across DNA molecules in a PCR (which remember, is at least in some regard independent of the sequence of those molecules), and that this efficiency gets 'inherited' by the descendent copies of that molecule. All in all a rather compelling case for using UMI-library preparations if you want robustly quantitative sequence data!
---
