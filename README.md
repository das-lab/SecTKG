# SecTKG
A Knowledge Graph for Open Source Security Tools

## Introduction
Open source tools are widely used by hackers and security developers, but researches on security tools in the open source community are still very limited. As far as we know, there is no systematic research and automation method for open source security tools' knowledge extraction. Due to the nonstandard expression in the open source community, it is challenging to extract knowledge from these unstructured texts. To address the limitations above, we propose a knowledge graph framework for security tools called SecTKG. SecTKG extracts security tools related knowledge from the open source community, updates security intelligence knowledge, and provides a knowledge base for attack detection and traceability. We build a specific security tools ontology model to portray and contact the applicable scenarios, technical characteristics, popularity, and related users of security tools. Different knowledge extraction methods are designed according to the entity types and relationships defined in the security tools ontology model. More specifically, a cybersecurity named entity recognition model based on BiLSTM-Attention algorithm is introduced, and entity classification models based on page-level and paragraph-level are separately designed. Experimental results demonstrate that the proposed framework has a good performance on the open source tools dataset. Ultimately, a visualization system for the constructed knowledge graph and a practical influence measuring application was realized based on the SecTKG.

## Directory
- KnowledgeExtractionModule: Importance knowledge extraction method code of SecTKG.

## Dataset
We will publish the dataset once the paper is accepted.
