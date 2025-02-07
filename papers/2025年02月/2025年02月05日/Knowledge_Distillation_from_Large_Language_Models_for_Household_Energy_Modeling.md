# 基于大型语言模型的知识蒸馏在家庭能源建模中的应用

发布时间：2025年02月05日

`LLM应用

**理由**：该论文主要探讨了如何将大型语言模型（LLMs）应用于能源建模，生成真实且文化敏感的家庭能源使用数据。研究涉及使用LLMs生成数据，并整合上下文信息，展示了LLMs在能源领域的实际应用。因此，该论文应归类为LLM应用。` `智能电网`

> Knowledge Distillation from Large Language Models for Household Energy Modeling

# 摘要

> 机器学习（ML）在智能电网研究中日益重要，但受限于隐私问题，获取真实且多样化的数据困难重重，这不仅拖慢了研究进展，也让能源行业对ML策略的采纳心存疑虑。我们提出将大型语言模型（LLMs）融入能源建模，生成真实、文化敏感且行为特定的家庭能源使用数据，覆盖全球多个地区。本研究对比了五种LLMs，系统生成了六个国家的家庭结构、天气模式和日常消费数据。通过四阶段方法，我们整合了包括文化活动、真实天气、HVAC操作及独特“能源签名”在内的上下文数据。此外，我们还探索了一种直接整合外部天气数据的策略，跳过中间建模步骤，确保数据输入的物理一致性。生成的数据集揭示了文化、气候和行为因素如何共同影响碳排放，为情景化能源优化提供了经济高效的途径。这一方法展示了提示工程与知识蒸馏如何助力可持续能源研究与气候缓解。源代码已发布在https://github.com/Singularity-AI-Lab/LLM-Energy-Knowledge-Distillation。

> Machine learning (ML) is increasingly vital for smart-grid research, yet restricted access to realistic, diverse data - often due to privacy concerns - slows progress and fuels doubts within the energy sector about adopting ML-based strategies. We propose integrating Large Language Models (LLMs) in energy modeling to generate realistic, culturally sensitive, and behavior-specific data for household energy usage across diverse geographies. In this study, we employ and compare five different LLMs to systematically produce family structures, weather patterns, and daily consumption profiles for households in six distinct countries. A four-stage methodology synthesizes contextual daily data, including culturally nuanced activities, realistic weather ranges, HVAC operations, and distinct `energy signatures' that capture unique consumption footprints. Additionally, we explore an alternative strategy where external weather datasets can be directly integrated, bypassing intermediate weather modeling stages while ensuring physically consistent data inputs. The resulting dataset provides insights into how cultural, climatic, and behavioral factors converge to shape carbon emissions, offering a cost-effective avenue for scenario-based energy optimization. This approach underscores how prompt engineering, combined with knowledge distillation, can advance sustainable energy research and climate mitigation efforts. Source code is available at https://github.com/Singularity-AI-Lab/LLM-Energy-Knowledge-Distillation .

[Arxiv](https://arxiv.org/abs/2502.03034)