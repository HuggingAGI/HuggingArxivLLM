# DSCC-HS：大型语言模型幻觉抑制的动态自强化框架

发布时间：2025年09月17日

`Agent` `基础理论`

> DSCC-HS: A Dynamic Self-Reinforcing Framework for Hallucination Suppression in Large Language Models

# 摘要

> 大型语言模型（LLM）的幻觉问题是其可靠部署的一大障碍。当前如检索增强生成（RAG）等方法多为被动应对，为此我们提出**动态自增强校准幻觉抑制（DSCC-HS）**——一种新颖的主动式框架，可在自回归解码过程中实时干预。受双过程认知理论启发，DSCC-HS采用一个紧凑的代理模型，通过对抗性训练分别扮演事实对齐代理（FAP）和幻觉检测代理（HDP）的角色。推理阶段，这些代理通过在每个解码步骤注入实时引导向量（即FAP与HDP的logits差值），动态引导大型目标模型。这种即插即用的方法无需修改目标模型。在TruthfulQA和BioGEN数据集上的实验表明，DSCC-HS性能达到了当前最优水平：在TruthfulQA上，其事实一致性率（FCR）高达99.2%；在长文本基准测试BioGEN上，它的FActScore指标也达到最高的46.50。这些结果证实，DSCC-HS是一种提升LLM事实性的高效且理论扎实的解决方案。

> Large Language Model (LLM) hallucination is a significant barrier to their reliable deployment. Current methods like Retrieval-Augmented Generation (RAG) are often reactive. We introduce **Dynamic Self-reinforcing Calibration for Hallucination Suppression (DSCC-HS)**, a novel, proactive framework that intervenes during autoregressive decoding. Inspired by dual-process cognitive theory, DSCC-HS uses a compact proxy model, trained in adversarial roles as a Factual Alignment Proxy (FAP) and a Hallucination Detection Proxy (HDP). During inference, these proxies dynamically steer a large target model by injecting a real-time steering vector, which is the difference between FAP and HDP logits, at each decoding step. This plug-and-play approach requires no modification to the target model. Our experiments on TruthfulQA and BioGEN show DSCC-HS achieves state-of-the-art performance. On TruthfulQA, it reached a 99.2% Factual Consistency Rate (FCR). On the long-form BioGEN benchmark, it attained the highest FActScore of 46.50. These results validate DSCC-HS as a principled and efficient solution for enhancing LLM factuality.

[Arxiv](https://arxiv.org/abs/2509.13702)