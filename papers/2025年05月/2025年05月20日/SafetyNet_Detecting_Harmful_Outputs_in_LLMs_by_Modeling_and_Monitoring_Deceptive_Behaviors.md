# # SafetyNet：通过建模与监控欺骗行为，识别大型语言模型中的有害输出

发布时间：2025年05月20日

`LLM应用

理由：这篇论文探讨了如何实时监控和预防大型语言模型生成有害内容，属于LLM的实际应用安全措施。` `实时监控`

> SafetyNet: Detecting Harmful Outputs in LLMs by Modeling and Monitoring Deceptive Behaviors

# 摘要

> 高风险行业如核能和航空通过实时监控保障安全，大型语言模型 (LLMs) 同样需要这样的守护。我们提出了一种实时框架，采用无监督方法将正常行为作为基准，将有害输出视为异常，从而在有害 AI 输出发生前进行预测。我们的研究聚焦于后门触发响应——特定输入短语激活隐藏漏洞，导致模型生成暴力、色情或仇恨言论等不安全内容。我们解决了两大关键挑战：1) 识别真正的原因指标而非表面相关性；2) 防止先进模型欺骗——故意规避监控系统。我们从无监督的角度入手，将其与人类欺骗进行类比：就像人类在撒谎时会露出马脚，我们研究 LLM 在生成有害内容时是否会显示独特的内部行为特征。我们的研究发现，模型可以通过因果机制生成有害内容，并可能通过以下方式变得欺骗性：(a) 在线性与非线性表示之间切换，以及 (b) 修改特征关系。为此，我们开发了 Safety-Net——一个多检测器框架，监控不同的表示维度，即使信息在表示空间之间转移以规避单个监控器，也能成功检测有害行为。我们的评估显示，使用无监督集成方法检测有害案例的准确率高达 96%。

> High-risk industries like nuclear and aviation use real-time monitoring to detect dangerous system conditions. Similarly, Large Language Models (LLMs) need monitoring safeguards. We propose a real-time framework to predict harmful AI outputs before they occur by using an unsupervised approach that treats normal behavior as the baseline and harmful outputs as outliers. Our study focuses specifically on backdoor-triggered responses -- where specific input phrases activate hidden vulnerabilities causing the model to generate unsafe content like violence, pornography, or hate speech. We address two key challenges: (1) identifying true causal indicators rather than surface correlations, and (2) preventing advanced models from deception -- deliberately evading monitoring systems. Hence, we approach this problem from an unsupervised lens by drawing parallels to human deception: just as humans exhibit physical indicators while lying, we investigate whether LLMs display distinct internal behavioral signatures when generating harmful content. Our study addresses two critical challenges: 1) designing monitoring systems that capture true causal indicators rather than superficial correlations; and 2)preventing intentional evasion by increasingly capable "Future models''. Our findings show that models can produce harmful content through causal mechanisms and can become deceptive by: (a) alternating between linear and non-linear representations, and (b) modifying feature relationships. To counter this, we developed Safety-Net -- a multi-detector framework that monitors different representation dimensions, successfully detecting harmful behavior even when information is shifted across representational spaces to evade individual monitors. Our evaluation shows 96% accuracy in detecting harmful cases using our unsupervised ensemble approach.

[Arxiv](https://arxiv.org/abs/2505.14300)