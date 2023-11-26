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
- [On the Challenges and Perspectives of Foundation Models for Medical Image Analysis](https://www.sciencedirect.com/science/article/abs/pii/S1361841523002566). *Medical Image Analysis* [[Bibtex](https://github.com/openmedlab/.github/blob/main/paper/position.txt)]
- [MedFMC: A Real-world Dataset and Benchmark For Foundation Model Adaptation in Medical Image Classification](https://www.nature.com/articles/s41597-023-02460-0). *Scientific Data* [[Code](https://github.com/openmedlab/MedFM))]
- [A Large-scale Synthetic Pathological Dataset for Deep Learning-enabled Segmentation of Breast Cancer](https://www.nature.com/articles/s41597-023-02125-y). *Scientific Data* [[Bibtex](https://github.com/openmedlab/.github/blob/main/paper/dingkx.txt)] 
- [Medical Image Understanding with Pretrained Vision Language Models: A Comprehensive Study](https://iclr.cc/virtual/2023/poster/11569). *ICLR'2023* [[Code](https://github.com/openmedlab/MIU-VL)]
- [Foundation Model for Endoscopy Video Analysis via Large-scale Self-supervised Pre-train](https://link.springer.com/chapter/10.1007/978-3-031-43996-4_10). *MICCAI'2023* [[Code](https://github.com/openmedlab/Endo-FM)] 
- [A Foundation Model for Generalizable Disease Detection from Retinal Images](https://www.nature.com/articles/s41586-023-06555-x). *Nature* [[Code](https://github.com/openmedlab/RETFound_MAE)] 

### Models

In OpenMEDLab, we open-source a bundle of medical foundation models and their applications in various medical data modalities, ranging from medical image analysis and medical large language models to protein engineering, as shown in the diagram above.

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="https://github.com/openmedlab/.github/blob/main/model_spectrum_new.png"></a>
</div>
<p style="text-align:center;font-size:5px;"><em>Image from "S. Zhang and D. Metaxas. On the Challenges and Perspectives of Foundation Models for Medical Image Analysis. Medical Image Analysis"</em></p>

#### Highlight Models

- The Medical Large Language Model: [PULSE](https://github.com/openmedlab/PULSE)
- The 3D CT Segmentation Foundation Model: [MIS-FM](https://github.com/openmedlab/MIS-FM)
- The Scalable and Transferable 3D Segmentation Foundation Model: [STU-Net](https://github.com/openmedlab/STU-Net)
- The Foundation Model for Retinal Image: [RETFound](https://github.com/openmedlab/RETFound_MAE)
- The Foundation Model for Endoscopy Video Analysis: [Endo-FM](https://github.com/openmedlab/Endo-FM)

Comprehensive introduction of models in OpenMEDLab could be found [here](https://github.com/openmedlab/.github/blob/main/models.md).

### Datasets

In OpenMEDLab, we also open-source a bundle of medical datasets for corresponding research of foundation models and their applications in various medical data modalities, ranging from CT, MR, pathology datasets and so on.

#### Highlight Datasets

- [MedFM](https://github.com/openmedlab/dataset/blob/main/MedFM.md) Dataset: Real-world Dataset and Benchmark For Foundation Model Adaptation in Medical Image Classification.
- [SA-Med2D-20M](https://github.com/openmedlab/dataset/blob/main/SA-Med2D-20M.md) Dataset: Segment Anything in 2D Medical Imaging with 20 Million masks.
- [SNOW](https://github.com/openmedlab/dataset/blob/main/SNOW.md) Dataset: A Large-scale Synthetic Pathological Dataset for Deep Learning-enabled Segmentation of Breast Cancer.

<!-- Comprehensive introduction of datasets in OpenMEDLab could be found [here](https://github.com/openmedlab/dataset/blob/main/README.md).-->

### Evaluation

In clinical application and research area, there are always strong needs to evaluate model performance. 

#### Segmentation Task

- [A-Eval](https://github.com/openmedlab/A-Eval): A Benchmark for Cross-Dataset Evaluation of Abdominal Multi-Organ Segmentation

#### Classification (Few-shot Learning) Task

- [MedFM Test Set](https://medfm2023.grand-challenge.org/medfm2023/): Test Set of Foundation Model Prompting for Medical Image Classification Challenge 2023.

---

## Contributors

**Project Leader**: [Shaoting Zhang](https://scholar.google.com/citations?user=oiBMWK4AAAAJ&hl=en&oi=ao) <br />
**Key Contributors:** <br />
*Shanghai AI Laboratory*:  [Xiaosong Wang](https://xiaosongwang.github.io/), [Junjun He](https://junjun2016.github.io/) <br />
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
*Rutgers University*:  [Dimitris Metaxas](https://scholar.google.com/citations?user=a7VNhCIAAAAJ) <br />
*West China Hospital*:  [Kang Li](https://yjs.cd120.com/showteacher.asp?id=1071) <br />
*Xinhua Hospital*:  [Xin Sun](https://) <br />
*Ruijin Hospital*:  [Lifeng Zhu](https://) <br />
*The First Affiliated Hospital of Zhengzhou University*:  [Jie Zhao](https://) <br />

### Contact us
Please forward queries to [openmedlab@pjlab.org.cn](mailto:openmedlab@pjlab.org.cn)
