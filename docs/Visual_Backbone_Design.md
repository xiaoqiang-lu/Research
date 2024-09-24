# Visual Backbone Design

> Efficient backbones serve as foundation models that provide powerful feature representations for downstream tasks, can be divided into three main architectures: Convolutional Neural Network (CNN), Transformer, amd Mamba. To gain a quicker understanding of the field and achieve improvements in practical projects, based on my personal experiences, I recommend you to read the following methods:
> > CNN: ResNet, Inceptionv3, ConvNeXt, UniRepLKNet, InceptionNeXt, WTConv, LSKNet
>
> > Transformer: ViT, Swin, BEiT, CSwin, FocalNet, iFormer, BEiTv2, ViT-Adapter, InternImage, TransNeXt, Agent Attention, PVT, MiT, PVTv2, VAN, CAS-ViT
>
> > Mamba: VMamba
#

**1. Deep Residual Learning for Image Recognition, _CVPR 2016_**
- Paper: https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf
- Code: https://github.com/huggingface/pytorch-image-models/blob/main/timm/models/resnet.py
```
@inproceedings{resnet,
  title={Deep residual learning for image recognition},
  author={He, Kaiming and Zhang, Xiangyu and Ren, Shaoqing and Sun, Jian},
  booktitle=CVPR,
  pages={770--778},
  year={2016}
}
```

**2. Rethinking the Inception Architecture for Computer Vision, _CVPR 2016_**
- Paper: https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Szegedy_Rethinking_the_Inception_CVPR_2016_paper.pdf
- Code: https://github.com/huggingface/pytorch-image-models/blob/main/timm/models/inception_v3.py
```
@inproceedings{inceptionv3,
  title={Rethinking the inception architecture for computer vision},
  author={Szegedy, Christian and Vanhoucke, Vincent and Ioffe, Sergey and Shlens, Jon and Wojna, Zbigniew},
  booktitle=CVPR,
  pages={2818--2826},
  year={2016}
}
```

**3. An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale, _ICLR 2021_**
- Paper: https://arxiv.org/abs/2010.11929
- Code: https://github.com/huggingface/pytorch-image-models/blob/main/timm/models/vision_transformer.py
```
@inproceedings{vit,
  title={An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale},
  author={Dosovitskiy, Alexey and Beyer, Lucas and Kolesnikov, Alexander and Weissenborn, Dirk and Zhai, Xiaohua and Unterthiner, Thomas and Dehghani, Mostafa and Minderer, Matthias and Heigold, Georg and Gelly, Sylvain and others},
  booktitle=ICLR,
  year={2021}
}
```

**4. Swin transformer: Hierarchical vision transformer using shifted windows, _ICCV 2021_**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Swin_Transformer_Hierarchical_Vision_Transformer_Using_Shifted_Windows_ICCV_2021_paper.pdf
- Code: https://github.com/microsoft/Swin-Transformer
```
@inproceedings{swin,
  title={Swin transformer: Hierarchical vision transformer using shifted windows},
  author={Liu, Ze and Lin, Yutong and Cao, Yue and Hu, Han and Wei, Yixuan and Zhang, Zheng and Lin, Stephen and Guo, Baining},
  booktitle=ICCV,
  pages={10012--10022},
  year={2021}
}
```

**5. BEiT: BERT Pre-Training of Image Transformers, _ICLR 2022_**
- Paper: https://arxiv.org/pdf/2106.08254
- Code: https://github.com/microsoft/unilm/tree/master/beit
```
@inproceedings{beit,
  title={Beit: Bert pre-training of image transformers},
  author={Bao, Hangbo and Dong, Li and Piao, Songhao and Wei, Furu},
  booktitle=ICLR,
  year={2022}
}
```

**6. A ConvNet for the 2020s, _CVPR 2022_**
- Paper: https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_A_ConvNet_for_the_2020s_CVPR_2022_paper.pdf
- Code: https://github.com/facebookresearch/ConvNeXt
```
@inproceedings{convnext,
  title={A convnet for the 2020s},
  author={Liu, Zhuang and Mao, Hanzi and Wu, Chao-Yuan and Feichtenhofer, Christoph and Darrell, Trevor and Xie, Saining},
  booktitle=CVPR,
  pages={11976--11986},
  year={2022}
}
```

**7. CSWin Transformer: A General Vision Transformer Backbone with Cross-Shaped Windows, _CVPR 2022_**
- Paper: https://openaccess.thecvf.com/content/CVPR2022/papers/Dong_CSWin_Transformer_A_General_Vision_Transformer_Backbone_With_Cross-Shaped_Windows_CVPR_2022_paper.pdf
- Code: https://github.com/microsoft/CSWin-Transformer
```
@inproceedings{cswin,
  title={Cswin transformer: A general vision transformer backbone with cross-shaped windows},
  author={Dong, Xiaoyi and Bao, Jianmin and Chen, Dongdong and Zhang, Weiming and Yu, Nenghai and Yuan, Lu and Chen, Dong and Guo, Baining},
  booktitle=CVPR,
  pages={12124--12134},
  year={2022}
}
```

**8. Focal Modulation Networks, _NIPS 2022_**
- Paper: https://proceedings.neurips.cc/paper_files/paper/2022/file/1b08f585b0171b74d1401a5195e986f1-Paper-Conference.pdf
- Code: https://github.com/microsoft/FocalNet
```
@article{focalnet,
  title={Focal modulation networks},
  author={Yang, Jianwei and Li, Chunyuan and Dai, Xiyang and Gao, Jianfeng},
  journal=NIPS,
  volume={35},
  pages={4203--4217},
  year={2022}
}
```

**9. Inception Transformer, _NIPS 2022_**
- Paper: https://proceedings.neurips.cc/paper_files/paper/2022/file/94e85561a342de88b559b72c9b29f638-Paper-Conference.pdf
- Code: https://github.com/sail-sg/iFormer
```
@article{iformer,
  title={Inception transformer},
  author={Si, Chenyang and Yu, Weihao and Zhou, Pan and Zhou, Yichen and Wang, Xinchao and Yan, Shuicheng},
  journal=NIPS,
  volume={35},
  pages={23495--23509},
  year={2022}
}
```

**10. BEiT v2: Masked Image Modeling with Vector-Quantized Visual Tokenizers, _ArXiv 2022_**
- Paper: https://arxiv.org/abs/2208.06366
- Code: https://github.com/microsoft/unilm/tree/master/beit2
```
@article{beitv2,
  title={Beit v2: Masked image modeling with vector-quantized visual tokenizers},
  author={Peng, Zhiliang and Dong, Li and Bao, Hangbo and Ye, Qixiang and Wei, Furu},
  journal={arXiv preprint arXiv:2208.06366},
  year={2022}
}
```

**11. Vision Transformer Adapter for Dense Predictions, _ICLR 2023_**
- Paper: https://arxiv.org/abs/2205.08534
- Code: https://github.com/czczup/ViT-Adapter
```
@inproceedings{vitadapter,
  title={Vision transformer adapter for dense predictions},
  author={Chen, Zhe and Duan, Yuchen and Wang, Wenhai and He, Junjun and Lu, Tong and Dai, Jifeng and Qiao, Yu},
  booktitle=ICLR,
  year={2023}
}
```

**12. Internimage: Exploring large-scale vision foundation models with deformable convolutions, _CVPR 2023_**
- Paper: https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_InternImage_Exploring_Large-Scale_Vision_Foundation_Models_With_Deformable_Convolutions_CVPR_2023_paper.pdf
- Code: https://github.com/OpenGVLab/InternImage
```
@inproceedings{internimage,
  title={Internimage: Exploring large-scale vision foundation models with deformable convolutions},
  author={Wang, Wenhai and Dai, Jifeng and Chen, Zhe and Huang, Zhenhang and Li, Zhiqi and Zhu, Xizhou and Hu, Xiaowei and Lu, Tong and Lu, Lewei and Li, Hongsheng and others},
  booktitle=CVPR,
  pages={14408--14419},
  year={2023}
}
```

**13. UniRepLKNet: A Universal Perception Large-Kernel ConvNet for Audio Video Point Cloud Time-Series and Image Recognition, _CVPR 2024_**
- Paper: https://openaccess.thecvf.com/content/CVPR2024/papers/Ding_UniRepLKNet_A_Universal_Perception_Large-Kernel_ConvNet_for_Audio_Video_Point_CVPR_2024_paper.pdf
- Code: https://github.com/AILab-CVC/UniRepLKNet
```
@inproceedings{unireplknet,
  title={UniRepLKNet: A Universal Perception Large-Kernel ConvNet for Audio Video Point Cloud Time-Series and Image Recognition},
  author={Ding, Xiaohan and Zhang, Yiyuan and Ge, Yixiao and Zhao, Sijie and Song, Lin and Yue, Xiangyu and Shan, Ying},
  booktitle=CVPR,
  pages={5513--5524},
  year={2024}
}
```

**14. TransNeXt: Robust Foveal Visual Perception for Vision Transformers, _CVPR 2024_**
- Paper: https://openaccess.thecvf.com/content/CVPR2024/papers/Shi_TransNeXt_Robust_Foveal_Visual_Perception_for_Vision_Transformers_CVPR_2024_paper.pdf
- Code: https://github.com/DaiShiResearch/TransNeXt
```
@inproceedings{transnext,
  title={TransNeXt: Robust Foveal Visual Perception for Vision Transformers},
  author={Shi, Dai},
  booktitle=CVPR,
  pages={17773--17783},
  year={2024}
}
```

**15. InceptionNeXt: When Inception Meets ConvNeXt, _CVPR 2024_**
- Paper: https://openaccess.thecvf.com/content/CVPR2024/papers/Yu_InceptionNeXt_When_Inception_Meets_ConvNeXt_CVPR_2024_paper.pdf
- Code: https://github.com/sail-sg/inceptionnext
```
@inproceedings{inceptionnext,
  title={Inceptionnext: When inception meets convnext},
  author={Yu, Weihao and Zhou, Pan and Yan, Shuicheng and Wang, Xinchao},
  booktitle=CVPR,
  pages={5672--5683},
  year={2024}
}
```

**16. Agent Attention: On the Integration of Softmax and Linear Attention, _ECCV 2024_**
- Paper: https://arxiv.org/abs/2312.08874
- Code: https://github.com/LeapLabTHU/Agent-Attention
```
@inproceedings{agentatt,
  title={Agent attention: On the integration of softmax and linear attention},
  author={Han, Dongchen and Ye, Tianzhu and Han, Yizeng and Xia, Zhuofan and Song, Shiji and Huang, Gao},
  booktitle=ECCV,
  year={2024}
}
```

**17. Wavelet Convolutions for Large Receptive Fields, _ECCV 2024_**
- Paper: https://arxiv.org/abs/2407.05848
- Code: https://github.com/BGU-CS-VIL/WTConv
```
@inproceedings{wtconv,
  title={Wavelet Convolutions for Large Receptive Fields},
  author={Finder, Shahaf E and Amoyal, Roy and Treister, Eran and Freifeld, Oren},
  booktitle=ECCV,
  year={2024}
}
```

**18. VMamba: Visual State Space Model, _ArXiv 2024_**
- Paper: https://arxiv.org/abs/2401.10166
- Code: https://github.com/MzeroMiko/VMamba
```
@article{vmamba,
  title={VMamba: Visual State Space Model},
  author={Liu, Yue and Tian, Yunjie and Zhao, Yuzhong and Yu, Hongtian and Xie, Lingxi and Wang, Yaowei and Ye, Qixiang and Liu, Yunfan},
  journal={arXiv preprint arXiv:2401.10166},
  year={2024}
}
```

**19. Pyramid Vision Transformer: A Versatile Backbone for Dense Prediction without Convolutions, _ICCV 2021_**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Pyramid_Vision_Transformer_A_Versatile_Backbone_for_Dense_Prediction_Without_ICCV_2021_paper.pdf
- Code: https://github.com/whai362/PVT
```
@inproceedings{pvt,
  title={Pyramid vision transformer: A versatile backbone for dense prediction without convolutions},
  author={Wang, Wenhai and Xie, Enze and Li, Xiang and Fan, Deng-Ping and Song, Kaitao and Liang, Ding and Lu, Tong and Luo, Ping and Shao, Ling},
  booktitle=ICCV,
  pages={568--578},
  year={2021}
}
```

**20. SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers, _NIPS 2021_**
- Paper: https://proceedings.neurips.cc/paper_files/paper/2021/file/64f1f27bf1b4ec22924fd0acb550c235-Paper.pdf
- Code: https://github.com/NVlabs/SegFormer
```
@article{segformer,
  title={SegFormer: Simple and efficient design for semantic segmentation with transformers},
  author={Xie, Enze and Wang, Wenhai and Yu, Zhiding and Anandkumar, Anima and Alvarez, Jose M and Luo, Ping},
  journal=NIPS,
  volume={34},
  pages={12077--12090},
  year={2021}
}
```

**21. PVT v2: Improved Baselines with Pyramid Vision Transformer, _CVM 2022_**
- Paper: https://link.springer.com/article/10.1007/s41095-022-0274-8
- Code: https://github.com/whai362/PVT
```
@article{pvtv2,
  title={Pvt v2: Improved baselines with pyramid vision transformer},
  author={Wang, Wenhai and Xie, Enze and Li, Xiang and Fan, Deng-Ping and Song, Kaitao and Liang, Ding and Lu, Tong and Luo, Ping and Shao, Ling},
  journal={Computational Visual Media},
  volume={8},
  number={3},
  pages={415--424},
  year={2022},
  publisher={Springer}
}
```

**22. Visual Attention Network, _CVM 2023_**
- Paper: https://link.springer.com/article/10.1007/s41095-023-0364-2
- Code: https://github.com/Visual-Attention-Network
```
@article{van,
  title={Visual attention network},
  author={Guo, Meng-Hao and Lu, Cheng-Ze and Liu, Zheng-Ning and Cheng, Ming-Ming and Hu, Shi-Min},
  journal={Computational Visual Media},
  volume={9},
  number={4},
  pages={733--752},
  year={2023},
  publisher={Springer}
}
```

**23. Large Selective Kernel Network for Remote Sensing Object Detection, _ICCV 2023_**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Large_Selective_Kernel_Network_for_Remote_Sensing_Object_Detection_ICCV_2023_paper.pdf
- Code: https://github.com/zcablii/LSKNet
```
@inproceedings{lsknet,
  title={Large selective kernel network for remote sensing object detection},
  author={Li, Yuxuan and Hou, Qibin and Zheng, Zhaohui and Cheng, Ming-Ming and Yang, Jian and Li, Xiang},
  booktitle=ICCV,
  pages={16794--16805},
  year={2023}
}
```

**24. CAS-ViT: Convolutional Additive Self-attention Vision Transformers for Efficient Mobile Applications, _ArXiv 2024_**
- Paper: https://arxiv.org/pdf/2408.03703
- Code: https://github.com/Tianfang-Zhang/CAS-ViT
```
@article{casvit,
  title={CAS-ViT: Convolutional Additive Self-attention Vision Transformers for Efficient Mobile Applications},
  author={Zhang, Tianfang and Li, Lei and Zhou, Yang and Liu, Wentao and Qian, Chen and Ji, Xiangyang},
  journal={arXiv preprint arXiv:2408.03703},
  year={2024}
}
```