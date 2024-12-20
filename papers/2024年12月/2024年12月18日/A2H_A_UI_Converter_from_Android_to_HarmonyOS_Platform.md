# A2H：一款实现从 Android 到 HarmonyOS 平台的 UI 转换工具

发布时间：2024年12月18日

`LLM应用` `移动开发` `用户界面`

> A2H: A UI Converter from Android to HarmonyOS Platform

# 摘要

> 随着智能手机愈发重要，开发人员面临为多个平台（如安卓、iOS 与鸿蒙 OS）分别创建应用的挑战，致使开发成本上升、迭代周期延长。一个可行的办法是在一个平台开发应用，然后自动转换到其他平台，减少单独开发的工作量。然而，由于布局结构和开发范式存在显著差异，比如安卓的 XML 布局文件和鸿蒙 OS 的 ArkUI 框架的不同，平台间的用户界面（UI）迁移难度颇大。手动转换 UI 既耗时又易错，效率还低，所以需要自动化解决方案来简化流程，实现从安卓到鸿蒙 OS 的无缝迁移。为应对此挑战，我们推出了 A2H 转换器，这是一款用于将安卓 UI 迁移至鸿蒙 OS 的自动化工具。该工具借助大型语言模型（LLM）驱动的多智能体框架，把安卓 XML 布局转换为鸿蒙 OS 的 ArkUI 布局。通过结合决策规则的 RAG，系统将安卓 UI 组件映射为 ArkUI 等效组件，同时反射机制持续提升转换精度。A2H 转换器处理项目级布局，保证多个文件的一致性，解决复杂的 UI 逻辑。对从 GitHub 收集的六个安卓应用所做的实验表明，我们的 A2H 转换器在组件、页面和项目级别，迁移成功率分别超过 90.1%、89.3%和 89.2%。演示视频可在  查看。该工具可在 http://124.70.54.129:37860/ 获取。

> With the growing importance of smartphones, developers face the challenge of creating separate applications for multiple platforms (e.g., Android, iOS, and HarmonyOS), leading to increased development costs and longer iteration cycles. One potential solution is to develop an app on one platform and then automatically convert it to other platforms, reducing the need for separate development efforts. However, migrating user interfaces (UIs) between platforms is particularly challenging due to significant differences in layout structures and development paradigms, such as the disparity between XML layout files in Android and ArkUI framework in HarmonyOS. Manual conversion of UIs is time-consuming, error-prone, and inefficient, necessitating an automated solution to streamline the process and enable seamless migration from Android to HarmonyOS. To address this challenge, we propose the A2H Converter, an automated tool for migrating Android UIs to HarmonyOS. The tool employs an large language model (LLM)-driven multi-agent framework to convert Android XML layouts into HarmonyOS ArkUI layouts. Using the RAG combing with decision rules, the system maps Android UI components to ArkUI equivalents, while a reflective mechanism continuously improves conversion accuracy. A2H Converter handles project-level layouts, ensuring consistency across multiple files and addressing complex UI logic. Experiments on six Android applications collected from GitHub demonstrate that our A2H Converter achieves a migration success rate of over 90.1%, 89.3%, and 89.2% at the component, page, and project levels, respectively. The demo video is available at. The tool is available at http://124.70.54.129:37860/.

[Arxiv](https://arxiv.org/abs/2412.13693)