# SWE-Bench错觉：当最先进的LLMs依赖记忆而非真正推理时

发布时间：2025年06月13日

`LLM应用

理由：这篇论文探讨了大型语言模型在软件工程任务中的应用，特别是通过基准测试评估其能力。虽然重点在评估方法，但这是应用层面的评估，因此归类为LLM应用。` `软件工程`

> The SWE-Bench Illusion: When State-of-the-Art LLMs Remember Instead of Reason

# 摘要

> 随着大型语言模型（LLMs）能力的不断提升和广泛应用，基准测试在评估其实际效用中扮演着关键角色。例如，SWE-Bench Verified已成为评估LLMs软件工程能力的重要基准，特别是它们解决真实GitHub问题的能力。近期的LLMs在SWE-Bench上表现优异，这让人对其处理复杂编码任务的能力充满信心。然而，现有的评估协议可能夸大了这些模型的真实能力。区分LLMs的通用问题解决能力和其他学习到的特征至关重要。在本研究中，我们引入了一个诊断任务：仅从问题描述中识别文件路径，以探查模型的内在知识。我们发现，最先进的模型仅通过问题描述就能以高达76%的准确率识别出有缺陷的文件路径，而无需访问仓库结构。然而，在未包含于SWE-Bench中的仓库任务上，这一准确率仅为53%，这表明可能存在数据污染或记忆现象。这些发现引发了对现有结果有效性的担忧，并强调了需要更加稳健、抗污染的基准测试，以可靠评估LLMs的编码能力。

> As large language models (LLMs) become increasingly capable and widely adopted, benchmarks play a central role in assessing their practical utility. For example, SWE-Bench Verified has emerged as a critical benchmark for evaluating LLMs' software engineering abilities, particularly their aptitude for resolving real-world GitHub issues. Recent LLMs show impressive performance on SWE-Bench, leading to optimism about their capacity for complex coding tasks. However, current evaluation protocols may overstate these models' true capabilities. It is crucial to distinguish LLMs' generalizable problem-solving ability and other learned artifacts. In this work, we introduce a diagnostic task: file path identification from issue descriptions alone, to probe models' underlying knowledge. We present empirical evidence that performance gains on SWE-Bench-Verified may be partially driven by memorization rather than genuine problem-solving. We show that state-of-the-art models achieve up to 76% accuracy in identifying buggy file paths using only issue descriptions, without access to repository structure. This performance is merely up to 53% on tasks from repositories not included in SWE-Bench, pointing to possible data contamination or memorization. These findings raise concerns about the validity of existing results and underscore the need for more robust, contamination-resistant benchmarks to reliably evaluate LLMs' coding abilities.

[Arxiv](https://arxiv.org/abs/2506.12286)