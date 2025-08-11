# 大型模型能否骗过双眼？生物动画的新图灵测试

发布时间：2025年08月08日

`LLM应用` `人工智能` `计算机图形学`

> Can Large Models Fool the Eye? A New Turing Test for Biological Animation

# 摘要

> 评估大型模型的能力及其差距充满挑战。现有评测方法要么基于静态数据集采用依赖真实值的评分式评估，要么采用模糊的文本式聊天机器人风格的人类偏好收集，这些方法可能无法为用户提供即时、直观且可感知的性能差异反馈。本文中，我们引入了BioMotion Arena——一个通过视觉动画评估大型语言模型（LLMs）和多模态大型语言模型（MLLMs）能力的新颖框架。我们的方法从生物体固有的运动模式视觉感知中汲取灵感，利用点光源成像技术放大模型间的性能差异。具体而言，我们采用配对比较评估方式，针对90种生物运动变体，收集了53种主流LLMs和MLLMs的超4.5万张投票。数据分析表明，群体化的人类投票结果与专家评分高度一致，这凸显了BioMotion Arena在提供区分性反馈方面的优势。我们还发现，包括前沿开源模型InternVL3和专有Claude-4系列在内的90%以上的评测模型，均无法生成基础的人形点光源组，更遑论平滑且符合生物力学的运动。这使得BioMotion Arena不仅成为性能可视化极具挑战性的评测基准，同时也为构建无真实值依赖的灵活评测框架奠定了基础。

> Evaluating the abilities of large models and manifesting their gaps are challenging. Current benchmarks adopt either ground-truth-based score-form evaluation on static datasets or indistinct textual chatbot-style human preferences collection, which may not provide users with immediate, intuitive, and perceptible feedback on performance differences. In this paper, we introduce BioMotion Arena, a novel framework for evaluating large language models (LLMs) and multimodal large language models (MLLMs) via visual animation. Our methodology draws inspiration from the inherent visual perception of motion patterns characteristic of living organisms that utilizes point-light source imaging to amplify the performance discrepancies between models. Specifically, we employ a pairwise comparison evaluation and collect more than 45k votes for 53 mainstream LLMs and MLLMs on 90 biological motion variants. Data analyses show that the crowd-sourced human votes are in good agreement with those of expert raters, demonstrating the superiority of our BioMotion Arena in offering discriminative feedback. We also find that over 90\% of evaluated models, including the cutting-edge open-source InternVL3 and proprietary Claude-4 series, fail to produce fundamental humanoid point-light groups, much less smooth and biologically plausible motions. This enables BioMotion Arena to serve as a challenging benchmark for performance visualization and a flexible evaluation framework without restrictions on ground-truth.

[Arxiv](https://arxiv.org/abs/2508.06072)