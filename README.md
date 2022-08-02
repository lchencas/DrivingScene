# DrivingScene
![dataset_overview](./img/dataset_overview.png)

This is the repository for the DrivingScene Dataset.

# Overview

We provide 52 different kinds of driving scenes, cutting across common driving instances, weather conditions, places and road structures. which is currently, to our best knowledge, the largest dataset in terms of scene recognition in self-driving domain. The scene category structure is shown in Fig. 1, in which each image is tagged with fine-grained and carefully annotated labels.

# Dataset stats

![image-20220705101400493](./img/stats.png)



# Structure

Every image and its annotations are inside a `ImageData`:

`images`: a folder with all the instances in that image, and its annotations are  can be found in `total_info.txt` .

# Download

To download the dataset：<a href="https://pan.baidu.com/s/14sTulr8tN7ZPj-Wgm06y1A?pwd=mvtz">baidu yun</a>, code: `mvtz`.

# Citation

If you use this data, please cite the following papers:

```latex
@article{chen2019deep,
  title={Deep integration: A multi-label architecture for road scene recognition},
  author={Chen, Long and Zhan, Wujing and Tian, Wei and He, Yuhang and Zou, Qin},
  journal={IEEE Transactions on Image Processing},
  volume={28},
  number={10},
  pages={4883--4898},
  year={2019},
  publisher={IEEE}
}
```
