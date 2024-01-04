# Awesome-Deep-Machine-Unlearning 

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <img src="https://img.shields.io/badge/Contributions-Welcome-278ea5" alt="Contrib"/>

> A collection of academic articles, published methodology, and datasets on the subject of **machine unlearning**, focusing on deep learning.
> 
> We would like to say thanks to repository of [awesome-machine-unlearning](https://github.com/tamlhp/awesome-machine-unlearning) for their contributions.

## Contents

- [Awesome-Deep-Machine-Unlearning](#awesome-deep-machine-unlearning)
  - [Contents](#contents)
  - [Survey Papers](#survey-papers)
  - [Methods](#methods)
    - [Model-based](#model-based)
    - [Data-based](#data-based)
  - [Datasets](#datasets)
    - [Computer Vision](#computer-vision)
    - [Text](#text)
    - [Tabular Data](#tabular-data)
  - [Contribute](#contribute)


## Survey Papers

We arranged all published (some pre-printed) review papers in descending order of year.

| **Title** | **Year** | **Venue** | **Topic** |
|---------|:--------:|:---------:|:--------:|
|[Knowledge Unlearning for LLMs: Tasks, Methods, and Challenges](https://arxiv.org/abs/2311.15766)| 2023/11         | _Arxiv_          | LLMs |
[A Survey on Federated Unlearning: Challenges, Methods, and Future Directions](https://arxiv.org/abs/2310.20448)| 2023/10           | _Arxiv_         |  Federated Learning         |
[A Survey of Federated Unlearning: A Taxonomy, Challenges and Future Directions](https://arxiv.org/abs/2310.19218)| 2023/10 | _Arxiv_| Federated Learning|
|[A Survey of Graph Unlearning](https://arxiv.org/abs/2310.02164)|2023/10|_Arxiv_| Graph |
|[Machine Unlearning: Solutions and Challenges](https://arxiv.org/abs/2308.07061)|2023/08|_Arxiv_|General|
|[Machine Unlearning: A Survey](https://doi.org/10.1145/3603620)|2023/08|_ACM Computing Surveys_|General|
|[Learn to Unlearn: Insights into Machine Unlearing](https://arxiv.org/abs/2305.07512)| 2023/05| _Arxiv_| General|
|[Exploring the Landscape of Machine Unlearning: A Comprehensive Survey and Taxonomy](https://arxiv.org/abs/2305.06360)|2023/05|_Arxiv_| General|
|[A Survey of Machine Unlearning](https://doi.org/10.1007/s42979-023-01767-4)|2023/04|_SN Computer Science_| General|
|[A Survey of Machine Unlearning](https://arxiv.org/abs/2209.02299)|2022/09|_Arxiv_|General|
| [Machine Unlearning: Its Need and Implementation Strategies](https://dl.acm.org/doi/abs/10.1145/3474124.3474158) |2021/08| _IC3_ | General |
| [“Amnesia” - A Selection of Machine Learning Models That Can Forget User Data Very Fast](https://www.cidrdb.org/cidr2020/papers/p32-schelter-cidr20.pdf) | 2020/01 |_CIDR_ | General | 
| [Humans forget, machines remember: Artificial intelligence and the Right to Be Forgotten](https://www.sciencedirect.com/science/article/pii/S0267364917302091) |2018/04 | _Computer Law & Security Review_ |  Law|
| [Algorithms that remember: model inversion attacks and data protection law](https://doi.org/10.1098/rsta.2018.0083) |2018/10 | _Philosophical Transactions of the Royal Society A_ | Law|
| [Making machine learning forget](https://www.sciencedirect.com/science/article/pii/S0267364917302091)| 2018/04 | _Annual Privacy Forum_ | General |

## Methods

We arranged all published (some pre-printed) review papers in ascending order of year, in order to provide with a clear pipeline of the development of machine unlearning.

### Model-based
| **Title** | **Year** | **Authors** | **Venue** | **Code** | **Dataset** |**Topic** | **Summary** |
|:---------:|:--------:|:-----------:|:---------:|:--------:|:---------:|:-----------:|:-----------:|
|||||||||
|[Eternal Sunshine of the Spotless Net: Selective Forgetting in Deep Networks](https://openaccess.thecvf.com/content_CVPR_2020/papers/Golatkar_Eternal_Sunshine_of_the_Spotless_Net_Selective_Forgetting_in_Deep_CVPR_2020_paper.pdf)| 2020 | Golatkar et al. |_CVPR_|[Code](https://github.com/AdityaGolatkar/SelectiveForgetting)|MNIST, CIFAR, Lacuna (not open), VGGFaces2| |[Intro](short_intro/Eternal_2020_Golatkar.md)|
|[Remember What You Want to Forget: Algorithms for Machine Unlearning](https://arxiv.org/abs/2103.03279)|	2021|	Sekhari et al.|_NeurIPS_|-|-|Theory|[Intro](short_intro/Remember_2021_Sekhari.md)|

### Data-based

| **Title** | **Year** | **Authors** | **Venue** | **Code** | **Dataset** |**Topic** | **Summary** |
|:---------:|:--------:|:-----------:|:---------:|:--------:|:---------:|:-----------:|:-----------:|
|[Towards Making Systems Forget with Machine Unlearning](https://dl.acm.org/doi/10.1109/SP.2015.35) | 2015 | Cao et al. | _S&P_ | - | Collected from Facebook (not open) |Statistical Query Learning, Exact Unlearning  | [Intro](short_intro/Towards_2015_Cao.md)|
|[DeltaGrad: Rapid retraining of machine learning models](https://proceedings.mlr.press/v119/wu20b.html)|	2020|	Wu et al.|	_ICML_	|[Code](https://github.com/thuwuyinjun/DeltaGrad)|MNIST, RCV1, HIGGS|Data Influence, Exact Unlearning | [Intro](short_intro/DeltaGrad_2020_Wu.md)|
|[Certified data removal from machine learning models](https://arxiv.org/abs/1911.03030)| 2020| Guo et al. |_ICML_| [Code](https://github.com/facebookresearch/certified-removal) | MNIST, LSUN, SST, SVHN|Approximate Unlearning, $L_2$-regularisation, Convex, CV, Class-based| [Intro](short_intro/Certified_2020_Guo.md)| 
|[Machine Unlearning](https://ieeexplore.ieee.org/document/9519428)|	2021|	Bourtoule et al.|	_IEEE SSP_| [Code](https://github.com/cleverhans-lab/machine-unlearning) |Purchase, SVHN|Data Partitioning, Exact Unlearning, CV, NLP, Class-based| [Intro](short_intro/Machine_2021_Bourtoule.md)|



## Datasets
### Computer Vision

|    **Name**   | **Dimensionality** | **Size** | **Classes** |
|-------------|:------------------:|:--------:|:-----------:|
| [MNIST](https://yann.lecun.com/exdb/mnist/)         |       28 x 28      |   60000  |      10     |
| [SVHN](http://ufldl.stanford.edu/housenumbers/)          |     32 x 32 x 3    |  604833  |      10     |
| [LSUN](https://github.com/fyu/lsun)| 256 x 256 x 3 | 1262277 | 10 |
| [VGGFaces2]() | Various | 3.3 M | 9000 |
| [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)     |     32 x 32 x 3    |   60000  |     10     |
| [CIFAR-100](https://www.cs.toronto.edu/~kriz/cifar.html)     |     32 x 32 x 3    |   60000  |     100     |
| [ImageNet](https://www.image-net.org/)      |    224 x 224 x 3   |  1281167 |     1000    |
| [Mini-ImageNet](https://paperswithcode.com/dataset/mini-imagenet) |    224 x 224 x 3   |  128545  |     100     |

### Text

|    **Name**   | **Size** | **Classes** |
|-------------|:--------:|:-----------:|
|[RCV1 (Reuters Corpus Volume 1)](https://paperswithcode.com/dataset/rcv1)| 804414| 3|
| [SST](https://nlp.stanford.edu/sentiment/treebank.html)| 215000 | 5 |

### Tabular Data

|    **Name**   | **Dimensionality** | **Size** | **Classes** |
|-------------|:------------------:|:--------:|:-----------:|
| [Purchase](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7256375/)      |         600        |  250000  |      2      |
|[HIGGS](https://archive.ics.uci.edu/dataset/280/higgs)| 28| 11000000| 2|


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
