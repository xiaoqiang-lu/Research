# Semi-supervised Semantic Segmentation

**Semi-supervised semantic segmentation aims to learn a semantic segmentation model via limited labeled images and adequate unlabeled images, can be divided into three main branches: Generative Adversarial Networks (GANs), Self-training (ST), amd Consistency Regularization (CR).**
- **GANs:** AdvSemiSeg, s4GAN
- **ST:** ST++, LSST, CISC-R
- **CR:** CutMixSeg, CPS, AEL, U2PL, PSMT, UniMatch, AugSeg, WSCL, LogicDiag, CSS, AllSpark, CorrMatch, S4Former, SPEED

## Natural Data

**1. Adversarial Learning for Semi-Supervised Semantic Segmentation, _BMVC 2018_**
- Paper: https://arxiv.org/abs/1802.07934
- Code: https://github.com/hfslyc/AdvSemiSeg
```
@inproceedings{advsemiseg,
  title={Adversarial learning for semi-supervised semantic segmentation},
  author={Hung, Wei-Chih and Tsai, Yi-Hsuan and Liou, Yan-Ting and Lin, Yen-Yu and Yang, Ming-Hsuan},
  booktitle=BMVC,
  year={2018}
}
```

**2. Semi-Supervised Semantic Segmentation With High- and Low-Level Consistency, _TPAMI 2019_**
- Paper: https://ieeexplore.ieee.org/document/8935407
- Code: https://github.com/sud0301/semisup-semseg
```
@article{s4gan,
  title={Semi-supervised semantic segmentation with high-and low-level consistency},
  author={Mittal, Sudhanshu and Tatarchenko, Maxim and Brox, Thomas},
  journal=TPAMI,
  volume={43},
  number={4},
  pages={1369--1379},
  year={2019},
  publisher={IEEE}
}
```

**3. Semi-supervised semantic segmentation needs strong, varied perturbations, _BMVC 2020_**
- Paper: https://arxiv.org/abs/1906.01916
- Code: https://github.com/Britefury/cutmix-semisup-seg
```
@inproceedings{cutmixseg,
  title={Semi-supervised semantic segmentation needs strong, varied perturbations},
  author={French, Geoff and Laine, Samuli and Aila, Timo and Mackiewicz, Michal and Finlayson, Graham},
  booktitle=BMVC,
  year={2020}
}
```

**4. Semi-Supervised Semantic Segmentation With Cross Pseudo Supervision, _CVPR 2021_**
- Paper: https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Semi-Supervised_Semantic_Segmentation_With_Cross_Pseudo_Supervision_CVPR_2021_paper.pdf
- Code: https://github.com/charlesCXK/TorchSemiSeg
```
@inproceedings{cps,
  title={Semi-supervised semantic segmentation with cross pseudo supervision},
  author={Chen, Xiaokang and Yuan, Yuhui and Zeng, Gang and Wang, Jingdong},
  booktitle=CVPR,
  pages={2613--2622},
  year={2021}
}
```

**5. Semi-Supervised Semantic Segmentation via Adaptive Equalization Learning, _NIPS 2021_**
- Paper: https://proceedings.neurips.cc/paper_files/paper/2021/file/b98249b38337c5088bbc660d8f872d6a-Paper.pdf
- Code: https://github.com/hzhupku/SemiSeg-AEL
```
@article{ael,
  title={Semi-supervised semantic segmentation via adaptive equalization learning},
  author={Hu, Hanzhe and Wei, Fangyun and Hu, Han and Ye, Qiwei and Cui, Jinshi and Wang, Liwei},
  journal=NIPS,
  volume={34},
  pages={22106--22118},
  year={2021}
}
```

**6. ST++: Make Self-training Work Better for Semi-supervised Semantic Segmentation, _CVPR 2022_**
- Paper: https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_ST_Make_Self-Training_Work_Better_for_Semi-Supervised_Semantic_Segmentation_CVPR_2022_paper.pdf
- Code: https://github.com/LiheYoung/ST-PlusPlus
```
@inproceedings{stpp,
  title={St++: Make self-training work better for semi-supervised semantic segmentation},
  author={Yang, Lihe and Zhuo, Wei and Qi, Lei and Shi, Yinghuan and Gao, Yang},
  booktitle=CVPR,
  pages={4268--4277},
  year={2022}
}
```

**7. Semi-Supervised Semantic Segmentation Using Unreliable Pseudo-Labels, _CVPR 2022_**
- Paper: https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Semi-Supervised_Semantic_Segmentation_Using_Unreliable_Pseudo-Labels_CVPR_2022_paper.pdf
- Code: https://github.com/Haochen-Wang409/U2PL/
```
@inproceedings{u2pl,
  title={Semi-supervised semantic segmentation using unreliable pseudo-labels},
  author={Wang, Yuchao and Wang, Haochen and Shen, Yujun and Fei, Jingjing and Li, Wei and Jin, Guoqiang and Wu, Liwei and Zhao, Rui and Le, Xinyi},
  booktitle=CVPR,
  pages={4248--4257},
  year={2022}
}
```

**8. Perturbed and Strict Mean Teachers for Semi-supervised Semantic Segmentation, _CVPR 2022_**
- Paper: https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Perturbed_and_Strict_Mean_Teachers_for_Semi-Supervised_Semantic_Segmentation_CVPR_2022_paper.pdf
- Code: https://github.com/yyliu01/PS-MT
```
@inproceedings{psmt,
  title={Perturbed and strict mean teachers for semi-supervised semantic segmentation},
  author={Liu, Yuyuan and Tian, Yu and Chen, Yuanhong and Liu, Fengbei and Belagiannis, Vasileios and Carneiro, Gustavo},
  booktitle=CVPR,
  pages={4258--4267},
  year={2022}
}
```

**9. Querying Labeled for Unlabeled: Cross-Image Semantic Consistency Guided Semi-Supervised Semantic Segmentation, _TPAMI 2023_**
- Paper: https://ieeexplore.ieee.org/document/10005033
- Code: https://github.com/Luffy03/CISC-R
```
@article{cisc-r,
  title={Querying labeled for unlabeled: Cross-image semantic consistency guided semi-supervised semantic segmentation},
  author={Wu, Linshan and Fang, Leyuan and He, Xingxin and He, Min and Ma, Jiayi and Zhong, Zhun},
  journal=TPAMI,
  volume={45},
  number={7},
  pages={8827--8844},
  year={2023},
  publisher={IEEE}
}
```

**10. Revisiting Weak-to-Strong Consistency in Semi-Supervised Semantic Segmentation, _CVPR 2023_**
- Paper: https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_Revisiting_Weak-to-Strong_Consistency_in_Semi-Supervised_Semantic_Segmentation_CVPR_2023_paper.pdf
- Code: https://github.com/LiheYoung/UniMatch
```
@inproceedings{unimatch,
  title={Revisiting weak-to-strong consistency in semi-supervised semantic segmentation},
  author={Yang, Lihe and Qi, Lei and Feng, Litong and Zhang, Wayne and Shi, Yinghuan},
  booktitle=CVPR,
  pages={7236--7246},
  year={2023}
}
```

**11. Augmentation Matters: A Simple-yet-Effective Approach to Semi-supervised Semantic Segmentation, _CVPR 2023_**
- Paper: https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_Augmentation_Matters_A_Simple-Yet-Effective_Approach_to_Semi-Supervised_Semantic_Segmentation_CVPR_2023_paper.pdf
- Code: https://github.com/zhenzhao/AugSeg
```
@inproceedings{augseg,
  title={Augmentation matters: A simple-yet-effective approach to semi-supervised semantic segmentation},
  author={Zhao, Zhen and Yang, Lihe and Long, Sifan and Pi, Jimin and Zhou, Luping and Wang, Jingdong},
  booktitle=CVPR,
  pages={11350--11359},
  year={2023}
}
```

**12. Logic-induced Diagnostic Reasoning for Semi-supervised Semantic Segmentation, _ICCV 2023_**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/papers/Liang_Logic-induced_Diagnostic_Reasoning_for_Semi-supervised_Semantic_Segmentation_ICCV_2023_paper.pdf
- Code: https://github.com/leonnnop/LogicDiag
```
@inproceedings{logicdiag,
  title={Logic-induced diagnostic reasoning for semi-supervised semantic segmentation},
  author={Liang, Chen and Wang, Wenguan and Miao, Jiaxu and Yang, Yi},
  booktitle=ICCV,
  pages={16197--16208},
  year={2023}
}
```

**13. Space Engage: Collaborative Space Supervision for Contrastive-Based Semi-Supervised Semantic Segmentation, _ICCV 2023_**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Space_Engage_Collaborative_Space_Supervision_for_Contrastive-Based_Semi-Supervised_Semantic_Segmentation_ICCV_2023_paper.pdf
- Code: https://github.com/WangChangqi98/CSS
```
@inproceedings{css,
  title={Space engage: Collaborative space supervision for contrastive-based semi-supervised semantic segmentation},
  author={Wang, Changqi and Xie, Haoyu and Yuan, Yuhui and Fu, Chong and Yue, Xiangyu},
  booktitle=ICCV,
  pages={931--942},
  year={2023}
}
```

**14. AllSpark: Reborn Labeled Features from Unlabeled in Transformer for Semi-Supervised Semantic Segmentation, _CVPR 2024_**
- Paper: https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_AllSpark_Reborn_Labeled_Features_from_Unlabeled_in_Transformer_for_Semi-Supervised_CVPR_2024_paper.pdf
- Code: https://github.com/xmed-lab/AllSpark
```
@inproceedings{allspark,
  title={AllSpark: Reborn Labeled Features from Unlabeled in Transformer for Semi-Supervised Semantic Segmentation},
  author={Wang, Haonan and Zhang, Qixiang and Li, Yi and Li, Xiaomeng},
  booktitle=CVPR,
  pages={3627--3636},
  year={2024}
}
```

**15. CorrMatch: Label Propagation via Correlation Matching for Semi-Supervised Semantic Segmentation, _CVPR 2024_**
- Paper: https://openaccess.thecvf.com/content/CVPR2024/papers/Sun_CorrMatch_Label_Propagation_via_Correlation_Matching_for_Semi-Supervised_Semantic_Segmentation_CVPR_2024_paper.pdf
- Code: https://github.com/BBBBchan/CorrMatch
```
@inproceedings{corrmatch,
  title={Corrmatch: Label propagation via correlation matching for semi-supervised semantic segmentation},
  author={Sun, Boyuan and Yang, Yuqi and Zhang, Le and Cheng, Ming-Ming and Hou, Qibin},
  booktitle=CVPR,
  pages={3097--3107},
  year={2024}
}
```

**16. Training Vision Transformers for Semi-Supervised Semantic Segmentation, _CVPR 2024_**
- Paper: https://openaccess.thecvf.com/content/CVPR2024/papers/Hu_Training_Vision_Transformers_for_Semi-Supervised_Semantic_Segmentation_CVPR_2024_paper.pdf
- Code: https://github.com/JoyHuYY1412/S4Former
```
@inproceedings{s4former,
  title={Training Vision Transformers for Semi-Supervised Semantic Segmentation},
  author={Hu, Xinting and Jiang, Li and Schiele, Bernt},
  booktitle=CVPR,
  pages={4007--4017},
  year={2024}
}
```

**17. Self Pseudo Entropy Knowledge Distillation for Semi-supervised Semantic Segmentation, _TCSVT 2024_**
- Paper: https://ieeexplore.ieee.org/document/10464380
- Code: https://github.com/xiaoqiang-lu/SPEED
```
@article{speed,
  title={Self Pseudo Entropy Knowledge Distillation for Semi-supervised Semantic Segmentation},
  author={Lu, Xiaoqiang and Jiao, Licheng and Li, Lingling and Liu, Fang and Liu, Xu and Yang, Shuyuan},
  journal=TCSVT,
  year={2024},
  publisher={IEEE}
}
```

## Remote Sensing Data

**1. Simple and Efficient: A Semisupervised Learning Framework for Remote Sensing Image Semantic Segmentation, _TGRS 2022_**
- Paper: https://ieeexplore.ieee.org/document/9943552
- Code: https://github.com/xiaoqiang-lu/LSST
```
@article{lsst,
  title={Simple and efficient: A semisupervised learning framework for remote sensing image semantic segmentation},
  author={Lu, Xiaoqiang and Jiao, Licheng and Liu, Fang and Yang, Shuyuan and Liu, Xu and Feng, Zhixi and Li, Lingling and Chen, Puhua},
  journal=TGRS,
  volume={60},
  pages={1--16},
  year={2022},
  publisher={IEEE}
}
```

**2. Weak-to-Strong Consistency Learning for Semisupervised Image Segmentation, _TGRS 2023_**
- Paper: https://ieeexplore.ieee.org/document/10114409
- Code: https://github.com/xiaoqiang-lu/WSCL
```
@article{wscl,
  title={Weak-to-strong consistency learning for semisupervised image segmentation},
  author={Lu, Xiaoqiang and Jiao, Licheng and Li, Lingling and Liu, Fang and Liu, Xu and Yang, Shuyuan and Feng, Zhixi and Chen, Puhua},
  journal=TGRS,
  volume={61},
  pages={1--15},
  year={2023},
  publisher={IEEE}
}
```

**3. SegMind: Semisupervised Remote Sensing Image Semantic Segmentation With Masked Image Modeling and Contrastive Learning Method, _TGRS 2023_**
- Paper: https://ieeexplore.ieee.org/document/10268382
- Code: https://github.com/lzh-ggs-ddu/SegMind
```
@article{segmind,
  title={SegMind: Semi-supervised rEmote sensing image semantic seGmentation with Masked Image modeling and coNtrastive learning methoD},
  author={Li, Zhenghong and Chen, Hao and Wu, Jiangjiang and Li, Jun and Jing, Ning},
  journal=TGRS,
  year={2023},
  publisher={IEEE}
}
```

**4. AdaptMatch: Adaptive Matching for Semisupervised Binary Segmentation of Remote Sensing Images, _TGRS 2023_**
- Paper: https://ieeexplore.ieee.org/document/10329942
- Code: https://github.com/zhu-xlab/AdaptMatch
```
@article{adaptmatch,
  title={AdaptMatch: Adaptive matching for semisupervised binary segmentation of remote sensing images},
  author={Huang, Wei and Shi, Yilei and Xiong, Zhitong and Zhu, Xiao Xiang},
  journal=TGRS,
  volume={61},
  pages={1--16},
  year={2023},
  publisher={IEEE}
}
```

**5. Advancing Data-Efficient Exploitation for Semi-Supervised Remote Sensing Images Semantic Segmentation, _TGRS 2024_**
- Paper: https://ieeexplore.ieee.org/document/10497698
- Code: https://github.com/lvliang6879/MCSS
```
@article{mcss,
  title={Advancing Data-Efficient Exploitation for Semi-Supervised Remote Sensing Images Semantic Segmentation},
  author={Lv, Liang and Zhang, Lefei},
  journal=TGRS,
  year={2024},
  publisher={IEEE}
}
```

**6. Decouple and weight semi-supervised semantic segmentation of remote sensing images, _ISPRS 2024_**
- Paper: https://www.sciencedirect.com/science/article/pii/S0924271624001710?__cf_chl_tk=oiCsxGFsroow78gDkoVBe0UnmLgukdw6HzY8IsLd.fU-1727171977-0.0.1.1-8852
- Code: https://github.com/zhu-xlab/RS-DWL
```
@article{huang2024decouple,
  title={Decouple and weight semi-supervised semantic segmentation of remote sensing images},
  author={Huang, Wei and Shi, Yilei and Xiong, Zhitong and Zhu, Xiao Xiang},
  journal=ISPRS,
  volume={212},
  pages={13--26},
  year={2024},
  publisher={Elsevier}
}
```