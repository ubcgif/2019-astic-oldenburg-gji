# A framework for petrophysically and geologically guided geophysical inversion using a dynamic Gaussian mixture model prior

_Thibaut Astic, and Douglas W. Oldenburg_

https://doi.org/10.1093/gji/ggz389

![thumbnail](./paper/thumbnail.png)

## Summary

We propose a new framework for incorporating petrophysical and geological information into voxel-based geophysical inversion. By developing the geophysical inverse problem from a probabilistic perspective, we redesign the objective function and the iteration steps as a suite of cyclic optimization problems in which three separate MAP optimization problems are solved using geophysical, petrophysical and geological data respectively. By quantitatively linking these data into a single framework, we recover a final inverted model that reproduces the observed, or desired, petrophysical and geological features while fitting the geophysical data. To achieve our goal we replace the Gaussian prior, used in the Tikhonov inversion approach, by a Gaussian mixture model. After each geophysical model update, the mixture parameters (means, variances and proportions) are determined by the geophysical model and the expected characteristics of the lithologies through another optimization process using the Expectation-Maximization algorithm. We then classify the model cells into rock units according to the petrophysical and geological information. These two additional steps over the petrophysical and geological data result in a dynamic update of the reference model and associated weights and guide the inversion towards reproducing the expected petrophysical and geological characteristics. The resulting geophysical objective function does not require extra terms to include the additional petrophysical and geological information; this is an important distinction between our work and previous frameworks that carry out joint geophysical and petrophysical data inversion. We highlight different capabilities of our methodology by inverting magnetotelluric and DC resistivity data in 1D and 2D respectively. Finally we apply our framework to inverting airborne frequency domain data, acquired in Australia, for the detection and characterization of saline contamination of freshwater.


## Citation

Thibaut Astic, Douglas W Oldenburg, A framework for petrophysically and geologically guided geophysical inversion using a dynamic Gaussian mixture model prior, Geophysical Journal International, Volume 219, Issue 3, December 2019, Pages 1989–2012, https://doi.org/10.1093/gji/ggz389

```
@article{astic_inversion_2019,
    author = {Astic, Thibaut and Oldenburg, Douglas W},
    title = "{A framework for petrophysically and geologically guided geophysical inversion using a dynamic 
    Gaussian mixture model prior}",
    journal = {Geophysical Journal International},
    volume = {219},
    number = {3},
    pages = {1989-2012},
    year = {2019},
    month = {08},
    issn = {0956-540X},
    doi = {10.1093/gji/ggz389},
    url = {https://doi.org/10.1093/gji/ggz389},
}
```
