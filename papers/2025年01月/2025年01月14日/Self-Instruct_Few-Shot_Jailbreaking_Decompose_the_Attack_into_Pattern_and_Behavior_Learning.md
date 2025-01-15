# 自指导少样本越狱：将攻击拆解为模式与行为学习

发布时间：2025年01月14日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的漏洞和破解机制，特别是通过特殊标记注入和少样本破解（FSJ）来诱导模型的有害行为。研究内容涉及对模型行为的理论分析和攻击方法的改进，属于对LLM内部机制和理论的研究，因此分类为LLM理论。` `网络安全` `人工智能`

> Self-Instruct Few-Shot Jailbreaking: Decompose the Attack into Pattern and Behavior Learning

# 摘要

> 最近，一些研究探讨了如何通过少量恶意示例破解大型语言模型（LLMs）。Zheng等人（2024）通过向示例中注入特殊标记并采用示例级随机搜索，提升了少样本破解（FSJ）的效率。然而，这种方法因依赖特定的指令-响应结构而缺乏通用性，且特殊标记为何能诱导有害行为的原因仅从经验上进行了讨论。本文深入研究了特殊标记注入的机制，提出了基于示例级贪婪搜索的自指导少样本破解（Self-Instruct-FSJ）。该框架将FSJ攻击分解为模式学习和行为学习，以更通用和高效的方式利用模型的漏洞。我们通过详细实验评估了该方法在常见开源模型上的表现，并与基线算法进行了对比。代码已开源：https://github.com/iphosi/Self-Instruct-FSJ。

> Recently, several works have been conducted on jailbreaking Large Language Models (LLMs) with few-shot malicious demos. In particular, Zheng et al. (2024) focuses on improving the efficiency of Few-Shot Jailbreaking (FSJ) by injecting special tokens into the demos and employing demo-level random search. Nevertheless, this method lacks generality since it specifies the instruction-response structure. Moreover, the reason why inserting special tokens takes effect in inducing harmful behaviors is only empirically discussed. In this paper, we take a deeper insight into the mechanism of special token injection and propose Self-Instruct Few-Shot Jailbreaking (Self-Instruct-FSJ) facilitated with the demo-level greedy search. This framework decomposes the FSJ attack into pattern and behavior learning to exploit the model's vulnerabilities in a more generalized and efficient way. We conduct elaborate experiments to evaluate our method on common open-source models and compare it with baseline algorithms. Our code is available at https://github.com/iphosi/Self-Instruct-FSJ.

[Arxiv](https://arxiv.org/abs/2501.07959)