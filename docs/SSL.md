# Self-supervised Learning

**Self-supervised learning generally involves a pretext task that is solved to learn a good representation without the use of labels, can mainly be divided into contrastive learning and generative learning:**
- **Contrastive Learning:** MoCo, SimCLR, SimCLRv2, BYOL, SwAV, MoCov3, DINO, DINOv2
- **Generative Learning:** MAE, iBOT, SimMIM
# 

## Survey

**1. A Survey on Self-supervised Learning: Algorithms, Applications, and Future Trends, _TPAMI 2024_**
- Paper: https://ieeexplore.ieee.org/abstract/document/10559458
- Code: https://github.com/guijiejie/SSL
```
@article{gui2024survey,
  title={A Survey on Self-supervised Learning: Algorithms, Applications, and Future Trends},
  author={Gui, Jie and Chen, Tuo and Zhang, Jing and Cao, Qiong and Sun, Zhenan and Luo, Hao and Tao, Dacheng},
  journal=TPAMI,
  year={2024},
  publisher={IEEE}
}
```

## Natural Data

**1. Momentum Contrast for Unsupervised Visual Representation Learning, _CVPR 2020_**
- Paper: https://openaccess.thecvf.com/content_CVPR_2020/papers/He_Momentum_Contrast_for_Unsupervised_Visual_Representation_Learning_CVPR_2020_paper.pdf
- Code: https://github.com/facebookresearch/moco
```
@inproceedings{moco,
  title={Momentum contrast for unsupervised visual representation learning},
  author={He, Kaiming and Fan, Haoqi and Wu, Yuxin and Xie, Saining and Girshick, Ross},
  booktitle=CVPR,
  pages={9729--9738},
  year={2020}
}
```

**2. A Simple Framework for Contrastive Learning of Visual Representations, _ICML 2020_**
- Paper: https://proceedings.mlr.press/v119/chen20j.html
- Code: https://github.com/google-research/simclr
```
@inproceedings{simclr,
  title={A simple framework for contrastive learning of visual representations},
  author={Chen, Ting and Kornblith, Simon and Norouzi, Mohammad and Hinton, Geoffrey},
  booktitle=ICML,
  pages={1597--1607},
  year={2020},
  organization={PMLR}
}
```

**3. Big Self-Supervised Models are Strong Semi-Supervised Learners, _NIPS 2020_**
- Paper: https://proceedings.neurips.cc/paper_files/paper/2020/file/fcbc95ccdd551da181207c0c1400c655-Paper.pdf
- Code: https://github.com/google-research/simclr
```
@article{simclrv2,
  title={Big self-supervised models are strong semi-supervised learners},
  author={Chen, Ting and Kornblith, Simon and Swersky, Kevin and Norouzi, Mohammad and Hinton, Geoffrey},
  journal=NIPS,
  volume={33},
  pages={22243--22255},
  year={2020}
}
```

**4. Bootstrap Your Own Latent A New Approach to Self-Supervised Learning, _NIPS 2020_**
- Paper: https://proceedings.neurips.cc/paper_files/paper/2020/file/f3ada80d5c4ee70142b17b8192b2958e-Paper.pdf
- Code: https://github.com/lucidrains/byol-pytorch
```
@article{byol,
  title={Bootstrap your own latent-a new approach to self-supervised learning},
  author={Grill, Jean-Bastien and Strub, Florian and Altch{\'e}, Florent and Tallec, Corentin and Richemond, Pierre and Buchatskaya, Elena and Doersch, Carl and Avila Pires, Bernardo and Guo, Zhaohan and Gheshlaghi Azar, Mohammad and others},
  journal=NIPS,
  volume={33},
  pages={21271--21284},
  year={2020}
}
```

**5. Unsupervised Learning of Visual Features by Contrasting Cluster Assignments, _NIPS 2020_**
- Paper: https://proceedings.neurips.cc/paper_files/paper/2020/file/70feb62b69f16e0238f741fab228fec2-Paper.pdf
- Code: https://github.com/facebookresearch/swav
```
@article{swav,
  title={Unsupervised learning of visual features by contrasting cluster assignments},
  author={Caron, Mathilde and Misra, Ishan and Mairal, Julien and Goyal, Priya and Bojanowski, Piotr and Joulin, Armand},
  journal=NIPS,
  volume={33},
  pages={9912--9924},
  year={2020}
}
```

**6. An Empirical Study of Training Self-Supervised Vision Transformers, _ICCV 2021_**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_An_Empirical_Study_of_Training_Self-Supervised_Vision_Transformers_ICCV_2021_paper.pdf
- Code: https://github.com/facebookresearch/moco-v3
```
@inproceedings{mocov3,
  title={An empirical study of training self-supervised vision transformers},
  author={Chen, Xinlei and Xie, Saining and He, Kaiming},
  booktitle=ICCV,
  pages={9640--9649},
  year={2021}
}
```

**7. Emerging Properties in Self-Supervised Vision Transformers, _ICCV 2021_**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/papers/Caron_Emerging_Properties_in_Self-Supervised_Vision_Transformers_ICCV_2021_paper.pdf
- Code: https://github.com/facebookresearch/dino
```
@inproceedings{dino,
  title={Emerging properties in self-supervised vision transformers},
  author={Caron, Mathilde and Touvron, Hugo and Misra, Ishan and J{\'e}gou, Herv{\'e} and Mairal, Julien and Bojanowski, Piotr and Joulin, Armand},
  booktitle=ICCV,
  pages={9650--9660},
  year={2021}
}
```

**8. iBOT: Image BERT Pre-Training with Online Tokenizer, _ICLR 2022_**
- Paper: https://arxiv.org/abs/2111.07832
- Code: https://github.com/bytedance/ibot
```
@inproceedings{ibot,
  title={ibot: Image bert pre-training with online tokenizer},
  author={Zhou, Jinghao and Wei, Chen and Wang, Huiyu and Shen, Wei and Xie, Cihang and Yuille, Alan and Kong, Tao},
  booktitle=ICLR,
  year={2021}
}
```

**9. Masked Autoencoders Are Scalable Vision Learners, _CVPR 2022_**
- Paper: https://openaccess.thecvf.com/content/CVPR2022/papers/He_Masked_Autoencoders_Are_Scalable_Vision_Learners_CVPR_2022_paper.pdf
- Code: https://github.com/facebookresearch/mae
```
@inproceedings{mae,
  title={Masked autoencoders are scalable vision learners},
  author={He, Kaiming and Chen, Xinlei and Xie, Saining and Li, Yanghao and Doll{\'a}r, Piotr and Girshick, Ross},
  booktitle=CVPR,
  pages={16000--16009},
  year={2022}
}
```

**10. SimMIM: A Simple Framework for Masked Image Modeling, _CVPR 2022_**
- Paper: https://openaccess.thecvf.com/content/CVPR2022/papers/Xie_SimMIM_A_Simple_Framework_for_Masked_Image_Modeling_CVPR_2022_paper.pdf
- Code: https://github.com/microsoft/SimMIM
```
@inproceedings{simmim,
  title={Simmim: A simple framework for masked image modeling},
  author={Xie, Zhenda and Zhang, Zheng and Cao, Yue and Lin, Yutong and Bao, Jianmin and Yao, Zhuliang and Dai, Qi and Hu, Han},
  booktitle=CVPR,
  pages={9653--9663},
  year={2022}
}
```

**11. DINOv2: Learning Robust Visual Features without Supervision, _TMLR 2024_**
- Paper: https://arxiv.org/abs/2304.07193
- Code: https://github.com/facebookresearch/dinov2
```
@article{dinov2,
  title={DINOv2: Learning Robust Visual Features without Supervision},
  author={Oquab, Maxime and Darcet, Timoth{\'e}e and Moutakanni, Th{\'e}o and Vo, Huy and Szafraniec, Marc and Khalidov, Vasil and Fernandez, Pierre and Haziza, Daniel and Massa, Francisco and El-Nouby, Alaaeldin and others},
  journal=TMLR,
  pages={1--31},
  year={2024}
}
```

## Remote Sensing Data

**1. SatMAE: Pre-training Transformers for Temporal and Multi-Spectral Satellite Imagery, _NIPS 2022_**
- Paper: https://proceedings.neurips.cc/paper_files/paper/2022/file/01c561df365429f33fcd7a7faa44c985-Paper-Conference.pdf
- Code: https://github.com/sustainlab-group/SatMAE
```
@article{satmae,
  title={Satmae: Pre-training transformers for temporal and multi-spectral satellite imagery},
  author={Cong, Yezhen and Khanna, Samar and Meng, Chenlin and Liu, Patrick and Rozi, Erik and He, Yutong and Burke, Marshall and Lobell, David and Ermon, Stefano},
  journal=NIPS,
  volume={35},
  pages={197--211},
  year={2022}
}
```

**2. An Empirical Study of Remote Sensing Pretraining, _TGRS 2022_**
- Paper: https://ieeexplore.ieee.org/abstract/document/9782149/
- Code: https://github.com/ViTAE-Transformer/RSP
```
@article{rsp,
  title={An empirical study of remote sensing pretraining},
  author={Wang, Di and Zhang, Jing and Du, Bo and Xia, Gui-Song and Tao, Dacheng},
  journal=TGRS,
  volume={61},
  pages={1--20},
  year={2022},
  publisher={IEEE}
}
```

**3. Advancing Plain Vision Transformer Towards Remote Sensing Foundation Model, _TGRS 2022_**
- Paper: https://ieeexplore.ieee.org/abstract/document/9956816/
- Code: https://github.com/ViTAE-Transformer/Remote-Sensing-RVSA
```
@article{rvsa,
  title={Advancing plain vision transformer toward remote sensing foundation model},
  author={Wang, Di and Zhang, Qiming and Xu, Yufei and Zhang, Jing and Du, Bo and Tao, Dacheng and Zhang, Liangpei},
  journal=TGRS,
  volume={61},
  pages={1--15},
  year={2022},
  publisher={IEEE}
}
```

**4. Scale-MAE: A Scale-Aware Masked Autoencoder for Multiscale Geospatial Representation Learning, _ICCV 2023_**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/papers/Reed_Scale-MAE_A_Scale-Aware_Masked_Autoencoder_for_Multiscale_Geospatial_Representation_Learning_ICCV_2023_paper.pdf
- Code: https://github.com/bair-climate-initiative/scale-mae
```
@inproceedings{scalemae,
  title={Scale-mae: A scale-aware masked autoencoder for multiscale geospatial representation learning},
  author={Reed, Colorado J and Gupta, Ritwik and Li, Shufan and Brockman, Sarah and Funk, Christopher and Clipp, Brian and Keutzer, Kurt and Candido, Salvatore and Uyttendaele, Matt and Darrell, Trevor},
  booktitle=ICCV,
  pages={4088--4099},
  year={2023}
}
```

**5. Towards Geospatial Foundation Models via Continual Pretraining, _ICCV 2023_**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/papers/Mendieta_Towards_Geospatial_Foundation_Models_via_Continual_Pretraining_ICCV_2023_paper.pdf
- Code: https://github.com/mmendiet/GFM
```
@inproceedings{gfm,
  title={Towards geospatial foundation models via continual pretraining},
  author={Mendieta, Mat{\'\i}as and Han, Boran and Shi, Xingjian and Zhu, Yi and Chen, Chen},
  booktitle=ICCV,
  pages={16806--16816},
  year={2023}
}
```

**6. Cross-Scale MAE: A Tale of Multi-Scale Exploitation in Remote Sensing, _NIPS 2023_**
- Paper: https://proceedings.neurips.cc/paper_files/paper/2023/file/3fadcbd0437f4717723ff3f6f7216800-Paper-Conference.pdf
- Code: https://github.com/aicip/Cross-Scale-MAE
```
@article{crossscalemae,
  title={Cross-Scale MAE: A tale of multiscale exploitation in remote sensing},
  author={Tang, Maofeng and Cozma, Andrei and Georgiou, Konstantinos and Qi, Hairong},
  journal=NIPS,
  volume={36},
  year={2023}
}
```

**7. CMID: A Unified Self-Supervised Learning Framework for Remote Sensing Image Understanding, _TGRS 2023_**
- Paper: https://ieeexplore.ieee.org/abstract/document/10105625/
- Code: https://github.com/NJU-LHRS/official-CMID
```
@article{cmid,
  title={Cmid: A unified self-supervised learning framework for remote sensing image understanding},
  author={Muhtar, Dilxat and Zhang, Xueliang and Xiao, Pengfeng and Li, Zhenshi and Gu, Feng},
  journal=TGRS,
  volume={61},
  pages={1--17},
  year={2023},
  publisher={IEEE}
}
```

**8. Generative ConvNet Foundation Model With Sparse Modeling and Low-Frequency Reconstruction for Remote Sensing Image Interpretation, _TGRS 2024_**
- Paper: https://ieeexplore.ieee.org/abstract/document/10378718/
- Code: https://github.com/HIT-SIRS/SMLFR
```
@article{smlfr,
  title={Generative convnet foundation model with sparse modeling and low-frequency reconstruction for remote sensing image interpretation},
  author={Dong, Zhe and Gu, Yanfeng and Liu, Tianzhu},
  journal=TGRS,
  year={2024},
  publisher={IEEE}
}
```

**9. Rethinking Transformers Pre-training for Multi-Spectral Satellite Imagery, _CVPR 2024_**
- Paper: https://openaccess.thecvf.com/content/CVPR2024/papers/Noman_Rethinking_Transformers_Pre-training_for_Multi-Spectral_Satellite_Imagery_CVPR_2024_paper.pdf
- Code: https://github.com/techmn/satmae_pp
```
@inproceedings{satmaepp,
  title={Rethinking transformers pre-training for multi-spectral satellite imagery},
  author={Noman, Mubashir and Naseer, Muzammal and Cholakkal, Hisham and Anwer, Rao Muhammad and Khan, Salman and Khan, Fahad Shahbaz},
  booktitle=CVPR,
  pages={27811--27819},
  year={2024}
}
```

**10. SpectralGPT: Spectral remote sensing foundation model, _TPAMI 2024_**
- Paper: https://ieeexplore.ieee.org/abstract/document/10490262/
- Code: https://github.com/danfenghong/IEEE_TPAMI_SpectralGPT
```
@article{spectralgpt,
  title={SpectralGPT: Spectral remote sensing foundation model},
  author={Hong, Danfeng and Zhang, Bing and Li, Xuyang and Li, Yuxuan and Li, Chenyu and Yao, Jing and Yokoya, Naoto and Li, Hao and Ghamisi, Pedram and Jia, Xiuping and others},
  journal=TPAMI,
  year={2024},
  publisher={IEEE}
}
```