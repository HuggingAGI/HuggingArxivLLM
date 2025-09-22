# BEFT：语言模型的偏差高效微调

发布时间：2025年09月19日

`LLM应用` `基础理论`

> BEFT: Bias-Efficient Fine-Tuning of Language Models

# 摘要

> 在各类参数高效微调（PEFT）技术中，全偏置项微调凭借开箱即用的便捷性和优异性能崭露头角，在低数据场景下表现尤为突出。仅微调偏置项甚至有望达成前所未有的参数效率。但目前，微调不同偏置项（如查询、键或值投影层的偏置）如何影响下游性能，这一关联机制尚不清晰。现有方法（如基于偏置变化幅度或经验Fisher信息的策略）在筛选特定偏置项以实现高效微调时，指导意义较为有限。为此，本文提出一种待微调偏置项选择方法，奠定了偏置高效微调（BEFT）的技术基础。我们在参数规模1.1亿至67亿、涵盖仅编码器与仅解码器架构的多种大型语言模型（LLMs）上，将该方法与其他偏置选择策略进行了全面对比实验。实验结果证实，该偏置高效方法在分类、多项选择、生成等各类下游任务中均展现出显著的有效性与优越性。

> Fine-tuning all-bias-terms stands out among various parameter-efficient fine-tuning (PEFT) techniques, owing to its out-of-the-box usability and competitive performance, especially in low-data regimes. Bias-only fine-tuning has the potential for unprecedented parameter efficiency. However, the link between fine-tuning different bias terms (i.e., bias terms in the query, key, or value projections) and downstream performance remains unclear. The existing approaches, e.g., based on the magnitude of bias change or empirical Fisher information, provide limited guidance for selecting the particular bias term for effective fine-tuning. In this paper, we propose an approach for selecting the bias term to be fine-tuned, forming the foundation of our bias-efficient fine-tuning (BEFT). We extensively evaluate our bias-efficient approach against other bias-selection approaches, across a wide range of large language models (LLMs) spanning encoder-only and decoder-only architectures from 110M to 6.7B parameters. Our results demonstrate the effectiveness and superiority of our bias-efficient approach on diverse downstream tasks, including classification, multiple-choice, and generation tasks.

[Arxiv](https://arxiv.org/abs/2509.15974)