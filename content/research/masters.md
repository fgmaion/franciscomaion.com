---
draft: false
featuredImage: "/img/grafico_1.png"
tags: 
- Redshift-Space Distortions
- Spectroscopic Surveys
- Window Function
menu:
    main:
        identifier: "Masters"
        weight: 101
        parent: "research"
---

# Constraining the matter growth-rate using VIPERS

During my masters I worked with spectroscopic surveys, mainly to develop an analysis pipeline inside the research group led by Prof. Raul Abramo. I implemented recipes to estimate the power spectra using optimal weights and correct these estimates for systematic distortions. I also wrote a code to compute the window function of the survey and incorporate its effects into the theoretical model for the power spectrum, in order to obtain unbiased constraints on cosmological parameters. I applied this pipeline to the public dataset of the VIPERS survey, obtaining constraints on the matter growth-rate at redshifts z=0.55, 0.7 and 0.9, which are shown in the figures below.

{{< figure src="/img/grafico_1.png" class="img-fluid" caption="**Figure 1**: Observing mask of the VIPERS survey. This mask is quite complex due to selection effects, and the geometry of the CCD plates themselves. This figure was made using data publicly available at http://vipers.inaf.it/.">}}

</br>

{{< figure src="/img/grafico_2.png" class="img-fluid" caption="**Figure 2**: Comparison between measurements of the power-spectrum multipoles from VIPERS dataset and the theoretical model at the best fit values of the parameters." >}}
</br>

{{< figure src="/img/grafico_3.png" class="img-fluid" caption=" **Figure 3**: Compilation of measurements of σ. The stars in red show our measurements, and the stars in green show previous measurements done using the VIPERS dataset." >}}
</br>

{{< button url="https://www.teses.usp.br/teses/disponiveis/43/43134/tde-02092021-150358/publico/Maion_Francisco_Dissertation.pdf" text="Download the full thesis" >}}



