# LayerCraft：借助CoT推理与分层对象整合，提升文本图像生成能力

发布时间：2025年03月25日

`Agent` `人工智能` `创意设计`

> LayerCraft: Enhancing Text-to-Image Generation with CoT Reasoning and Layered Object Integration

# 摘要

> 文本到图像生成（T2I）已成为一个具有广泛应用的关键研究领域。然而，现有方法在处理复杂空间关系和多概念精细控制方面仍面临挑战。许多现有方法需要对架构进行大幅修改、大量训练，或需要专家级的提示工程。为了解决这些问题，我们提出了	extbf{LayerCraft}，一个利用大型语言模型（LLMs）作为自主代理的自动化框架，专注于结构化程序生成。LayerCraft让用户能够轻松自定义图像中的对象，并支持叙述驱动的创作，几乎无需额外努力。系统的核心是一个协调器代理，它负责整个生成过程，并与两个专门代理协同工作：	extbf{ChainArchitect}，通过链式思维（CoT）推理生成依赖关系感知的3D布局，实现精确的实例级别控制；以及	extbf{Object-Integration Network (OIN)}，基于文本提示，通过LoRA微调在预训练的T2I模型上，将对象无缝融入图像的指定区域，而无需改变架构。大量实验表明，LayerCraft在多概念定制到叙事生成等应用中表现出卓越的 versatility。通过为非专业人士提供对T2I生成的直观、精确控制，我们的框架使创意图像创作更加普及。我们的代码将在github.com/PeterYYZhang/LayerCraft上发布，待接受后。


> Text-to-image generation (T2I) has become a key area of research with broad applications. However, existing methods often struggle with complex spatial relationships and fine-grained control over multiple concepts. Many existing approaches require significant architectural modifications, extensive training, or expert-level prompt engineering. To address these challenges, we introduce \textbf{LayerCraft}, an automated framework that leverages large language models (LLMs) as autonomous agents for structured procedural generation. LayerCraft enables users to customize objects within an image and supports narrative-driven creation with minimal effort. At its core, the system includes a coordinator agent that directs the process, along with two specialized agents: \textbf{ChainArchitect}, which employs chain-of-thought (CoT) reasoning to generate a dependency-aware 3D layout for precise instance-level control, and the \textbf{Object-Integration Network (OIN)}, which utilizes LoRA fine-tuning on pre-trained T2I models to seamlessly blend objects into specified regions of an image based on textual prompts without requiring architectural changes. Extensive evaluations demonstrate LayerCraft's versatility in applications ranging from multi-concept customization to storytelling. By providing non-experts with intuitive, precise control over T2I generation, our framework democratizes creative image creation. Our code will be released upon acceptance at github.com/PeterYYZhang/LayerCraft

[Arxiv](https://arxiv.org/abs/2504.00010)