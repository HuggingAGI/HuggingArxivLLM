# # 心脏关怀套件：多维度理解心电图，基于原始多导联信号建模

发布时间：2025年06月06日

`LLM应用

摘要中提到Heartcare Suite是一个专注于ECG理解的多模态框架，其中包含了一个医学多模态大型语言模型HeartcareGPT。HeartcareGPT的应用场景是医疗领域的ECG分析，属于LLM在具体领域的应用。因此，这篇论文应归类为LLM应用。` `多模态`

> Heartcare Suite: Multi-dimensional Understanding of ECG with Raw Multi-lead Signal Modeling

# 摘要

> 我们很高兴推出Heartcare Suite，一个专注于细粒度心电图（ECG）理解的多模态综合性框架。该框架由三大核心组件构成：(i) Heartcare-220K，一个高质量、结构化且全面覆盖疾病诊断、波形形态分析及心律解读等关键任务的多模态ECG数据集；(ii) Heartcare-Bench，一个系统化、多维度的基准测试框架，专为评估诊断智能并优化医学多模态大型语言模型（Med-MLLMs）在ECG场景下的性能而设计；(iii) HeartcareGPT，配备专门设计的分词器Bidirectional ECG Abstract Tokenization (Beat)，通过双层向量量化和查询引导的双向扩散机制，将原始多导联信号高效转化为语义丰富的离散化分词。基于Heartcare-220K数据集，HeartcareGPT在多个具有临床意义的任务中展现出卓越的泛化能力和最优性能。大量实验结果证实，Heartcare Suite在推动ECG特定的多模态理解和评估方面具有显著效果。欢迎访问我们的项目页面https://github.com/Wznnnnn/Heartcare-Suite，获取更多详细信息。

> We present Heartcare Suite, a multimodal comprehensive framework for finegrained electrocardiogram (ECG) understanding. It comprises three key components: (i) Heartcare-220K, a high-quality, structured, and comprehensive multimodal ECG dataset covering essential tasks such as disease diagnosis, waveform morphology analysis, and rhythm interpretation. (ii) Heartcare-Bench, a systematic and multi-dimensional benchmark designed to evaluate diagnostic intelligence and guide the optimization of Medical Multimodal Large Language Models (Med-MLLMs) in ECG scenarios. and (iii) HeartcareGPT with a tailored tokenizer Bidirectional ECG Abstract Tokenization (Beat), which compresses raw multi-lead signals into semantically rich discrete tokens via duallevel vector quantization and query-guided bidirectional diffusion mechanism. Built upon Heartcare-220K, HeartcareGPT achieves strong generalization and SoTA performance across multiple clinically meaningful tasks. Extensive experiments demonstrate that Heartcare Suite is highly effective in advancing ECGspecific multimodal understanding and evaluation. Our project is available at https://github.com/Wznnnnn/Heartcare-Suite .

[Arxiv](https://arxiv.org/abs/2506.05831)