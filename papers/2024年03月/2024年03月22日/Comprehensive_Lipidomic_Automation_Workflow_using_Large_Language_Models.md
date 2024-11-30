# 借助大型语言模型实现全方位脂质组学自动化流程

发布时间：2024年03月22日

`Agent` `脂质组学` `生物信息学`

> Comprehensive Lipidomic Automation Workflow using Large Language Models

# 摘要

> 面对脂质组学产出的海量数据，手动注解及解读颇为困难，而脂质复杂的化学结构及其结构异构体的存在更是加剧了解读难题。尽管市面上已有一些商用和开源软件可用于目标脂质的识别，但往往缺少自动化方法构建流程及与统计学和生物信息学工具的整合功能。为此，我们研发了“全面脂质组学自动化工作流程平台CLAW”，它集成了定制化的多反应监测（MRM）策略，可实现对脂质数据的解析、详尽统计分析以及精准注解。CLAW平台内含多个功能模块，甚至能够借助OzESI-MRM技术精确定位不饱和脂质中的碳-碳双键位置。为了验证CLAW平台上自动化流程的有效性，我们在生物和非生物样本上运用传统及OzESI-MRM技术采集了大规模脂质组学数据。具体而言，针对18-24个月大的阿尔茨海默病小鼠和相应年龄匹配的野生型对照小鼠不同脑区提取的脂滴，我们运用10种基于MRM质谱方法设计的1497个转化对进行脂质特征描述。另外，通过OzESI-MRM技术，我们还从菜籽油样品中获得了特定碳-碳双键结构的三酰甘油谱图。同时，我们创新性地引入了融合大型语言模型的人工智能代理，开发了一个一体化的语言用户界面，用户可通过聊天机器人终端与CLAW平台互动，完成统计学和生物信息学分析。未来，我们期待CLAW流水线能在高通量脂质结构鉴定任务中大显身手，助力用户快速创建覆盖数据获取至基于AI代理的生物信息学分析的全自动脂质组学工作流程。

> Lipidomics generates large data that makes manual annotation and interpretation challenging. Lipid chemical and structural diversity with structural isomers further complicates annotation. Although, several commercial and open-source software for targeted lipid identification exists, it lacks automated method generation workflows and integration with statistical and bioinformatics tools. We have developed the Comprehensive Lipidomic Automated Workflow (CLAW) platform with integrated workflow for parsing, detailed statistical analysis and lipid annotations based on custom multiple reaction monitoring (MRM) precursor and product ion pair transitions. CLAW contains several modules including identification of carbon-carbon double bond position(s) in unsaturated lipids when combined with ozone electrospray ionization (OzESI)-MRM methodology. To demonstrate the utility of the automated workflow in CLAW, large-scale lipidomics data was collected with traditional and OzESI-MRM profiling on biological and non-biological samples. Specifically, a total of 1497 transitions organized into 10 MRM-based mass spectrometry methods were used to profile lipid droplets isolated from different brain regions of 18-24 month-old Alzheimer's disease mice and age-matched wild-type controls. Additionally, triacyclglycerols (TGs) profiles with carbon-carbon double bond specificity were generated from canola oil samples using OzESI-MRM profiling. We also developed an integrated language user interface with large language models using artificially intelligent (AI) agents that permits users to interact with the CLAW platform using a chatbot terminal to perform statistical and bioinformatic analyses. We envision CLAW pipeline to be used in high-throughput lipid structural identification tasks aiding users to generate automated lipidomics workflows ranging from data acquisition to AI agent-based bioinformatic analysis.

[Arxiv](https://arxiv.org/abs/2403.15076)