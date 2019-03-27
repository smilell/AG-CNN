# AG-CNN
The model of "Attention-based CNN for Glaucoma Detection (AG-CNN)", which has been poblished as "Attention Based Glaucoma Detection: A Large-scale Database with a CNN Model" at CVPR2019.

# Abstract
Recently, the attention mechanism has been successfully applied in convolutional neural networks (CNNs), significantly boosting the performance of many computer vision tasks. Unfortunately, few medical image recognition approaches incorporate the attention mechanism in the CNNs. In particular, there exists high redundancy in fundus images for glaucoma detection, such that the attention mechanism has potential in improving the performance of CNN-based glaucoma detection. This paper proposes an attention-based CNN for glaucoma detection (AG-CNN). Specifically, we first establish a large-scale attention based glaucoma (LAG) database, which includes 5,824 fundus images labeled with either positive glaucoma (2,392) or negative glaucoma (3,432). The attention maps of the ophthalmologists are also collected in LAG database through a simulated eye-tracking experiment. Then, a new structure of AG-CNN is designed, including an attention prediction subnet, a pathological area localization subnet and a glaucoma classification subnet. Different from other attention-based CNN methods, the features are also visualized as the localized pathological area, which can advance the performance of glaucoma detection. Finally, the experiment results show that the proposed AG-CNN approach significantly advances state-of-the-art glaucoma detection.


# Models
The whole architecture consists 3 parts, attention prediction subnet, pathological area localization subnet and glaucoma classification subnet, as shown below.
![1](https://github.com/smilell/AG-CNN/blob/master/fullnet_1.pdf)


# Database
![2](https://github.com/smilell/AG-CNN/blob/master/database2_s.pdf)
As introduced in our paper, our AG-CNN model is trained by our newly-established LAG database, which is available at [Dropbox](https://www.dropbox.com/s/nwvvk2fkb4t57f3/LAG_database.rar?dl=0) under request.
Please contact us for the passport.

# Contact
If any question, please contact liliu1995@buaa.edu.cn or liliu419@foxmail.com.


# Citation
@article{li2019attention,
  title={Attention Based Glaucoma Detection: A Large-scale Database with a CNN Model},
  author={Li, Liu and Xu, Mai and Wang, Xiaofei and Jiang, Lai and Liu, Hanruo},
  journal={arXiv preprint arXiv:1903.10831},
  year={2019}
}

