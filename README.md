# Experimental-cs
This repo was created to document the experimental case study carried out in the short paper submitted for Deep Learning Indaba, 2023.
Cc. 

## Short paper Title - Advancements and Applications of AI in Drug Discovery: A Comprehensive Review and Experimental Case Study
For the experimental case study, an already-built model by [Beker et al., 2020.](https://github.com/Nanotekton/drugability/tree/v0.1) incorporated into the [Ersilia model hub](https://github.com/ersilia-os/eos9sa2) was used to perform the case study. 
This model predicts the drug-likeness of a chemical compound. In normal research, whereby you extract your compounds to be screened for the physicochemical properties of a drug, this model comes in handy. Both for virtual screening and compound selection.
To test this model, [Zinc dataset](https://tdcommons.ai/generation_tasks/molgen/#zinc) was extracted from the [Therapeutics common dataset](https://tdcommons.ai/). The **drug-likeness** of the *zinc molecules* was generated with the **druggability model**.
This case study is more of an ML model implementation in a drug discovery pipeline. 

### References
1. Beker, W., Wołos, A., Szymkuć, S., & Grzybowski, B. A. (2020). Minimal-uncertainty prediction of general drug-likeness based on Bayesian neural networks. Nature Machine Intelligence, 2(8), 457-465. https://doi.org/10.1038/s42256-020-0209-y
2. Turon, G., Duran-Frigola, M. (2022). Ersilia Model Hub: a repository of AI/ML Models for neglected tropical diseases.
version: 1.0.0, doi: 10.5281/zenodo.7274646, url: "https://github.com/ersilia-os/ersilia"
3. Sterling, Teague, and John J. Irwin. “ZINC 15–ligand discovery for everyone.” Journal of chemical information and Modeling 55.11 (2015): 2324-2337.
4. Gómez-Bombarelli, Rafael, et al. “Automatic chemical design using a data-driven continuous representation of molecules.” ACS central science 4.2 (2018): 268-276.
5. Huang, K., Fu, T., Gao, W., Zhao, Y., Roohani, Y., Leskovec, J., Coley, C. W., Xiao, C., Sun, J., & Zitnik, M. (2022). Artificial intelligence foundation for therapeutic science. Nature Chemical Biology, 18(10), 1033-1036. https://doi.org/10.1038/s41589-022-01131-2
6. Huang, K., Fu, T., Gao, W., Zhao, Y., Roohani, Y., Leskovec, J., Coley, C. W., Xiao, C., Sun, J., & Zitnik, M. (2021). Therapeutics Data Commons: Machine Learning Datasets and Tasks for Drug Discovery and Development. ArXiv. /abs/2102.09548 
