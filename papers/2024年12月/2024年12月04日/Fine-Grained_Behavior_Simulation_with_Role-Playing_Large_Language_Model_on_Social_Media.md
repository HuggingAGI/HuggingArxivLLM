# 在社交媒体上利用角色扮演大型语言模型进行精细粒度的行为模拟

发布时间：2024年12月04日

`LLM应用` `社交媒体` `用户行为模拟`

> Fine-Grained Behavior Simulation with Role-Playing Large Language Model on Social Media

# 摘要

> 大型语言模型（LLMs）在角色扮演任务中表现出了非凡的能力。然而，对于 LLMs 在现实世界场景（比如社交媒体）中能否精准模拟用户行为，相关研究颇为有限。这就要求模型能够有效分析用户的过往行为并模拟其角色。在本文中，我们推出了	extbf{FineRob}，这是一个全新的细粒度行为模拟数据集。我们收集了来自三个社交媒体平台的 1866 位不同用户的完整行为历史。每个行为都被拆解为三个细粒度元素：对象、类型和内容，由此产生了 78.6 万条问答记录。基于 FineRob，我们在 LLMs 的行为模拟流程中识别出了两种主要的推理模式，并提出了	extbf{OM-CoT}微调方法来增强能力。通过全面的实验，我们对行为模拟的关键因素进行了深入剖析，同时也证明了 OM-CoT 方法的有效性ootnote{代码和数据集可在 url{https://github.com/linkseed18612254945/FineRob}获取}

> Large language models (LLMs) have demonstrated impressive capabilities in role-playing tasks. However, there is limited research on whether LLMs can accurately simulate user behavior in real-world scenarios, such as social media. This requires models to effectively analyze a user's history and simulate their role. In this paper, we introduce \textbf{FineRob}, a novel fine-grained behavior simulation dataset. We collect the complete behavioral history of 1,866 distinct users across three social media platforms. Each behavior is decomposed into three fine-grained elements: object, type, and content, resulting in 78.6k QA records. Based on FineRob, we identify two dominant reasoning patterns in LLMs' behavior simulation processes and propose the \textbf{OM-CoT} fine-tuning method to enhance the capability. Through comprehensive experiments, we conduct an in-depth analysis of key factors of behavior simulation and also demonstrate the effectiveness of OM-CoT approach\footnote{Code and dataset are available at url{https://github.com/linkseed18612254945/FineRob}}

[Arxiv](https://arxiv.org/abs/2412.03148)