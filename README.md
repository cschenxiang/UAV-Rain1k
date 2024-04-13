# <p align=center> :fire: `UAV-Rain1k: A Benchmark for Raindrop Removal from UAV Aerial Imagery`</p>

[Paper](https://arxiv.org/abs/2402.05773) | [Project Page](https://github.com/cschenxiang/UAV-Rain1k) 

> Wenhui Chang, Hongming Chen, Xin He, Xiang Chen, Liangduo Shen

>Shenyang Aerospace University, Naval Aviation University, Nanjing University of Science and Technology, Zhejiang Ocean University

---
### Dataset
![Example](figures/overview.jpg)
(The datasets are hosted on both Google Drive and BaiduPan)
| Download Link | Description | 
|:-----: |:-----: |
| [Google Drive](https://drive.google.com/file/d/1uELYr8-EesWXVi-Ty0vd4_7ig7taUDfq/view?usp=sharing) / [Baidu Netdisk](https://pan.baidu.com/s/1J8LP4mOFOGopo-8YEpj7KQ?pwd=soi3) (soi3) | A total of 800 pairs for training and 220 pairs for testing. |

### Evaluation
The PSNR and SSIM results are computed by using this [Python Code](https://github.com/cschenxiang/UAV-Rain1k/blob/main/evaluation.py), based on Y channel of YCbCr space.

### Visual Results
| Method | Download Link | 
|:-----: |:-----: |
| RCDNet | [Google Drive]() / [Baidu Netdisk](https://pan.baidu.com/s/1FcFyzhvbCoTLfsC6u2P_Aw?pwd=1vfj) (1vfj) |
| SPDNet | [Google Drive]() / [Baidu Netdisk](https://pan.baidu.com/s/1cGFcK7C1jOfN03r1HKNxqg?pwd=q82c) (q82c) |
| Restormer | [Google Drive]() / [Baidu Netdisk](https://pan.baidu.com/s/1qRRhwe_kN9lKJTnui6dhuw?pwd=y80k) (y80k) |
| IDT | [Google Drive]() / [Baidu Netdisk](https://pan.baidu.com/s/1G0To1q4j2dy9D6XUK489Nw?pwd=d37b) (d37b) |
| DRSformer | [Google Drive]() / [Baidu Netdisk](https://pan.baidu.com/s/1ww7wVF4AtSfQIUrrYVilnA?pwd=gj5b) (gj5b) |

### Citation
If you find this project useful in your research, please consider citing:
```
@inproceedings{UAV-Rain1k,
    title={UAV-Rain1k: A Benchmark for Raindrop Removal from UAV Aerial Imagery},
    author={Chang, Wenhui and Chen, Hongming and He, Xin and Chen, Xiang and Shen, Liangduo},
    booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops},
    year={2024}
}
```

### Disclaimer
Please only use the dataset for research purposes.

### Contact
If you have any questions, please feel free to reach me out at chenxiang@njust.edu.cn
