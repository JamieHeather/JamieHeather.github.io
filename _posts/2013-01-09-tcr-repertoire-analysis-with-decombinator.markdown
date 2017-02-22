---
layout: default
modal-id: 3
date: 2013-01-09
img: decombinator.png
alt: image-alt
project-date: January 2013
journal: Bioinformatics
doi: <a href="http://dx.doi.org/10.1093/bioinformatics/btt004">10.1093/bioinformatics/btt004</a>
authorship: Second
article: Research
topic: Bioinformatics | TCRs
description: This is the first paper I was on at UCL, where I did my PhD under Prof Benny Chain and Dr Maddy Noursadeghi in the <a href="http://www.innate2adaptive.com/">Innate2Adaptive</a> lab, and is largely the work of Nic Thomas, then a mathematician PhD student in the lab who started just over a year before I did.<p>Decombinator is a tool to analyse deep-sequenced T-cell receptor (TCR) datasets, as are now produced through the use of high-throughput DNA sequencing technologies. Decombinator uses the extremely fast Aho-Corasick string-matching algorithm to determine which V and J genes are used in a given receptor by looking for specific 'tag' sequences, and after finding them reducing the complexity of the sequencing read down into a simple five-part identifier.<p> This article was very much Nic's work, so I only played a minor role - specifically I designed the original tags for analysing the human alpha chain and helped refine the code once a working version was built (mostly debugging and adding a few biological sanity checks, being the first person to use it on the type of longer read data I was generating). I wrote about this work in more detail nearer the time <a href="http://jamimmunology.blogspot.co.uk/2013/08/Decombinator-TCR-repertoire-analysis.html">on my blog</a>.<p> After Nic left the lab I took over maintainence of Decombinator, and updated it to incorporate the error-correcting functionality I developed during my PhD. The current version of the pipeline lives on <a href="https://innate2adaptive.github.io/Decombinator/">the Innate2Adaptive Github repo</a>.
---
