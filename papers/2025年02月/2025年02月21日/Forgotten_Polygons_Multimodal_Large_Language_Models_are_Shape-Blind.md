# # 多模态大语言模型对形状视而不见：被遗忘的多边形研究

发布时间：2025年02月21日

`LLM应用` `数学推理` `视觉推理`

> Forgotten Polygons: Multimodal Large Language Models are Shape-Blind

# 摘要

> 尽管在视觉语言任务中表现强劲，多模态大型语言模型（MLLMs）在数学问题解决方面却显得力不从心，开源和最先进的模型在视觉数学基准测试中均未能达到人类水平。为了系统性地考察MLLMs的视觉数学推理能力，我们从三个方面展开研究：首先评估模型对几何基本元素的理解，其次测试多步推理能力，最后探索提升视觉推理能力的潜在方案。研究发现，模型在形状识别方面存在根本性缺陷，顶尖模型在识别正多边形时的准确率不足50%。我们通过双重加工理论的视角分析了这些失败案例，发现MLLMs主要依赖于系统1（直觉和记忆关联），而非系统2（深思熟虑的推理）。因此，MLLMs无法准确计算熟悉和新颖形状的边数，这表明它们既未真正掌握"边"的概念，也无法有效处理视觉输入。最后，我们提出了视觉引导的链式思考（VC-CoT）提示方法，通过在图示中明确引用视觉标注来增强多步数学推理能力，将GPT-4o在不规则多边形边数计算任务中的准确率从7%提升至93%。我们的研究结果表明，MLLMs中的系统2推理仍是一个开放性问题，而视觉引导的提示对于成功激活视觉推理至关重要。代码可从以下链接获取：https://github.com/rsinghlab/Shape-Blind.

> Despite strong performance on vision-language tasks, Multimodal Large Language Models (MLLMs) struggle with mathematical problem-solving, with both open-source and state-of-the-art models falling short of human performance on visual-math benchmarks. To systematically examine visual-mathematical reasoning in MLLMs, we (1) evaluate their understanding of geometric primitives, (2) test multi-step reasoning, and (3) explore a potential solution to improve visual reasoning capabilities. Our findings reveal fundamental shortcomings in shape recognition, with top models achieving under 50% accuracy in identifying regular polygons. We analyze these failures through the lens of dual-process theory and show that MLLMs rely on System 1 (intuitive, memorized associations) rather than System 2 (deliberate reasoning). Consequently, MLLMs fail to count the sides of both familiar and novel shapes, suggesting they have neither learned the concept of sides nor effectively process visual inputs. Finally, we propose Visually Cued Chain-of-Thought (VC-CoT) prompting, which enhances multi-step mathematical reasoning by explicitly referencing visual annotations in diagrams, boosting GPT-4o's accuracy on an irregular polygon side-counting task from 7% to 93%. Our findings suggest that System 2 reasoning in MLLMs remains an open problem, and visually-guided prompting is essential for successfully engaging visual reasoning. Code available at: https://github.com/rsinghlab/Shape-Blind.

[Arxiv](https://arxiv.org/abs/2502.15969)