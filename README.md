# MAGIQ - MEDICAL ANSWER GENERATION FROM IMAGES AND QUESTIONS
Overview
The project focuses on Visual Question Answering (VQA) in the medical imaging domain, leveraging AI to analyze medical images and answer related questions.

Objectives
1. To implement a state-of-the-art VQA system along with baselines and upper bounds tailored for medical images.
2. To explore and compare various model architectures and pipelines for effective medical VQA.
3. To enhance accuracy and efficiency in interpreting and answering clinical queries based on visual data.

Methodology
The project encompasses multiple processing pipelines, including:
1. Implementation of SOTA PMC-VQA pipeline on VQA-RAD dataset.
2. Design and testing of a VQA pipeline using ResNet152, BERT, and MFB (Multimodal Factorized Bilinear Pooling).
3. Experimentation with fine-tuned ResNet152, BioBERT, and UNet in the VQA pipeline.
4. Evaluation of BLIP2, a transformer-based pipeline, on PathVQA and VQA-RAD datasets.
5. Assessment of answer accuracy using BLEU score and other metrics.

Repository Contents
1. PMC-VQA: Implementation details and results of the PMC-VQA (SOTA) pipeline.
2. BLIP2.ipynb: Notebook detailing the BLIP2 model implementation.
3. Baseline_pretrained.ipynb: Initial baseline model using pretrained components.
4. ESE546_Project_Resnet.ipynb: Exploration and results using the ResNet architecture and saving the model weights.
5. Resnet_BERT_MFB.ipynb: Integration of ResNet, BERT, and MFB in the VQA pipeline.
6. UNet.ipynb: UNet model implementation, its application in medical VQA and saving the model weights.
7. UNet_BERT_MFB.ipynb: Pipeline combining UNet, BERT, and MFB.
8. requirements.txt: List of dependencies for the project.

Installation
To replicate the project, clone the repository and install the dependencies listed in requirements.txt.
git clone [repository-url]
pip install -r requirements.txt


