# 移动智能语言理解基准测试：Mobile-MMLU

发布时间：2025年03月26日

`LLM应用` `移动计算` `数据集`

> Mobile-MMLU: A Mobile Intelligence Language Understanding Benchmark

# 摘要

> 大型语言模型（LLMs）的快速发展在移动设备上的应用引发了广泛关注。与桌面用户不同，移动用户与LLMs的交互方式形成了独特的期望和数据偏见。然而，现有基准数据集主要针对服务器和桌面环境，缺乏专门针对移动场景的大型数据集。此外，移动设备的存储和计算资源限制了模型的大小和能力，因此需要优化效率并优先考虑知识。为了解决这些问题，我们推出了Mobile-MMLU——一个专为移动智能设计的大规模基准数据集。它包含80个移动相关领域的16,186个问题，旨在评估LLMs在现实移动场景中的表现。其中，更具挑战性的子集Mobile-MMLU-Pro提供了类似MMLU-Pro规模的高级评估，但难度远高于标准完整集。两个基准均采用选择题形式，专注于实际的移动交互场景，如食谱建议、旅行规划和日常基本任务。该数据集重点评估推理延迟、能源消耗、内存使用和响应质量等关键移动指标，全面揭示模型在移动环境下的性能表现。此外，它还注重隐私和适应性，评估模型在设备端处理、保护用户隐私和适应个性化使用模式的能力。Mobile-MMLU家族为开发和比较移动优化的LLMs提供了标准化框架，助力移动计算环境中的生产力和决策能力提升。我们的代码和数据可在GitHub上获取：https://github.com/VILA-Lab/Mobile-MMLU。

> Rapid advancements in large language models (LLMs) have increased interest in deploying them on mobile devices for on-device AI applications. Mobile users interact differently with LLMs compared to desktop users, creating unique expectations and data biases. Current benchmark datasets primarily target at server and desktop environments, and there is a notable lack of extensive datasets specifically designed for mobile contexts. Additionally, mobile devices face strict limitations in storage and computing resources, constraining model size and capabilities, thus requiring optimized efficiency and prioritized knowledge. To address these challenges, we introduce Mobile-MMLU, a large-scale benchmark dataset tailored for mobile intelligence. It consists of 16,186 questions across 80 mobile-related fields, designed to evaluate LLM performance in realistic mobile scenarios. A challenging subset, Mobile-MMLU-Pro, provides advanced evaluation similar in size to MMLU-Pro but significantly more difficult than our standard full set. Both benchmarks use multiple-choice, order-invariant questions focused on practical mobile interactions, such as recipe suggestions, travel planning, and essential daily tasks. The dataset emphasizes critical mobile-specific metrics like inference latency, energy consumption, memory usage, and response quality, offering comprehensive insights into model performance under mobile constraints. Moreover, it prioritizes privacy and adaptability, assessing models' ability to perform on-device processing, maintain user privacy, and adapt to personalized usage patterns. Mobile-MMLU family offers a standardized framework for developing and comparing mobile-optimized LLMs, enabling advancements in productivity and decision-making within mobile computing environments. Our code and data are available at: https://github.com/VILA-Lab/Mobile-MMLU.

[Arxiv](https://arxiv.org/abs/2503.20786)