# 从模型归因的角度剖析大型语言模型的记忆化机制

发布时间：2025年01月09日

`LLM理论

**理由**：这篇论文主要探讨了大型语言模型（LLMs）的架构因素对记忆和泛化性能的影响，特别是通过分析不同层注意力模块的作用来揭示其内在机制。研究涉及理论分析和实验验证，旨在理解LLMs的底层工作原理，并提出减轻记忆问题的方法。因此，这篇论文属于**LLM理论**分类。` `人工智能` `隐私保护`

> Analyzing Memorization in Large Language Models through the Lens of Model Attribution

# 摘要

> 大型语言模型（LLMs）在现代应用中广泛应用，但常常会记住训练数据，引发隐私泄露和版权问题。现有研究多集中于事后分析，如提取记忆内容或开发记忆度量，却鲜少探讨导致记忆的底层架构因素。本研究从架构视角切入，通过分析不同层注意力模块对记忆和泛化性能的影响，揭示其内在机制。我们运用归因技术，系统干预LLM架构，绕过特定块的注意力模块，同时保持层归一化和MLP变换等组件不变。通过数学定理，我们分析了干预机制，限定了有和没有归因时层输出的差异。理论和实证分析表明，深层transformer块的注意力模块主要负责记忆，而早期块则对模型的泛化和推理能力至关重要。我们在Pythia和GPTNeo等LLM家族及五个基准数据集上进行了全面实验，验证了这些发现。这些见解为减轻LLMs记忆、同时保持性能提供了实用方法，助力其在现实世界应用中更安全、更道德地部署。

> Large Language Models (LLMs) are prevalent in modern applications but often memorize training data, leading to privacy breaches and copyright issues. Existing research has mainly focused on posthoc analyses, such as extracting memorized content or developing memorization metrics, without exploring the underlying architectural factors that contribute to memorization. In this work, we investigate memorization from an architectural lens by analyzing how attention modules at different layers impact its memorization and generalization performance. Using attribution techniques, we systematically intervene in the LLM architecture by bypassing attention modules at specific blocks while keeping other components like layer normalization and MLP transformations intact. We provide theorems analyzing our intervention mechanism from a mathematical view, bounding the difference in layer outputs with and without our attributions. Our theoretical and empirical analyses reveal that attention modules in deeper transformer blocks are primarily responsible for memorization, whereas earlier blocks are crucial for the models generalization and reasoning capabilities. We validate our findings through comprehensive experiments on different LLM families (Pythia and GPTNeo) and five benchmark datasets. Our insights offer a practical approach to mitigate memorization in LLMs while preserving their performance, contributing to safer and more ethical deployment in real world applications.

[Arxiv](https://arxiv.org/abs/2501.05078)