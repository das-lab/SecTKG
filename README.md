# SecTKG
A Knowledge Graph for Open Source Security Tools

## Research paper
We present the findings of this work in the following research paper:

Sun S, Huang C, Shen Y, et al. SecTKG: A Knowledge Graph for Open Source Security Tools[J]. International Journal of Intelligent Systems, 2023. [view](https://downloads.hindawi.com/journals/ijis/2023/4464974.pdf)

## Introduction
Open source tools are widely used by hackers and security developers, but researches on security tools in the open source community are still very limited. As far as we know, there is no systematic research and automation method for open source security tools' knowledge extraction. Due to the nonstandard expression in the open source community, it is challenging to extract knowledge from these unstructured texts. To address the limitations above, we propose a knowledge graph framework for security tools called SecTKG. SecTKG extracts security tools related knowledge from the open source community, updates security intelligence knowledge, and provides a knowledge base for attack detection and traceability. We build a specific security tools ontology model to portray and contact the applicable scenarios, technical characteristics, popularity, and related users of security tools. Different knowledge extraction methods are designed according to the entity types and relationships defined in the security tools ontology model. More specifically, a cybersecurity named entity recognition model based on BiLSTM-Attention algorithm is introduced, and entity classification models based on page-level and paragraph-level are separately designed. Experimental results demonstrate that the proposed framework has a good performance on the open source tools dataset. Ultimately, a visualization system for the constructed knowledge graph and a practical influence measuring application was realized based on the SecTKG.

## Details
- `security tools ontology.owx`: This file provides the OWL format of our ontology model. The ontology model serves as the foundation for the SecTKG, aiding in the better organization and expression of knowledge and facilitating knowledge sharing. A total of 9 entity types and 7 relationships are defined in the ontology.
- `visualization example.svg`: This file represents a visual example of the nodes and relationships exported by Neo4j Graphical User Interface.
- `KnowledgeExtractionModule`: This directory contains the important code of the knowledge extraction method of SecTKG. We implement different entity recognition methods according to the features of different entity types to realize efficient and automatic knowledge extraction.

## Dataset
The dataset is not publicly available directly due to the security issue of attack tools. If you are conducting similar research on this topic, we kindly suggest you contact the corresponding author of the paper via your institute email. Please provide a brief summary of your research interests, the intended use of the dataset, and any relevant background or qualifications that support your request. Thanks!
