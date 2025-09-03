# <翻译失败>

发布时间：2025年08月31日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。`

> OmniDPO: A Preference Optimization Framework to Address Omni-Modal Hallucination

# 摘要

> <翻译失败>

> Recently, Omni-modal large language models (OLLMs) have sparked a new wave of research, achieving impressive results in tasks such as audio-video understanding and real-time environment perception. However, hallucination issues still persist. Similar to the bimodal setting, the priors from the text modality tend to dominate, leading OLLMs to rely more heavily on textual cues while neglecting visual and audio information. In addition, fully multimodal scenarios introduce new challenges. Most existing models align visual or auditory modalities with text independently during training, while ignoring the intrinsic correlations between video and its corresponding audio. This oversight results in hallucinations when reasoning requires interpreting hidden audio cues embedded in video content. To address these challenges, we propose OmniDPO, a preference-alignment framework designed to mitigate hallucinations in OLLMs. Specifically, OmniDPO incorporates two strategies: (1) constructing text-preference sample pairs to enhance the model's understanding of audio-video interactions; and (2) constructing multimodal-preference sample pairs to strengthen the model's attention to visual and auditory information. By tackling both challenges, OmniDPO effectively improves multimodal grounding and reduces hallucination. Experiments conducted on two OLLMs demonstrate that OmniDPO not only effectively mitigates multimodal hallucinations but also significantly enhances the models' reasoning capabilities across modalities. All code and datasets will be released upon paper acceptance.

[Arxiv](https://arxiv.org/abs/2509.00723)