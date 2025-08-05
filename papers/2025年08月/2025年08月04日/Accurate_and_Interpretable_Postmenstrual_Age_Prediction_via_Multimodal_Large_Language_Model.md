# 利用多模态大型语言模型进行准确且可解释的产后年龄预测

发布时间：2025年08月04日

`LLM应用

摘要中的论文探讨了使用多模态大型语言模型（MLLM）进行产后年龄（PMA）预测，并结合指令调优和低秩适应（LoRA）策略优化模型。研究重点在于模型的应用及其在医学领域的实际效果，属于LLM的实际应用案例。` `可解释AI`

> Accurate and Interpretable Postmenstrual Age Prediction via Multimodal Large Language Model

# 摘要

> 准确估计扫描时的产后年龄（PMA）对评估新生儿发育和健康至关重要。深度学习模型虽能在脑部MRI预测PMA方面达到高精度，但其黑箱特性限制了临床决策支持的透明度和可解释性。为此，我们提出了一种多模态大型语言模型（MLLM）解决方案，旨在同时实现高精度PMA预测和生成临床相关解释。我们采用基于指令调优和低秩适应（LoRA）的参数高效微调（PEFT）策略，对Qwen2.5-VL-7B模型进行优化。模型基于新生儿MRI的四个二维皮层表面投影图训练，并通过区分训练与推理阶段的提示设计，使其既能处理回归任务，又能生成临床相关的解释。微调后的模型在预测误差上表现出色，95%置信区间为0.78至1.52周，同时输出基于发育特征的可解释结果，为围产期神经科学中构建透明可信的AI系统迈出了重要一步。

> Accurate estimation of postmenstrual age (PMA) at scan is crucial for assessing neonatal development and health. While deep learning models have achieved high accuracy in predicting PMA from brain MRI, they often function as black boxes, offering limited transparency and interpretability in clinical decision support. In this work, we address the dual challenge of accuracy and interpretability by adapting a multimodal large language model (MLLM) to perform both precise PMA prediction and clinically relevant explanation generation. We introduce a parameter-efficient fine-tuning (PEFT) strategy using instruction tuning and Low-Rank Adaptation (LoRA) applied to the Qwen2.5-VL-7B model. The model is trained on four 2D cortical surface projection maps derived from neonatal MRI scans. By employing distinct prompts for training and inference, our approach enables the MLLM to handle a regression task during training and generate clinically relevant explanations during inference. The fine-tuned model achieves a low prediction error with a 95 percent confidence interval of 0.78 to 1.52 weeks, while producing interpretable outputs grounded in developmental features, marking a significant step toward transparent and trustworthy AI systems in perinatal neuroscience.

[Arxiv](https://arxiv.org/abs/2508.02525)