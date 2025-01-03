# # 人性化机器：如何通过代理攻击误导LLM检测器

发布时间：2024年10月24日

`Agent

理由：这篇论文主要讨论了一种代理攻击策略，通过使用强化学习微调的小型语言模型来操控大型语言模型，使其生成与人类文本高度相似的输出，从而误导检测系统。这种策略涉及到代理（Agent）的概念，即通过一个代理模型来影响或操控另一个模型的输出。因此，这篇论文更适合归类为Agent。` `文本生成` `安全检测`

> Humanizing the Machine: Proxy Attacks to Mislead LLM Detectors

# 摘要

> 大型语言模型（LLMs）的崛起彻底革新了文本生成领域，生成的文本几乎可以以假乱真。尽管学术界和工业界已开发出检测器来防止LLM生成文本的滥用，但这些系统的鲁棒性仍受到质疑。为了对这些检测器进行压力测试，我们提出了一种代理攻击策略，能够轻松操控LLMs，使其生成与人类文本高度相似的输出，从而误导检测系统。我们的方法通过在解码阶段使用强化学习（RL）微调的人性化小型语言模型（SLM）来攻击源模型。通过深入分析，我们证明了该策略能够生成检测器无法区分的文本，使其无法分辨机器生成与人类编写的文本。我们在多个数据集上对开源模型（包括Llama2-13B、Llama3-70B和Mixtral-8*7B）进行了系统评估，涵盖白盒和黑盒场景。结果显示，代理攻击策略成功欺骗了主流检测器，导致多个数据集的平均AUROC下降70.4%，单个数据集的最大降幅达90.3%。此外，在跨学科和跨语言场景中，该策略也成功绕过了检测器，相对降幅分别高达90.9%和91.3%。尽管代理攻击策略以显著的降幅成功绕过检测器，但我们发现，受攻击模型的生成质量仍得以保持，即使在一个适度的效用预算内，其文本质量与未受攻击的源模型相当。

> The advent of large language models (LLMs) has revolutionized the field of text generation, producing outputs that closely mimic human-like writing. Although academic and industrial institutions have developed detectors to prevent the malicious usage of LLM-generated texts, other research has doubt about the robustness of these systems. To stress test these detectors, we introduce a proxy-attack strategy that effortlessly compromises LLMs, causing them to produce outputs that align with human-written text and mislead detection systems. Our method attacks the source model by leveraging a reinforcement learning (RL) fine-tuned humanized small language model (SLM) in the decoding phase. Through an in-depth analysis, we demonstrate that our attack strategy is capable of generating responses that are indistinguishable to detectors, preventing them from differentiating between machine-generated and human-written text. We conduct systematic evaluations on extensive datasets using proxy-attacked open-source models, including Llama2-13B, Llama3-70B, and Mixtral-8*7B in both white- and black-box settings. Our findings show that the proxy-attack strategy effectively deceives the leading detectors, resulting in an average AUROC drop of 70.4% across multiple datasets, with a maximum drop of 90.3% on a single dataset. Furthermore, in cross-discipline scenarios, our strategy also bypasses these detectors, leading to a significant relative decrease of up to 90.9%, while in cross-language scenario, the drop reaches 91.3%. Despite our proxy-attack strategy successfully bypassing the detectors with such significant relative drops, we find that the generation quality of the attacked models remains preserved, even within a modest utility budget, when compared to the text produced by the original, unattacked source model.

[Arxiv](https://arxiv.org/abs/2410.19230)