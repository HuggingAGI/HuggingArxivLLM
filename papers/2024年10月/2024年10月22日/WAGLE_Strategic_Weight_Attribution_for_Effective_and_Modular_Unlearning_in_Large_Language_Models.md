# WAGLE: 大型语言模型中的战略权重分配，实现高效模块化遗忘

发布时间：2024年10月22日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中模型权重与遗忘过程的内在关系，并提出了一种新的遗忘方法WAGLE。研究内容涉及模型权重的归因和其对遗忘过程的影响，属于对LLM内部机制和理论的研究，因此分类为LLM理论。` `人工智能` `数据隐私`

> WAGLE: Strategic Weight Attribution for Effective and Modular Unlearning in Large Language Models

# 摘要

> # 摘要
随着数据法规的遵守和生成式AI伦理实践的推动，大型语言模型（LLMs）中有效的遗忘机制需求日益迫切。尽管LLM遗忘研究热度上升，但现有工作多聚焦于提升遗忘方法的有效性和效率，而模型权重与遗忘之间的内在关系却鲜有探讨。本文系统研究了模型权重如何影响LLM的遗忘过程，并提出了权重归因引导的遗忘方法WAGLE，揭示了权重“影响”与数据“影响”在LLM生成中的交互关系。通过策略性地引导LLM在不同遗忘方法和任务中进行遗忘，WAGLE能够在消除不必要内容的同时，保持原始任务的性能。我们称这种方法为WAGLE，它揭示了权重与数据在LLM生成中的相互影响。实验表明，WAGLE在多种LLM遗忘方法（如梯度差异和负偏好优化）、应用场景（如虚构遗忘、恶意使用预防和版权信息删除）以及模型（如Zephyr-7b-beta和Llama2-7b）中均显著提升了遗忘性能。据我们所知，这是首个基于权重归因的LLM遗忘原则性方法，与以往缺乏权重归因或仅使用简单归因技术的方法形成鲜明对比。

> The need for effective unlearning mechanisms in large language models (LLMs) is increasingly urgent, driven by the necessity to adhere to data regulations and foster ethical generative AI practices. Despite growing interest of LLM unlearning, much of the existing research has focused on varied unlearning method designs to boost effectiveness and efficiency. However, the inherent relationship between model weights and LLM unlearning has not been extensively examined. In this paper, we systematically explore how model weights interact with unlearning processes in LLMs and we design the weight attribution-guided LLM unlearning method, WAGLE, which unveils the interconnections between 'influence' of weights and 'influence' of data to forget and retain in LLM generation. By strategically guiding the LLM unlearning across different types of unlearning methods and tasks, WAGLE can erase the undesired content, while maintaining the performance of the original tasks. We refer to the weight attribution-guided LLM unlearning method as WAGLE, which unveils the interconnections between 'influence' of weights and 'influence' of data to forget and retain in LLM generation. Our extensive experiments show that WAGLE boosts unlearning performance across a range of LLM unlearning methods such as gradient difference and (negative) preference optimization, applications such as fictitious unlearning, malicious use prevention, and copyrighted information removal, and models including Zephyr-7b-beta and Llama2-7b. To the best of our knowledge, our work offers the first principled method for attributing and pinpointing the influential weights in enhancing LLM unlearning. It stands in contrast to previous methods that lack weight attribution and simpler weight attribution techniques.

[Arxiv](https://arxiv.org/abs/2410.17509)