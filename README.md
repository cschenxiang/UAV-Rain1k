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
| [Google Drive]() / [Baidu Netdisk]() () | A total of 800 pairs for training and 220 pairs for testing. |

### Evaluation
The PSNR and SSIM results are computed by using this [Python Code](https://github.com/cschenxiang/UAV-Rain1k/blob/main/evaluation.py), based on Y channel of YCbCr space.

### Visual Results
| Method | Download Link | 
|:-----: |:-----: |
| RCDNet | [Google Drive]() / [Baidu Netdisk]() () |
| SPDNet | [Google Drive]() / [Baidu Netdisk]() () |
| Restormer | [Google Drive]() / [Baidu Netdisk]() () |
| IDT | [Google Drive]() / [Baidu Netdisk]() () |
| DRSformer | [Google Drive]() / [Baidu Netdisk]() () |

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
