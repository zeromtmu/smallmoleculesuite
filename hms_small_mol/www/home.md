# HMS-LINCS Small Molecule Suite Applications

<br><br>
<div class = "ui equal width stackable grid">
<div class = "row" style = "padding: 0px">
<div class = "stackable column">
<div class = "ui basic center aligned segment" style = "font-size: large; font-weight: bold; padding: 0px; margin: 0px;">
<a href = "/apps/SelectivitySelectR/" style = "color:#EC4353;">
<img src = "gene.png" height = "100"><br><br>
</a>
</div>
</div>

<div class = "stackable column">
<div class = "ui basic center aligned segment" style = "font-size: large; font-weight: bold; padding: 0px; margin: 0px;">
<a href = "/apps/SimilaritySelectR/" style = "color: #00AC9F;">
<img src = "small_molecule.png" height = "100"><br><br>
</a>
</div>
</div>

<div class = "stackable column">
<div class = "ui basic center aligned segment" style = "font-size: large; font-weight: bold; padding: 0px; margin: 0px;">
<a href = "/apps/LibraryR/" style = "color: orange">
<img src = "library.png" height = "100"><br><br>
</a>
</div>
</div>
</div>

<div class = "row" style = "padding: 0px">
<div class = "stackable column">
<div class = "ui basic left aligned segment" style = "font-size: medium;">
<p>&emsp;&emsp;<b><a href = "/apps/SelectivitySelectR/" style = "color:#EC4353;">SelectivitySelectR</a></b> shows the affinity and selectivity of compounds in the <a href = "http://lincs.hms.harvard.edu/db/sm/">HMS-LINCS collection</a> for a gene of interest. To use SelectivitySelectR, first select your target of interest and binding criteria. Subsequently, select a region in the main plot with compounds of your interest. You can then select three compounds in the bottom table and view their known binding affinities in detail.</p>
</div>
</div>

<div class = "stackable column">
<div class = "ui basic left aligned segment" style = "font-size: medium;">
<p>&emsp;&emsp;<b><a href = "/apps/SimilaritySelectR/" style = "color: #00AC9F;">SimilaritySelectR</a></b> shows the similarity of compounds in the <a href = "http://lincs.hms.harvard.edu/db/sm/">HMS-LINCS collection</a> to a reference compound. Similarity is regarded in threefold: structural similarity (Tanimoto similarity of Morgan2 fingerprints), target affinity spectrum similarity (TAS) and phenotypic fingerprint similarity (PFP). To use SimilaritySelectR, select a reference compound and adjust filters as desired. From the main plots, select a region with compounds of interest. Then, select up to three compounds in the bottom table and view their known binding affinities in detail.</p>
</div>
</div>

<div class = "stackable column">
<div class = "ui basic left aligned segment" style = "font-size: medium;">
<p>&emsp;&emsp;<b><a href = "/apps/LibraryR/" style = "color: orange">LibraryR</a></b> composes custom chemical genetics libraries for gene-sets of interest. Compounds in the library are selected based on affinity, selectivity, structural similarity and clinical development phase. Additionally we source several expert opinion "best-in-class" lists. To use LibraryR, simply submit a list of genes for which the library should be designed, or load one of the example gene-sets, click 'Submit' and adjust the inclusion criteria to fit your research purpose. The library will be adjusted based on the input genes and inclusion criteria.
</p>
</div>
</div>

</div>
</div>

# Development and links

Design/idea by [Nienke Moret](https://scholar.harvard.edu/nienkemoret) and [Marc Hafner](https://scholar.harvard.edu/hafner) (HMS - LINCS data and signature generation center)<br>
R code by [Nienke Moret](https://scholar.harvard.edu/nienkemoret) (HMS - LINCS data and signature generation center)<br>
Shiny/R web application development by [Nicholas Clark](https://github.com/NicholasClark) (U of Cincinnati - LINCS data coordination and integration center)<br>
Supervision by [Peter Sorger](https://sorger.med.harvard.edu/people/peter-sorger-phd/) (HMS - LINCS data and signature generation center)<br>
Icon design and development by [Vasileios Stathias](http://ccs.miami.edu/team_member/vasileios-vas-stathias/) (U of Miami - LINCS data coordination and integration center)

This work was supported by NIH grants **U54-HL127365**, **U24-DK116204** and **U54-HL127624**.