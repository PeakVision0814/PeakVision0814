# 👋 你好，欢迎来到我的 GitHub！

简体中文 | [English](https://github.com/PeakVision0814/PeakVision0814/blob/main/README.md)

## ℹ️ 关于我

2017年至2021年，我本科就读于安阳工学院数学与信息科学学院，获信息与计算科学专业理学学士学位。目前，在杭州电子科技大学通信工程学院智能信息处理实验室攻读硕士学位。我的研究方向为人工智能、深度学习、计算机视觉及医学影像分割。研究旨在应用人工智能技术推动医学影像处理或其他视觉领域的创新发展，解决其中的关键实际问题。

[智能信息处理实验室](http://iipl.net.cn/) | [我们科研小组的GitHub主页](https://github.com/IMOP-lab) | [我的Google学术主页](https://scholar.google.com/citations?user=RDfnwXMAAAAJ&hl=zh-CN) | [我的ORCID主页](https://orcid.org/0009-0008-3190-5669)

## 🔭 我目前正在做...

### 研究领域

- 人工智能（AI）
- 深度学习
- 计算机视觉
- 医学影像分割

### 正在审核

1. Huang X, Chen S, Wang H, Huang T, **Huang G,** et al. "TriFTM-Net: Tri-Path Fourier-Temporal Modulation Network for Macular Edema Pathology Segmentation and Reconstruction in High-Precision Intraoperative Navigation".
2. Chen M, Zhao X, **Huang G**, et al. "Edge-Optimized Cutaneous Carcinoma Detection via Polyphase Lightweight Integration".
3. **Huang G**, Huang X, Huang Z, Yang H, et, al. "Physics-Guided Dual-Path Collaborative Network Embedding Explicit Reaction–Diffusion and Schrödinger-Domain Attentional Priors for Robust Breast DCE-MRI Tumor Segmentation".
4. Huang X, Ye S, Huang Z, **Huang G**, et al. "Spectral-Spatial Modulation and Nonlinear Relational Projection for Complex OCT Macular Morphological Delineation".

### 最近出版

1. Huang X, Zhang T, Xu Z, Huang J, **Huang G**, et al. Multi-aspect fusion in foundational large vision model for visible light medical imaging segmentation[J]. Information Fusion, 2025: 103385. [[文章](https://linkinghub.elsevier.com/retrieve/pii/S1566253525004580) | [代码](https://github.com/IMOP-lab/MasLVM-Pytorch)]

为解决医学图像分割中存在的语义模糊、几何结构复杂和噪声干扰等问题，本研究引入了MasLVM模型，其核心是一个三路径编码器（Tri-Path Encoder）和mKAN解码器框架。三路径编码器通过三个专用模块分别编码语义信息、频域特征和几何形态。其中，语义上下文编码器（SCE）通过整合全局上下文感知来增强语义提取；频谱样条编码器（SSE）利用多频特征调制器和KAN通道注意力来优化频域表示并抑制噪声；层次可变形形态测量编码器（HDME）则使用可变形卷积和自适应特征编码捕捉多尺度的复杂几何形状。该模型利用mKAN解码器，通过KAN多重自注意力机制和迭代注意力特征融合（iAFF）来自适应地优先处理并综合与任务相关的特征，从而优化分割结果。在包括ISIC2017、ISIC2018、PH2、CVC-ClinicDB、Kvasir-SEG和PolypGen在内的六个基准数据集上的实验评估表明，MasLVM在实现顶尖分割性能方面表现出色。这些结果证实了该模型在不同成像条件下的适应性和鲁棒性，显示了其在临床诊断和术中导航等领域的应用潜力，但仍需进一步验证。未来的工作可聚焦于减少对大量标注数据的依赖、提高计算效率、增强对不同成像模式的兼容性，以及通过多模态融合提升诊断精度。

```latex
@article{huang2025multi,
  title={Multi-aspect fusion in foundational large vision model for visible light medical imaging segmentation},
  author={Huang, Xingru and Zhang, Tianyun and Xu, Zhaoyang and Huang, Jian and Huang, Haopeng and Yang, Han and Zou, Binfeng and Ding, Shouqin and Ruan, Renjie and Huang, Zhao and others},
  journal={Information Fusion},
  pages={103385},
  year={2025},
  publisher={Elsevier}
}
```

2. Wang H, **Huang G**, et, al. Kolmogorov–Arnold–Enhanced Nonlinear Expansions for Fine-Grained Feature Amplification in Robust Near-Shore SAR Vessel Discrimination[J]. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2025. [[文章](https://doi.org/10.1109/jstars.2025.3575439)]

这篇研究论文介绍了一种名为 KaneYOLO 的新方法，旨在改进合成孔径雷达（SAR）图像中的船舶检测，特别针对两大挑战：一是在复杂的近岸环境中，船舶易与岸上物体混淆导致漏检；二是由于分辨率限制和下采样导致小型船舶特征丢失。KaneYOLO 在 YOLOv8 模型的基础上，通过引入三项关键创新进行了增强：一是 KAN 模块，它利用柯尔莫哥洛夫-阿诺德定理和 KAGN 卷积来模拟复杂的非线性关系，抑制背景杂波同时增强船舶特征；二是特征融合分配结构（FFAS），采用并行化深度卷积来有效聚合多尺度特征并保留小目标的细节；三是细节增强检测头（DEDH），使用共享卷积和组归一化（Group Normalization）以实现高效计算并改善局部特征的利用。在 HRSID 和 SSDD 数据集上的实验结果表明，KaneYOLO 具有良好的鲁棒性，取得了较高的平均精度（在 HRSID 上达到 93.9% AP，在 SSDD 上达到 98.3% AP50），并在区分杂乱近岸场景中的船舶以及检测小型船只方面显示出显著改进。

如果这篇文章对你有帮助，欢迎引用。

```latex
@article{wang2025kolmogorov,
  title={Kolmogorov--Arnold--Enhanced Nonlinear Expansions for Fine-Grained Feature Amplification in Robust Near-Shore SAR Vessel Discrimination},
  author={Wang, Hankang and Huang, Gaopeng and Huang, Zhao and Huang, Xingru and Xu, Zhaoyang and Zheng, Zhiwen and Liu, Shanwei and Wei, Shiqing and Liu, Jin and Zhang, Xiaoshuai},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing},
  year={2025},
  publisher={IEEE}
}
```

3. Sun Y, Xu Z, Guo Y, Huang J, **Huang G**, et, al. Scale-Adaptive viable tumor burden estimation via histopathological microscopy image segmentation[J]. Computers in Biology and Medicine, 2025, 189: 109915. [ [文章](https://www.sciencedirect.com/science/article/pii/S0010482525002665) | [代码](https://github.com/IMOP-lab/Scale-Adaptive-Net) ]

这篇文章提出了一种新的方法，用于解决在全切片图像中进行癌症分割以估计肿瘤负荷这一关键步骤所面临的挑战。这些挑战包括肿瘤边界模糊以及与活肿瘤区域分离的小区域。考虑到多尺度特征在各种视觉相关任务中的有效性，本文提出了一种尺度自适应的方法。该研究关注于通过组织病理学显微镜图像的分割来准确估计活肿瘤的负荷，这对于癌症的评估至关重要。文章中提到了癌症分割、结构相似性、深度学习、数字病理学和计算病理学等关键词。

如果这篇文章对你有帮助，欢迎引用：

```latex
@article{sun2025scale,
  title={Scale-Adaptive viable tumor burden estimation via histopathological microscopy image segmentation},
  author={Sun, Yibao and Xu, Zhaoyang and Guo, Yihao and Huang, Jian and Huang, Gaopeng and Huang, Tangsen and Zhao, Lou and Jiang, Shaowei and Zheng, Zhiwen and Liu, Jin and others},
  journal={Computers in Biology and Medicine},
  volume={189},
  pages={109915},
  year={2025},
  publisher={Elsevier}
}
```

4. Huang X, Zhang T, Huang J, Guo Y, **Huang G,** et al. LiGu-LVM: Linguistic-Guided Generative Large Vision Model for IoMT Clinical Ocular Disease Screening via Morphology Dissection[J]. IEEE Internet of Things Journal, 2024.[ [文章](https://ieeexplore.ieee.org/abstract/document/10742080) ]

本文提出了一种语言引导生成的大型视觉模型（LiGu-LVM），旨在提高物联网医疗设备（IoMT）支持的移动眼科扫描仪的诊断能力。LiGu-LVM通过整合动态分配的高速量化系统（DAHSQS）、语言引导生成局部隔离模块（LiGu）、眼视觉变换段分析模块（OVT-SAM）和多尺度递归注意力分割引擎（MuRASE），解决了低分辨率图像处理效率低、复杂眼部形态测量难度大等问题。实验结果表明，LiGu-LVM在眼部语义分割任务中取得了超过80%的交并比（IoU），并在CelebA-HQ数据集上达到82.9%的IoU，相较现有模型性能提升了4.9%。该方法为IoMT临床环境中的大规模高精度早期筛查提供了可靠支持。

如果这篇文章对你有帮助，欢迎引用：
```latex
@article{huang2024ligu,
  title={LiGu-LVM: Linguistic-Guided Generative Large Vision Model for IoMT Clinical Ocular Disease Screening via Morphology Dissection},
  author={Huang, Xingru and Zhang, Tianyun and Huang, Jian and Guo, Yihao and Huang, Gaopeng and Yang, Han and Zheng, Zhiwen and Zhao, Lou and Jiang, Shaowei and Liu, Jin and others},
  journal={IEEE Internet of Things Journal},
  year={2024},
  publisher={IEEE}
}
```

5. Li Z, **Huang G**, Zou B, et al. Segmentation of Low-Light Optical Coherence Tomography Angiography Images under the Constraints of Vascular Network Topology[J]. Sensors, 2024, 24(3): 774.[ [文章](https://www.mdpi.com/1424-8220/24/3/774) | [代码](https://github.com/RicoLeehdu/BiSTIM) ]


本文探讨了在血管网络拓扑约束下分割低光条件下的光学相干断层扫描血管造影（OCTA）图像的技术。研究中提出了一种基于生物学信息信号传递成像框架（BiSTIM）的新方法，包含蛋白组学启发的拓扑分割模块（PrIS-TS）和生物发光适应模块（BLAAM）。这些模块在解决成像伪影、低信噪比及血管分支复杂性方面表现出色。通过对视网膜浅层和深层血管层的精确分割，该方法显著提高了疾病诊断和分类的可靠性，尤其在视网膜静脉阻塞（RVO）和半中心静脉阻塞（HCRVO）的研究中表现优异。实验表明，该技术在多个数据集上的表现超越了现有方法，推动了OCTA图像分割和分析领域的发展。

如果这篇文章对你有帮助，欢迎引用：

```latex
@article{li2024segmentation,
  title={Segmentation of Low-Light Optical Coherence Tomography Angiography Images under the Constraints of Vascular Network Topology},
  author={Li, Zhi and Huang, Gaopeng and Zou, Binfeng and Chen, Wenhao and Zhang, Tianyun and Xu, Zhaoyang and Cai, Kunyan and Wang, Tingyu and Sun, Yaoqi and Wang, Yaqi and others},
  journal={Sensors},
  volume={24},
  number={3},
  pages={774},
  year={2024},
  publisher={MDPI}
}
```

## 💬 欢迎向我提问...

我乐意与大家分享有关深度学习、图像处理、卷积神经网络等方面的研究经验与知识。

## 📫 如何联系我：

如果对我或者我的工作感兴趣，欢迎通过电子邮箱与我联系：[gaopeng.huang@hdu.edu.cn](mailto:gaopeng.huang@hdu.edu.cn)。

## 🎓 教育背景：

**本科教育**：安阳工学院，数学与信息科学学院，信息与计算科学，理学学士学位（2017-2021）

**研究生教育**：杭州电子科技大学，通信工程学院，信息与通信工程，工学硕士学位（2023 至今）

## ⚡ 有趣的事实：

我对人工智能技术充满浓厚兴趣，尤其是如何运用它来提升医疗诊断的效率。除了科研，我还喜欢打羽毛球🏸，这不仅让我保持健康的身体状态，也可以我更好地投入学习和工作😊。如果你也对羽毛球感兴趣，且又在附近的话，欢迎随时找我切磋交流！

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=PeakVision0814)

![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=PeakVision0814)
