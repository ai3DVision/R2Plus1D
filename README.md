# R(2+1)D and Mixed-Convolutions for Action Recognition

![r2plus1d1](https://raw.githubusercontent.com/dutran/R2Plus1D/master/r2plus1d.png)

[[project page](https://dutran.github.io/R2Plus1D/)] [[paper](https://arxiv.org/abs/1711.11248)]

If you find this work helpful for your research, please cite:

D. Tran, H. Wang, L. Torresani, J. Ray, Y. LeCun and M. Paluri. **A Closer Look at Spatiotemporal Convolutions for Action Recognition.** IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2018.

```
@inproceedings{r2plus1d_cvpr18,
    title = {A Closer Look at Spatiotemporal Convolutions for Action Recognition},
    author = {Du Tran and Heng Wang and Lorenzo Torresani and Jamie Ray and Yann LeCun and
               Manohar Paluri},
    booktitle = {CVPR},
    year = 2018
}
```
If you have any question or feedback about the code, please contact: trandu@fb.com, hengwang@fb.com. 

## Requirements
R2Plus1D requires the following dependencies:
* [Caffe2](https://caffe2.ai) and its dependencies.
* [OpenCV](https://opencv.org) (tested on 3.4.1) and [ffmpeg](https://trac.ffmpeg.org).
* And lmdb, python-lmdb, and pandas.

## Installation
* You need to install ffmpeg, OpenCV, and caffe2. Caffe2 installation instructions can be found [here](https://caffe2.ai/docs/getting-started.html). You also need to install lmdb, python-lmdb, and pandas.


## Tutorials
We provide some basic tutorials for you to get familar with the code and tools.
* [Training Kinetics from scratch](tutorials/kinetics_train.md)
* [Finetuning R(2+1)D on HMDB51](tutorials/hmdb51_finetune.md)
* [Dense prediction](tutorials/dense_prediction.md)
* [Feature extraction](tutorials/feature_extraction.md)
* [Download and evaluate pre-trained models](tutorials/models.md)


## License
R2Plus1D is Apache 2.0 licensed, as found in the LICENSE file.
