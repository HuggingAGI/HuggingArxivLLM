# 链式诱捕：一种合成叙事驱动的大型语言模型操控方法

发布时间：2025年05月23日

`LLM应用` `AI安全` `生成式AI`

> Chain-of-Lure: A Synthetic Narrative-Driven Approach to Compromise Large Language Models

# 摘要

> 在生成式AI快速发展的时代，人与大型语言模型之间的互动面临显著的滥用风险。此前的研究主要集中在使用人类指导提示的黑盒场景，以及利用基于梯度的LLM生成方法的白盒场景，却忽视了LLMs不仅可以作为受害者模型，还可以作为攻击者模型去损害其他模型的可能性。

我们提出了一种受思维链机制启发的新型越狱攻击方法。攻击者模型通过任务迁移将有害用户意图隐藏在对话中，并生成连锁叙事诱饵以激发受害者模型的推理能力，从而实现成功越狱。为了提高攻击成功率，我们引入了一个辅助模型，在多轮对话中对叙事诱饵进行随机叙事优化，同时确保与原始意图保持一致，使得优化后的诱饵能够有效绕过受害者模型的安全屏障。

我们的实验表明，安全机制较弱的模型表现出更强的攻击能力，证明了模型不仅可以被利用，还能帮助他人造成伤害。通过引入毒性评分，我们采用第三方模型评估受害者模型对越狱攻击尝试的有害性。研究表明，使用拒绝关键词作为攻击成功率的评估指标存在严重缺陷，因为它未能评估回复是否引导有害问题，而毒性评分则能更精确地衡量生成内容的伤害性及其与有害问题的关联性。

我们的方法表现出色，揭示了大型语言模型的潜在漏洞，并提供了数据驱动的反馈以优化LLM的安全机制。我们还讨论了两种防御策略，为提升防御机制提供指导。

> In the era of rapid generative AI development, interactions between humans and large language models face significant misusing risks. Previous research has primarily focused on black-box scenarios using human-guided prompts and white-box scenarios leveraging gradient-based LLM generation methods, neglecting the possibility that LLMs can act not only as victim models, but also as attacker models to harm other models. We proposes a novel jailbreaking method inspired by the Chain-of-Thought mechanism, where the attacker model uses mission transfer to conceal harmful user intent in dialogue and generates chained narrative lures to stimulate the reasoning capabilities of victim models, leading to successful jailbreaking. To enhance the attack success rate, we introduce a helper model that performs random narrative optimization on the narrative lures during multi-turn dialogues while ensuring alignment with the original intent, enabling the optimized lures to bypass the safety barriers of victim models effectively. Our experiments reveal that models with weaker safety mechanisms exhibit stronger attack capabilities, demonstrating that models can not only be exploited, but also help harm others. By incorporating toxicity scores, we employ third-party models to evaluate the harmfulness of victim models' responses to jailbreaking attempts. The study shows that using refusal keywords as an evaluation metric for attack success rates is significantly flawed because it does not assess whether the responses guide harmful questions, while toxicity scores measure the harm of generated content with more precision and its alignment with harmful questions. Our approach demonstrates outstanding performance, uncovering latent vulnerabilities in LLMs and providing data-driven feedback to optimize LLM safety mechanisms. We also discuss two defensive strategies to offer guidance on improving defense mechanisms.

[Arxiv](https://arxiv.org/abs/2505.17519)