# 用于交通场景中视觉语言模型的幻觉消除与语义增强框架

发布时间：2024年12月10日

`LLM应用` `自动驾驶`

> Hallucination Elimination and Semantic Enhancement Framework for Vision-Language Models in Traffic Scenarios

# 摘要

> 大型视觉语言模型（LVLMs）在多模态理解与生成任务中展现出卓越能力。然而，这些模型有时会生成幻觉文本，致使描述看似合理，实则与图像不符，这可能致使自动驾驶系统做出错误驾驶决策。为应对此挑战，本文提出 HCOENet，这是一种即插即用的思维链校正方法，旨在消除对象幻觉，并为初始响应中被忽略的关键对象生成强化描述。具体来说，HCOENet 运用交叉检查机制过滤实体，直接从给定图像中提取关键对象，丰富描述文本。POPE 基准的实验结果显示，HCOENet 分别使 Mini-InternVL-4B 和 mPLUG-Owl3 模型的 F1 分数提升了 12.58%和 4.28%。此外，在开放校园场景中收集的图像的定性结果进一步凸显了所提方法的实际适用性。与 GPT-4o 模型相比，HCOENet 在达到相近描述性能的同时，大幅降低了成本。最后，为交通场景创建了两个新的语义理解数据集 CODA_desc 和 nuScenes_desc，以支持未来研究。代码和数据集可在 https://github.com/fjq-tongji/HCOENet 公开获取。

> Large vision-language models (LVLMs) have demonstrated remarkable capabilities in multimodal understanding and generation tasks. However, these models occasionally generate hallucinatory texts, resulting in descriptions that seem reasonable but do not correspond to the image. This phenomenon can lead to wrong driving decisions of the autonomous driving system. To address this challenge, this paper proposes HCOENet, a plug-and-play chain-of-thought correction method designed to eliminate object hallucinations and generate enhanced descriptions for critical objects overlooked in the initial response. Specifically, HCOENet employs a cross-checking mechanism to filter entities and directly extracts critical objects from the given image, enriching the descriptive text. Experimental results on the POPE benchmark demonstrate that HCOENet improves the F1-score of the Mini-InternVL-4B and mPLUG-Owl3 models by 12.58% and 4.28%, respectively. Additionally, qualitative results using images collected in open campus scene further highlight the practical applicability of the proposed method. Compared with the GPT-4o model, HCOENet achieves comparable descriptive performance while significantly reducing costs. Finally, two novel semantic understanding datasets, CODA_desc and nuScenes_desc, are created for traffic scenarios to support future research. The codes and datasets are publicly available at https://github.com/fjq-tongji/HCOENet.

[Arxiv](https://arxiv.org/abs/2412.07518)