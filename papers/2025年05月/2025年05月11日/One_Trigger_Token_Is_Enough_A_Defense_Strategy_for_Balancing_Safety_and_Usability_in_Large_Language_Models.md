# # 一个触发词就搞定！平衡大型语言模型安全与实用性的策略
一个触发词就足够了！这项防御策略巧妙地在大型语言模型的安全性和实用性之间找到了完美平衡。

发布时间：2025年05月11日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在防御越狱攻击方面的应用，提出了一种名为D-STT的防御算法。该研究集中在如何通过识别和处理安全触发标记来提升模型的安全性，属于模型的应用层面研究。` `信息安全` `虚拟助手`

> One Trigger Token Is Enough: A Defense Strategy for Balancing Safety and Usability in Large Language Models

# 摘要

> 大型语言模型（LLMs）在虚拟助手、自动代码生成和科学研究等多个领域得到了广泛应用。然而，这些模型仍然容易受到越狱攻击的影响，这类攻击会诱导模型生成有害回应，即便模型已经进行了安全对齐。近期研究表明，当前经过安全对齐的LLMs通常存在浅层安全对齐问题，其中前几个标记（token）往往决定了回应是否会带来危害。通过全面观察，我们发现安全对齐的LLMs和各种防御策略在拒绝回应中生成的初始标记高度相似，我们将其定义为安全触发标记。基于这一发现，我们提出了	exttt{D-STT}，一种简单而有效的防御算法。该算法通过识别并显式解码给定安全对齐LLMs的安全触发标记，触发模型学习到的安全模式。在此过程中，安全触发被限制为单个标记，从而在解码过程中引入最小干预，有效保持了模型的可用性。在多种越狱攻击和良性提示的广泛实验中，\ours显著降低了输出的有害性，同时保持了模型的可用性，并仅引入了微不足道的响应时间开销，优于十种基线方法。

> Large Language Models (LLMs) have been extensively used across diverse domains, including virtual assistants, automated code generation, and scientific research. However, they remain vulnerable to jailbreak attacks, which manipulate the models into generating harmful responses despite safety alignment. Recent studies have shown that current safety-aligned LLMs often undergo the shallow safety alignment, where the first few tokens largely determine whether the response will be harmful. Through comprehensive observations, we find that safety-aligned LLMs and various defense strategies generate highly similar initial tokens in their refusal responses, which we define as safety trigger tokens. Building on this insight, we propose \texttt{D-STT}, a simple yet effective defense algorithm that identifies and explicitly decodes safety trigger tokens of the given safety-aligned LLM to trigger the model's learned safety patterns. In this process, the safety trigger is constrained to a single token, which effectively preserves model usability by introducing minimum intervention in the decoding process. Extensive experiments across diverse jailbreak attacks and benign prompts demonstrate that \ours significantly reduces output harmfulness while preserving model usability and incurring negligible response time overhead, outperforming ten baseline methods.

[Arxiv](https://arxiv.org/abs/2505.07167)