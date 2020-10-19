# Marine Microbiology: Computational pathway analysis

## Tutorial: Proteins in L-serine and L-glycine synthesis

The aim with this tutorial is to show you how to find proteins that you can search for as markers of a certain metabolism.
I will exemplify with synthesis of two small amino acids that are related to each other in how they're produced: L-serine and L-glycine.

Briefly, I will show how to find information about a pathway, identify enzymes that are good markers for the pathway and find search tools that you can apply to nucleotide sequence data such as metagenomes or metatranscriptomes.

### Pathway databases

The first step will be to find information about the metabolic pathway used to synthesize the two amino acids.
Metabolic pathway information can be found in two online databases: [Kyoto Encyclopedia of Genes and Genomes (KEGG)](https://www.kegg.jp) and the [BioCyc Database Collection](https://biocyc.org).
I'm going to use the latter, but I encourage you to also check out KEGG.

BioCyc is a collection of organism specific metabolic and genomic databases.
This means you choose which organism you want to work with (click the link "change organism database" in the top right corner) and then get access to information about its metabolic capacity (plus many more things!).
Different organisms have different metabolic capacities and may also differ in how pathways are built.
Besides the organism specific databases, [MetaCyc](https://metacyc.org) is a collection of *all* pathways.

To make things clearer, I will use the *E. coli* K-12 database [EcoCyc](https://ecocyc.org) in this tutorial, even though MetaCyc would give us a more complete picture.

#### Finding the L-serine and L-glycine synthesis pathway in *E. coli*

* Open [EcoCyc](https://ecocyc.org)

* Search for "glycine" (top right corner)

* Select "superpathway of L-serine and glycine biosynthesis I" under "Pathways"

* Change "Detail level" to "Main compound structures"

![Serine/Glycine superpathway](img/ecocyc_serine_glycine_main_strcts.png)

In the above pathway you can see how L-serine is synthesized from 3-phospho-D-glycerate in three steps.
A key step is when the amino group in L-serine is donated from a glutamate in step two.
After L-serine is synthesized, L-glycine is synthesized by extraction of the side chain, making it four steps for the total pathway.

I have marked three key concepts with red ellipses: The enzyme/protein name, the gene name and the Enzyme Commission (EC) number.
They will be important when we start searching for the enzymes and proteins.

It is a bit of an art to study a pathway and identify which steps and enzymes might be good candidates as markers for the pathway, as, in many cases, different pathways cross each other so that reactions and compounds participate in many pathways.
Moreover, reactions in pathways do not necessarily run in only one direction but are equilibrium reactions whose direction are determined by the concentrations of compounds on either side of the reaction.
In the L-serine and L-glycine pathway as described in EcoCyc, you can see that all arrows except one have arrowheads on both sides, indicating they're equilibrium reactions.

### Protein databases

### Protein profile databases
