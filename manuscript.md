---
author-meta:
- John Doe
- Jane Roe
date-meta: '2018-08-01'
keywords:
- markdown
- publishing
- manubot
lang: en-US
title: 'Manubot Rootstock: Manuscript Title'
...






<small><em>
This manuscript
([permalink](https://simonvh.github.io/gimmemotifs-manuscript/v/3b000d98850a9345b656bbc1af3f19480b0dfbb8/))
was automatically generated
from [simonvh/gimmemotifs-manuscript@3b000d9](https://github.com/simonvh/gimmemotifs-manuscript/tree/3b000d98850a9345b656bbc1af3f19480b0dfbb8)
on August 1, 2018.
</em></small>

## Authors



+ **John Doe**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [johndoe](https://github.com/johndoe)
    · ![Twitter icon](images/twitter.svg){height="13px" width="13px"}
    [johndoe](https://twitter.com/johndoe)<br>
  <small>
     Department of Something, University of Whatever
     · Funded by Grant XXXXXXXX
  </small>

+ **Jane Roe**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [janeroe](https://github.com/janeroe)<br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>



## Abstract {.page_break_before}




# Introduction

The regulatory networks that determine cell and tissue identity are robust, yet
remarkably flexible. Transcription factors (TFs) control the expression of genes
by binding to their cognate DNA sequences, TF motifs, in cis-regulatory
elements. To understand how genetic variation affects binding and to elucidate
the role of TFs in regulatory networks we need to be able to accurately model
binding of TFs to the DNA sequence.

The most widely adopted representation of TF binding is the position frequency
matrix (PFM). This matrix, a TF motif, contains (normalized) frequencies of each
nucleotide at each position in a collection of aligned binding sites. These PFMs
can be derived from high-throughput experiments such as ChIP-sequencing,
HT-SELEX or Protein Binding Microarrays (PBMs). 

Even though the PFM is a convenient representation, it has certain limitations.
A PFM cannot model inter-nucleotide dependencies, that are known to affect
binding of certain TFs. Multiple different representations have been proposed
[@Jc96vlRF; @1F4IFj9vd; @7nxD51Mq; @nswYGz33; @1FTeX7ahA],
however, no single one of these has gained much traction.  

Here, we present GimmeMotifs, a Python module and set of command-line tools for
TF motif analysis. Amongst other possibilities it can be used to perfom *de
novo* motif analysis, calculate enrichment statistics and identify differential
motifs. We illustrate the functionality of GimmeMotifs using three different
examples.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
