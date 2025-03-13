# # 提升大型语言模型在硬件验证中的性能：一个创新的SystemVerilog断言数据集

发布时间：2025年03月11日

`LLM应用` `硬件验证` `电子设计自动化`

> Enhancing Large Language Models for Hardware Verification: A Novel SystemVerilog Assertion Dataset

# 摘要

> 硬件验证在现代SoC设计中至关重要，占据了约70%的开发时间。SystemVerilog断言确保了功能的正确性。然而，现有的工业实践依赖于手动生成断言，随着硬件系统的复杂化，这种方法变得越来越不可行。最近的研究表明，大语言模型（LLMs）可以自动化这一过程。然而，像GPT-4o这样的专有SOTA模型经常生成不准确的断言，并且需要昂贵的许可证，而较小的开源LLMs需要微调以处理HDL代码的复杂性。

为了解决这些问题，我们引入了**VERT**，一个开源数据集，旨在利用LLMs提升SystemVerilog断言的生成能力。VERT使学术界和工业界的研究人员能够微调开源模型，在准确性和效率上超越更大的专有模型，同时通过本地微调确保数据隐私并消除昂贵的许可证。该数据集通过从开源HDL存储库中系统地增强变量，生成与相应断言配对的合成代码片段。

实验结果表明，在OpenTitan、CVA6、OpenPiton和Pulpissimo等平台上，微调后的模型如Deepseek Coder 6.7B和Llama 3.1 8B优于GPT-4o，与基础模型相比提高了96.88%，与GPT-4o相比提高了24.14%。VERT可在https://github.com/AnandMenon12/VERT获取。

> Hardware verification is crucial in modern SoC design, consuming around 70% of development time. SystemVerilog assertions ensure correct functionality. However, existing industrial practices rely on manual efforts for assertion generation, which becomes increasingly untenable as hardware systems become complex. Recent research shows that Large Language Models (LLMs) can automate this process. However, proprietary SOTA models like GPT-4o often generate inaccurate assertions and require expensive licenses, while smaller open-source LLMs need fine-tuning to manage HDL code complexities. To address these issues, we introduce **VERT**, an open-source dataset designed to enhance SystemVerilog assertion generation using LLMs. VERT enables researchers in academia and industry to fine-tune open-source models, outperforming larger proprietary ones in both accuracy and efficiency while ensuring data privacy through local fine-tuning and eliminating costly licenses. The dataset is curated by systematically augmenting variables from open-source HDL repositories to generate synthetic code snippets paired with corresponding assertions. Experimental results demonstrate that fine-tuned models like Deepseek Coder 6.7B and Llama 3.1 8B outperform GPT-4o, achieving up to 96.88% improvement over base models and 24.14% over GPT-4o on platforms including OpenTitan, CVA6, OpenPiton and Pulpissimo. VERT is available at https://github.com/AnandMenon12/VERT.

[Arxiv](https://arxiv.org/abs/2503.08923)