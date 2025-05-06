# 汽车软件开发自动化：生成式AI与形式化方法的结合

发布时间：2025年05月05日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在汽车软件开发中的应用，特别是在需求分析、代码生成和系统验证方面的自动化。它将LLMs与基于模型的工程相结合，展示了其在实际场景中的应用，因此属于LLM应用类别。` `汽车工业` `软件工程`

> Automating Automotive Software Development: A Synergy of Generative AI and Formal Methods

# 摘要

> 随着汽车工业向软件定义的车辆转型，对高效可靠的软件开发需求日益增长。然而，传统方法已显现出其局限性。生成式人工智能（GenAI），尤其是大型语言模型（LLMs），为汽车软件开发任务（如需求分析和代码生成）带来了自动化的新机遇。然而，汽车系统的复杂性要求软件组件无缝交互，这在软件集成和系统级验证方面仍具挑战。本文提出将GenAI与基于模型的工程相结合，以实现汽车软件开发的自动化。我们的方法利用LLMs将自由文本需求转化为事件链描述，并生成独立于平台的软件组件以实现所需功能。同时，基于事件链描述创建正式模型，支持系统验证，并通过中间件生成集成代码，将生成的软件组件无缝集成到整车系统中。这种方法不仅提升了开发自动化水平，还通过形式化分析增强了系统可靠性。作为概念验证，我们采用GPT-4o实现该方法，并在CARLA模拟环境中结合ROS2中间件进行了测试。我们在简单的自动紧急制动场景中对系统进行了评估。

> As the automotive industry shifts its focus toward software-defined vehicles, the need for faster and reliable software development continues to grow. However, traditional methods show their limitations. The rise of Generative Artificial Intelligence (GenAI), particularly Large Language Models (LLMs), introduces new opportunities to automate automotive software development tasks such as requirement analysis and code generation. However, due to the complexity of automotive systems, where software components must interact with each other seamlessly, challenges remain in software integration and system-level validation. In this paper, we propose to combine GenAI with model-driven engineering to automate automotive software development. Our approach uses LLMs to convert free-text requirements into event chain descriptions and to generate platform-independent software components that realize the required functionality. At the same time, formal models are created based on event chain descriptions to support system validation and the generation of integration code for integrating generated software components in the whole vehicle system through middleware. This approach increases development automation while enabling formal analysis to improve system reliability. As a proof of concept, we used GPT-4o to implement our method and tested it in the CARLA simulation environment with ROS2 middleware. We evaluated the system in a simple Autonomous Emergency Braking scenario.

[Arxiv](https://arxiv.org/abs/2505.02500)