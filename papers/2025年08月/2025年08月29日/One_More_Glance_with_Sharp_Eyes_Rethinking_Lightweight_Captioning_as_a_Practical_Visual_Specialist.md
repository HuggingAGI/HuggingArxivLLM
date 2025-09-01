# 慧眼再瞥：重新定位轻量级图像描述为实用视觉专家

发布时间：2025年08月29日

`LLM应用` `工业与制造`

> One More Glance with Sharp Eyes: Rethinking Lightweight Captioning as a Practical Visual Specialist

# 摘要

> 图像描述是视频指导系统、探测机器人等应用的基础，但多模态大型语言模型（MLLMs）计算量巨大，在本地设备部署这类模型颇具挑战。为此，我们首先探索轻量级描述方案：基于一个1.25亿参数的语言模型构建专家模型（比LLaMA-7B小56倍），并在单句描述和详细描述任务中测试其性能。令人意外的是，该模型性能竟能媲美大型多模态通才模型，这表明它有望成为本地设备应用的强大视觉专家。不过，该模型也存在局限：与其他MLLMs类似，它存在视觉盲区，偶尔会产生语义描述错误。我们通过简单实验探究其根源，发现问题在于注意力机制低效和视觉表征不足。为缓解这些问题，我们开发了名为“锐眼优化”（Sharp-Eyed Refinement）的新型描述框架，通过改进视觉接地提升描述质量。该框架的核心是DeepLens，它通过聚焦初始浏览时识别的关键信息区域，提取细致的视觉表征。实验结果证实：我们的专家模型不仅优于以往的小型描述模型和大型通才模型，且所提框架也切实有效。

> Image captioning is fundamental for applications like video instruction systems and exploration robots, yet deploying such models on local devices is challenging due to the high computational demands of multimodal large language models (MLLMs). To address this, we first explore lightweight captioning by implementing a specialist based on a 125M-parameter language model, 56 times smaller than LLaMA-7B, and evaluating its performance on both single-sentence and detailed captioning tasks. Surprisingly, we find that our model can achieve performance comparable to large multimodal generalists, suggesting its potential to serve as a strong visual specialist for on-device applications. While promising, our model also exhibits a limitation: like other MLLMs, it suffers from visual blindness, occasionally resulting in semantic captioning errors. We carry out toy experiments and investigate the underlying causes, where we observe that the problems arise from ineffective attention mechanisms and limited visual representations. To alleviate them, we develop a novel captioning framework, Sharp-Eyed Refinement, which enhances caption quality through improved visual grounding. At its core, our DeepLens extracts detailed visual representations by concentrating on informative regions identified during the initial glance. Our experiments confirm both the advantages of our specialist over prior small captioning models and large generalists and the effectiveness of our framework.

[Arxiv](https://arxiv.org/abs/2508.21451)