
### **Galaxy: Illuminating Plant Biology throught Isoform Analysis and Beyond**

---

### Index of contents

- 1. Introduction
- 2. Galaxy workflow
- 3. Preliminary results

---

<span class="menu-title" style="display: none"> What do we mean by non-canonical ORFs?</span>

#### What are non-canonical isoforms?

<img src="img/expression_distribution.png" alt="drawing" width="600"/>
<p  style="font-size:20px">Mean Ribo-Seq expression and Ribo-Seq expression standard deviation (SD). </p>
<p style="font-size:14px;">Source: Erady, Chaitanya, et al. "Pan-cancer analysis of transcripts encoding novel open-reading frames (nORFs) and their potential biological functions." NPJ Genomic Medicine 6.1 (2021): 4.</p>

---

<span class="menu-title" style="display: none">How identify non-canonical ORFs?</span>

### How identify non-canonical isoforms?

<img src="img/isoform_switching.jpg" alt="drawing" width="600"/>

---

<span class="menu-title" style="display: none">Galaxy Workflow</span>

#### Galaxy Workflow

<img src="img/simple_workflow.png" alt="drawing" width="700"/>
<p  style="font-size:20px">Full detailed explanation in the <a href="https://gxy.io/GTN:T00345">Genome-wide alternative splicing analysis</a> Galaxy training. </p>

---

#### Mapping and identication of novel splicing sites with RNASTAR

<img src="img/STAR_pipeline.png" alt="drawing" width="900"/>
<p style="font-size:14px;">Two-pass alignment enables sequence reads to span novel splice junctions by fewer nucleotides, conferring greater read depth and providing significantly more accurate quantification of novel splice junctions.</p>

---

#### Reference-based transcriptome assembly and quantification with StringTie

<img src="img/stringtie_pipeline.png" alt="drawing" width="1000"/>
<p style="font-size:14px;">StringTie is a fast and highly efficient assembler of RNA-seq alignments into potential transcripts.</p>

---

#### Isoform switching and functional analysis with IsoformSwitchAnalyzeR

<img src="img/isoformswitch_pipeline.png" alt="drawing" width="1000"/>
<p style="font-size:14px;">IsoformSwitchAnalyzieR performs the differential isoform usage analysis by using DEXSeq.</p>

---

#### Isoform switching and functional analysis with IsoformSwitchAnalyzeR

<img src="img/consequences_plot.png" alt="drawing" width="500"/>
<p style="font-size:14px;">To analyze large-scale patterns in predicted IS consequences, IsoformSwitchAnalyzeR computes all isoform switching events resulting in a gain/loss of a specific consequence (e.g. protein domain gain/loss).</p>
</span>

---

<span class="menu-title" style="display: none">Preliminary results</span>

#### Isoform switching and functional analysis with IsoformSwitchAnalyzeR

<div class="r-stack">
<span class="fragment fade-out" data-fragment-index="0">
<img src="img/FBXO4.png" alt="drawing" width="700"/>
<p style="font-size:14px;">The complete analysis can be found in this <a href="https://usegalaxy.eu/u/gallardoalba/h/genome-wide-splicing-history">Galaxy history</a>.</p>
</span>
<span class="fragment" data-fragment-index="0">
<img src="img/fbxo4_information.png" alt="drawing" width="700"/>
<p style="font-size:14px;">The complete analysis can be found in this <a href="https://usegalaxy.eu/u/gallardoalba/h/genome-wide-splicing-history">Galaxy history</a>.</p>
</span>
</div>

---

Thanks for you attention!
