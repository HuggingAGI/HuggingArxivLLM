# # TxGemma：高效且自主的大型语言模型，专为治疗学打造

发布时间：2025年04月08日

`LLM应用` `药物开发` `生命科学`

> TxGemma: Efficient and Agentic LLMs for Therapeutics

# 摘要

> 药物开发是一项高成本、高风险的事业，常常面临高失败率的困扰。为了解决这一难题，我们推出了TxGemma——一套高效且通用的大型语言模型（LLMs），它不仅能够预测治疗特性，还支持交互式推理和解释。与专注于特定任务的模型不同，TxGemma能够整合多源信息，使其在药物开发的各个环节中具有广泛应用潜力。该套件包括2B、9B和27B参数的模型，这些模型基于Gemma-2微调而来，使用涵盖小分子、蛋白质、核酸、疾病和细胞系的综合数据集进行训练。在66个药物开发任务中，TxGemma在64项任务中表现优于或与现有最优通用模型相当（其中45项超越），与现有专业模型相比在50项任务中表现更优（其中26项超越）。在临床试验不良事件预测等药物开发下游任务中，对TxGemma模型进行微调所需的训练数据少于对基础LLMs的微调，这使得TxGemma特别适用于数据有限的应用场景。除了强大的预测能力，TxGemma还配备了对话模型，架起了通用LLMs与专业特性预测器之间的桥梁。这些模型使科学家能够以自然语言进行交互，基于分子结构提供预测的机制解释，并参与科学讨论。在此基础上，我们进一步推出了Agentic-Tx——一个由Gemini 2.5驱动的通用治疗智能系统，它能够进行推理、执行操作、管理多样化的工作流程，并获取外部领域知识。在Humanity's Last Exam基准测试（化学与生物学领域）中，Agentic-Tx显著超越了之前的领先模型，在GPQA（化学）任务中，相较于o3-mini（高），其相对提升了52.3%和26.7%。此外，在ChemBench-Preference和ChemBench-Mini任务中，Agentic-Tx分别比o3-mini（高）提升了6.3%和2.4%。


> Therapeutic development is a costly and high-risk endeavor that is often plagued by high failure rates. To address this, we introduce TxGemma, a suite of efficient, generalist large language models (LLMs) capable of therapeutic property prediction as well as interactive reasoning and explainability. Unlike task-specific models, TxGemma synthesizes information from diverse sources, enabling broad application across the therapeutic development pipeline. The suite includes 2B, 9B, and 27B parameter models, fine-tuned from Gemma-2 on a comprehensive dataset of small molecules, proteins, nucleic acids, diseases, and cell lines. Across 66 therapeutic development tasks, TxGemma achieved superior or comparable performance to the state-of-the-art generalist model on 64 (superior on 45), and against state-of-the-art specialist models on 50 (superior on 26). Fine-tuning TxGemma models on therapeutic downstream tasks, such as clinical trial adverse event prediction, requires less training data than fine-tuning base LLMs, making TxGemma suitable for data-limited applications. Beyond these predictive capabilities, TxGemma features conversational models that bridge the gap between general LLMs and specialized property predictors. These allow scientists to interact in natural language, provide mechanistic reasoning for predictions based on molecular structure, and engage in scientific discussions. Building on this, we further introduce Agentic-Tx, a generalist therapeutic agentic system powered by Gemini 2.5 that reasons, acts, manages diverse workflows, and acquires external domain knowledge. Agentic-Tx surpasses prior leading models on the Humanity's Last Exam benchmark (Chemistry & Biology) with 52.3% relative improvement over o3-mini (high) and 26.7% over o3-mini (high) on GPQA (Chemistry) and excels with improvements of 6.3% (ChemBench-Preference) and 2.4% (ChemBench-Mini) over o3-mini (high).

[Arxiv](https://arxiv.org/abs/2504.06196)