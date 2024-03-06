# Unmasking Deception: A Topic-Oriented Multimodal Approach to Uncover False Information on Social Media

## How it works
**TM-FID** *(Topic-oriented Multimodal False Information Detection)* is a deep learning methodology for multimodal topic-oriented false information detection in online news published on social media platforms.

- *Identification of main topics*: using BERTopic, the methodology extracts the main topics of discussion underlying social media conversation, considering both text and images.
- *False Information Detection*: TM-FID assesses the presence of false information present in social posts, through a multimodal classification model enhanced with a cross-attention fusion mechanism.
- *False information impact assessment*: the methodology calculates a false information score for each identified multimodal topic identified by BERTopic, thus providing a quantitative assessment of the influence of false information on specific discussion topics.

By following a multimodal and topic-oriented approach, **TM-FID** allows for a deeper understanding of the underlying factors and dynamics that foster its dissemination, also enabling the fine-grained identification of specific instances of false information. This understanding is critical for developing targeted interventions and effective strategies to counter the spread of false information, helping to strengthen trustworthiness and confidence in information shared on social media.

## Reproducibility
This repository hosts all the code (Jupyter notebooks) necessary for reproducing experiments. The dataset used, namely *FakeNewsNet* was originally provided by *Shu, K. et al.*, and it is publicly available at the following link: https://github.com/KaiDMML/FakeNewsNet/tree/master
