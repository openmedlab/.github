<!-- Insert the project banner here -->
<div align="center">
    <a href="https://github.com/openmedlab"><img width="1000px" height="auto" src="https://github.com/openmedlab/.github/blob/main/banner.png"></a>
</div>



OpenMEDLab is an open-source platform to share medical foundation models in multi-modalities, e.g., medical imaging, medical NLP, bioinformatics, protein, etc. It targets promoting novel approaches to long-tail problems in medicine, and meanwhile, it seeks solutions to achieve lower cost, higher efficiency, and better generalizability in training medical AI models. The new learning paradigm of adapting foundation models to downstream applications makes it possible to develop innovative solutions for cross-domain and cross-modality diagnostic tasks efficiently. OpenMEDLab is distinguished by several features:

- World's first open-source platform for medical foundation models 
- Large-scale medical data for training with injected medical domain knowledge
- 10+ medical data modalities targeting long-tail (rate diseases) problem
- Pioneering works of the new learning paradigm using foundation models, including pre-trained models, code, and data.
- Collaboration with top medical institutes and facilities

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="900px" height="auto" src="https://github.com/openmedlab/.github/blob/main/spectrum.png"></a>
</div>

<!--
## Medical Foundation Model Spectrum
-->
Here, we present and open-source a bundle of medical foundation models and their applications in various medical data modalities, ranging from medical image analysis and medical large language models to protein engineering, as shown in the diagram above.

In the field of medical image analysis, task-specific models are still the main approaches, especially for real-world applications such as computer-aided disease diagnosis. Developing medical foundation models presents a significant challenge due to the diverse imaging modalities used in medicine. They could differ greatly from natural images and are based on a range of physics-based properties and energy sources, e.g., using light, electrons, lasers, X-rays, ultrasound, nuclear physics, and magnetic resonance. The images produced span multiple scales, ranging from molecules and cells to organ systems and the full body. Therefore, it may be infeasible to develop a unified multi-scale foundation model trained from a combination of these multi-modality images. OpenMEDLab presents a variety of foundation models and their uses in medical image analysis, ranging from modality-specific models to organ and task-specific models (see projects in [Pre-trained Medical Image Foundation Models](https://github.com/openmedlab/.github/blob/main/profile/README.md#pre-trained-medical-image-foundation-models)).

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="https://github.com/openmedlab/.github/blob/main/model_spectrum.png"></a>
</div>

Additionally, the large-scale pre-trained vision and language models have shown remarkable domain transfer capability on natural images. However, it remains unknown whether this capability can also apply to the medical image domain due to the unique characteristics of medical images. OpenMEDLab showcases the feasibility of transferring knowledge from pre-trained vision and language foundation models to the medical domain via well-engineered medical text prompts or building visual prompts in training (see projects in [Prompting for Medical Image Analysis](https://github.com/openmedlab/.github/blob/main/profile/README.md#prompting-for-medical-image-analysis)).

Insert NLP intro here...

OpenMEDLab also encapsulates the advances in the research field of protein engineering (see projects in [Protein Engineering](https://github.com/openmedlab/.github/blob/main/profile/README.md#protein-engineering)). As a pioneering work, we introduce TemPL, a novel deep learning approach for zero-shot prediction of protein stability and activity, harnessing temperature-guided large language modeling. An extensive dataset of 96 million sequence-host bacterial strain optimal growth temperatures (OGTs) and ∆Tm data is assembled for point mutations under consistent experimental conditions. TemPL offers considerable promise for protein engineering applications, facilitating the design of mutation sequences with enhanced stability and activity.


## Pre-trained Medical Image Foundation Models
<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM Endo.png"> MedFM Endo: 
> [Foundation model for endoscope video analysis](https://github.com/openmedlab/Endo-FM)

<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM CT.png"> MedFM CT/MR: 
> Foundation model for 3D segmentation [[Model 1]](https://github.com/openmedlab/MIS-FM)
> [[Model 2]](https://github.com/openmedlab/STU-Net)

<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM Path.png"> MedFM Path: 
> [Foundation model for pathological image staining](https://github.com/openmedlab/PathoDuet) and [classification](https://github.com/openmedlab/WSI_FoundationModel)

<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM US.png"> MedFM US: 
> Foundation model for ultrasound images [[Model 1]](https://github.com/openmedlab/DeblurringMIM)
> [[Model 2]](https://github.com/openmedlab)

<!-- <img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM DR.png"> MedFM DR: 
> [](https://github.com/openmedlab/OmniFM-DR)
-->

## Medical Large Language Models

<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM NLP.png"> MedFM NLP: 
> [MedLLM](https://github.com/openmedlab/MedGPT)
> 
> [MedLLM Covid](https://github.com/openmedlab/covid)


## Prompting for Medical Image Analysis

<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM X.png"> MedFM CV: 
> [Prompting for medical image classification](https://github.com/openmedlab/CITE)
>
> [Prompting for medical image detection](https://github.com/openmedlab/MIU-VL)
>
> [NeurIPS 2023 Competition](https://medfm2023.grand-challenge.org/) 


## Protein Engineering

<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM Fold.png"> MedFM Protein: 
> [ Foundation model to predict protein stability and activity](https://github.com/openmedlab/TemPL)

## Contributors

**Project Leader**: Shaoting Zhang <br />
**Key Contributors:** <br />
*Shanghai AI Laboratory*:  Xiaosong Wang <br />
*Guangzhou Laboratory*:  Yixue Li <br />
*Zhejiang Laboratory*:  Wentao Zhu <br />
*Shanghai Jiao Tong University*:  Dequan Wang, Xiaofan Zhang, Liang Hong <br />
*Fudan University*:  Yi Guo <br />
*University of Electronic Science and Technology of China*:  Guotai Wang <br />
*East China University Of Science And Technology*:  Tong Ruan <br />
*Beijing University of Posts and Telecommunications*:  Qicheng Lao <br />
*Chinese University of Hong Kong*:  Qi Dou <br />
*University of British Columbia*:  Xiaoxiao Li <br />
*Rutgers University*:  Dimitris Metaxas <br />
*West China Hospital*:  Kang Li <br />
*Xinhua Hospital*:  Xin Sun <br />
*Ruijin Hospital*:  Lifeng Zhu <br />
*The First Affiliated Hospital of Zhengzhou University*:  Jie Zhao <br />

### Contact us
Please forward queries to [openmedlab@pjlab.org.cn](mailto:openmedlab@pjlab.org.cn)
