# 压力测试机器生成文本检测：通过改变语言模型的写作风格来欺骗检测器

发布时间：2025年05月30日

`LLM应用` `信息安全` `内容安全`

> Stress-testing Machine Generated Text Detection: Shifting Language Models Writing Style to Fool Detectors

# 摘要

> 生成式AI与大型语言模型（LLMs）的最新进展推动了高度逼真合成内容的生成，但也引发了对虚假信息和操纵行为等恶意应用的担忧。目前，由于缺乏能够有效评估真实场景泛化能力的基准测试，检测机器生成文本（MGT）仍面临挑战。本研究提出了一种测试管道，旨在评估当前先进的MGT检测器（如Mage、Radar、LLM-DetectAIve）在面对基于语言学知识的对抗攻击时的韧性。通过采用直接偏好优化（DPO）微调语言模型，我们将MGT的风格调整得更接近人类书写的文本（HWT），从而利用检测器对风格线索的依赖性，使生成内容更难被识别。此外，我们深入分析了对齐过程中引发的语言变化，以及检测器在识别MGT文本时所依赖的特征。实验结果显示，只需少量示例即可轻易欺骗检测器，导致其性能大幅下降。这一结果突显了改进检测方法并增强其对未知领域文本的鲁棒性的重要性。

> Recent advancements in Generative AI and Large Language Models (LLMs) have enabled the creation of highly realistic synthetic content, raising concerns about the potential for malicious use, such as misinformation and manipulation. Moreover, detecting Machine-Generated Text (MGT) remains challenging due to the lack of robust benchmarks that assess generalization to real-world scenarios. In this work, we present a pipeline to test the resilience of state-of-the-art MGT detectors (e.g., Mage, Radar, LLM-DetectAIve) to linguistically informed adversarial attacks. To challenge the detectors, we fine-tune language models using Direct Preference Optimization (DPO) to shift the MGT style toward human-written text (HWT). This exploits the detectors' reliance on stylistic clues, making new generations more challenging to detect. Additionally, we analyze the linguistic shifts induced by the alignment and which features are used by detectors to detect MGT texts. Our results show that detectors can be easily fooled with relatively few examples, resulting in a significant drop in detection performance. This highlights the importance of improving detection methods and making them robust to unseen in-domain texts.

[Arxiv](https://arxiv.org/abs/2505.24523)