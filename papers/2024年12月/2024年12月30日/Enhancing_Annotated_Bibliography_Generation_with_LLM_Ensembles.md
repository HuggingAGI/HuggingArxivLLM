# 利用 LLM 集成提升注释参考书目生成能力

发布时间：2024年12月30日

`LLM应用` `注释生成`

> Enhancing Annotated Bibliography Generation with LLM Ensembles

# 摘要

> 这项工作提出了一种借助大型语言模型（LLM）集成来提升注释参考书目生成效果的新颖方法。具体而言，引入了在不同角色（如可控文本生成、评估及总结）中发挥作用的多个LLM，并运用系统方法加以验证，以增强学术任务中的模型表现。利用不同的LLM参数获取生成文本的集成中的输出多样性，接着由一个LLM充当评判者来评估相关性、准确性和连贯性。通过多种组合策略所选的响应随后经总结和冗余去除技术进行合并与优化。初步的实验验证显示，与单个响应相比，LLM集成的组合输出增强了连贯性和相关性，使注释质量提升了38%，内容冗余降低了51%，从而凸显了在维持高质量标准的同时实现复杂学术任务自动化的潜力。

> This work proposes a novel approach to enhancing annotated bibliography generation through Large Language Model (LLM) ensembles. In particular, multiple LLMs in different roles -- controllable text generation, evaluation, and summarization -- are introduced and validated using a systematic methodology to enhance model performance in scholarly tasks. Output diversity among the ensemble that generates text is obtained using different LLM parameters, followed by an LLM acting as a judge to assess relevance, accuracy, and coherence. Responses selected by several combining strategies are then merged and refined through summarization and redundancy removal techniques. The preliminary experimental validation demonstrates that the combined outputs from the LLM ensemble improve coherence and relevance compared to individual responses, leading to a 38% improvement in annotation quality and a 51% reduction in content redundancy, thus highlighting the potential for automating complex scholarly tasks while maintaining high-quality standards.

[Arxiv](https://arxiv.org/abs/2412.20864)