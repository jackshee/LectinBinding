# Summary

This repository leverages the glycowork package to analyze lectin-glycan interactions, with applications in nanobiosensor development for pancreatic cancer detection. Glycoinformatics is the computational study of glycans and is critical because:

 - Glycans (sugar chains) decorate cell surfaces and play key roles in cancer progression, immune evasion, and metastasis
 - Lectins are proteins that bind glycans with high specificity making them ideal for nanobiosensor design where lectins act as biorecognition elements to capture cancer-associated glycans.

This project aims to analyse and apply glycowork's deep learning models to find lectins that are specific to CA 19-9 with the sialyl-lewis A (sLeA) motif. Currently, the most well understood class of lectins that bind to sLeA are selectins. Using generative models to simulate protein structures that mimic selectins could be useful in generating novel proteins that have similar function which can then be repurposed as nanobiosensors.

![Binding Plot](figures/binding.png)

# References 
-  https://bojarlab.github.io/glycowork/core.html
-  Lundstrøm, J., Korhonen, E., Lisacek, F., Bojar, D., 2022. LectinOracle: A Generalizable Deep Learning Model for Lectin–Glycan Binding Prediction. Advanced Science 9, 2103807. https://doi.org/10.1002/advs.202103807
