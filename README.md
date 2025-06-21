# A Global-Local Fusion Network with Similarity-Aware Focal Self-Distillation for Multimodal Emotion Recognition in Conversations


## 🚀 Overview
Multimodal emotion recognition in conversations (MERC) plays a vital role in applications such as mental health support and intelligent dialogue systems. 
Although existing methods have achieved remarkable progress, challenges remain in insufficient multimodal fusion, class imbalance in multimodal learning, 
and limited ability to distinguish between similar emotions. To address these challenges, this paper proposes a global-local fusion network with similarity-aware 
focal self-distillation (SAFSD-GLNet) for MERC. First, SAFSD-GLNet uses Transformer with self-attention and cross-attention, and masked GCN for global-local multimodal 
fusion, which capture both semantic relevance and modality complementarity. Moreover, SAFSD-GLNet introduces a similarity-aware focal loss (SAF Loss) to improve 
recognition of minority classes and enhance discrimination between semantically similar emotions. Finally, SAFSD-GLNet introduces self-distillation to guide unimodal 
student models to learn more informative representations by incorporating SAF Loss into the optimization objective. Experiments on IEMOCAP and MELD datasets 
demonstrate that SAFSD-GLNet outperforms previous state-of-the-art baselines.

## 🧠 SAFSD-GLNet

![SAFSD-GLNet Framework](SAFSD-GLNet.png)

## 🛠️ Setup

### Preparing the Code and Environment
https://anonymous.4open.science/r/SAFSD-GLNet
```bash
cd SAFSD-GLNet
conda activate SAFSD-GLNet
```
- Check the packages needed or simply run the command:
```console

pip install -r requirements.txt
```



## 🙏 Acknowledgements


