# # MM-IFEngine: 走向多模态指令遵循

发布时间：2025年04月10日

`LLM应用` `人工智能`

> MM-IFEngine: Towards Multimodal Instruction Following

# 摘要

> 指令遵循（IF）能力评估多模态大语言模型（MLLMs）对用户指示的理解程度及其执行的准确性。然而，现有的多模态指令遵循训练数据稀缺，基准测试使用简单的原子指令，且对需要精确输出约束的任务的评估策略不够精准。为解决这一问题，我们提出了MM-IFEngine，一个高效生成高质量图像-指令对的管道。我们的MM-IFEngine管道生成了大规模、多样化且高质量的训练数据集MM-IFInstruct-23k，适用于监督微调（SFT），并扩展为MM-IFDPO-23k用于直接偏好优化（DPO）。此外，我们引入了MM-IFEval，一个具有挑战性和多样性的多模态指令遵循基准，其中包括（1）针对输出响应的组合级别约束以及与输入图像相关的感知级别约束，（2）一个全面的评估管道，结合了基于规则的评估和判断模型。通过SFT和DPO实验，我们证明在MM-IFInstruct-23k和MM-IFDPO-23k上微调MLLMs在多种IF基准上取得了显著提升，如MM-IFEval（+10.2$\%$）、MIA（+7.6$\%$）和IFEval（+12.3$\%$）。完整的数据和评估代码将在https://github.com/SYuan03/MM-IFEngine上发布。

> The Instruction Following (IF) ability measures how well Multi-modal Large Language Models (MLLMs) understand exactly what users are telling them and whether they are doing it right. Existing multimodal instruction following training data is scarce, the benchmarks are simple with atomic instructions, and the evaluation strategies are imprecise for tasks demanding exact output constraints. To address this, we present MM-IFEngine, an effective pipeline to generate high-quality image-instruction pairs. Our MM-IFEngine pipeline yields large-scale, diverse, and high-quality training data MM-IFInstruct-23k, which is suitable for Supervised Fine-Tuning (SFT) and extended as MM-IFDPO-23k for Direct Preference Optimization (DPO). We further introduce MM-IFEval, a challenging and diverse multi-modal instruction-following benchmark that includes (1) both compose-level constraints for output responses and perception-level constraints tied to the input images, and (2) a comprehensive evaluation pipeline incorporating both rule-based assessment and judge model. We conduct SFT and DPO experiments and demonstrate that fine-tuning MLLMs on MM-IFInstruct-23k and MM-IFDPO-23k achieves notable gains on various IF benchmarks, such as MM-IFEval (+10.2$\%$), MIA (+7.6$\%$), and IFEval (+12.3$\%$). The full data and evaluation code will be released on https://github.com/SYuan03/MM-IFEngine.

[Arxiv](https://arxiv.org/abs/2504.07957)