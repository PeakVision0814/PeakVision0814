<!--
**PeakVision0814/PeakVision0814** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# 👋 Hello, welcome to my GitHub!

English | [简体中文](https://github.com/PeakVision0814/PeakVision0814/blob/main/README_zh.md)

## ℹ️ About Me

I pursued my Bachelor of Science degree in Information and Computational Science at the School of Mathematics and Information Science, Anyang Institute of Technology, from 2017 to 2021. Currently, I am a Master's student at the School of Communication Engineering, Hangzhou Dianzi University, affiliated with the Intelligent Information Processing Laboratory. My research interests span artificial intelligence, deep learning, computer vision, and medical image segmentation. My goal is to leverage AI technologies to drive innovation in medical image processing or other visual fields and address key challenges in practical applications.

[**Intelligent Information Processing Laboratory**](http://iipl.net.cn/) | [**Our Research Group's GitHub Page**](https://github.com/IMOP-lab) | [**My Google Scholar Profile**](https://scholar.google.com/citations?user=RDfnwXMAAAAJ&hl=en) | [**My ORCID Profile**](https://orcid.org/0009-0008-3190-5669)

## 🔭 I’m currently working on ...

### Research Areas

- Artificial Intelligence (AI)
- Deep Learning
- Computer Vision
- Medical Image Segmentation

### Under Review

1. Huang X, Chen S, Wang H, Huang T, **Huang G,** et al. "TriFTM-Net: Tri-Path Fourier-Temporal Modulation Network for Macular Edema Pathology Segmentation and Reconstruction in High-Precision Intraoperative Navigation".
2. Chen M, Zhao X, **Huang G**, et al. "Edge-Optimized Cutaneous Carcinoma Detection via Polyphase Lightweight Integration".
3. Huang X, Ye S, Huang Z, **Huang G**, et al. "Spectral-Spatial Modulation and Nonlinear Relational Projection for Complex OCT Macular Morphological Delineation".
4. **Huang G**, Huang X, Huang Z, Yang H, et, al. "Physics-Guided Dual-Path Collaborative Network Embedding Explicit Reaction–Diffusion and Schrödinger-Domain Attentional Priors for Robust Breast DCE-MRI Tumor Segmentation".


### Recent Publications

1. Huang X, Zhang T, Xu Z, Huang J, **Huang G**, et, al. Multi-aspect fusion in foundational large vision model for visible light medical imaging segmentation[J]. Information Fusion, 2025. [[paper](https://linkinghub.elsevier.com/retrieve/pii/S1566253525004580) | [code](https://github.com/IMOP-lab/MasLVM-Pytorch)]

To address challenges in visible-light medical imaging such as semantic ambiguity, noise, and geometric complexity, this paper introduces the Multi-Aspect Large Vision Model (MasLVM). This model features a parallel Tri-Path Encoder architecture and a multi-layer KAN (mKAN) Decoder. The encoder consists of three specialized branches: the Semantic Context Encoder (SCE) leverages a large vision model for contextual understanding, the Spectral Spline Encoder (SSE) operates in the frequency domain to mitigate noise, and the Hierarchical Deformable Morphometry Encoder (HDME) uses deformable convolutions to capture complex shapes. The mKAN decoder then adaptively fuses these multi-faceted features using KAN-based self-attention and iterative attentional fusion. MasLVM's performance was validated across six public medical imaging datasets (ISIC2017, ISIC2018, PH2, CVC-ClinicDB, Kvasir-SEG, and Polypgen), where it demonstrated stable and competitive results compared to state-of-the-art methods.

2. Wang H, **Huang G**, et, al. Kolmogorov–Arnold–Enhanced Nonlinear Expansions for Fine-Grained Feature Amplification in Robust Near-Shore SAR Vessel Discrimination[J]. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2025. [[paper](https://doi.org/10.1109/jstars.2025.3575439)]

This research paper introduces KaneYOLO, a novel method for improving ship detection in Synthetic Aperture Radar (SAR) images, specifically targeting the challenges of missed detections in complex nearshore environments where ships can be confused with shore objects, and the loss of features for small ships due to resolution limits and downsampling. KaneYOLO enhances the YOLOv8 model by incorporating three key innovations: a KAN Block, leveraging the Kolmogorov-Arnold theorem with KAGN convolutions to model complex nonlinearities and suppress background clutter while amplifying ship features; a Feature Fusion Allocation Structure (FFAS) with parallelized deep convolutions to effectively aggregate multi-scale features and preserve details of small targets; and a Detail Enhancement Detection Head (DEDH) using shared convolutions and Group Normalization for efficient computation and improved local feature utilization. Experimental results on the HRSID and SSDD datasets demonstrate KaneYOLO's robustness, achieving high average precision (93.9% AP on HRSID and 98.3% AP50 on SSDD) and showing significant improvements in distinguishing ships in cluttered nearshore scenes and detecting small vessels.

If this article helps, feel free to cite it.

```latex
@article{wang2025kolmogorov,
  title={Kolmogorov--Arnold--Enhanced Nonlinear Expansions for Fine-Grained Feature Amplification in Robust Near-Shore SAR Vessel Discrimination},
  author={Wang, Hankang and Huang, Gaopeng and Huang, Zhao and Huang, Xingru and Xu, Zhaoyang and Zheng, Zhiwen and Liu, Shanwei and Wei, Shiqing and Liu, Jin and Zhang, Xiaoshuai},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing},
  year={2025},
  publisher={IEEE}s
}
```

3. Sun Y, Xu Z, Guo Y, Huang J, **Huang G**, et, al. Scale-Adaptive viable tumor burden estimation via histopathological microscopy image segmentation[J]. Computers in Biology and Medicine, 2025, 189: 109915. [ [paper](https://www.sciencedirect.com/science/article/pii/S0010482525002665) | [code](https://github.com/IMOP-lab/Scale-Adaptive-Net) ]

The paper presents a new approach to address the challenges in cancer segmentation in whole-slide images, which is a fundamental step for estimating tumor burden crucial for cancer assessment. These challenges include vague boundaries and small regions dissociated from viable tumor areas. Considering the usefulness of multi-scale features in various vision-related tasks, the paper proposes a scale-adaptive method. The research focuses on accurately estimating the viable tumor burden through the segmentation of histopathological microscopy images, which is essential for cancer evaluation. The keywords mentioned in the article include cancer segmentation, structural similarity, deep learning, digital pathology, and computational pathology.

If this article helps, feel free to cite it:

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

4. Huang X, Zhang T, Huang J, Guo Y, **Huang G,** et al. LiGu-LVM: Linguistic-Guided Generative Large Vision Model for IoMT Clinical Ocular Disease Screening via Morphology Dissection[J]. IEEE Internet of Things Journal, 2024. [ [paper](https://ieeexplore.ieee.org/abstract/document/10742080) ]

This paper introduces a Linguistic-Guided Generative Large Vision Model (LiGu-LVM) to enhance the diagnostic capability of IoMT-enabled mobile ocular scanners. LiGu-LVM integrates a Dynamically Allocated High-Speed Quantization System (DAHSQS), a Linguistic-Guided Generative Local-Isolation module (LiGu), an Oculo Visio Transformatrix Segmentum-Analytica Modulorum (OVT-SAM), and a Multi-Scale Recursive Attention Segmentation Engine (MuRASE) to address challenges like low imaging quality and complex ocular morphology measurement. Experimental results demonstrate that LiGu-LVM achieves over 80% Intersection over Union (IoU) in ocular semantic segmentation, reaching 82.9% IoU on the CelebA-HQ dataset, outperforming existing models by 4.9%. This approach provides robust support for large-scale, high-precision early screening of ocular diseases in IoMT clinical environments.

If this article helps, feel free to cite it:

```latex
@article{huang2024ligu,
  title={LiGu-LVM: Linguistic-Guided Generative Large Vision Model for IoMT Clinical Ocular Disease Screening via Morphology Dissection},
  author={Huang, Xingru and Zhang, Tianyun and Huang, Jian and Guo, Yihao and Huang, Gaopeng and Yang, Han and Zheng, Zhiwen and Zhao, Lou and Jiang, Shaowei and Liu, Jin and others},
  journal={IEEE Internet of Things Journal},
  year={2024},
  publisher={IEEE}
}
```

5. Li Z, **Huang G**, Zou B, et al. Segmentation of Low-Light Optical Coherence Tomography Angiography Images under the Constraints of Vascular Network Topology[J]. Sensors, 2024, 24(3): 774. [ [paper](https://www.mdpi.com/1424-8220/24/3/774) | [code](https://github.com/RicoLeehdu/BiSTIM) ]

This paper explores techniques for segmenting optical coherence tomography angiography (OCTA) images under low-light conditions with vascular network topology constraints. A novel Biological Information Signal Transduction Imaging Framework (BiSTIM) is proposed, incorporating the Proteomic-Inspired Topological Segmentation (PrIS-TS) and Bio-Luminescence Adaptation (BLAAM) modules. These modules effectively address imaging artifacts, low signal-to-noise ratios, and vascular branching complexities. By achieving precise segmentation of superficial and deep retinal vascular layers, this method significantly enhances the reliability of disease diagnosis and classification, particularly in retinal vein occlusion (RVO) and hemicentral retinal vein occlusion (HCRVO) studies. Experiments demonstrate that this approach outperforms existing methods across multiple datasets, advancing the field of OCTA image segmentation and analysis.

If this article helps, feel free to cite it:

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

## 💬 Ask me about ...

I am happy to share my knowledge and research experiences on deep learning, image processing, convolutional neural networks, and related topics.

## 📫 How to Reach Me:

If you are interested in my work, feel free to contact me via email: [gaopeng.huang@hdu.edu.cn](mailto:gaopeng.huang@hdu.edu.cn).

## 🎓 Educational Background:

**Undergraduate**: Anyang Institute of Technology, School of Mathematics and Information Science, Bachelor of Science in Information and Computational Science (2017–2021)

**Graduate**: Hangzhou Dianzi University, School of Communication Engineering, Master of Engineering in Information and Communication Engineering (2023–Present)

## ⚡ Fun Facts:

I have a keen interest in artificial intelligence, particularly its application in improving medical diagnostics. Outside of research, I enjoy playing badminton🏸, which helps me stay physically fit and energized for learning and work 😊. If you are also interested in badminton, feel free to connect with me—I’d love to play and share the joy of sports with friends!

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=PeakVision0814)

![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=PeakVision0814)
