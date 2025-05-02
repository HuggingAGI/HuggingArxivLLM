# # 角色分离的幻象：LLM角色学习中的隐藏捷径（及其修复之道）

发布时间：2025年05月01日

`LLM理论` `人工智能` `对话系统`

> The Illusion of Role Separation: Hidden Shortcuts in LLM Role Learning (and How to Fix Them)

# 摘要

> 整合多种输入角色（如系统指令、用户查询、外部工具输出）的大语言模型（LLMs）在实践中越来越普遍。确保模型能够准确区分来自不同角色的消息——我们将其称为\emph{角色分离}——对于保持多角色行为的一致性至关重要。尽管近期研究常致力于最先进的注入攻击防御方法，但目前尚不清楚这些方法是否真正教会了LLMs区分角色，还是仅让模型记住了已知的触发词。本文探讨了\emph{角色分离学习}：即教导LLMs稳健地区分系统和用户标记的过程。通过一个\emph{简单、受控的实验框架}，我们发现微调后的模型通常依赖于两种角色识别的替代方法：（1）任务类型利用，和（2）靠近文本开头的位置。尽管数据增强可以在一定程度上缓解这些捷径，但通常会导致迭代修补，而非根本性解决。为此，我们提出通过调整模型输入编码中的逐词提示来强化\emph{不变量信号}，以标记角色边界。特别是，调整位置ID有助于模型学习更清晰的区分，并减少对表面替代方法的依赖。通过专注于这一机制为中心的视角，我们的研究揭示了LLMs如何在不单纯记住已知提示或触发词的情况下，更可靠地维持一致的多角色行为。

> Large language models (LLMs) that integrate multiple input roles (e.g., system instructions, user queries, external tool outputs) are increasingly prevalent in practice. Ensuring that the model accurately distinguishes messages from each role -- a concept we call \emph{role separation} -- is crucial for consistent multi-role behavior. Although recent work often targets state-of-the-art prompt injection defenses, it remains unclear whether such methods truly teach LLMs to differentiate roles or merely memorize known triggers. In this paper, we examine \emph{role-separation learning}: the process of teaching LLMs to robustly distinguish system and user tokens. Through a \emph{simple, controlled experimental framework}, we find that fine-tuned models often rely on two proxies for role identification: (1) task type exploitation, and (2) proximity to begin-of-text. Although data augmentation can partially mitigate these shortcuts, it generally leads to iterative patching rather than a deeper fix. To address this, we propose reinforcing \emph{invariant signals} that mark role boundaries by adjusting token-wise cues in the model's input encoding. In particular, manipulating position IDs helps the model learn clearer distinctions and reduces reliance on superficial proxies. By focusing on this mechanism-centered perspective, our work illuminates how LLMs can more reliably maintain consistent multi-role behavior without merely memorizing known prompts or triggers.

[Arxiv](https://arxiv.org/abs/2505.00626)