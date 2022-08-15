# Analysing gene 🧬 expression and brain 🧠 images in Alzheimer's Disease

Starting with data from [Bart de Strooper's lab in 2020](https://doi.org/10.1016/j.cell.2020.06.038) [1], which can be found on Synapse [here](https://www.synapse.org/#!Synapse:syn22164713).

Using brains from mouse models of Alzherimer's disease (AD), they captured brain images and quantified the gene expression throughout the brains (called "spatial transcriptomics"). They discovered certain genes were expressed together at certain locations in the brain, and that some genes were expressed more when they were near amyloid plaques. They then confirmed many of their gene expression findings in human brain slices using in-situ sequencing.

Both the mouse and human data are available on [Synapse](https://www.synapse.org/#!Synapse:syn22164713).

The mouse data are more detailed, but is a model of human AD. The human data are more authentic, but they do not probe the expression of as many genes.

## Questions for exploration

- Can the images or spatial gene expression data be used to classify between AD and control brains?
  - If so, which features drive the classification?
- How well correlated are the mouse and human genes? 
  - Gene names/symbols may not be the same, even if particular genes are orthologous (same but from differnt species), so we'd need a lookup table
- Can we use gene expression to map locations of the mouse brain to the human brain? 
  - They are different shapes, but would neighbourhoods of high mouse-human correlation indicate equivalence?
  - Can we find paramters of an image warping model that maximises mouse-human spatial correlation?

## References

[1] Chen et al., Spatial Transcriptomics and In Situ Sequencing to
Study Alzheimer’s Disease, 2020, _Cell_ 182, 976–991, https://doi.org/10.1016/j.cell.2020.06.038
