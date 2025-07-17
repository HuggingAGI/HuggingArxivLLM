# MATE：基于大型语言模型的多智能体翻译环境，专为可及性应用打造

发布时间：2025年07月15日

`Agent` `医疗保健` `可访问性`

> MATE: LLM-Powered Multi-Agent Translation Environment for Accessibility Applications

# 摘要

> 可访问性仍是当今社会的重要议题，许多技术未能充分满足所有用户需求。现有的多智能体系统（MAS）常因闭源设计缺乏定制化，难以全面协助有需求的用户。残障人士在与数字环境互动时往往面临诸多障碍。我们推出MATE，一个多模态可访问性MAS，根据用户需求进行模态转换。该系统通过将数据转换为易理解的格式，为残障人士提供有力支持。例如，视力不佳的用户收到图片时，系统会将其转换为音频描述。MATE可应用于医疗保健等多个领域，成为各类用户的得力助手。系统支持从LLM API到自定义ML分类器等多种模型，确保灵活性与硬件兼容性。本地运行保障了敏感信息的隐私安全。此外，该框架可与机构技术（如数字医疗服务）集成，实现实时协助。我们还推出ModCon-Task-Identifier模型，能精准提取用户输入中的模态转换任务。实验表明，该模型在自定义数据集上优于其他LLMs和统计模型。我们的代码和数据可在GitHub上获取。

> Accessibility remains a critical concern in today's society, as many technologies are not developed to support the full range of user needs. Existing multi-agent systems (MAS) often cannot provide comprehensive assistance for users in need due to the lack of customization stemming from closed-source designs. Consequently, individuals with disabilities frequently encounter significant barriers when attempting to interact with digital environments. We introduce MATE, a multimodal accessibility MAS, which performs the modality conversions based on the user's needs. The system is useful for assisting people with disabilities by ensuring that data will be converted to an understandable format. For instance, if the user cannot see well and receives an image, the system converts this image to its audio description. MATE can be applied to a wide range of domains, industries, and areas, such as healthcare, and can become a useful assistant for various groups of users. The system supports multiple types of models, ranging from LLM API calling to using custom machine learning (ML) classifiers. This flexibility ensures that the system can be adapted to various needs and is compatible with a wide variety of hardware. Since the system is expected to run locally, it ensures the privacy and security of sensitive information. In addition, the framework can be effectively integrated with institutional technologies (e.g., digital healthcare service) for real-time user assistance. Furthermore, we introduce ModCon-Task-Identifier, a model that is capable of extracting the precise modality conversion task from the user input. Numerous experiments show that ModCon-Task-Identifier consistently outperforms other LLMs and statistical models on our custom data. Our code and data are publicly available at https://github.com/AlgazinovAleksandr/Multi-Agent-MATE.

[Arxiv](https://arxiv.org/abs/2506.19502)