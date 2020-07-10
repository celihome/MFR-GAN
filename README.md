# MFR-GAN
This repository is implementation of the "Muti-scale Deep Feature Representation Based on SR-GAN for Low Resolution Person Re-identiﬁcation"

### Prepare the initial models and dataset.
> Download the [VGG model](https://pan.baidu.com/s/17164p0is8rc1G092dAmd6A) to current folder.

> Download the [Basic Re-id model](https://pan.baidu.com/s/1C4MtuUvo-jZdP1FIiIbXXQ), pre-trained on Market-1501, to current folder.

> Download the [dataset](https://pan.baidu.com/s/1OVOAR6Ga9qHCvi4RsgVXkA) to `.\dataset\`.

### Prerequisites
python 3.6

tensorflow 1.14.0

GPUs,memory>11G

### Train 
> Run `python train.py`

### Extract Feature.
> Run `python get_feature.py`
