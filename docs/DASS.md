# Domain Adaptive Semantic Segmentation

**Efficient backbones serve as foundation models that provide powerful feature representations for downstream tasks, can be divided into three main architectures: Convolutional Neural Network (CNN), Transformer, amd Mamba. To gain a quicker understanding of the field and achieve improvements in practical projects, based on my personal experiences, I recommend you to read the following methods:**
- **CNN**: ResNet, Inceptionv3, ConvNeXt, UniRepLKNet, InceptionNeXt, WTConv, LSKNet
- **Transformer**: ViT, Swin, BEiT, CSwin, FocalNet, iFormer, BEiTv2, ViT-Adapter, InternImage, TransNeXt, Agent Attention, PVT, MiT, PVTv2, VAN, CAS-ViT
- **Mamba**: VMamba
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