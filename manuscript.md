---
author-meta:
- Simon J. van Heeringen
date-meta: '2018-08-01'
keywords:
- transcription factor
- ChIP-seq
- regulatory motif
- TF motif
lang: en-US
title: 'GimmeMotifs: '
...






<small><em>
This manuscript
([permalink](https://simonvh.github.io/gimmemotifs-manuscript/v/b8efae039bdd034a13c18d4cbdeb4736ec37ffa3/))
was automatically generated
from [simonvh/gimmemotifs-manuscript@b8efae0](https://github.com/simonvh/gimmemotifs-manuscript/tree/b8efae039bdd034a13c18d4cbdeb4736ec37ffa3)
on August 1, 2018.
</em></small>

## Authors



+ **Simon J. van Heeringen**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0002-0411-3219](https://orcid.org/0000-0002-0411-3219)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [simonvh](https://github.com/simonvh)
    · ![Twitter icon](images/twitter.svg){height="13px" width="13px"}
    [svheeringen](https://twitter.com/svheeringen)<br>
  <small>
     Radboud University, Faculty of Science, Department of Molecular Developmental Biology, Radboud Institute for Molecular Life Sciences, 6500 HB Nijmegen, The Netherlands
     · Funded by Grant XXXXXXXX
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
