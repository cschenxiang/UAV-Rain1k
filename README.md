# <p align=center> :fire: `UAV-Rain1k: A Benchmark for Raindrop Removal from UAV Aerial Imagery`</p>

[Paper](https://arxiv.org/abs/2402.05773) | [Project Page](https://github.com/cschenxiang/UAV-Rain1k) 

> Wenhui Chang, Hongming Chen, Xin He, Xiang Chen*, Liangduo Shen*

>Shenyang Aerospace University, Naval Aviation University, Nanjing University of Science and Technology, Zhejiang Ocean University

---
### Dataset
![Example](figures/overview.jpg)
(The datasets are hosted on both Google Drive and BaiduPan)
| Download Link | Description | 
|:-----: |:-----: |
| [Google Drive](https://drive.google.com/file/d/1GOhd5RYf8AHIt0mhJRGm91vKM8EbBpYQ/view?usp=sharing) / [Baidu Netdisk](https://pan.baidu.com/s/1E9b2sW_BEclQUROg8xKdkg?pwd=du3z) (du3z) | A total of 800 pairs for training and 220 pairs for testing. |

### Evaluation
The PSNR and SSIM results are computed by using this [Python Code](https://github.com/cschenxiang/UAV-Rain1k/blob/main/evaluation.py), based on Y channel of YCbCr space.

### Visual Results
| Method | Download Link | 
|:-----: |:-----: |
| RCDNet | [Google Drive](https://drive.google.com/file/d/1XdiscL05-OEonpZlU1tsw0yvQ6jJZNR-/view?usp=sharing) / [Baidu Netdisk](https://pan.baidu.com/s/1ZHZqQVbKCnCuIh6atvS0zQ?pwd=n4gl) (n4gl) |
| SPDNet | [Google Drive](https://drive.google.com/file/d/18-x_dGt_Fe6AkePAtLupHoEu0qpoj6a_/view?usp=sharing) / [Baidu Netdisk](https://pan.baidu.com/s/1yQdLAnUVexOKuYLYtkFLgg?pwd=hca4) (hca4) |
| Restormer | [Google Drive](https://drive.google.com/file/d/15i1zHg8GEPh2UE8-V9YPLBRONsAZggfJ/view?usp=sharing) / [Baidu Netdisk](https://pan.baidu.com/s/1j7X2NpfEPXYMCyZ1v5pbFw?pwd=si1w) (si1w) |
| IDT | [Google Drive](https://drive.google.com/file/d/1EAGepDCy0lSYaY8-I-PqiYWSlKZ_WMTY/view?usp=sharing) / [Baidu Netdisk](https://pan.baidu.com/s/1sVcMX35YCQEvWDhoYaL3Cg?pwd=onx0) (onx0) |
| DRSformer | [Google Drive](https://drive.google.com/file/d/1wnEPkd_dOPJoNVvEa4Ck9ILEKvzxATOY/view?usp=sharing) / [Baidu Netdisk](https://pan.baidu.com/s/1kHGefiug6dJ5I0Ia8Kv96Q?pwd=hyg6) (hyg6) |

### Citation
If you find this project useful in your research, please consider citing:
```
@article{UAV-Rain1k,
    title={UAV-Rain1k: A Benchmark for Raindrop Removal from UAV Aerial Imagery},
    author={Chang, Wenhui and Chen, Hongming and He, Xin and Chen, Xiang and Shen, Liangduo},
    journal={arXiv preprint arXiv:2402.05773},  
    year={2024}
}
```

### Disclaimer
Please only use the dataset for research purposes.

### Contact
If you have any questions, please feel free to reach me out at chenxiang@njust.edu.cn
