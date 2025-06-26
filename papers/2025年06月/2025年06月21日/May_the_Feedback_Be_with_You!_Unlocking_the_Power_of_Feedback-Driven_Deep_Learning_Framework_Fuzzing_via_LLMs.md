# 愿反馈与你同在！借助LLMs释放反馈驱动的深度学习框架模糊测试的强大力量。

发布时间：2025年06月21日

`LLM应用

理由：这篇论文探讨了将大型语言模型（LLMs）应用于模糊测试（Fuzzing）领域，以提高深度学习框架中的缺陷检测能力。论文中提出了一种基于LLMs的模糊测试方法FUEL，该方法利用LLMs来分析反馈信息并生成测试用例。这种方法属于将LLMs技术应用到具体任务中的范畴，因此归类为LLM应用。` `自动驾驶`

> May the Feedback Be with You! Unlocking the Power of Feedback-Driven Deep Learning Framework Fuzzing via LLMs

# 摘要

> 以深度学习（DL）框架为代表的AI基础设施在过去十年中一直是基础的DL系统。然而，DL框架中的缺陷在某些关键场景（如医疗和自动驾驶）中可能会导致灾难性后果。通过模糊测试（Fuzzing）发现DL框架中的缺陷是一种简单而有效的方法。遗憾的是，现有的模糊测试技术尚未全面考虑多种类型的反馈信息，且以粗粒度的方式分析反馈，例如仅根据覆盖率是否增加来变异测试用例。最近，研究人员将大型语言模型（LLMs）引入模糊测试领域，但目前基于LLMs的模糊测试技术仅关注生成测试用例，忽视了LLMs在分析反馈信息方面的潜力，导致无法生成更多有效且多样的测试用例。为填补这一空白，我们提出了FUEL，以打破DL框架中基于反馈的模糊测试的限制。FUEL的核心由两个基于LLMs的代理组成：分析LLM代理从反馈信息中推断分析摘要，生成LLM代理则根据这些摘要创建测试用例。迄今为止，FUEL已在PyTorch和TensorFlow中检测到104个缺陷，其中93个为新缺陷，47个已修复，5个已分配CVE ID。我们的研究表明，考虑多种反馈类型对模糊测试性能有益，而利用LLMs分析反馈信息是一个有前景的方向。我们的成果已发布在https://github.com/NJU-iSE/FUEL

> Artificial Intelligence (AI) Infrastructures, represented by Deep Learning (DL) frameworks, have served as fundamental DL systems over the last decade. However, the bugs in DL frameworks could lead to catastrophic consequences in some critical scenarios (e.g., healthcare and autonomous driving). A simple yet effective way to find bugs in DL frameworks is fuzz testing (Fuzzing). Unfortunately, existing fuzzing techniques have not comprehensively considered multiple types of feedback. Additionally, they analyze feedback in a coarse-grained manner, such as mutating the test cases only according to whether the coverage increases. Recently, researchers introduced Large Language Models (LLMs) into fuzzing. However, current LLM-based fuzzing techniques only focus on using LLMs to generate test cases while overlooking their potential to analyze feedback information, failing to create more valid and diverse test cases. To fill this gap, we propose FUEL to break the seal of Feedback-driven fuzzing for DL frameworks. The backbone of FUEL comprises two LLM-based agents, namely analysis LLM and generation LLM. Analysis LLM agent infers analysis summaries from feedback information, while the generation LLM agent creates tests guided by these analysis summaries. So far, FUEL has detected 104 bugs for PyTorch and TensorFlow, with 93 confirmed as new bugs, 47 already fixed, and 5 assigned with CVE IDs. Our work indicates that considering multiple types of feedback is beneficial to fuzzing performance, and leveraging LLMs to analyze feedback information is a promising direction. Our artifact is available at https://github.com/NJU-iSE/FUEL

[Arxiv](https://arxiv.org/abs/2506.17642)