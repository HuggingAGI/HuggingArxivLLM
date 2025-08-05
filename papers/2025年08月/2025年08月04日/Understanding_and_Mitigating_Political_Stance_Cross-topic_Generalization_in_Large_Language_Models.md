# 理解并缓解大型语言模型中的跨主题政治立场泛化

发布时间：2025年08月04日

`LLM理论` `人工智能` `神经科学`

> Understanding and Mitigating Political Stance Cross-topic Generalization in Large Language Models

# 摘要

> 在政治话题上对大型语言模型进行微调，不仅会显著影响其在各种政治问题上的立场，还可能无意中影响其对无关话题的立场。尽管这一问题已被先前研究提出，但目前对于这些立场的内部表示以及导致无意中跨话题泛化的机制仍缺乏深入理解。在本文中，我们从神经元层面系统地探索了这一现象背后的内部机制，以及如何有效减轻政治微调的跨话题泛化。

首先，我们提出了一种通过激活对比进行政治神经元定位 (PNLAC) 的方法，成功识别出两类政治理论神经元：通用政治神经元，它们控制多个政治话题的立场；以及特定话题神经元，它们影响模型在单个政治话题上的立场。通过在四个模型和数据集上进行激活补丁实验，我们验证了这两种政治理论神经元的存在。

基于这些发现，我们引入了基于抑制的微调方法 InhibitFT，有效缓解了跨话题立场泛化问题。实验结果表明，所识别的神经元类型在各种模型和数据集上均具有较强的鲁棒性。同时，InhibitFT 方法平均将跨话题立场泛化减少了 20%，且在保留特定话题性能的同时，仅需选择性抑制 5% 的神经元即可实现这一效果。

> Fine-tuning Large Language Models on a political topic will significantly manipulate their political stance on various issues and unintentionally affect their stance on unrelated topics. While previous studies have proposed this issue, there is still a lack of understanding regarding the internal representations of these stances and the mechanisms that lead to unintended cross-topic generalization. In this paper, we systematically explore the internal mechanisms underlying this phenomenon from a neuron-level perspective and how to mitigate the cross-topic generalization of political fine-tuning. Firstly, we propose Political Neuron Localization through Activation Contrasting (PNLAC) to identify two distinct types of political neurons: general political neurons, which govern stance across multiple political topics, and topic-specific neurons} that affect the model's political stance on individual topics. We find the existence of these political neuron types across four models and datasets through activation patching experiments. Leveraging these insights, we introduce InhibitFT, an inhibition-based fine-tuning method, effectively mitigating the cross-topic stance generalization. Experimental results demonstrate the robustness of identified neuron types across various models and datasets, and show that InhibitFT significantly reduces the cross-topic stance generalization by 20% on average, while preserving topic-specific performance. Moreover, we demonstrate that selectively inhibiting only 5% of neurons is sufficient to effectively mitigate the cross-topic stance generalization.

[Arxiv](https://arxiv.org/abs/2508.02360)