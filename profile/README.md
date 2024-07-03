<!-- Insert the project banner here -->
<div align="center">
    <a href="https://github.com/openmedlab"><img width="1000px" height="auto" src="https://github.com/openmedlab/.github/blob/main/banner.png"></a>
</div>

---
**Welcome to OpenMEDLab! Models, algorithms, and data will be continuously updated, so stay tuned!**
---

OpenMEDLab is an open-source platform to share medical foundation models in multi-modalities, e.g., medical imaging, medical NLP, bioinformatics, protein, etc. It targets promoting novel approaches to long-tail problems in medicine, and meanwhile, it seeks solutions to achieve lower cost, higher efficiency, and better generalizability in training medical AI models. The new learning paradigm of adapting foundation models to downstream applications makes it possible to develop innovative solutions for cross-domain and cross-modality diagnostic tasks efficiently. OpenMEDLab is distinguished by several features:

- World's first open-source platform for medical foundation models.
- 10+ medical data modalities targeting a variety of clinical and research problems.
- Pioneering works of the new learning paradigm using foundation models, including pre-trained models, code, and data.
- Releasing multiple sets of medical data for pre-training and downstream applications.
- Collaboration with top medical institutes and facilities.

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="1000px" height="auto" src="https://github.com/openmedlab/.github/blob/main/spectrum_feat.png"></a>
</div>

### Our Representive Papers
- OpenMEDLab: An Open-source Platform for Multi-modality Foundation Models in Medicine. *ArXiv'2024* [[Paper](https://arxiv.org/pdf/2402.18028)]
- [On the Challenges and Perspectives of Foundation Models for Medical Image Analysis](https://www.sciencedirect.com/science/article/abs/pii/S1361841523002566). *Medical Image Analysis* [[Paper](https://arxiv.org/pdf/2306.05705.pdf)]
- [MedFMC: A Real-world Dataset and Benchmark For Foundation Model Adaptation in Medical Image Classification](https://www.nature.com/articles/s41597-023-02460-0). *Scientific Data* [[Code](https://github.com/openmedlab/MedFM)]
- [A Large-scale Synthetic Pathological Dataset for Deep Learning-enabled Segmentation of Breast Cancer](https://www.nature.com/articles/s41597-023-02125-y). *Scientific Data* [[Code](https://github.com/openmedlab/dataset/blob/main/SNOW.md)]
- [D-LMBmap: a fully automated deep-learning pipeline for whole-brain profiling of neural circuitry](https://www.nature.com/articles/s41592-023-01998-6). *Nature Methods* [[Code](https://github.com/openmedlab/Axon-Segmentation)] 
- [A Foundation Model for Generalizable Disease Detection from Retinal Images](https://www.nature.com/articles/s41586-023-06555-x). *Nature* [[Code](https://github.com/openmedlab/RETFound_MAE)] 

### Models

In OpenMEDLab, we open-source a bundle of medical foundation models and their applications in various medical data modalities, ranging from medical image analysis and medical large language models to protein engineering, as shown in the diagram above.

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="https://github.com/openmedlab/.github/blob/main/model_spectrum_new.png"></a>
</div>
<p style="text-align:center;font-size:5px;"><em>Image from "S. Zhang and D. Metaxas. On the Challenges and Perspectives of Foundation Models for Medical Image Analysis. Medical Image Analysis"</em></p>

- The Medical Large Language Model: [PULSE](https://github.com/openmedlab/PULSE).
- The 3D CT Segmentation Foundation Model: [MIS-FM](https://github.com/openmedlab/MIS-FM).
- The 2D and 3D Medical Segmentation Foundation Model using SAM: [SAM-Med2D](https://github.com/openmedlab/SAM-Med2D), [SAM-Med3D](https://github.com/openmedlab/SAM-Med3D).
- The Foundation Model for Retinal Image: [RETFound](https://github.com/openmedlab/RETFound_MAE).
- The Foundation Model for Whole-brain Axon Segmentation and Circuitry Profiling: [D-LMBmap](https://github.com/openmedlab/Axon-Segmentation).
- The Foundation Model for Endoscopy Video Analysis: [Endo-FM](https://github.com/openmedlab/Endo-FM).
- The Survey on Data-Centric Foundation Models in Computational Healthcare: [Data-Centric-FM-Healthcare](https://github.com/openmedlab/Data-Centric-FM-Healthcare).

More foundation models for medical images could be found [here](https://github.com/openmedlab/.github/blob/main/models.md).

### Datasets

In OpenMEDLab, we also open-source a bundle of medical datasets for corresponding research of foundation models and their applications in various medical data modalities, ranging from CT, MR, pathology datasets and so on.

- [MedFM](https://github.com/openmedlab/dataset/blob/main/MedFM.md) Dataset: Real-world Dataset and Benchmark For Foundation Model Adaptation in Medical Image Classification.
- [SA-Med2D-20M](https://github.com/openmedlab/dataset/blob/main/SA-Med2D-20M.md) Dataset: Segment Anything in 2D Medical Imaging with 20 Million masks.
- [SNOW](https://github.com/openmedlab/dataset/blob/main/SNOW.md) Dataset: A Large-scale Synthetic Pathological Dataset for Deep Learning-enabled Segmentation of Breast Cancer.
- [Endo-FM](https://github.com/openmedlab/Endo-FM#pre-training-data-6-public--1-private) Private Dataset: A Large-scale Endoscopic Video Dataset with over 33K Video Clips.

🔥🔥🔥 The collection of public medical dataset is continuously updating: [Awesome-Medical-Dataset](https://github.com/openmedlab/Awesome-Medical-Dataset/tree/main).

<!-- Comprehensive introduction of datasets in OpenMEDLab could be found [here](https://github.com/openmedlab/dataset/blob/main/README.md).-->

### Evaluation

In clinical application and research area, there are always strong needs to evaluate model performance. 

- [MedBench](https://medbench.opencompass.org.cn/home): An Open Evaluation Platform for Chinese Medical Large Language Models.
- [OmniMedVQA](https://github.com/OpenGVLab/Multi-Modality-Arena?tab=readme-ov-file#omnimedvqa-a-new-large-scale-comprehensive-evaluation-benchmark-for-medical-lvlm): A New Large-Scale Comprehensive Evaluation Benchmark for Medical LVLM.
- [A-Eval](https://github.com/openmedlab/A-Eval): A Benchmark for Cross-Dataset Evaluation of Abdominal Multi-Organ Segmentation.
- [ELO](): The widely used Elo Rating tournament evaluation method for calculating the relative skill levels of LLMs.

### Multimodality

With the development of Artificial General Intelligence (AGI), deep learning methods are utilized in many other fields with image, text and other information.

- [ProSST](https://github.com/openmedlab/ProSST): A Pre-trained Protein Sequence and Structure Transformer with Disentangled Attention.
- [ProtSSN](https://github.com/openmedlab/ProtSSN): Fusion of protein sequence and structural information, using denoising pre-training network for protein engineering (zero-shot).
- [Swin-UMamba](https://github.com/openmedlab/Swin-UMamba): Mamba-based UNet with ImageNet-based pretraining.
- [Osteoarthritis-Benchmark](https://github.com/openmedlab/Osteoarthritis-Benchmark): Benchmark for Assessing Large Language Models on Knowledge and Decision-Making Capacity in Osteoarthritis Treatment.

---

## Contributors

**Project Leader**: [Shaoting Zhang](https://scholar.google.com/citations?user=oiBMWK4AAAAJ&hl=en&oi=ao), [Xiaosong Wang](https://scholar.google.com/citations?user=c66GnOEAAAAJ&hl=en) <br />
**Key Contributors:** <br />
*Shanghai AI Laboratory*:  [Junjun He](https://junjun2016.github.io/) <br />
*Guangzhou Laboratory*:  [Yixue Li](https://scholar.google.com/citations?user=Qv27G1cAAAAJ) <br />
*Zhejiang Laboratory*:  [Wentao Zhu](https://en.zhejianglab.com/institutescenters/Faculty/202112/t20211206_2900.shtml) <br />
*Shanghai Jiao Tong University*:  [Dequan Wang](https://dequan.wang/), [Xiaofan Zhang](https://scholar.google.com/citations?user=30e95fEAAAAJ), [Liang Hong](https://scholar.google.com/citations?user=pcz1yA4AAAAJ) <br />
*Fudan University*:  [Yi Guo](http://www.it.fudan.edu.cn/Data/View/1169) <br />
*University of Electronic Science and Technology of China*:  [Guotai Wang](https://scholar.google.co.uk/citations?user=Z2sFN4EAAAAJ&hl=en) <br />
*East China University Of Science And Technology*:  [Tong Ruan](https://cise.ecust.edu.cn/2011/0615/c7766a55144/page.htm) <br />
*Beijing University of Posts and Telecommunications*:  [Qicheng Lao](https://) <br />
*Chinese University of Hong Kong*:  [Qi Dou](https://www.cse.cuhk.edu.hk/~qdou/) <br />
*University of British Columbia*:  [Xiaoxiao Li](https://tea.ece.ubc.ca/) <br />
*University College London*:  [Yukun Zhou](https://rmaphoh.github.io/) <br />
*Xi'an Jiaotong University*:  [Zhongyu Li](https://webpages.charlotte.edu/~zli35/) <br />
*Rutgers University*:  [Dimitris Metaxas](https://scholar.google.com/citations?user=a7VNhCIAAAAJ) <br />
*West China Hospital*:  [Kang Li](https://yjs.cd120.com/showteacher.asp?id=1071) <br />
*Xinhua Hospital*:  [Xin Sun](https://) <br />
*Ruijin Hospital*:  [Lifeng Zhu](https://) <br />
*The First Affiliated Hospital of Zhengzhou University*:  [Jie Zhao](https://) <br />

### Contact us
Please forward queries to [openmedlab@pjlab.org.cn](mailto:openmedlab@pjlab.org.cn)
