# # 精炼积极与有害样本，实现LLMs的双重安全自我对齐，仅需少量人工干预

发布时间：2025年02月08日

`LLM应用

摘要中提到的PT-ALIGN方法专注于通过改进训练策略来提升大型语言模型的安全性和对齐性，属于应用层面的技术改进，因此归类为LLM应用。` `AI安全` `内容安全`

> Refining Positive and Toxic Samples for Dual Safety Self-Alignment of LLMs with Minimal Human Interventions

# 摘要

> 最近，像ChatGPT和LLaMA这样的AI代理主要通过指令微调和强化学习来调整大型语言模型（LLMs）的输出，使其更符合人类意图，确保输出无害且有用。现有方法虽然依赖高质量正面样本的手动标注，但面临标签噪声和理想与非理想响应数据差异小的问题。此外，尽管有害样本具有明确的安全区别且易于获取，却常被过滤，这导致失去了帮助LLMs进行安全对齐的宝贵负面参考。为解决这些问题，我们提出了PT-ALIGN，这是一种全新的安全自我对齐方法，通过自动精炼正面和有害样本并进行细粒度双指令微调，显著减少了人工监督的需求。正面样本是无害的响应，而有害样本则故意包含极其有害的内容，作为新的监督信号。具体来说，我们仅利用不到50个人类标注，通过LLM本身迭代生成和精炼训练实例。然后，我们采用最大似然估计（MLE）和细粒度不相似度训练（UT）两种损失函数，联合学习以增强LLM的安全性。MLE损失鼓励LLM基于正面样本最大化无害内容的生成，而细粒度UT损失则指导LLM基于负面样本在token级别最小化有害词汇的输出。这种方法不仅引导模型将安全性与有效性解耦，还使其朝着更安全的微调目标发展，从而提高生成有用且可靠内容的可能性。在9个流行的开源LLMs上的实验结果验证了PT-ALIGN在安全对齐方面的有效性，同时保持了相当程度的帮助性和实用性。

> Recent AI agents, such as ChatGPT and LLaMA, primarily rely on instruction tuning and reinforcement learning to calibrate the output of large language models (LLMs) with human intentions, ensuring the outputs are harmless and helpful. Existing methods heavily depend on the manual annotation of high-quality positive samples, while contending with issues such as noisy labels and minimal distinctions between preferred and dispreferred response data. However, readily available toxic samples with clear safety distinctions are often filtered out, removing valuable negative references that could aid LLMs in safety alignment. In response, we propose PT-ALIGN, a novel safety self-alignment approach that minimizes human supervision by automatically refining positive and toxic samples and performing fine-grained dual instruction tuning. Positive samples are harmless responses, while toxic samples deliberately contain extremely harmful content, serving as a new supervisory signals. Specifically, we utilize LLM itself to iteratively generate and refine training instances by only exploring fewer than 50 human annotations. We then employ two losses, i.e., maximum likelihood estimation (MLE) and fine-grained unlikelihood training (UT), to jointly learn to enhance the LLM's safety. The MLE loss encourages an LLM to maximize the generation of harmless content based on positive samples. Conversely, the fine-grained UT loss guides the LLM to minimize the output of harmful words based on negative samples at the token-level, thereby guiding the model to decouple safety from effectiveness, directing it toward safer fine-tuning objectives, and increasing the likelihood of generating helpful and reliable content. Experiments on 9 popular open-source LLMs demonstrate the effectiveness of our PT-ALIGN for safety alignment, while maintaining comparable levels of helpfulness and usefulness.

[Arxiv](https://arxiv.org/abs/2502.08657)