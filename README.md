
## Introduction

The code is being reformatted for better readability!
A major update will come soon!

## Installation

TAM is built on [MMetection](https://github.com/open-mmlab/mmdetection).

Please refer to [Installation](https://github.com/open-mmlab/mmdetection/docs/en/get_started.md/#Installation) for installation instructions.

## Getting Started

Please see [get_started.md](https://github.com/open-mmlab/mmdetection/docs/en/get_started.md) for the basic usage of MMDetection.


Training TAM (baseline=ATSS):

```shell
python tools/train.py \
    configs/TAM/TAM_jiaoti_atss_r50_fpn_1x_coco.py 
```


## Model Zoo


| Model        | Backbone    | mAP(%) | Download                                                               |
|--------------|-------------|--------|------------------------------------------------------------------------|
| `ATSS+TAM`   | ResNet-50   | 40.9   | [提取码：dk7t](https://pan.baidu.com/s/1bHaFRWVGP1COz_vMXNkRzw?pwd=dk7t)   |
| `DyHead+TAM` | ResNeXt-101 | 49.9   | [提取码：ddqq](https://pan.baidu.com/s/1JqaKUwqM0LpefdIeqSXOkQ?pwd=ddqq)   |

