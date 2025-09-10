# ALLabel：基于演示检索的LLM实体识别三阶段主动学习方法

发布时间：2025年09月09日

`LLM应用` `基础理论`

> ALLabel: Three-stage Active Learning for LLM-based Entity Recognition using Demonstration Retrieval

# 摘要

> 如今，化学、材料科学等自然科学领域的众多数据驱动研究，都需要从科学数据集中进行大规模、高性能的实体识别。大型语言模型（LLMs）已被广泛应用于实体识别任务，这一趋势在全谱系NLP任务中同样显著。目前主流的实体识别LLMs多依赖微调技术，然而微调过程往往成本高昂。为了在性能与成本间取得最佳平衡，我们提出了三阶段框架ALLabel，其核心是为LLM建模的演示环节筛选出信息最丰富、代表性最强的样本。这些标注示例将用于构建LLM上下文学习的真实检索语料库。通过依次运用三种不同的主动学习策略，在三个专业领域数据集上，相同标注预算下，ALLabel的性能始终超越所有基线模型。实验结果还显示，借助ALLabel仅选择性标注5%-10%的数据集，性能即可媲美全量标注的方法。进一步的分析与消融实验也证实了该方法的有效性和普适性。

> Many contemporary data-driven research efforts in the natural sciences, such as chemistry and materials science, require large-scale, high-performance entity recognition from scientific datasets. Large language models (LLMs) have increasingly been adopted to solve the entity recognition task, with the same trend being observed on all-spectrum NLP tasks. The prevailing entity recognition LLMs rely on fine-tuned technology, yet the fine-tuning process often incurs significant cost. To achieve a best performance-cost trade-off, we propose ALLabel, a three-stage framework designed to select the most informative and representative samples in preparing the demonstrations for LLM modeling. The annotated examples are used to construct a ground-truth retrieval corpus for LLM in-context learning. By sequentially employing three distinct active learning strategies, ALLabel consistently outperforms all baselines under the same annotation budget across three specialized domain datasets. Experimental results also demonstrate that selectively annotating only 5\%-10\% of the dataset with ALLabel can achieve performance comparable to the method annotating the entire dataset. Further analyses and ablation studies verify the effectiveness and generalizability of our proposal.

[Arxiv](https://arxiv.org/abs/2509.07512)