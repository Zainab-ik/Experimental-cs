# Experimental-cs
This repo was created to document the experimental case study carried out in the short paper submitted for Deep Learning Indaba, 2023.
Cc. @[Mary Adewunmi](https://github.com/) @[Josiah Isong](https://github.com/isongjosiah) Groupname: [caresAi](https://github.com/caresAi)

## Short paper Title - Advancements and Applications of AI in Drug Discovery: A Comprehensive Review and Experimental Case Study
For the experimental case study, an already-built model by [Beker et al., 2020.](https://github.com/Nanotekton/drugability/tree/v0.1) incorporated into the [Ersilia model hub](https://github.com/ersilia-os/eos9sa2) was used to perform the case study. 
This model predicts the drug-likeness of a chemical compound. In normal research, whereby you extract your compounds to be screened for the physicochemical properties of a drug, this model comes in handy. Both for virtual screening and compound selection.
To test this model, our benchmark dataset [test molecules](https://moleculenet.org/datasets-1) was extracted from the [MoleculeNet](https://moleculenet.org/). The **drug-likeness** of the *test molecules* was generated with the **druggability model**.
This case study is more of an ML model implementation in a drug discovery pipeline. 

### Software used
1. Operating system Ubuntu; Ersilia only works well on CLI
2. Microsoft Excel to view your dataset and results.

### References
1. Beker, W., Wołos, A., Szymkuć, S., & Grzybowski, B. A. (2020). Minimal-uncertainty prediction of general drug-likeness based on Bayesian neural networks. Nature Machine Intelligence, 2(8), 457-465. https://doi.org/10.1038/s42256-020-0209-y
2. Turon, G., Duran-Frigola, M. (2022). Ersilia Model Hub: a repository of AI/ML Models for neglected tropical diseases.
version: 1.0.0, doi: 10.5281/zenodo.7274646, url: "https://github.com/ersilia-os/ersilia"
3. Zhenqin Wu, Bharath Ramsundar, Evan N. Feinberg, Joseph Gomes, Caleb Geniesse, Aneesh S. Pappu, Karl Leswing, Vijay Pande, MoleculeNet: A Benchmark for Molecular Machine Learning, arXiv preprint, arXiv: 1703.00564, 2017.
4. Ramsundar, B., Eastman, P., Walters, P., Pande, V., Leswing, K., & Wu, Z. (2019). Deep Learning for the Life Sciences. O'Reilly Media. Retrieved from https://www.amazon.com/Deep-Learning-Life-Sciences-Microscopy/dp/1492039837.
