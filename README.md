# Unmasking Deception: A Topic-Oriented Multimodal Approach to Uncover False Information on Social Media

## How it works
**TM-FID** Is a deep learning methodology for detecting false information and topics detection in social media 

- Identification of main topics: Using BERTopic, the methodology extracts the main topics of discussion found in social media, considering both text and images. This provides a comprehensive overview of online conversations and related topics.
- False Information Detection: Through a multimodal classification model, TM-FID assesses the presence of false information within social posts, considering both textual and visual content. This step makes it possible to identify potential sources of misinformation within different thematic discussions.
- False information impact assessment: The methodology calculates a misinformation score for each topic identified by BERTopic, weighting the presence of false information in the posts that make up that particular topic. This provides a quantitative assessment of the influence of misinformation on specific online discussion topics.

**TM-FID** The TM-FID methodology integrates textual and visual information to identify major themes in social media conversations and assess the presence of misinformation. Through a multimodal classification process, it analyzes the content of posts to detect misinformation and calculates a misinformation score for each identified topic. It uses BERTopic to extract major themes and a cross-attention technique to combine textual and visual representations, providing a comprehensive assessment of the impact of online misinformation. Finally, it undergoes an experimental evaluation to compare it with other multimodal methodologies and assess its overall effectiveness.

## Reproducibility
This repository hosts all the code (Jupyter notebook). The dataset used was originally provided by FakeNewsNet, and can also be accessed at the following link: https://github.com/KaiDMML/FakeNewsNet/tree/master
