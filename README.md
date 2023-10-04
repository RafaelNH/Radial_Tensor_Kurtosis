# Radial_Tensor_Kurtosis

In this repository, I am sharing the code to process the radial tensor kurtosis from diffusional kurtosis estimates extracted from DIPY's diffusional kurtosis imaging data fit.

Radial Tensor Kurtosis is defined according to [Hansen et al., 2017](https://pubmed.ncbi.nlm.nih.gov/27539807/).

To see how to apply the code to diffusion MRI datasets give a look to the notebook: 
``Radial_tensor_kurtosis_comparison_in_invivo_data.ipynb``

As demonstrated in simulations, radial tensor kurtosis estimates are more robust to implausible negative kurtosis estimates than conventional radial kurtosis, notebook:
``Radial_tensor_kurtosis_comparison_in_simulations.ipynb``
