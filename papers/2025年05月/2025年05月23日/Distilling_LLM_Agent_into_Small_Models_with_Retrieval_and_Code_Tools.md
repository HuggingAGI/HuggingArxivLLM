# 将 LLM 代理知识蒸馏到小型模型中，借助检索与代码工具实现高效迁移

发布时间：2025年05月23日

`Agent` `教育技术`

> Distilling LLM Agent into Small Models with Retrieval and Code Tools

# 摘要

> 大型语言模型（LLMs）在复杂推理任务中表现出色，但其高昂的计算成本限制了实际应用。为解决这一问题，近期研究专注于通过教师LLMs的思维链（CoT）轨迹，将推理能力迁移到更小型的语言模型（sLMs）中。然而，这种方法在需要罕见事实知识或精确计算的场景中表现欠佳，因为sLMs常因能力限制而产生幻觉。为此，我们提出了Agent Distillation框架，旨在将不仅推理能力，还包括完整的任务解决行为，从配备检索和代码工具的LLM代理迁移到sLMs中。我们从两个互补角度优化了代理蒸馏：(1) 引入了名为first-thought prefix的提示方法，提升教师生成轨迹的质量；(2) 提出了一种自洽的动作生成方法，提高小型代理在测试时的鲁棒性。我们在涵盖事实和数学领域的八个推理任务上评估了该方法，包括领域内和领域外的泛化能力。结果显示，参数量仅为0.5B、1.5B和3B的小型sLMs，在使用CoT蒸馏微调后，其性能可与更高一级的1.5B、3B和7B模型相媲美，这证明了代理蒸馏在构建实用工具型小型代理方面的潜力。我们的代码可在https://github.com/Nardien/agent-distillation获取。

> Large language models (LLMs) excel at complex reasoning tasks but remain computationally expensive, limiting their practical deployment. To address this, recent works have focused on distilling reasoning capabilities into smaller language models (sLMs) using chain-of-thought (CoT) traces from teacher LLMs. However, this approach struggles in scenarios requiring rare factual knowledge or precise computation, where sLMs often hallucinate due to limited capability. In this work, we propose Agent Distillation, a framework for transferring not only reasoning capability but full task-solving behavior from LLM-based agents into sLMs with retrieval and code tools. We improve agent distillation along two complementary axes: (1) we introduce a prompting method called first-thought prefix to enhance the quality of teacher-generated trajectories; and (2) we propose a self-consistent action generation for improving test-time robustness of small agents. We evaluate our method on eight reasoning tasks across factual and mathematical domains, covering both in-domain and out-of-domain generalization. Our results show that sLMs as small as 0.5B, 1.5B, 3B parameters can achieve performance competitive with next-tier larger 1.5B, 3B, 7B models fine-tuned using CoT distillation, demonstrating the potential of agent distillation for building practical, tool-using small agents. Our code is available at https://github.com/Nardien/agent-distillation.

[Arxiv](https://arxiv.org/abs/2505.17612)