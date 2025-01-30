# OpenAI o3-mini的早期外部安全测试：预部署评估的洞见

发布时间：2025年01月29日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）的安全性问题，特别是通过外部安全测试来评估LLMs的安全性。论文描述了使用ASTRAL工具生成不安全测试输入，并在OpenAI的o3-mini LLM上进行测试的过程。这些内容属于LLM在实际应用中的安全测试和评估，因此归类为LLM应用。` `人工智能` `安全测试`

> Early External Safety Testing of OpenAI's o3-mini: Insights from the Pre-Deployment Evaluation

# 摘要

> 大型语言模型（LLMs）已深入我们的日常生活，但它们也伴随着隐私侵害、偏见延续和错误信息传播等风险。这些风险要求我们建立强大的安全机制、制定道德准则并进行全面测试，以确保LLMs的负责任部署。安全性是LLMs的关键属性，必须在模型部署前进行彻底测试。本文分享了蒙德拉贡大学和塞维利亚大学研究人员对OpenAI新o3-mini LLM进行的外部安全测试经验，这是OpenAI早期安全测试计划的一部分。我们使用ASTRAL工具自动生成最新的不安全测试输入（即提示），以测试和评估LLMs的不同安全类别。在早期的o3-mini测试版上，我们自动生成并执行了10,080个不安全测试输入。经过手动验证，我们发现了87个实际的不安全LLM行为实例。本文还总结了在OpenAI最新LLM预部署外部测试阶段的关键发现和见解。

> Large Language Models (LLMs) have become an integral part of our daily lives. However, they impose certain risks, including those that can harm individuals' privacy, perpetuate biases and spread misinformation. These risks highlight the need for robust safety mechanisms, ethical guidelines, and thorough testing to ensure their responsible deployment. Safety of LLMs is a key property that needs to be thoroughly tested prior the model to be deployed and accessible to the general users. This paper reports the external safety testing experience conducted by researchers from Mondragon University and University of Seville on OpenAI's new o3-mini LLM as part of OpenAI's early access for safety testing program. In particular, we apply our tool, ASTRAL, to automatically and systematically generate up to date unsafe test inputs (i.e., prompts) that helps us test and assess different safety categories of LLMs. We automatically generate and execute a total of 10,080 unsafe test input on a early o3-mini beta version. After manually verifying the test cases classified as unsafe by ASTRAL, we identify a total of 87 actual instances of unsafe LLM behavior. We highlight key insights and findings uncovered during the pre-deployment external testing phase of OpenAI's latest LLM.

[Arxiv](https://arxiv.org/abs/2501.17749)