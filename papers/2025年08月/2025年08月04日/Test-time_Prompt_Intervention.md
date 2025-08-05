# 测试时的提示干预

发布时间：2025年08月04日

`LLM应用

摘要分析：这篇论文专注于优化大型语言模型（LLM）在推理过程中的思维链生成问题，提出了一种新的干预框架PI，以减少冗余和提高推理效率。这属于对LLM的应用优化，因此归类为LLM应用。` `人工智能` `认知科学`

> Test-time Prompt Intervention

# 摘要

> 测试时计算在大型语言模型（LLM）领域取得了显著成功，尤其在复杂任务中，通过生成更长的思维链（CoTs）来提升推理能力。然而，这类推理模型生成的思维链常常受到冗余过多的困扰，包括不必要的验证步骤和重复的推理转变。这种现象的根本原因在于这些模型的后训练过程过度依赖结果奖励范式，而过程奖励范式的数据难以大规模构建。为了解决这一问题，我们提出了PI，一个全新的测试时提示干预框架。PI通过及时的（When模块）和适当的（How模块）干预以及干预后采样（Which模块），在推理过程中动态引导和调节推理路径。这使得人类的问题解决专业知识和认知科学原理能够无缝融入LLM的推理过程，从而提高可控性和可解释性。在多个模型和数据集上的广泛实验表明，PI显著缩短了思维链，同时减少了幻觉现象，使推理更加简洁可靠。

> Test-time compute has led to remarkable success in the large language model (LLM) community, particularly for complex tasks, where longer chains of thought (CoTs) are generated to enhance reasoning capabilities. However, growing evidence reveals that such reasoning models often produce CoTs plagued by excessive redundancy, including unnecessary verification steps and repetitive reasoning shifts. The root cause lies in post-training of them that overly rely on outcome reward paradigms, as the data of process reward paradigms, which regulate intermediate reasoning steps, is difficult to construct at scale. To address this, we propose PI, a novel framework for Test-time Prompt Intervention. PI provides an interface to dynamically guide and regulate reasoning paths during inference through timely (When module) and proper (How module) interventions and post-intervention sampling (Which module). This allows human problem-solving expertise and cognitive science principles to be seamlessly integrated into LLMs' reasoning processes, enhancing controllability and interpretability. Extensive experiments across multiple models and datasets demonstrate that PI significantly shortens CoTs while reducing hallucination, yielding more concise and reliable reasoning.

[Arxiv](https://arxiv.org/abs/2508.02511)