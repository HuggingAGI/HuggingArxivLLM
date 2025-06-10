# # 双自我奖励机制助力多模态理解和生成的强化

发布时间：2025年06月09日

`LLM应用` `内容生成` `生成技术`

> Reinforcing Multimodal Understanding and Generation with Dual Self-rewards

# 摘要

> 基于大型语言模型（LLMs）构建的大型多模态模型（LMMs）将跨模态的理解与生成能力整合到一个统一框架中。然而，LMMs在实现精准的图像-文本对齐方面仍面临挑战，常常生成与视觉输入矛盾的文本，或无法准确响应文本到图像的提示。现有解决方案依赖外部监督（如人工反馈或奖励模型），且仅适用于单向任务——要么理解，要么生成。基于理解与生成互为逆向对偶任务的观察，本研究提出了一种自监督双奖励机制，旨在强化LMMs的理解与生成能力。具体而言，我们为给定输入在某一任务域中生成多个输出，随后将输入-输出对反转，计算模型的双似然性作为自奖励进行优化。在视觉理解和生成基准测试中的大量实验表明，本方法无需外部监督即可显著提升模型性能，尤其在文本到图像任务中取得了突破性进展。

> Building upon large language models (LLMs), recent large multimodal models (LMMs) unify cross-model understanding and generation into a single framework. However, LMMs still struggle to achieve accurate image-text alignment, prone to generating text responses contradicting the visual input or failing to follow the text-to-image prompts. Current solutions require external supervision (e.g., human feedback or reward models) and only address unidirectional tasks-either understanding or generation. In this work, based on the observation that understanding and generation are inverse dual tasks, we introduce a self-supervised dual reward mechanism to reinforce the understanding and generation capabilities of LMMs. Specifically, we sample multiple outputs for a given input in one task domain, then reverse the input-output pairs to compute the dual likelihood of the model as self-rewards for optimization. Extensive experimental results on visual understanding and generation benchmarks demonstrate that our method can effectively enhance the performance of the model without any external supervision, especially achieving remarkable improvements in text-to-image tasks.

[Arxiv](https://arxiv.org/abs/2506.07963)