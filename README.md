# SIXray：A Large-scale Security Inspection X-ray Benchmark for  Prohibited Item Discovery in Overlapping Images

[[Paper]](https://arxiv.org/pdf/1901.00303.pdf) [[code]](https://github.com/MeioJane/CHR)

## INTRODUCTION
The SIXray dataset is constructed by Pattern Recognition and Intelligent System Development Laboratory, University of Chinese Academy of Sciences.
![Illustration](image.png)
The SIXray dataset contains 1,059,231 X-ray images which are collected from some several subway stations. There are six common categories of prohibited items, namely, gun, knife, wrench, pliers, scissors and hammer.
To study the impact brought by training data imbalance, we construct three subsets of this dataset, and name them as SIXray10, SIXray100 and SIXray1000
On the entire dataset, we use the image-level annotations provided by human security inspectors. In addition, on the testing sets, we manually add a bounding-box for each prohibited item to evaluate the performance of object localization.
## LICENSE
*  The images and the corresponding annotation results for download are part of UCAS SIXray dataset.
* The images and the corresponding annotation results can only be used for ACADEMIC PURPOSES. NO COMERCIAL USE is allowed
*  Copyright © Pattern Recognition and Intelligent System Development Laboratory, University of Chinese Academy of Sciences (UCAS-PRISDL). All rights reserved.

All publications using SIXray dataset should cite the paper below:

```bibtex
@INPROCEEDINGS{Miao2019SIXray,
    author = {Miao, Caijing and Xie, Lingxi and Wan, Fang and Su, chi and Liu, Hongye and Jiao, jianbin and Ye, Qixiang },
    title = {SIXray: A Large-scale Security Inspection X-ray Benchmark for Prohibited Item Discovery in Overlapping Images},
    booktitle = {CVPR},
    year = {2019}
}
```

## DOWNLOAD
* A way to download the dataset
  1. Prerequisites:  JDK1.7 or 1.8
  2. download `ks3util-1.1.1`
  3.   `cd $DIR/ks3util-1.1.1`
  
        `chmod 755 bin/ks3util`
        
        `chmod 777 up_to_ks3.sh`
        
         `./up_to_ks3.sh `
  4. more information see `ks3util-1.1.1/README.html`

* Another way to download all the dataset from [here](https://pan.baidu.com/s/1zSbpapRURc9Uzjl-1ZWI_w)

* Download all the positive annotation from [here](https://pan.baidu.com/s/1ZNxsYWdVXHyDGG5EvVeadQ)

