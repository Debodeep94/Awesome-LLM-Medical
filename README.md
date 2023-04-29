# Awesome-LLM-Medical [![Awesome](figures/awesome.svg)](https://github.com/Debodeep94/Awesome-LLM-Medical)

In this repository, we are interested in collecting the articles based on the use of *large langugae models* in medical domains. To download the bibtex file, click [here](https://raw.githubusercontent.com/Debodeep94/Awesome-LLM-Medical/main/llm_medical.bib).

LLM's offer a diverse range of usage in various fields. Even when focus on a specific domain, in particular medical domain, LLM's can be used to perform a varity of tasks. We categorise the variations into the following segments.

- Content

    - Chat based use

    - Not chat based use

## Interactive chatting

- Supervised and unsupervised language modelling in Chest X-Ray radiological reports

    - **Abstract:** 
    
    ChatCAD: Chest radiography (CXR) is the most commonly used imaging modality and deep neural network (DNN) algorithms have shown promise in effective triage of normal and abnormal radiograms. Typically, DNNs require large quantities of expertly labelled training exemplars, which in clinical contexts is a major bottleneck to effective modelling, as both considerable clinical skill and time is required to produce high-quality ground truths. In this work we evaluate thirteen supervised classifiers using two large free-text corpora and demonstrate that bidirectional long short-term memory (BiLSTM) networks with attention mechanism effectively identify Normal, Abnormal, and Unclear CXR reports in internal (n = 965 manually-labelled reports, f1-score = 0.94) and external (n = 465 manually-labelled reports, f1-score = 0.90) testing sets using a relatively small number of expert-labelled training observations (n = 3,856 annotated reports). Furthermore, we introduce a general unsupervised approach that accurately distinguishes Normal and Abnormal CXR reports in a large unlabelled corpus. We anticipate that the results presented in this work can be used to automatically extract standardized clinical information from free-text CXR radiological reports, facilitating the training of clinical decision support systems for CXR triage.

- Vision–Language Model for Visual Question Answering in Medical Imagery

    - **Abstract:** 
    
    In the clinical and healthcare domains, medical images play a critical role. A mature medical visual question answering system (VQA) can improve diagnosis by answering clinical questions presented with a medical image. Despite its enormous potential in the healthcare industry and services, this technology is still in its infancy and is far from practical use. This paper introduces an approach based on a transformer encoder–decoder architecture. Specifically, we extract image features using the vision transformer (ViT) model, and we embed the question using a textual encoder transformer. Then, we concatenate the resulting visual and textual representations and feed them into a multi-modal decoder for generating the answer in an autoregressive way. In the experiments, we validate the proposed model on two VQA datasets for radiology images termed VQA-RAD and PathVQA. The model shows promising results compared to existing solutions. It yields closed and open accuracies of 84.99% and 72.97%, respectively, for VQA-RAD, and 83.86% and 62.37%, respectively, for PathVQA. Other metrics such as the BLUE score showing the alignment between the predicted and true answer sentences are also reported.

- ChatDoctor: A Medical Chat Model Fine-tuned on LLaMA Model using Medical Domain Knowledge

    - **Abstract:** 
    
    Recent large language models (LLMs) in the general domain, such as ChatGPT, have shown remarkable success in following instructions and producing human-like responses. However, such language models have not been tailored to the medical domain, resulting in poor answer accuracy and inability to give plausible recommendations for medical diagnosis, medications, etc. To address this issue, we collected more than 700 diseases and their corresponding symptoms, required medical tests, and recommended medications, from which we generated 5K doctor-patient conversations. In addition, we obtained 200K real patient-doctor conversations from online Q\&A medical consultation sites. By fine-tuning LLMs using these 205k doctor-patient conversations, the resulting models emerge with great potential to understand patients' needs, provide informed advice, and offer valuable assistance in a variety of medical-related fields. The integration of these advanced language models into healthcare can revolutionize the way healthcare professionals and patients communicate, ultimately improving the overall efficiency and quality of patient care and outcomes. In addition, we made public all the source codes, datasets, and model weights to facilitate the further development of dialogue models in the medical field. The training data, codes, and weights of this project are available at: The training data, codes, and weights of this project are available at: https://github.com/Kent0n-Li/ChatDoctor.

- ChatCAD: Interactive Computer-Aided Diagnosis on Medical Image using Large Language Models

    - **Abstract:**
    
    Large language models (LLMs) have recently demonstrated their potential in clinical applications, providing valuable medical knowledge and advice. For example, a large dialog LLM like ChatGPT has successfully passed part of the US medical licensing exam. However, LLMs currently have difficulty processing images, making it challenging to interpret information from medical images, which are rich in information that supports clinical decisions. On the other hand, computer-aided diagnosis (CAD) networks for medical images have seen significant success in the medical field by using advanced deep-learning algorithms to support clinical decision-making. This paper presents a method for integrating LLMs into medical-image CAD networks. The proposed framework uses LLMs to enhance the output of multiple CAD networks, such as diagnosis networks, lesion segmentation networks, and report generation networks, by summarizing and reorganizing the information presented in natural language text format. The goal is to merge the strengths of LLMs' medical domain knowledge and logical reasoning with the vision understanding capability of existing medical-image CAD models to create a more user-friendly and understandable system for patients compared to conventional CAD systems. In the future, LLM's medical knowledge can be also used to improve the performance of vision-based medical-image CAD models.

# Non chat based use

- ProGen: Language Modeling for Protein Generation

    - **Abstract:** 
    
    Generative modeling for protein engineering is key to solving fundamental problems in synthetic biology, medicine, and material science. We pose protein engineering as an unsupervised sequence generation problem in order to leverage the exponentially growing set of proteins that lack costly, structural annotations. We train a 1.2B-parameter language model, ProGen, on ~280M protein sequences conditioned on taxonomic and keyword tags such as molecular function and cellular component. This provides ProGen with an unprecedented range of evolutionary sequence diversity and allows it to generate with fine-grained control as demonstrated by metrics based on primary sequence similarity, secondary structure accuracy, and conformational energy.

