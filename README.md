# Adaptive Data-Free Quantization [CVPR 2023]
This repository is the official code for the paper "Adaptive Data-Free Quantization" by Biao Qian, Yang Wang (corresponding author: yangwang@hfut.edu.cn), Richang Hong, Meng Wang (CVPR 2023, Vancouver, Canada).


## Dependencies
* python3.6
* pytorch1.3.1
* cuda10.0
* lmdb

## Usages

On CIFAR-100, taking the pre-trained ResNet-20 as an example, run the following command:
```
python main.py --conf_path=./cifar100_resnet20.hocon --id=01
```

On ImageNet, taking the pre-trained ResNet-18 as an example, run the following command:
```
python main.py --conf_path=./imagenet_res18.hocon --id=01
```

## Citation
If you find the project codes useful for your research, please consider citing
```
@inproceedings{qian2023adaptive,
  title={Adaptive Data-Free Quantization},
  author={Qian, Biao and Wang, Yang and Hong, Richang and Wang, Meng},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={7960--7968},
  year={2023}
}
```
