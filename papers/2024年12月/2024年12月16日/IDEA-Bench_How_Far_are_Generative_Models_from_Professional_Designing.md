# IDEA-Bench：生成式模型与专业设计的差距究竟有多大？

发布时间：2024年12月16日

`LLM应用` `视觉生成`

> IDEA-Bench: How Far are Generative Models from Professional Designing?

# 摘要

> 现实世界中的设计任务，像绘本创作、借助角色集开发电影故事板、照片修图、视觉特效、字体转换等，丰富多样且复杂，需要从指令、描述和参考图像中深度解读和提取各类元素。生成的图像往往会隐性地抓取参考或用户输入中的关键特征，这让开发能有效应对这类多样任务的模型颇具难度。尽管现有的视觉生成模型能依据提示生成高品质图像，但在涉及多种形式以及多个输入输出的专业设计场景中，即便搭配了诸如 ControlNets 和 LoRAs 之类的适配器，它们仍面临重大局限。为解决此问题，我们推出了 IDEA-Bench，这一综合基准涵盖 100 项现实世界的设计任务，包含渲染、视觉效果、故事板、绘本、字体、基于风格和保持身份的生成等，拥有 275 个测试用例，以全面评估模型的通用生成能力。值得注意的是，表现最佳的模型在 IDEA-Bench 上也仅得 22.48 分，而最优的通用模型仅获 6.81 分。我们对这些结果展开了详尽分析，突出了内在挑战，并给出了可行的改进方向。另外，我们提供了 18 个具有代表性的任务子集，并配备基于多模态大型语言模型（MLLM）的自动评估技术，以助力模型的快速开发与比较。我们在 https://github.com/ali-vilab/IDEA-Bench 发布了基准数据、评估工具包和在线排行榜，旨在推动生成模型朝着更全能和适用的智能设计系统迈进。

> Real-world design tasks - such as picture book creation, film storyboard development using character sets, photo retouching, visual effects, and font transfer - are highly diverse and complex, requiring deep interpretation and extraction of various elements from instructions, descriptions, and reference images. The resulting images often implicitly capture key features from references or user inputs, making it challenging to develop models that can effectively address such varied tasks. While existing visual generative models can produce high-quality images based on prompts, they face significant limitations in professional design scenarios that involve varied forms and multiple inputs and outputs, even when enhanced with adapters like ControlNets and LoRAs. To address this, we introduce IDEA-Bench, a comprehensive benchmark encompassing 100 real-world design tasks, including rendering, visual effects, storyboarding, picture books, fonts, style-based, and identity-preserving generation, with 275 test cases to thoroughly evaluate a model's general-purpose generation capabilities. Notably, even the best-performing model only achieves 22.48 on IDEA-Bench, while the best general-purpose model only achieves 6.81. We provide a detailed analysis of these results, highlighting the inherent challenges and providing actionable directions for improvement. Additionally, we provide a subset of 18 representative tasks equipped with multimodal large language model (MLLM)-based auto-evaluation techniques to facilitate rapid model development and comparison. We releases the benchmark data, evaluation toolkits, and an online leaderboard at https://github.com/ali-vilab/IDEA-Bench, aiming to drive the advancement of generative models toward more versatile and applicable intelligent design systems.

[Arxiv](https://arxiv.org/abs/2412.11767)