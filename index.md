---
title: 联机托管说明
permalink: index.html
layout: home
---

# 内容目录

本课程的演示基于加速器工具包“[演示指南和话题.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG)”中的演示。

在提供此培训之前，请务必熟悉演示。 对于多个实验室，将利用示例文档和预先创建的 Teams 会议和电子邮件。

- 请在[此处](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles)预下载所有示例文档。
- 按照[此处](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG)的说明设置 Teams 会议和电子邮件线程。
- 熟悉[此处](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012_interactive_experience.pdf)找到的交互式体验。

    > **注意：** 交互式体验 PDF 文件将直接下载到设备（下载文件夹）。

- 在[此处](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012-ENU-PowerPoint.pptx)查看最新的培训幻灯片组。

## 课程描述

探索 Microsoft Copilot 的变革潜力及其对组织效率的影响。 这种体验专为没有 Copilot 许可证的高管和业务领袖设计，深入探讨制作有效提示的艺术，提供交互式体验，并演示了适用于 Microsoft 365 的 Microsoft Copilot 如何无缝集成到日常业务工作流中，以提高工作效率和创新。

此交付的主要目标是：

- 教授如何制作有效的提示
- 演示 Microsoft Copilot（Web 范围）并引导参与者完成交互式体验
- 演示适用于 Microsoft 365 的 Microsoft Copilot - Microsoft Copilot（工作范围）、Word、Outlook 和 Teams
- 邀请参与者下载并尝试 Microsoft Copilot for Mobile

## 课时安排（未最终确定） 

| # | 主题                                 | 详细信息                                                                                          | 总时间      |
|---|---------------------------------------|--------------------------------------------------------------------------------------------------|-----------------|
| 1 | 在适用于 Microsoft 365 的 Copilot 中创制有效提示 | - 提示的艺术页面 <br> - 生成提示页面 <br> - Copilot 实验室页面 | 5-10 分钟    |
| 2 | Microsoft Copilot 网页版          | - 演示 Microsoft Copilot（Web 模式） <br> - 交互式的体验  <br> - 共享“体验”页面 | 35 分钟      |
| 3 | 工作中的适用于 Microsoft 365 的 Copilot     | - Microsoft Graph 页面 <br> - 在 Word 中演示 Copilot、Microsoft Copilot（工作模式）、Outlook 中的 Copilot 和 Teams 中的 Copilot <br> - 推荐页面 <br> - Microsoft Copilot on Mobile 页面 | 25 分钟      |
|   |                                       |                                                                                                  | **总时间可能推送 70 分钟** |


下面列出了每个演示的超链接。

## 演示

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| 演示 |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
