# fruit-SALAD

**fruit-SALAD** is a synthetic image dataset with 10,000 generated images of fruit depictions. This combined semantic category and style benchmark comprises 100 instances each of 10 easily recognizable fruit categories and 10 easy distinguishable styles. 

The carefully designed Style Aligned Artwork Dataset (SALAD) provides a controlled and balanced platform for the comparative analysis of similarity perception of different computational models. The SALAD framework allows the comparison of how these models perform semantic category and style recognition tasks, going beyond the level of anecdotal knowledge, making them robustly quantifiable and qualitatively interpretable.

We used [Stable Diffusion XL](https://arxiv.org/abs/2307.01952){:target="_blank"} and [StyleAligned](https://arxiv.org/abs/2312.02133){:target="_blank"} to create the fruit-SALAD by carefully crafting text prompts and overseeing the image generation process.

Please note that this dataset is available for academic research purposes only.

![fruit-SALAD_100](overview.png)


### Dataset
You can access the complete fruit-SALAD_10k dataset at [https://doi.org/10.5281/zenodo.11158522](https://doi.org/10.5281/zenodo.11158522){:target="_blank"}.
```
Ohm, T. (2024). fruit-SALAD [Data set]. Zenodo. https://doi.org/10.5281/zenodo.11158522
```

### Code
This repository contains the code to reproduce the fruit-SALAD dataset. Please see the jupyter notebook [generate_fruit_SALAD.ipynb](generate_fruit_SALAD.ipynb) for more details.

