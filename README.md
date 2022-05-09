<div align="center">
  <img src="resources/mmediting-logo.png" width="500px"/>
</div>

<br/>

[![build](https://github.com/open-mmlab/mmediting/workflows/build/badge.svg)](https://github.com/open-mmlab/mmediting/actions)
[![docs](https://readthedocs.org/projects/mmediting/badge/?version=latest)](https://mmediting.readthedocs.io/en/latest/?badge=latest)
[![codecov](https://codecov.io/gh/open-mmlab/mmediting/branch/master/graph/badge.svg)](https://codecov.io/gh/open-mmlab/mmediting)
[![license](https://img.shields.io/github/license/open-mmlab/mmediting.svg)](https://github.com/open-mmlab/mmediting/blob/master/LICENSE)

## Adjust for HM dataset

This fork is based in the `HimariO` solution for the Hateful memes competition by Facebook. The main idea of this repository is clear (inpainting) the meme dataset from text. This will be done in 4 steps:

1. Detect text via OCR.
2. Put boxes coordenates where the text was detected.
3. Generate mask where the text was detected.
4. Inpainting the zone that where the mask.

You could see how to reproduce the result in the following [notebook](https://colab.research.google.com/drive/1XBiNhKOV4uv532swUWaXcT_VatU7qGl2#scrollTo=Z7qV3YHGyPqj)

## Introduction

MMEditing is an open source image and video editing toolbox based on PyTorch. It is a part of the [OpenMMLab](https://open-mmlab.github.io/) project.

The master branch works with **PyTorch 1.3 to 1.6**.

Documentation: https://mmediting.readthedocs.io/en/latest/.

<div align="left">
  <img src="resources/mmediting-demo.jpg"/>
</div>

### Major features

- **Modular design**

  We decompose the editing framework into different components and one can easily construct a customized editor framework by combining different modules.

- **Support of multiple tasks in editing**

  The toolbox directly supports popular and contemporary *inpainting*, *matting*, *super-resolution* ang *generation* tasks.

- **State of the art**

  The toolbox provides state-of-the-art methods in inpainting/matting/super-resolution/generation.


## License

This project is released under the [Apache 2.0 license](LICENSE).

## Changelog

v0.5 was released in 09/07/2020.

Note that **MMSR** has been merged into this repo, as a part of MMEditing.
With elaborate designs of the new framework and careful implementations,
hope MMEditing could provide better experience.

## Benchmark and model zoo

Please refer to [model_zoo.md](docs/model_zoo.md) for more details.

## Installation

Please refer to [install.md](docs/install.md) for installation.


## Get Started

Please see [getting_started.md](docs/getting_started.md) for the basic usage of MMEditing.

## Contributing

We appreciate all contributions to improve MMEditing. Please refer to [CONTRIBUTING.md in MMDetection](https://github.com/open-mmlab/mmdetection/blob/master/.github/CONTRIBUTING.md) for the contributing guideline.

## Acknowledgement

MMEditing is an open source project that is contributed by researchers and engineers from various colleges and companies. We appreciate all the contributors who implement their methods or add new features, as well as users who give valuable feedbacks. We wish that the toolbox and benchmark could serve the growing research community by providing a flexible toolkit to reimplement existing methods and develop their own new methods.
