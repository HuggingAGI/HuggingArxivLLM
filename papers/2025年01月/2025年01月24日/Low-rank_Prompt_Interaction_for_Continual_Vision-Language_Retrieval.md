# 持续视觉-语言检索中的低秩提示交互

发布时间：2025年01月24日

`LLM应用

**理由**：这篇论文主要关注多模态任务中的持续学习问题，提出了低秩提示交互（LPI）方法来解决跨模态和跨任务交互的问题。虽然论文没有直接提到大型语言模型（LLM），但其研究内容涉及多模态理解和提示学习，这些都是LLM应用中的重要研究方向。因此，将其归类为LLM应用是合适的。` `多模态学习` `持续学习`

> Low-rank Prompt Interaction for Continual Vision-Language Retrieval

# 摘要

> # 摘要
多模态任务中的持续学习研究日益受到关注，但现有工作大多忽略了显式的跨模态和跨任务交互。本文创新性地提出低秩提示交互（LPI），以解决多模态理解中的这一普遍问题，同时兼顾跨模态和跨任务交互。具体而言，针对跨模态交互，我们为Transformer层设计了多模态关联模块。考虑到训练参数随层数和任务数量增加而膨胀，我们提出低秩交互增强分解，通过共享和分离共同特定的低秩因子，既避免内存爆炸，又增强跨模态关联。此外，针对低秩初始化带来的多模态语义差异，我们采用分层低秩对比学习，确保训练鲁棒性。针对跨任务交互，我们通过视觉分析发现不同任务在接近度上存在明显差异，因此在提示学习过程中引入基于任务语义距离的显式任务对比约束。在两个检索任务上的实验表明，仅引入少量参数即可提升性能，验证了方法的有效性。代码已开源：https://github.com/Kelvin-ywc/LPI。

> Research on continual learning in multi-modal tasks has been receiving increasing attention. However, most existing work overlooks the explicit cross-modal and cross-task interactions. In this paper, we innovatively propose the Low-rank Prompt Interaction (LPI) to address this general problem of multi-modal understanding, which considers both cross-modal and cross-task interactions. Specifically, as for the former, we employ multi-modal correlation modules for corresponding Transformer layers. Considering that the training parameters scale to the number of layers and tasks, we propose low-rank interaction-augmented decomposition to avoid memory explosion while enhancing the cross-modal association through sharing and separating common-specific low-rank factors. In addition, due to the multi-modal semantic differences carried by the low-rank initialization, we adopt hierarchical low-rank contrastive learning to ensure training robustness. As for the latter, we initially employ a visual analysis and identify that different tasks have clear distinctions in proximity. Therefore, we introduce explicit task contrastive constraints in the prompt learning process based on task semantic distances. Experiments on two retrieval tasks show performance improvements with the introduction of a minimal number of parameters, demonstrating the effectiveness of our method. Code is available at https://github.com/Kelvin-ywc/LPI.

[Arxiv](https://arxiv.org/abs/2501.14369)