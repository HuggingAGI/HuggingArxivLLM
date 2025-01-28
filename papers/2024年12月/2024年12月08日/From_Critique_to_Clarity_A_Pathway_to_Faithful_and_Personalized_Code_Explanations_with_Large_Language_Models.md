# 从批评到清晰：利用大型语言模型实现忠实且个性化的代码解释

发布时间：2024年12月08日

`Agent

理由：这篇论文描述了一种利用多个LLM代理协作生成代码解释的方法。该方法结合了提示增强、自我纠正机制、个性化内容定制以及与外部工具的交互，强调了多个代理之间的协作和交互。因此，这篇论文更适合归类为Agent，因为它主要关注的是多个代理的协作和交互机制，而不是单纯的LLM应用或理论。` `软件开发` `人工智能`

> From Critique to Clarity: A Pathway to Faithful and Personalized Code Explanations with Large Language Models

# 摘要

> 在软件开发中，提供精准且个性化的代码解释对技术专家和业务利益相关者都至关重要。技术专家能借此提升理解和解决问题的能力，而业务利益相关者则能更好地把握项目的一致性和透明度。然而，生成此类解释往往耗时且困难。本文提出了一种创新方法，利用大型语言模型（LLMs）的强大能力，生成忠实且个性化的代码解释。我们的方法结合了提示增强、自我纠正机制、个性化内容定制以及与外部工具的交互，并通过多个LLM代理的协作实现。通过自动和人工评估，我们证明了该方法不仅能生成准确的解释，还能根据用户偏好进行定制。研究结果表明，该方法显著提升了代码解释的质量和相关性，为开发人员和利益相关者提供了宝贵的工具。

> In the realm of software development, providing accurate and personalized code explanations is crucial for both technical professionals and business stakeholders. Technical professionals benefit from enhanced understanding and improved problem-solving skills, while business stakeholders gain insights into project alignments and transparency. Despite the potential, generating such explanations is often time-consuming and challenging. This paper presents an innovative approach that leverages the advanced capabilities of large language models (LLMs) to generate faithful and personalized code explanations. Our methodology integrates prompt enhancement, self-correction mechanisms, personalized content customization, and interaction with external tools, facilitated by collaboration among multiple LLM agents. We evaluate our approach using both automatic and human assessments, demonstrating that our method not only produces accurate explanations but also tailors them to individual user preferences. Our findings suggest that this approach significantly improves the quality and relevance of code explanations, offering a valuable tool for developers and stakeholders alike.

[Arxiv](https://arxiv.org/abs/2501.14731)