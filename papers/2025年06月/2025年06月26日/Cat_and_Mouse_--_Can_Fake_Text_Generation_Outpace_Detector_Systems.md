# # 猫鼠游戏：虚假文本生成能否跑赢检测系统？

发布时间：2025年06月26日

`LLM应用

摘要讨论了大型语言模型生成假文本的能力及其检测方法，属于LLM的应用领域。` `内容生成` `内容安全`

> Cat and Mouse -- Can Fake Text Generation Outpace Detector Systems?

# 摘要

> 大型语言模型在学术写作、产品评论和政治新闻等领域能生成令人信服的'假文本'。针对人工生成文本的检测，人们已经探索了多种方法。尽管这可能看起来像是一场永无止境的'军备竞赛'，但我们注意到，更新的大型语言模型正不断加大参数量、训练数据和能源的投入，而相对简单的分类器却能在有限资源下实现良好的检测效果。为研究模型击败检测器的能力是否可能达到瓶颈，我们考察了统计分类器识别'假文本'的能力，特别是古典侦探小说风格的文本。在一个版本号提升0.5的测试中，我们发现Gemini生成欺骗性文本的能力有所增强，而GPT则未见明显变化。这表明，即便面对日益庞大的模型，可靠检测假文本仍有可能实现，尽管新的模型架构可能会提升它们的欺骗能力。

> Large language models can produce convincing "fake text" in domains such as academic writing, product reviews, and political news. Many approaches have been investigated for the detection of artificially generated text. While this may seem to presage an endless "arms race", we note that newer LLMs use ever more parameters, training data, and energy, while relatively simple classifiers demonstrate a good level of detection accuracy with modest resources. To approach the question of whether the models' ability to beat the detectors may therefore reach a plateau, we examine the ability of statistical classifiers to identify "fake text" in the style of classical detective fiction. Over a 0.5 version increase, we found that Gemini showed an increased ability to generate deceptive text, while GPT did not. This suggests that reliable detection of fake text may remain feasible even for ever-larger models, though new model architectures may improve their deceptiveness

[Arxiv](https://arxiv.org/abs/2506.21274)