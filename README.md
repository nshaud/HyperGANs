# HyperGANs

Code for the paper *Generative adversarial networks for realistic synthesis of hyperspectral samples*.


![http://www.onera.fr/en/dtim](https://lut.im/qwL8UPM0en/soXh7XtiPp4IoML8.png)
![https://www-obelix.irisa.fr/](https://lut.im/D9OHdqk6rK/Mod6HUGCtwjY00Vk.png)
![](https://lut.im/5UpsUhIzgE/Fa6XCquMRsnHwjHu.png)

Please cite the following if you use this code in your work.
```
@inproceedings{audebert_generative_2018,
    title = {Generative adversarial networks for realistic synthesis of hyperspectral samples},
    booktitle = {2018 {IEEE} {International} {Geoscience} and {Remote} {Sensing} {Symposium} ({IGARSS})},
    author = {Audebert, N. and Le Saux, B. and Lefèvre, S.},
    month = jul,
    year = {2018} } 
```

## Motivation

Hyperspectral imaging allows remote sensing experts to access the spectral signatures of the materials on the ground.
This makes hyperspectral cameras the perfect tools for land cover mapping. However, available hyperspectral datasets are rare
and weakly labeled. This makes training data hungry algorithms on such datasets challenging.

In this work, we investigate the use of Generative Adversarial Networks for hyperspectral sample synthesis.

## Code

This Jupyter notebook relies on PyTorch and implements a [Wasserstein GAN](https://arxiv.org/abs/1701.07875) using an auxiliary classifier.

![Proposed GAN architecture](https://framapic.org/HAQRmNhRQeEG/WhRgseZEFcsl)

The datasets can be downloaded through [this website](http://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes).

## License

Code (scripts and Jupyter notebooks) are released under the GPLv3 license for non-commercial and research purposes **only**. For commercial purposes, please contact the authors.

See `LICENSE.md` for more details.
