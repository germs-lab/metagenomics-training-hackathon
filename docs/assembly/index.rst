=================
Assembly Analysis
=================

* Short reads
* Long reads
* Hybrid
* Data reduction / Clustering / Dereplication

Links to resources that cover several for the above topics
----------------------------------------------------------
* `Dutilh Assembly <http://www.nbic.nl/uploads/media/Day3_Dutilh_Metagenome_assembly_2013.pdf>`_
* `Assembly <https://drive.google.com/open?id=0B-b6Xw3NFeyKWjIyTFVtUEhuSkk>`_
* `EDAMAME workshop <https://github.com/edamame-course/2015-tutorials/blob/master/final/2015-06-25-assembling_your_metagenome.md>`_

Learning Objectives
-------------------

Comprehension
-------------
* Students can list assembly methods (Overlap-Layout-Consensus; De Bruijn graphs; hybrid methods) and explain the (dis-)advantages
* Computational requirements
* Read length
* Basic types of assembly parameters (overlap length/kmer; identity
* Students should be aware that shotgun metagenomic data can be assembled
* Know that assembly requires high computational resources
* Know that assembly can improve annotation (longer sequences, less data so more sensitive homology annotation)
* Know that assembly can lead to chimeras
* Understand that assembly collapses at the lower taxonomic levels
* Students can interpret assembly results

Application
-----------
During the hands-on workshop, students will learn to:
* Create a k-mer profile of a metagenome and use it to assess whether assembly could be feasible
* Apply different assembly programs and understand program parameters
* List and apply metagenome assembly quality assessment measures (tool: Quast)
* How many reads from the original metagenome dataset map back to the assembly?
* N50 (length-based only)
* NGA50 (based on aligned to reference)
* % of ref genome covered
* misassemblies
* Evaluate assemblies and compare assembly results from different programs and/or parameter settings (tool: ALE)

For mock (or biome with good reference genomes) dataset by mapping contigs back to reference
* For paired reads by mapping reads back to contigs
Decide which is best

Synthesis
---------
* Students can explain when assembly would be a good approach in a metagenomic study 
* Students can design a metagenomic study involving assembly
* Following the course students will be able to critically review a metagenomics study involving assembly
* Assess whether assembly was the right approach to use considering biological question
* Assess how good the assembly was: were assembly quality checks incorporated? Did the assembly represent the metagenome?

ASSEMBLY is closely related to BINNING but we have not included that here. Assembly-binning-reassembly could be a pipeline.