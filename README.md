# Multimodal Emotion Prediction using Transformers

## Dataset: MAHNOB-HCI

### Problem Statement
In recent years, research in artificial intelligence has made significant strides in predicting human emotional states using text, facial expressions, or EEG signals. However, most approaches focus on unimodal or bimodal data, which often requires deep machine learning architectures for higher accuracy. This can be computationally inefficient for inference and deployment. Our approach proposes integrating more than two modalities (audio, video, and EEG signals) to enhance the precision of emotion prediction models while keeping the framework computationally efficient.

### Motivation
1. **Efficient Multimodal Frameworks**: Transformers have demonstrated success in handling unimodal sequential data in translation tasks, as well as object detection tasks using Vision Transformers (ViTs). We aim to build and validate a transformer-based architecture for multimodal tasks, expanding beyond two modalities to improve prediction accuracy.
   
2. **Applications in the Entertainment Industry**: This approach can be useful for social media content creators, film directors, and marketing agencies, enabling them to gauge the emotional reactions of viewers or consumers by integrating audio, video, and EEG data.

### Objectives
- Develop a transformer-based architecture that integrates and processes multiple modalities, including audio, video, and EEG signals, for accurate and real-time emotion prediction.
- Leverage the sequential nature of transformers to capture temporal dependencies both within and across modalities, enhancing the robustness and accuracy of emotion recognition compared to traditional models.

### Technologies Used
- **Transformers** for multimodal integration
- **MAHNOB-HCI** dataset for emotion prediction
- **Audio, video, and EEG signal** processing techniques

### Project Goals
- Develop a foundational framework for tackling multimodal problems using transformers.
- Apply this framework to real-time emotion prediction in contexts such as entertainment and consumer engagement.
