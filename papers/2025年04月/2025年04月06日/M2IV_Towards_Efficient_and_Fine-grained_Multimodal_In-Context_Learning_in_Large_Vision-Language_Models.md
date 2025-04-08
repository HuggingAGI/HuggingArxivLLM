# M2IV: 面向大型视觉-语言模型的高效精细多模态上下文学习探索

发布时间：2025年04月06日

`LLM应用

理由：这篇论文主要探讨了多模态上下文学习在大型视觉-语言模型中的应用，提出了一种新的方法（M2IV）来改进模型的性能和应用效果，属于LLM的应用层面。` `计算机视觉`

> M2IV: Towards Efficient and Fine-grained Multimodal In-Context Learning in Large Vision-Language Models

# 摘要

> 多模态上下文学习 (ICL) 是大型视觉-语言模型 (LVLMs) 的核心能力，它无需重新训练参数即可通过上下文提示实现任务适应。然而，输入的高 token 密集度和跨模态少样本学习的高复杂性限制了表示方法的表达能力，阻碍了其应用。为了解决这些挑战，我们提出了 	extbf{M2IV}，一种通过可学习的 	extbf{I}n-上下文 	extbf{V}ectors 直接替代显式演示的方法，并将其整合到 LVLMs 中。通过结合多头注意力 (	extbf{M}HA) 和多层感知机 (	extbf{M}LP) 的互补优势，M2IV 通过训练实现了稳健的跨模态保真度和细粒度语义蒸馏。这显著提升了各类 LVLMs 和任务的性能，并能高效扩展到多样本场景，突破了上下文窗口的限制。我们还引入了 	extbf{VLibrary}，一个用于存储和检索 M2IV 的仓库，支持跨模态对齐、定制生成和安全性提升等任务的灵活 LVLM 引导。在七个基准测试和三种 LVLMs 上的实验表明，M2IV 在相同样本数量下比 Vanilla ICL 和先前的表示工程方法表现更优，平均准确率提高了 	extbf{3.74\%}，同时具备显著的效率优势。

> Multimodal in-context learning (ICL) is a vital capability for Large Vision-Language Models (LVLMs), allowing task adaptation via contextual prompts without parameter retraining. However, its application is hindered by the token-intensive nature of inputs and the high complexity of cross-modal few-shot learning, which limits the expressive power of representation methods. To tackle these challenges, we propose \textbf{M2IV}, a method that substitutes explicit demonstrations with learnable \textbf{I}n-context \textbf{V}ectors directly integrated into LVLMs. By exploiting the complementary strengths of multi-head attention (\textbf{M}HA) and multi-layer perceptrons (\textbf{M}LP), M2IV achieves robust cross-modal fidelity and fine-grained semantic distillation through training. This significantly enhances performance across diverse LVLMs and tasks and scales efficiently to many-shot scenarios, bypassing the context window limitations. We also introduce \textbf{VLibrary}, a repository for storing and retrieving M2IV, enabling flexible LVLM steering for tasks like cross-modal alignment, customized generation and safety improvement. Experiments across seven benchmarks and three LVLMs show that M2IV surpasses Vanilla ICL and prior representation engineering approaches, with an average accuracy gain of \textbf{3.74\%} over ICL with the same shot count, alongside substantial efficiency advantages.

[Arxiv](https://arxiv.org/abs/2504.04633)