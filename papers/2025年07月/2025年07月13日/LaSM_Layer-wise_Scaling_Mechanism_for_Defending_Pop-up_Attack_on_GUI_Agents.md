# LaSM：分层缩放机制——守护GUI代理免受弹出攻击的防御措施

发布时间：2025年07月13日

`Agent` `GUI` `计算机科学`

> LaSM: Layer-wise Scaling Mechanism for Defending Pop-up Attack on GUI Agents

# 摘要

> 基于多模态大型语言模型（MLLMs）的图形用户界面（GUI）代理在屏幕交互任务中展现了强大的决策能力。然而，它们极易受到基于弹出窗口的环境注入攻击，其中恶意视觉元素会转移模型注意力，导致不安全或错误操作。现有防御方法要么需要高昂的重新训练成本，要么在归纳干扰下表现不佳。我们系统研究了此类攻击对GUI代理注意力行为的影响，揭示了正确与错误输出间的逐层注意力分歧模式。基于此，我们提出了	extbf{LaSM}——一种	extit{逐层缩放机制}，该机制选择性地放大关键层中的注意力和MLP模块。LaSM无需额外训练即可提升模型注意力与任务相关区域的对齐度。在12种弹出窗口扰动和4种不同模型架构上的实验表明，LaSM显著提升了防御成功率。结合提示级别警告，LaSM在强归纳攻击下仍实现了98%以上的鲁棒性。我们的研究发现，注意力不一致是MLLM代理的核心漏洞，而通过选择性逐层调制可有效解决这一问题。

> Graphical user interface (GUI) agents built on multimodal large language models (MLLMs) have recently demonstrated strong decision-making abilities in screen-based interaction tasks. However, they remain highly vulnerable to pop-up-based environmental injection attacks, where malicious visual elements divert model attention and lead to unsafe or incorrect actions. Existing defense methods either require costly retraining or perform poorly under inductive interference. In this work, we systematically study how such attacks alter the attention behavior of GUI agents and uncover a layer-wise attention divergence pattern between correct and incorrect outputs. Based on this insight, we propose \textbf{LaSM}, a \textit{Layer-wise Scaling Mechanism} that selectively amplifies attention and MLP modules in critical layers. LaSM improves the alignment between model saliency and task-relevant regions without additional training. Extensive experiments across 12 types of pop-up perturbations and 4 different model backbones show that LaSM consistently enhances the defense success rate. When combined with prompt-level alerts, LaSM achieves over 98\% robustness even under strong inductive attacks. Our findings reveal that attention misalignment is a core vulnerability in MLLM agents and can be effectively addressed through selective layer-wise modulation.

[Arxiv](https://arxiv.org/abs/2507.10610)