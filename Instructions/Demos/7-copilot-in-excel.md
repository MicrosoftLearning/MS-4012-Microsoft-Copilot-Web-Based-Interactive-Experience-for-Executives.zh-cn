---
demo:
  title: 演示：Excel 中的 Copilot
---

[返回到索引](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Excel 中的 Microsoft 365 Copilot

## 演示设置

下载 Excel 示例文档 [**EV_Charger_Sales_Analysis_v1.xlsx**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/raw/refs/heads/master/Resourcefiles/EV_Charger_Sales_Analysis_v1.xlsx)。 你将使用此文件运行本指南中概述的演示步骤。


## 讲座要点

Excel 中的 Microsoft 365 Copilot 使每个人都能成为数据分析师，让你能够快速了解关键趋势、性能指标以及推动业务或项目成果的因素。

无论你处理的是销售数据、财务报告、客户反馈还是操作指标，Copilot 都可以帮助你整理和分析信息，从多个来源的复杂数据集中提供见解。

借助 Copilot，可以轻松提取有意义的见解，以便做出更好的决策，无论数据类型或分析的复杂性如何。

## 演示步骤

> **备注：** 在继续操作之前，请确保打开 Excel 文件 **EV_Charger_Sales_Analysis_v1.xlsx**。

1. 在 Excel 文件中，**导航到“按产品划分的销售额”选项卡**。

1. 使用 Copilot 计算每月收入：  

   首先，弄清楚哪个业务类别能带来最多收入。 此工作表包含三年的销售数据，其中数千行显示了按产品和月份划分的销售情况。 虽然这是一项常规任务，但如此大的数据量可能会难以处理。 可以让 Copilot 快速计算按产品划分的每月收入。

   使用以下提示：

   ```text
   Calculate monthly revenue by product and add a column with total revenue - refer to the Prices worksheet.
   ```
    - Copilot 知道如何执行此操作，以及跨选项卡引用哪些数据。 
    - Copilot 会制定如何计算这些数字的计划，然后执行该计划并显示其工作情况，同时提示你提出问题或在其得出的解决方案上进行迭代。
    - 单击“**+插入列**”，然后导航回“**按产品划分的销售额**”选项卡。
   

1. 通过在 Copilot 窗格中输入以下提示，使用 Copilot 分析收入：

    ```text
    What is the total revenue for each category so far in 2024?
    ```

    - Copilot 将计算这些数字并创建可添加到工作簿的条形图。
    - 单击“**+添加到新工作表**”，然后返回“**按产品划分的销售额**”选项卡。

1. 现在，通过输入以下提示，使用 Copilot 突出显示销售额低的产品：

    ```text
    Highlight rows where the value in column H is less than $100K.
    ```

    - Copilot 将应用条件格式，帮助你识别不符合标准的产品。

1. **导航到“评论”选项卡**以分析客户反馈。

1. 通过输入以下提示，要求 Copilot 总结最受关注的问题：

    ```text
    Summarize the top 3 customer concerns we should focus on.
    ```

    - Copilot 将分析反馈，并显示客户最关心的三大问题。 看起来充电速度是一个新出现的问题。

1. 接下来，通过输入以下提示突出显示提及充电速度的评论：

    ```text
    Highlight reviews that mention issues related to charging speeds.
    ```

    - Copilot 将突出显示数据集中的所有相关评论。

### 总结

在 Copilot 的帮助下，你分析了复杂的数据集，并获得了有关产品性能和客户反馈的见解。 这些见解可用于指导你的下一次业务评审。
