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
   - 📖 Conference: CVPR, 2022
   - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2022/html/Chen_Scaling_Vision_Transformers_to_Gigapixel_Images_via_Hierarchical_Self-Supervised_Learning_CVPR_2022_paper.html?trk=public_post_comment-text)
   - 💻 [Code](https://github.com/mahmoodlab/HIPT)
   - 📌 Highlight: A Hierarchical Image Pyramid Transformer is proposed to leverage the inherent natural hierarchical structure in WSIs; A two-stage SSL approach is proposed to learn high-resolution image representations, which can model important inductive biases in the phenotypic hierarchical structure of the tumor microenvironment.

2. 📜 **Transformer-based unsupervised contrastive learning for histopathological image classification**
   - 📖 Journal: Medical Image Analysis, 2022
   - 📄 [PDF](https://www.sciencedirect.com/science/article/abs/pii/S1361841522002043)
   - 💻 [Code](https://github.com/Xiyue-Wang/TransPath)
   - 📌 Highlight: A proposed CTransPath integrates CNN and multi-scale Swin Transformer to better capture local fine structures and global context; A semantically-relevant contrastive learning framework proposed to improve SSL by selecting more similar positive samples from different instances.

3. 📜 **Benchmarking Self-Supervised Learning on Diverse Pathology Datasets**
   - 📖 Conference: CVPR, 2023
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
   - 📖 Conference: CVPR, 2024
   - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Alfasly_Rotation-Agnostic_Image_Representation_Learning_for_Digital_Pathology_CVPR_2024_paper.html)
   - 💻 [Code](https://kimialabmayo.github.io/PathDino-Page/)

7. 📜 **RudolfV: A Foundation Model by Pathologists for Pathologists**
   - 📖 Preprint: arXiv, 2024
   - 📄 [PDF](https://arxiv.org/abs/2401.04079)

8. 📜 **Towards a general-purpose foundation model for computational pathology**
   - 📖 Journal: Nature Medicine, 2024
   - 📄 [PDF](https://www.nature.com/articles/s41591-024-02857-3)
   - 💻 [Code](https://github.com/mahmoodlab/UNI)

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
    - 💻 [Code](https://github.com/birkhoffkiki/GPFM/tree/master)

13. 📜 **PathoDuet: Foundation models for pathological slide analysis of H&E and IHC stains**
    - 📖 Journal: Medical Image Analysis, 2024
    - 📄 [PDF](https://www.sciencedirect.com/science/article/abs/pii/S1361841524002147)
    - 💻 [Code](https://github.com/openmedlab/PathoDuet)

14. 📜 **Multistain Pretraining for Slide Representation Learning in Pathology**
    - 📖 ECCV, 2024
    - 📄 [PDF](https://link.springer.com/chapter/10.1007/978-3-031-73414-4_2)
    - 💻 [Code](https://github.com/mahmoodlab/MADELEINE)

15. 📜 **Rotation-agnostic image representation learning for digital pathology**
    - 📖 CVPR, 2024
    - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Alfasly_Rotation-Agnostic_Image_Representation_Learning_for_Digital_Pathology_CVPR_2024_paper.html)
    - 💻 [Code](https://github.com/KimiaLabMayo/PathDino)
      
16. 📜 **Tissue Concepts: supervised foundation models in computational pathology**
    - 📖 Journal: Computers in Biology and Medicine
    - 📄 [PDF](https://www.sciencedirect.com/science/article/pii/S0010482524017062)
    - 💻 [Code](https://github.com/FraunhoferMEVIS/MedicalMultitaskModeling)

17. 📜 **A foundation model for generalizable cancer diagnosis and survival prediction from histopathological images**
    - 📖 Journal: Nature Communications
    - 📄 [PDF](https://www.nature.com/articles/s41467-025-57587-y)
    - 💻 [Code](https://github.com/Zhcyoung/BEPH)

18. 📜 **SegAnyPath: A Foundation Model for Multi-resolution Stain-variant and Multi-task Pathology Image Segmentation**
    - 📖 Journal: IEEE Transactions on Medical Imaging
    - 📄 [PDF](https://ieeexplore.ieee.org/abstract/document/10756743)
    - 💻 [Code](https://github.com/wagnchogn/SegAnyPath)

[<sub>Return to List</sub>](#return-to-list)

---
### Contrastive Multi-modal Models

19. 📜 **Visual Language Pretrained Multiple Instance Zero-Shot Transfer for Histopathology Images**
     - 📖 Conference: CVPR, 2023
     - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2023/html/Lu_Visual_Language_Pretrained_Multiple_Instance_Zero-Shot_Transfer_for_Histopathology_Images_CVPR_2023_paper.html?ref=https://githubhelp.com)
     - 💻 [Code](https://github.com/mahmoodlab/MI-Zero)

20. 📜 **A visual-language foundation model for pathology image analysis using medical Twitter**
     - 📖 Journal: Nature Medicine, 2023
     - 📄 [PDF](https://www.nature.com/articles/s41591-023-02504-3)
     - 💻 [Code](https://tinyurl.com/webplip)

21. 📜 **Quilt-1M: One Million Image-Text Pairs for Histopathology**
     - 📖 Conference: NeurIPS 2023
     - 📄 [PDF](https://proceedings.neurips.cc/paper_files/paper/2023/hash/775ec578876fa6812c062644964b9870-Abstract-Datasets_and_Benchmarks.html)
     - 💻 [Code](https://github.com/wisdomikezogwo/quilt1m)
      
22. 📜 **A visual-language foundation model for computational pathology**
     - 📖 Journal: Nature Medicine, 2024
     - 📄 [PDF](https://www.nature.com/articles/s41591-024-02856-4)
     - 💻 [Code](http://github.com/mahmoodlab/CONCH)

23. 📜 **Knowledge-Enhanced Visual-Language Pretraining for Computational Pathology**
     - 📖 Conference: ECCV, 2024
     - 📄 [PDF](https://link.springer.com/chapter/10.1007/978-3-031-72943-0_20)
     - 💻 [Code](https://github.com/MAGIC-AI4Med/KEP)

24. 📜 **PRISM: A Multi-Modal Generative Foundation Model for Slide-Level Histopathology**
     - 📖 Preprint: arXiv, 2024
     - 📄 [PDF](https://arxiv.org/abs/2405.10254)
     - 💻 [Code](https://huggingface.co/paige-ai/Prism/tree/main)

25. 📜 **Transcriptomics-guided Slide Representation Learning in Computational Pathology**
     - 📖 Conference: CVPR, 2024
     - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Jaume_Transcriptomics-guided_Slide_Representation_Learning_in_Computational_Pathology_CVPR_2024_paper.html)
     - 💻 [Code](https://github.com/mahmoodlab/TANGLE)

26. 📜 **CPLIP: Zero-Shot Learning for Histopathology with Comprehensive Vision-Language Alignment**
     - 📖 Conference: CVPR, 2024
     - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Javed_CPLIP_Zero-Shot_Learning_for_Histopathology_with_Comprehensive_Vision-Language_Alignment_CVPR_2024_paper.html)
     - 💻 [Code](https://github.com/iyyakuttiiyappan/CPLIP)

27. 📜 **A Multimodal Knowledge-enhanced Whole-slide Pathology Foundation Model**
     - 📖 Preprint: arXiv, 2024
     - 📄 [PDF](https://arxiv.org/abs/2407.15362)
     - 💻 [Code](https://github.com/Innse/mSTAR)
   
28. 📜 **PathGen-1.6M: 1.6 Million Pathology Image-text Pairs Generation through Multi-agent Collaboration**
     - 📖 Conference: ICLR, 2025
     - 📄 [PDF](https://arxiv.org/abs/2407.00203)
     - 💻 [Code](https://github.com/PathFoundation/PathGen-1.6M/tree/main)
   
29. 📜 **Benchmarking PathCLIP for Pathology Image Analysis**
     - 📖 Journal: Journal of Imaging Informatics in Medicine, 2025
     - 📄 [PDF](https://link.springer.com/article/10.1007/s10278-024-01128-4)
     - 💻 [Code](https://github.com/superjamessyx/Generative-Foundation-AI-Assistant-for-Pathology)
   
30. 📜 **A pathology foundation model for cancer diagnosis and prognosis prediction**
     - 📖 Journal: Nature, 2024
     - 📄 [PDF](https://www.nature.com/articles/s41586-024-07894-z)
     - 💻 [Code](https://github.com/hms-dbmi/CHIEF)
   
31. 📜 **CPath-Omni: A Unified Multimodal Foundation Model for Patch and Whole Slide Image Analysis in Computational Pathology**
     - 📖 Conference: CVPR, 2025
     - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2025/html/Sun_CPath-Omni_A_Unified_Multimodal_Foundation_Model_for_Patch_and_Whole_CVPR_2025_paper.html)
     - 💻 [Code](https://github.com/PathFoundation/CPath-Omni)
   
32. 📜 **A vision–language foundation model for precision oncology**
     - 📖 Journal: Nature, 2025
     - 📄 [PDF](https://www.nature.com/articles/s41586-024-08378-w)
     - 💻 [Code](https://github.com/lilab-stanford/MUSK)
   
33. 📜 **A visual–omics foundation model to bridge histopathology with spatial transcriptomics**
     - 📖 Journal: Nature Methods, 2025
     - 📄 [PDF](https://www.nature.com/articles/s41592-025-02707-1)
     - 💻 [Code](https://github.com/GuangyuWangLab2021/Loki/)
  
[<sub>Return to List</sub>](#return-to-list)

---
### Multi-modal Large Language Models

34. 📜 **PathAsst: A Generative Foundation AI Assistant towards Artificial General Intelligence of Pathology**
     - 📖 Conference: AAAI, 2024
     - 📄 [PDF](https://ojs.aaai.org/index.php/AAAI/article/view/28308)
     - 💻 [Code](https://github.com/superjamessyx/Generative-Foundation-AI-Assistant-for-Pathology)
   
35. 📜 **Generating dermatopathology reports from gigapixel whole slide images with HistoGPT**
     - 📖 Journal: Nature Communications, 2025
     - 📄 [PDF](https://www.nature.com/articles/s41467-025-60014-x)
     - 💻 [Code](https://github.com/marrlab/HistoGPT)
       
36. 📜 **A multimodal generative AI copilot for human pathology**
     - 📖 Journal: Nature, 2024
     - 📄 [PDF](https://www.nature.com/articles/s41586-024-07618-3)

37. 📜 **PathGen-1.6M: 1.6 Million Pathology Image-text Pairs Generation through Multi-agent Collaboration**
     - 📖 Conference: ICLR, 2025
     - 📄 [PDF](https://arxiv.org/abs/2407.00203)
     - 💻 [Code](https://github.com/PathFoundation/PathGen-1.6M/tree/main)

38. 📜 **Quilt-LLaVA: Visual Instruction Tuning by Extracting Localized Narratives from Open-Source Histopathology Videos**
     - 📖 Conference: CVPR, 2024
     - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Seyfioglu_Quilt-LLaVA_Visual_Instruction_Tuning_by_Extracting_Localized_Narratives_from_Open-Source_CVPR_2024_paper.html)
     - 💻 [Code](https://github.com/aldraus/quilt-llava)

39. 📜 **SlideChat: A Large Vision-Language Assistant for Whole-Slide Pathology Image Understanding**
     - 📖 Conference: CVPR, 2025
     - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2025/html/Chen_SlideChat_A_Large_Vision-Language_Assistant_for_Whole-Slide_Pathology_Image_Understanding_CVPR_2025_paper.html)
     - 💻 [Code](https://github.com/uni-medical/SlideChat)

40. 📜 **CPath-Omni: A Unified Multimodal Foundation Model for Patch and Whole Slide Image Analysis in Computational Pathology**
     - 📖 Conference: CVPR, 2025
     - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2025/html/Sun_CPath-Omni_A_Unified_Multimodal_Foundation_Model_for_Patch_and_Whole_CVPR_2025_paper.html)
     - 💻 [Code](https://github.com/PathFoundation/CPath-Omni)

41. 📜 **WSI-LLaVA: A Multimodal Large Language Model for Whole Slide Image**
     - 📖 Conference: ICCV, 2025
     - 📄 [PDF](https://arxiv.org/abs/2412.02141)
     - 💻 [Code](https://github.com/XinhengLyu/WSI-LLaVA)
       
[<sub>Return to List</sub>](#return-to-list)

## Adapt Foundation Models for Specific Tasks

### Pathological Classification:

42. 📜 **Text-Guided Foundation Model Adaptation for Pathological Image Classification**
     - 📖 Conference: MICCAI, 2023
     - 📄 [PDF](https://link.springer.com/chapter/10.1007/978-3-031-43904-9_27)
     - 💻 [Code](https://github.com/Yunkun-Zhang/CITE)

43. 📜 **Prompt-MIL: Boosting Multi-instance Learning Schemes via Task-Specific Prompt Tuning**
     - 📖 Conference: MICCAI, 2023
     - 📄 [PDF](https://link.springer.com/chapter/10.1007/978-3-031-43993-3_60)
     - 💻 [Code](https://github.com/cvlab-stonybrook/PromptMIL)

44. 📜 **CLIPath: Fine-tune CLIP with Visual Feature Fusion for Pathology Image Analysis Towards Minimizing Data Collection Efforts**
     - 📖 Conference: ICCVW, 2023
     - 📄 [PDF](https://openaccess.thecvf.com/content/ICCV2023W/CVAMD/html/Lai_CLIPath_Fine-Tune_CLIP_with_Visual_Feature_Fusion_for_Pathology_Image_ICCVW_2023_paper.html)

45. 📜 **Prompt-MIL: Boosting Multi-instance Learning Schemes via Task-Specific Prompt Tuning**
     - 📖 Conference: MICCAI, 2023
     - 📄 [PDF](https://link.springer.com/chapter/10.1007/978-3-031-43993-3_60)
     - 💻 [Code](https://github.com/cvlab-stonybrook/PromptMIL)
   
46. 📜 **The Rise of AI Language Pathologists: Exploring Two-level Prompt Learning for Few-shot Weakly-supervised Whole Slide Image Classification**
     - 📖 Conference: NeurIPS, 2024
     - 📄 [PDF](https://proceedings.neurips.cc/paper_files/paper/2023/hash/d599b81036fd1a3b3949b7d444f31082-Abstract-Conference.html)
     - 💻 [Code](https://github.com/miccaiif/TOP)
   
47. 📜 **Generalizable Whole Slide Image Classification with Fine-Grained Visual-Semantic Interaction**
     - 📖 Conference: CVPR, 2024
     - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Li_Generalizable_Whole_Slide_Image_Classification_with_Fine-Grained_Visual-Semantic_Interaction_CVPR_2024_paper.html)
     - 💻 [Code](https://github.com/ls1rius/WSI_FiVE)
       
48. 📜 **Feature Re-Embedding: Towards Foundation Model-Level Performance in Computational Pathology**
     - 📖 Conference: CVPR, 2024
     - 📄 [PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Tang_Feature_Re-Embedding_Towards_Foundation_Model-Level_Performance_in_Computational_Pathology_CVPR_2024_paper.html)
     - 💻 [Code](https://github.com/DearCaat/RRT-MIL)

49. 📜 **Hierarchical Text-to-Vision Self Supervised Alignment for Improved Histopathology Representation Learning**
     - 📖 Conference: MICCAI, 2024
     - 📄 [PDF](https://link.springer.com/chapter/10.1007/978-3-031-72083-3_16)
     - 💻 [Code](https://github.com/Hasindri/HLSS)



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
