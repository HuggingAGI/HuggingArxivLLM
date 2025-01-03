# $C^2$: 基于LLM的图表生成的可扩展自动反馈

发布时间：2024年10月24日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）来解决生成高质量图表时面临的数据稀缺和扩展性问题。论文提出了一个包含自动反馈生成器和多样化数据集的框架，并通过实验验证了其有效性。这些内容属于LLM在实际应用中的使用和改进，因此归类为LLM应用。` `数据可视化`

> $C^2$: Scalable Auto-Feedback for LLM-based Chart Generation

# 摘要

> 使用大型语言模型生成高质量图表面临两大挑战：数据稀缺和人工扩展成本高。指令、数据和代码三元组不仅稀缺，且创建成本高，需要技术专长。为解决这一扩展性问题，我们推出了无需参考的自动反馈生成器，省去了昂贵的人工干预。我们的新框架$C^2$包含两个核心组件：（1）自动反馈提供者（ChartAF）和（2）多样化、无需参考的数据集（ChartUIE-8K）。实验结果令人振奋：首次实验中，74%的受访者强烈偏好反馈后的结果，10%的受访者表示偏好。第二次反馈后实验显示，ChartAF在九个基线模型中表现最佳。此外，ChartUIE-8K通过大幅增加查询、数据集和图表类型，分别提升了5982%、1936%和91%，显著增强了数据多样性。最后，LLM用户研究表明，94%的参与者更青睐ChartUIE-8K的查询，93%的参与者认为这些查询与现实用例高度契合。核心贡献已在匿名项目网站上开源，并附有丰富的定性示例。

> Generating high-quality charts with Large Language Models presents significant challenges due to limited data and the high cost of scaling through human curation. Instruction, data, and code triplets are scarce and expensive to manually curate as their creation demands technical expertise. To address this scalability issue, we introduce a reference-free automatic feedback generator, which eliminates the need for costly human intervention. Our novel framework, $C^2$, consists of (1) an automatic feedback provider (ChartAF) and (2) a diverse, reference-free dataset (ChartUIE-8K). Quantitative results are compelling: in our first experiment, 74% of respondents strongly preferred, and 10% preferred, the results after feedback. The second post-feedback experiment demonstrates that ChartAF outperforms nine baselines. Moreover, ChartUIE-8K significantly improves data diversity by increasing queries, datasets, and chart types by 5982%, 1936%, and 91%, respectively, over benchmarks. Finally, an LLM user study revealed that 94% of participants preferred ChartUIE-8K's queries, with 93% deeming them aligned with real-world use cases. Core contributions are available as open-source at an anonymized project site, with ample qualitative examples.

[Arxiv](https://arxiv.org/abs/2410.18652)