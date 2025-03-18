# 统一建模语言代码生成：基于图表图像的多模态大型语言模型应用

发布时间：2025年03月15日

`LLM应用` `软件工程` `软件开发工具`

> Unified Modeling Language Code Generation from Diagram Images Using Multimodal Large Language Models

# 摘要

> 统一建模语言（UML）是一种标准化的可视化语言，广泛应用于软件系统设计的建模与文档化。尽管现有工具能够从UML代码生成图表，但如何从图像化的UML图逆向生成可执行代码仍是一个难题。本文提出了一种基于大型多模态语言模型的新方法，可自动从图像生成UML代码。我们创建了合成的UML活动图和时序图数据集用于模型的训练与测试。通过对比标准微调与LoRA技术，优化了基础模型的性能。实验中，我们测量了不同模型规模和训练策略下的代码生成准确性。结果表明，经过领域适配的多模态大模型在UML代码生成自动化方面表现出色，其中最佳模型在时序图上达到了BLEU得分为0.779，SSIM得分为0.942。这一突破将推动 legacy 系统的现代化进程，并显著减少软件开发流程中的手动工作量。

> The Unified Modeling Language is a standardized visual language widely used for modeling and documenting the design of software systems. Although many tools generate UML diagrams from UML code, generating executable UML code from image-based UML diagrams remains challenging. This paper proposes a new approach to generate UML code using a large multimodal language model automatically. Synthetic UML activity and sequence diagram datasets were created to train and test the model. We compared standard fine-tuning with LoRA techniques to optimize base models. The experiments measured code generation accuracy across different model sizes and training strategies. These results demonstrated that domain-adapted MM-LLMs perform for UML code generation automation, whereby, at the best model, it achieved BLEU and SSIM scores of 0.779 and 0.942 on sequence diagrams. This will enable the modernization of legacy systems and decrease the manual effort in software development workflows.

[Arxiv](https://arxiv.org/abs/2503.12293)