# Awesome-Foundation-Models-for-Pathology-Image-Analysis

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)

:fire::fire: This is a collection of awesome articles about Foundation Models in Pathology Image Analysis:fire::fire:

:loudspeaker: Our review paper published on arXiv: [Foundation Models in Pathology Image Analysis](https://arxiv.org/abs/2307.16142) :heart:

#### Citation

```python
@inproceedings{molaei2023implicit,
  title={Implicit neural representation in medical imaging: A comparative survey},
  author={Molaei, Amirali and Aminimehr, Amirhossein and Tavakoli, Armin and Kazerouni, Amirhossein and Azad, Bobby and Azad, Reza and Merhof, Dorit},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={2381--2391},
  year={2023}
}
```

# Introduction 

Foundation models have gained popularity in recent years for a broad range of pathological imaging applications.

With the aim of providing easier access for researchers, this repo contains a comprehensive paper list of Foundation models in Pathology Image Analysis, including papers, codes, and related websites.<br>
We considered a sum of `81` research papers spanning from 2022 to 2025.

---
# papers

<a name="return-to-list"></a>

- [Large-scale Pre-trained Models](#Large-scale-Pre-trained-Models)
  - [Large Vision Models](#Large-Vision-Models)
  - [Contrastive Multi-modal Models](#Contrastive-Multi-modal-models)
  - [Multi-modal Large Language Models](#Multi-modal-Large-Language-Models)
- [Adapt Foundation Models for Specific Tasks](#Adapt-Foundation-Models-for-Specific-Tasks)
  - [Pathological Classification](#Pathological-Classification)
  - [Pathological Component Segmentation](#Pathological-Component-Segmentation)
  - [Other applications](#Other-applications)

(Each section is ordered by the publication dates)

## Large-scale Pre-trained Models
---

### Large Vision Models


1. 📜 **Scaling Vision Transformers to Gigapixel Images via Hierarchical Self-Supervised Learning**
   - 📖 Proceedings: IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2022
   - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2022/html/Chen_Scaling_Vision_Transformers_to_Gigapixel_Images_via_Hierarchical_Self-Supervised_Learning_CVPR_2022_paper.html?trk=public_post_comment-text)
   - 💻 [Code](https://github.com/mahmoodlab/HIPT)
   - 📌 Highlight: A Hierarchical Image Pyramid Transformer is proposed to leverage the inherent natural hierarchical structure in WSIs; A two-stage SSL approach is proposed to learn high-resolution image representations, which can model important inductive biases in the phenotypic hierarchical structure of the tumor microenvironment.

2. 📜 **Transformer-based unsupervised contrastive learning for histopathological image classification**
   - 📖 Journal: Medical Image Analysis, 2022
   - 📄 [PDF](https://www.sciencedirect.com/science/article/abs/pii/S1361841522002043)
   - 💻 [Code](https://github.com/Xiyue-Wang/TransPath)
   - 📌 Highlight: A proposed CTransPath integrates CNN and multi-scale Swin Transformer to better capture local fine structures and global context; A semantically-relevant contrastive learning framework proposed to improve SSL by selecting more similar positive samples from different instances.

3. 📜 **Benchmarking Self-Supervised Learning on Diverse Pathology Datasets**
   - 📖 Proceedings: IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2023
   - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2023/html/Kang_Benchmarking_Self-Supervised_Learning_on_Diverse_Pathology_Datasets_CVPR_2023_paper.html?ref=https://githubhelp.com)
   - 💻 [Code](https://github.com/lunit-io/benchmark-ssl-pathology#pre-trained-weights) 
   - 📌 Highlight: Systematically compare existing SSL methods and discuss how to adapt them to pathology; A set of carefully designed data preprocessing and data augmentation techniques proposed to further enhance downstream performance.

4. 📜 **Scaling Self-Supervised Learning for Histopathology with Masked Image Modeling**
   - 📖 Preprint: MedRxiv, 2023
   - 📄 [PDF](https://www.medrxiv.org/content/10.1101/2023.07.21.23292757v3)

5. 📜 **A foundation model for clinical-grade computational pathology and rare cancers detection**
   - 📖 Journal: Nature Medicine, 2024
   - 📄 [PDF](https://www.nature.com/articles/s41591-024-03141-0)
   - 💻 [Code](https://huggingface.co/paige-ai/Virchow)

6. 📜 **Rotation-Agnostic Image Representation Learning for Digital Pathology**
   - 📖 Proceedings: IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2024
   - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Alfasly_Rotation-Agnostic_Image_Representation_Learning_for_Digital_Pathology_CVPR_2024_paper.html)
   - 💻 [Code](https://kimialabmayo.github.io/PathDino-Page/)

7. 📜 **RudolfV: A Foundation Model by Pathologists for Pathologists**
   - 📖 Preprint: arXiv, 2024
   - 📄 [PDF](https://arxiv.org/abs/2401.04079)

8. 📜 **Towards a general-purpose foundation model for computational pathology**
   - 📖 Journal: Nature Medicine, 2024
   - 📄 [PDF](https://www.nature.com/articles/s41591-024-02857-3)
   - 💻 [Code](https://github.com/KatherLab/uni)

9. 📜 **Computational Pathology at Health System Scale- Self-Supervised Foundation Models from Billions of Images**
   - 📖 AAAI 2024 Spring Symposium
   - 📄 [PDF](https://openreview.net/forum?id=g8tF7gGzZb)

10. 📜 **A whole-slide foundation model for digital pathology from real-world data**
    - 📖 Nature 2024
    - 📄 [PDF](https://www.nature.com/articles/s41586-024-07441-w)
    - 💻 [Code](https://github.com/prov-gigapath/prov-gigapath)

11. 📜 **PLUTO: Pathology-Universal Transformer**
    - 📖 ICML 2024 FM-Wild Workshop
    - 📄 [PDF](https://openreview.net/forum?id=wy6RHXsEeM)

12. 📜 **Towards A Generalizable Pathology Foundation Model via Unified Knowledge Distillation**
    - 📖 Journal: Nature BME 2025
    - 📄 [PDF](https://arxiv.org/abs/2407.18449)
    - 💻 [GitHub](https://github.com/birkhoffkiki/GPFM/tree/master)
   
[<sub>Return to List</sub>](#return-to-list)

---
### Contrastive Multi-modal Models

13. 📜 **An Arbitrary Scale Super-Resolution Approach for 3-Dimensional Magnetic Resonance Image using Implicit Neural Representation**
     - 🗓️ Publication Date: 29th Oct. 2021
     - 🧑‍🔬 Authors: Qing Wu, Yuwei Li, Yawen Sun, Yan Zhou, Hongjiang Wei, Jingyi Yu, Yuyao Zhang
     - 📄 [PDF](https://arxiv.org/abs/2110.14476)
     - 💻 [GitHub](https://github.com/iwuqing/arssr)

14. 📜 **IREM: High-Resolution Magnetic Resonance (MR) Image Reconstruction via Implicit Neural Representation**
     - 🗓️ Publication Date: 29th Jun. 2021
     - 🧑‍🔬 Authors: Qing Wu, Yuwei Li, Lan Xu, Ruiming Feng, Hongjiang Wei, Qing Yang, Boliang Yu, Xiaozhao Liu, Jingyi Yu, Yuyao Zhang
     - 📄 [PDF](https://arxiv.org/abs/2106.15097)

15. 📜 **MRI Super-Resolution using Implicit Neural Representation with Frequency Domain Enhancement**
     - 🗓️ Publication Date: Aug. 2022
     - 🧑‍🔬 Authors: Shuangming Mao, Seiichiro Kamata
     - 📄 [PDF](https://dl.acm.org/doi/10.1145/3563737.3563759)

16. 📜 **NeSVoR: Implicit Neural Representation for Slice-to-Volume Reconstruction in MRI**
     - 🗓️ Publication Date: IEEE TRANSACTIONS ON MEDICAL IMAGING, 2022
     - 🧑‍🔬 Authors: Junshen Xu, Daniel Moyer, Borjan Gagoski, Juan Eugenio Iglesias, P. Ellen Grant, Polina Golland, Elfar Adalsteinsson
     - 📄 [PDF](https://www.techrxiv.org/articles/preprint/NeSVoR_Implicit_Neural_Representation_for_Slice-to-Volume_Reconstruction_in_MRI/21398868)
     - 💻 [GitHub](https://github.com/daviddmc/NeSVoR)

17. 📜 **Spatiotemporal implicit neural representation for unsupervised dynamic MRI reconstruction**
     - 🗓️ Publication Date: 31th Dec. 2022
     - 🧑‍🔬 Authors: Jie Feng, Ruimin Feng, Qing Wu, Zhiyong Zhang, Yuyao Zhang, Hongjiang Wei
     - 📄 [PDF](Link to PDF)

18. 📜 **Neural Implicit k-Space for Binning-free Non-Cartesian Cardiac MR Imaging**
      - 🗓️ Publication Date: 16th Dec. 2022
      - 📖 Conference: International Conference on Information Processing in Medical Imaging, 2023
      - 🧑‍🔬 Authors: Wenqi Huang, Hongwei Li, Jiazhen Pan, Gastao Cruz, Daniel Rueckert, Kerstin Hammernik
      - 📄 [PDF](https://arxiv.org/abs/2212.08479)

19. 📜 **Continuous longitudinal fetus brain atlas construction via implicit neural representation**
     - 🗓️ Publication Date: 14th Sep. 2022
     - 🧑‍🔬 Authors: Lixuan Chen, Jiangjie Wu, Qing Wu, Hongjiang Wei, Yuyao Zhang
     - 📄 [PDF](https://arxiv.org/abs/2209.06413)

20. 📜 **Multi-contrast MRI Super-resolution via Implicit Neural Representations**
      - 🗓️ Publication Date: 27th Mar. 2023
      - 📖 Conference: *MICCAI, 2023*
      - 🧑‍🔬 Authors: Julian McGinnis, Suprosanna Shit, Hongwei Bran Li, Vasiliki Sideri-Lampretsa, Robert Graf, Maik Dannecker, Jiazhen Pan, Nil Stolt Ansö, Mark Mühlau, Jan S. Kirschke, Daniel Rueckert, Benedikt Wiestler
      - 📄 [PDF](https://link.springer.com/chapter/10.1007/978-3-031-43993-3_17)
      - 💻 [GitHub](https://github.com/jqmcginnis/multi_contrast_inr)

21. 📜 **Streak artifacts reduction algorithm using an implicit neural representation in sparse-view CT.**
      - 📅 Publication Date: *4th Apr., 2022*
      - 📖 Journal: *Medical Imaging 2022: Physics of Medical Imaging, 2022*
      - 🧑‍🔬 Authors: *Byeongjoon Kim, Hyunjung Shim, Jongduk Baek.*
      - 📄 [PDF](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12031/120312N/Streak-artifacts-reduction-algorithm-using-an-implicit-neural-representation-in/10.1117/12.2610722.short)
   
  
22. 📜 **Spatial Attention-based Implicit Neural Representation for Arbitrary Reduction of MRI Slice Spacing**
     - 🗓️ Publication Date: 23rd May. 2022
     - 🧑‍🔬 Authors: Xin Wang, Sheng Wang, Honglin Xiong, Kai Xuan, Zixu Zhuang, Mengjun Liu, Zhenrong Shen, Xiangyu Zhao, Lichi Zhang, Qian Wang
     - 📄 [PDF](https://arxiv.org/abs/2205.11346)
     - 💻 [GitHub](https://jamesqfreeman.github.io/SA-INR/)
   
23. 📜 **A scan-specific unsupervised method for parallel MRI reconstruction via implicit neural representation**
     - 🗓️ Publication Date: 19th Oct. 2022
     - 🧑‍🔬 Authors: Ruimin Feng, Qing Wu, Yuyao Zhang, Hongjiang Wei
     - 📄 [PDF](https://arxiv.org/abs/2210.10439)
   
24. 📜 **Dual Arbitrary Scale Super-Resolution for Multi-Contrast MRI**
     - 🗓️ Publication Date: 5th Jul. 2023
     - 🧑‍🔬 Authors: Jiamiao Zhang, Yichen Chi, Jun Lyu, Wenming Yang, Yapeng Tian
     - 📄 [PDF](https://arxiv.org/abs/2307.02334)
     - 💻 [GitHub](https://github.com/jmzhang79/dual-arbnet)
   
25. 📜 **Unsupervised reconstruction of accelerated cardiac cine MRI using Neural Fields**
    - 🗓️ Publication Date: 24th Jul. 2023
    - 📖 Preprint: arxiv
    - 🧑‍🔬 Authors: Tabita Catalán, Matías Courdurier, Axel Osses, René Botnar, Francisco Sahli Costabal, Claudia Prieto
    - 📄 [PDF](https://arxiv.org/abs/2307.14363)
    - 💻 [GitHub](https://github.com/fsahli/NF-cMRI)
    - 📌 Highlight: An unsupervised INR approach that uses the spatio-temporal Fourier Features of the heart's motion.

26. 📜 **Self-supervised arbitrary scale super-resolution framework for anisotropic MRI**
     - 🗓️ Publication Date: 2th May. 2023
     - 🧑‍🔬 Authors: Haonan Zhang, Yuhan Zhang, Qing Wu, Jiangjie Wu, Zhiming Zhen, Feng Shi, Jianmin Yuan, Hongjiang Wei, Chen Liu, Yuyao Zhang
     - 📄 [PDF](https://arxiv.org/abs/2305.01360)
      
27. 📜 **Implicit Neural Networks with Fourier-Feature Inputs for Free-breathing Cardiac MRI Reconstruction**
     - 🗓️ Publication Date: 11th May. 2023
     - 🧑‍🔬 Authors: Johannes F. Kunz, Stefan Ruschke, Reinhard Heckel
     - 📄 [PDF](https://arxiv.org/abs/2305.06822)
     - 💻 [GitHub](https://github.com/mli-lab/cinemri)

28. 📜 **Implicit neural representations for unsupervised super-resolution and denoising of 4D flow MRI**
     - 🗓️ Publication Date: 24th Feb. 2023
     - 🧑‍🔬 Authors: Simone Saitta, Marcello Carioni, Subhadip Mukherjee, Carola-Bibiane Schönlieb, Alberto Redaelli
     - 📄 [PDF](https://arxiv.org/abs/2302.12835)
   
29. 📜 **CoNeS: Conditional neural fields with shift modulation for multi-sequence MRI translation.**
      - 📅 Publication Date: *6th Sep., 2023*
      - 📖 Preprint: *arxiv*
      - 🧑‍🔬 Authors: *Yunjie Chen, Marius Staring, Olaf M. Neve, Stephan R. Romeijn, Erik F. Hensen, Berit M. Verbist, Jelmer M. Wolterink, Qian Tao.*
      - 📄 [PDF](https://arxiv.org/abs/2309.03320)
      - 💻 [GitHub](https://github.com/cyjdswx/cones)
   
30. 📜 **Batch Implicit Neural Representation for MRI Parallel Reconstruction.**
      - 📅 Publication Date: *13th Sep., 2023*
      - 📖 Preprint: *arxiv*
      - 🧑‍🔬 Authors: *Hao Li, Yusheng Zhou, Jianan Liu, Xiling Liu, Tao Huang, Zhihan Lv.*
      - 📄 [PDF](https://arxiv.org/abs/2309.06067)
      - 📌 Highlight: Uses INR to parametrize fully-sampled MRI images as continuous functions, enhanced by a scale-embedded encoder for scale-independent feature production.


[<sub>Return to List</sub>](#return-to-list)

---
### Multi-modal Large Language Models

31. 📜 **NeRP: Implicit Neural Representation Learning with Prior Embedding for Sparsely Sampled Image Reconstruction**
    - 🗓️ Publication Date: *24th Aug. 2021*
    - 📖 Preprint: *IEEE Transactions on Neural Networks and Learning Systems, 2022*
    - 🧑‍🔬 Authors: *Liyue Shen, John Pauly, Lei Xing.*
    - 📄 [PDF](https://arxiv.org/abs/2108.10991)
    - 💻 [Github](https://github.com/liyues/nerp)
   
32. 📜 **CuNeRF: Cube-Based Neural Radiance Field for Zero-Shot Medical Image Arbitrary-Scale Super Resolution**
     - 🗓️ Publication Date: 28th Mar. 2023
     - 📖 Conference: *ICCV, 2023*
     - 🧑‍🔬 Authors: Zixuan Chen, Jianhuang Lai, Lingxiao Yang, Xiaohua Xie
     - 📄 [PDF](https://openaccess.thecvf.com/content/ICCV2023/html/Chen_CuNeRF_Cube-Based_Neural_Radiance_Field_for_Zero-Shot_Medical_Image_Arbitrary-Scale_ICCV_2023_paper.html)

[<sub>Return to List</sub>](#return-to-list)

## Adapt Foundation Models for Specific Tasks

### Pathological Classification:

46. 📜 **NeRD: Neural Representation of Distribution for Medical Image Segmentation**
    - 📅 Publication Date: *6th Mar., 2021*
    - 📖 Preprint: *arXiv, 2021*
    - 🧑‍🔬 Authors: *Hang Zhang, Rongguang Wang, Jinwei Zhang, Chao Li, Gufeng Yang, Pascal Spincemaille, Thanh Nguyen, Yi Wang*
    - 📄 [PDF](https://arxiv.org/abs/2103.04020)
    - 📌 Highlight: Addresses white matter lesion segmentation and left atrial segmentation.

47. 📜 **Implicit field learning for unsupervised anomaly detection in medical images**
    - 📅 Publication Date: *9th Jun., 2021*
    - 📖 Conference: *MICCAI 2021*
    - 🧑‍🔬 Authors: *Sergio Naval Marimont, Giacomo Tarroni*
    - 📄 [PDF](https://arxiv.org/abs/2106.05214)
    - 📌 Highlight: Aims to localize gliomas on brain MR images using an unsupervised out-of-distribution detection method.

48. 📜 **Direct localization and delineation of human pedunculopontine nucleus based on a self-supervised magnetic resonance image super-resolution method**
    - 📅 Publication Date: *25th Apr., 2023*
    - 📖 Journal: *Human Brain Mapping, 2023*
    - 🧑‍🔬 Authors: *Jun Li, Xiaojun Guan, Qing Wu, Chenyu He, Weimin Zhang, Xiyue Lin, Chunlei Liu, Hongjiang Wei, Xiaojun Xu, Yuyao Zhang*
    - 📄 [PDF](https://onlinelibrary.wiley.com/doi/full/10.1002/hbm.26311)
    - 📌 Highlight: Focuses on delineating the pedunculopontine nucleus (PPN).

---

### Pathological Component Segmentation:

52. 📜 **Deep Implicit Statistical Shape Models for 3D Medical Image Delineation**
    - 📅 Publication Date: *28th Jun., 2022*
    - 📖 Conference: *AAAI, 2022*
    - 🧑‍🔬 Authors: *Ashwin Raju, Shun Miao, Dakai Jin, Le Lu, Junzhou Huang, Adam P. Harrison*
    - 📄 [PDF](https://arxiv.org/abs/2104.02847)
    - 🖥️ [GitHub](https://github.com/ashstuff/dissm)
    - 📌 Highlight: Presents a methodology that emphasizes 3D delineation of anatomical structures using deep implicit statistical shape models.

53. 📜 **Implicit Neural Representations for Medical Imaging Segmentation**
    - 📅 Publication Date: *16th Sep., 2022*
    - 📖 Conference: *International Conference on Medical Image Computing and Computer-Assisted Intervention, 2022*
    - 🧑‍🔬 Authors: *Muhammad Osama Khan & Yi Fang*
    - 📄 [PDF](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_42)
    - 📌 Highlight: Specifically mentions 3D signals in medical imaging, hinting at 3D anatomical structures.

---

### Other Applications:

54. 📜 **Implicit Anatomical Rendering for Medical Image Segmentation with Stochastic Experts**
    - 📅 Publication Date: *6th Apr., 2023*
    - 📖 Preprint: *arXiv, 2023*
    - 🧑‍🔬 Authors: *Chenyu You, Weicheng Dai, Yifei Min, Lawrence Staib, James S. Duncan*
    - 📄 [PDF](https://arxiv.org/abs/2304.03209)
    - 🖥️ [GitHub](https://github.com/charlesyou999648/morse)
    - 📌 Highlight: Emphasizes refining the boundary regions of segmented medical images.

---
