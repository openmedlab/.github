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
- [On the Challenges and Perspectives of Foundation Models for Medical Image Analysis](https://arxiv.org/abs/2306.05705). *Medical Image Analysis* [[Bibtex](https://github.com/openmedlab/.github/blob/main/paper/position.txt)]
- [MedFMC: A Real-world Dataset and Benchmark For Foundation Model Adaptation in Medical Image Classification](https://arxiv.org/abs/2306.09579). *Scientific Data* [[Bibtex](https://github.com/openmedlab/.github/blob/main/paper/medfmc.txt)] 
- [A Large-scale Synthetic Pathological Dataset for Deep Learning-enabled Segmentation of Breast Cancer](https://www.nature.com/articles/s41597-023-02125-y). *Scientific Data* [[Bibtex](https://github.com/openmedlab/.github/blob/main/paper/dingkx.txt)] 
- [Medical Image Understanding with Pretrained Vision Language Models: A Comprehensive Study](https://arxiv.org/abs/2209.15517). *ICLR'2023* [[Bibtex](https://github.com/openmedlab/.github/blob/main/paper/MIU-VL.txt)]
- [Foundation Model for Endoscopy Video Analysis via Large-scale Self-supervised Pre-train](https://arxiv.org/abs/2306.16741). *MICCAI'2023* [[Bibtex](https://github.com/openmedlab/.github/blob/main/paper/Endo-FM.txt)] 
- [A Foundation Model for Generalizable Disease Detection from Retinal Images](https://www.nature.com/articles/s41586-023-06555-x). *Nature* [[Bibtex](https://github.com/openmedlab/.github/blob/main/paper/RETFound_MAE.txt)] 

---

<!--
## Medical Foundation Model Spectrum
-->
Here, we open-source a bundle of medical foundation models and their applications in various medical data modalities, ranging from medical image analysis and medical large language models to protein engineering, as shown in the diagram above.

Recently, there has been a surge in the popularity of deep learning foundation models, particularly in the fields of computer vision and natural language processing. As a result, many milestone works have been proposed, such as Vision Transformers (ViT), Generative Pretrained Transformers (GPT), Contrastive Language-Image Pretraining (CLIP), and Segment Anything (SAM). As the size (number of parameters) of these models grows bigger, the capacity of the models increases while the requirement of assembled data for training also inflates, following the scaling law. However, for specific domains like medicine, the shortage of public availability and quality annotations has been the bottleneck for training large-scale deep learning models. Therefore, a variety of learning paradigms has been researched to overcome the roadblock besides the conventional and monotone routine of finetuning the pre-trained model (e.g., ImageNet pre-trained models) using domain-specific data with labels.

The large-scale pre-trained vision and language models have shown remarkable domain transfer capability on natural images. However, it remains unknown whether this capability can also apply to the medical image domain due to the unique characteristics of medical images. OpenMEDLab showcases the feasibility of transferring knowledge from pre-trained vision and language foundation models to the medical domain via well-engineered medical text prompts or building visual prompts in training (see projects in [Foundation Model Prompting for Medical Image Analysis](https://github.com/openmedlab/.github/blob/main/profile/README.md#foundation-model-prompting-for-medical-image-analysis)).

In the field of medical image analysis, task-specific models are still the main approaches, especially for real-world applications such as computer-aided disease diagnosis. Developing medical foundation models presents a significant challenge due to the diverse imaging modalities used in medicine. They could differ greatly from natural images and are based on a range of physics-based properties and energy sources, e.g., using light, electrons, lasers, X-rays, ultrasound, nuclear physics, and magnetic resonance. The images produced span multiple scales, ranging from molecules and cells to organ systems and the full body. Therefore, it may be infeasible to develop a unified multi-scale foundation model trained from a combination of these multi-modality images. OpenMEDLab presents a variety of foundation models and their uses in medical image analysis, ranging from modality-specific models to organ and task-specific models (see projects in [Pre-trained Medical Image Foundation Models](https://github.com/openmedlab/.github/blob/main/profile/README.md#pre-trained-medical-image-foundation-models)).

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="https://github.com/openmedlab/.github/blob/main/model_spectrum_new.png"></a>
</div>
<p style="text-align:center;font-size:5px;"><em>Image from "S. Zhang and D. Metaxas. On the Challenges and Perspectives of Foundation Models for Medical Image Analysis. arXiv preprint arXiv:2306.05705."</em></p>



Moreover, the medical large language model, PULSE, is released in the OpenMEDLab. It collects a supervised fine-tuning dataset consisting of 4,000,000 data samples, which is equivalent to approximately 9.6 billion tokens, and has qualified experts labeled a reinforcement learning dataset with scores and ranks of responses generated by the model. PULSE is trained on these two datasets. A self-evaluation prompt is added to the reward model training, and the standard PPO framework is further optimized for better performance. It also demonstrates a fine-tuned version of the PULSE in understanding the literature on SARS-COV-2. Plugins for the downstream applications are under development. Quantized, updated versions and larger models are currently under fast development, and please contact us for access (see details in [Medical Large Language Models](https://github.com/openmedlab/.github/blob/main/profile/README.md#medical-large-language-models)).  

OpenMEDLab also encapsulates the advances in the research field of protein engineering (see projects in [Protein Engineering](https://github.com/openmedlab/.github/blob/main/profile/README.md#protein-engineering)). As a pioneering work, we introduce TemPL, a novel deep learning approach for zero-shot prediction of protein stability and activity, harnessing temperature-guided large language modeling. An extensive dataset of 96 million sequence-host bacterial strain optimal growth temperatures (OGTs) and ∆Tm data is assembled for point mutations under consistent experimental conditions. TemPL offers considerable promise for protein engineering applications, facilitating the design of mutation sequences with enhanced stability and activity.

## Foundation Model Prompting for Medical Image Analysis

<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM X.png"> MedFM CV: 

> [Prompting for medical image classification](https://github.com/openmedlab/CITE)
>
> [Prompting for medical image detection](https://github.com/openmedlab/MIU-VL)
>
> [Prompting for medical 3D image segmentation and localization](https://github.com/openmedlab/MedLSAM)
>
> [NeurIPS 2023 Competition](https://medfm2023.grand-challenge.org/) 

## Pre-trained Medical Image Foundation Models
<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM Endo.png"> MedFM Endo: 
> [Foundation model for endoscope video analysis](https://github.com/openmedlab/Endo-FM)

<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM CT.png"> MedFM CT/MR: 
> Foundation model for 3D segmentation [[MIS-FM]](https://github.com/openmedlab/MIS-FM)
> [[STU-Net]](https://github.com/openmedlab/STU-Net)

<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM Path.png"> MedFM Path: 
> Foundation model for pathological image staining [[PathoDuet]](https://github.com/openmedlab/PathoDuet) and classification [[BROW]](https://github.com/openmedlab/BROW)

<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM US.png"> MedFM US: 
> Foundation model for ultrasound images [[DeblurringMIM]](https://github.com/openmedlab/DeblurringMIM)

<!--
> [[Model 2]](https://github.com/openmedlab)
-->
<!-- <img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM DR.png"> MedFM DR: 
> [](https://github.com/openmedlab/OmniFM-DR)
-->

## Medical Large Language Models

<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM NLP.png"> MedFM NLP: 
> [MedLLM](https://github.com/openmedlab/PULSE)

<!--
> 
> [MedLLM Covid](https://github.com/openmedlab/covid)
-->

## Protein Engineering

<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM Fold.png"> MedFM Protein: 
> [ Foundation model to predict protein stability and activity](https://github.com/openmedlab/PRIME)

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
