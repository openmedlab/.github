<!-- Insert the project banner here -->
<div align="center">
    <a href="https://github.com/openmedlab"><img width="1000px" height="auto" src="https://github.com/openmedlab/.github/blob/main/banner.png"></a>
</div>



OpenMEDLab is an open-source platform to share medical foundation models in multi-modalities, e.g., medical imaging, medical NLP, bioinformatics, protein, etc. It targets promoting novel approaches to long-tail problems in medicine, and meanwhile, it seeks solutions to achieve lower cost, higher efficiency, and better generalizability in training medical AI models. The new learning paradigm of adapting foundation models to downstream applications makes it possible to develop innovative solutions for cross-domain and cross-modality diagnostic tasks efficiently. OpenMEDLad is distinguished by several features:

- World's first open-source platform for medical foundation models 
- Large-scale medical data for training with injected medical domain knowledge
- 10+ medical data modalities targeting long-tail (rate diseases) problem
- Pioneering works of the new learning paradigm using foundation models, including pre-trained models, code, and data.
- Collaboration with top medical institutes and facilities



<div align="center">
    <a href="https://github.com/openmedlab/"><img width="1000px" height="auto" src="https://github.com/openmedlab/.github/blob/main/spectrum.png"></a>
</div>

<!--
## Medical Foundation Model Spectrum
-->
Here, we present and open-source the spectrum of medical foundation models and their applications in various medical data modalities, ranging from medical image analysis and medical large language models to protein engineering, as shown in the landscape above.


## Pre-trained Medical Image Foundation Models

In the past few years, deep learning foundation models have gained popularity, especially in computer vision and natural language processing due to demonstrable improvements in related applications. Many milestone models have been proposed, such as Transformer~\cite{vaswani2017attention}, GPT~\cite{radford2018improving,radford2019language}, Vision Transformers, (ViT)~\cite{dosovitskiy2021an}, and Contrastive Language-Image Pretraining (CLIP)~\cite{radford2021learning}. They are designed to address many downstream tasks by utilizing the robust representation learning and generalization abilities of foundation models.
 
In the field of medical image analysis, however, task-specific models are still the main approaches, especially for real-world applications such as computer-aided disease diagnosis. Developing medical foundation models presents a significant challenge due to the diverse imaging modalities used in medicine, which differ greatly from natural images and are based on a range of physics-based properties and energy sources. These modalities are based on the use of light, electrons, lasers, X-rays, ultrasound, nuclear physics,  and magnetic resonance. The images produced span multiple scales, ranging from molecules and cells to organ systems and the full body. Therefore, it may be infeasible to develop a unified multi-scale foundation model trained from a combination of these multi-modality images. 

In the following, we will investigate and present our vision for the ``spectrum'' of foundation models and their uses in medical image analysis, ranging from general vision models, modality-specific models, to organ and task-specific models (Fig.~\ref{fig:spectrum}). Fortunately, the growing availability of high-quality publicly available annotated medical data has led to the gradual emergence of specialized foundational models with an innate capacity for generating more generalized representations of medical data. Therefore, foundation models trained with medical images and/or natural images in a self-supervised manner may serve as an improved solution basis for frontline clinical problems, advancing the field of medical imaging and improving the efficacy and efficiency of disease diagnosis and treatment.

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



<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM DR.png"> MedFM NLP: 
> [MedLLM](https://github.com/openmedlab/MedGPT)
> 
> [MedLLM Covid](https://github.com/openmedlab/covid)


## Prompting for Medical Image Analysis

The large-scale pre-trained vision language models (VLM) have shown remarkable domain transfer capability on natural images. However, it remains unknown
whether this capability can also apply to the medical image domain. This paper thoroughly studies the knowledge transferability of pre-trained VLMs to the
medical domain, where we show that well-designed medical prompts are the key
to elicit knowledge from pre-trained VLMs. We demonstrate that by prompting
with expressive attributes that are shared between domains, the VLM can carry
the knowledge across domains and improve its generalization. This mechanism
empowers VLMs to recognize novel objects with fewer or without image samples.
Furthermore, to avoid the laborious manual designing process, we develop three
approaches for automatic generation of medical prompts, which can inject expertlevel medical knowledge and image-specific information into the prompts for finegrained grounding. We conduct extensive experiments on thirteen different medical datasets across various modalities, showing that our well-designed prompts
greatly improve the zero-shot performance compared to the default prompts, and
our fine-tuned models surpass the supervised models by a significant margin. 1

The recent surge of foundation models in computer vision and
natural language processing opens up perspectives in utilizing multi-modal
clinical data to train large models with strong generalizability. Yet pathological
image datasets often lack biomedical text annotation and enrichment. Guiding
data-efficient image diagnosis from the use of biomedical text knowledge
becomes a substantial interest. In this paper, we propose to Connect Image
and Text Embeddings (CITE) to enhance pathological image classification.
CITE injects text insights gained from language models pre-trained with a
broad range of biomedical texts, leading to adapt foundation models towards
pathological image understanding. Through extensive experiments on the
PatchGastric stomach tumor pathological image dataset, we demonstrate that
CITE achieves leading performance compared with various baselines especially
when training data is scarce. CITE offers insights into leveraging in-domain
text knowledge to reinforce data-efficient pathological image classification.

However, while vision foundation models can learn general representations, medical images have unique characteristics whose features and patterns differ significantly from those in natural images. Therefore, carefully designed algorithms are necessary to adapt domain-specific problems. Fine-tuning, additional adapters, prompting strategies, and specialized architectures or modifications are potential solutions to achieve optimal performance in medical problems.


<img style="float: left;" width="20px" height="auto" src="https://github.com/openmedlab/.github/blob/main/profile/MedFM X.png"> MedFM CV: 
> [Prompting for medical image classification](https://github.com/openmedlab/CITE)
>
> [Prompting for medical image detection](https://github.com/openmedlab/MIU-VL)
>
> [NeurIPS 2023 Competition](https://medfm2023.grand-challenge.org/) 


## Protein Engineering
We introduce TemPL, a novel deep learning approach for zero-shot prediction of protein stability and activity, harnessing temperature-guided language modeling. By assembling an extensive dataset of 96 million sequence-host bacterial strain optimal growth temperatures (OGTs) and {\Delta}Tm data for point mutations under consistent experimental conditions, we effectively compared TemPL with state-of-the-art models. Notably, TemPL demonstrated superior performance in predicting protein stability. An ablation study was conducted to elucidate the influence of OGT prediction and language modeling modules on TemPL's performance, revealing the importance of integrating both components. Consequently, TemPL offers considerable promise for protein engineering applications, facilitating the design of mutation sequences with enhanced stability and activity.
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
