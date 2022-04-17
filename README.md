#### Hello! I am David
I am a [PhD candidate in the Bioinformatics group at Wageningen University](https://www.wur.nl/en/Persons/David-D-David-Meijer-MSc.htm), under the supervision of Dr Marnix Medema and Dr Justin van der Hooft. My interests revolve around the relationship between genotype and metabolome, and I'd like to improve genome mining efforts by inferring what secondary metabolites are produced by what biosynthetic gene clusters.

#### Interests
Secondary metabolism | Genome mining | Machine learning | Deep learning

#### Why are secondary metabolites, or natural products, so interesting? 
All sorts of organisms, like microbes, fungi, sponges, and plants, produce compounds to fend off competition, attract partners for symbiotic relationships, or protect oneself. Nature has perfected this chemistry over the course of billions of years of evolution, providing us now with a chemical space that contains a high variety of complex but potent molecules (e.g., antibiotics, surfactants, and pigments). The only problem is that nature is incredibly vast and we don't have the means right now to explore it adequately... 

#### What do we need to explore nature's potential more easily?
Genome mining tools like [antiSMASH](https://antismash.secondarymetabolites.org/) can readily mine genomes for coding biosynthetic gene clusters and annotate those as well. However, it is often still unclear what compounds these clusters are responsible for. If we would know what compounds mined clusters likely produce and what mode of action those compounds deploy, we can target producing organisms in a more profitable way. Additionally, if we know what genomic sequence codes for what enzymatic machinery, and how that translates to what compound, we can use that knowledge to bioengineer biosynthetic gene clusters more effectively in order to produce complex compounds by deploying nature's machinery.    

#### How am I hoping to contribute?
* Currently, I am using message passing neural networks (MPNNs) to learn biologically relevant molecular conformers in order to improve bioactivity prediction. The manuscript is still a work in progress, but you can already have a look at [an online repository](https://donphan-database.github.io/#/Molecule) I made that houses a previously in-house dataset of compounds with bioactivity labels.
* I am also working on a graph neural network (GNN) link predictor for predicting regioselectivity of tailoring enzymes on natural product scaffold structures. This Tailoring Enzymes Regioselectivity Predictor (TERP) is still a work in progress. I will present TERP this May in Copenhagen, Denmark at the [Natural Products (Meta)Genome Mining](https://cph-bioscience.com/en/events/natural-products-genome-mining) meeting and in June at the [International Conference on Chemical Structures](https://iccs-nl.org/) in Noordwijkerhout, The Netherlands. 
* Another project I am working on is a platform for researching polyketide backbone motifs. We will use this [platform](https://github.com/davidmeijer/monomer_aligner) for finding and investigating common polyketide substructure motifs.
* Finally, another bigger project I am collaborating on is on linking cryptic biosynthetic gene clusters to mass spectra of produced compounds. We will present our early findings this May also in Copenhagen, Denmark at the [Natural Products (Meta)Genome Mining](https://cph-bioscience.com/en/events/natural-products-genome-mining) meeting.

#### Other projects I am working on
* Check out the website I made for the Van der Hooft Computational Metabolomics group [here](https://vdhooftcompmet.github.io/). I also created a template you can easily use to create your own group website which you can find [here](https://github.com/vdhooftcompmet/group-website).
* I like to experiment with 3D molecular visualization tools and write wrappers for them to fit my needs. I made a [wrapper around 3dmol.js](https://github.com/davidmeijer/mol2html), a molecule [ray-tracer](https://github.com/davidmeijer/molray), and a [wrapper around PyVista for making molecule gifs](https://github.com/davidmeijer/pyvista-molecule).
