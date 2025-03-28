# 个人介绍



<table>
  <tr>
    <td>

   
&emsp; 我的主要研究兴趣方向是以数据驱动型的分析，从明确的数据任务出发来探索有效的模型和理论。我希望能通过人工智能技术探索基于**多模态**数据的医疗辅助诊断方法以及更简单、高效的可量化分析策略，主要兴趣方向包含机器学习方向的多模态模型、**强化学习** 以及统计方向的**因果推断**。

&emsp; 关于学术研究的看法，我很喜欢一句话就是“**往前走不是消除不确定性，而是学会习惯不确定性**”。

&emsp; 我想，一路走来的成长教会我的就是脱离被潮水被动拍打的习惯，然后学会划动自己的桨，在潮汐中找到自己的节奏，静下心来做一些真正**有意义**的事情。

&emsp; 我很喜欢右边的这一句简短的拉丁文谚语，它作为我的微信朋友圈背景并激励着我走过很多艰难的时刻。
    </td>
    <td align="center">
     <img src="https://github.com/user-attachments/assets/3cb18d53-5f69-4803-b6b2-8e33482efbe3" width="700px">
    </td>
  </tr>
</table>

以下内容的目录如下：

**一、[🫡有趣的小项目](#有趣的小项目)**

**二、[📝课程设计](#课程设计)**

# 🫡有趣的小项目

### 🌠接住高速移动物体游戏的自动化辅助脚本

<table>
  <tr>
    <td align="center">
    <img src="/img/tangyuan.gif" alt="GIF 1" width="450">
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/66a46fbc-da6f-4abf-bf53-af611226f6cb" alt="GIF 2" width="140">
    </td>
  </tr>
</table>

本项目通过实时屏幕捕捉与OpenCV**图像识别**技术，结合**自适应反应距离算法**和鼠标自动化控制，为《汤圆大作战》游戏开发了高效辅助工具。脚本可智能识别加分汤圆、炸弹等道具，动态调整接取策略，在高速移动场景下实现精准操作，最高得分达11000+分，显著超越人工极限。支持A**DB**投屏控制，包含多级性能优化，助力轻松登顶全行前四~

项目链接：https://github.com/Augustlnx/Game-Automation-Assistant-with-Computer-Vision

# 📝课程设计

### ✨统计计算03（2024.9-2025.1） ——0-1膨胀负二项回归模型的贝叶斯参数估计

<div align=center>
<img src="https://github.com/user-attachments/assets/6389477a-64f0-4fb0-8d91-6878e916cc9b" width="400px">
</div>

本项目基于贝叶斯方法，针对**0-1膨胀负二项回归模型**（ZOINB）的参数估计问题展开研究，使用**Gibbs抽样**与**M-H算法**对模型参数进行推断，并结合模拟数据验证方法的有效性。

项目链接：https://github.com/Augustlnx/Statistical-Computing-Course-Project03

### ✨统计计算02（2024.9-2025.1） ——强化学习下随机化井字棋



<table>
  <tr>
    <td align="center">
    <img src="https://github.com/user-attachments/assets/f842922c-367b-43db-b4e9-c35f77c06e65" alt="GIF 1" width="500">
    </td>
    <td align="center">
      <img src="img/井字棋示例1.gif" alt="GIF 1" width="200">
    </td>
    <td align="center">
      <img src="img/井字棋示例2.gif" alt="GIF 2" width="200">
    </td>
  </tr>
</table>




本项目利用**强化学习Q-learning**算法实现一个变体的井字棋游戏。游戏包含经典的 3×3 和 4×3 井字基本策略探索分析，以及考虑**引入随机性**后如何制定合适的拒绝策略。项目通过对比三种不同的AI算法（Random，**MinMax**，**RL**），分析它们在**无随机性**和**有随机性**条件下的表现及关于拒绝策略的重要结论，最后提供了完整的实验报告和可交互的游戏界面，供用户体验和研究。

项目链接：https://github.com/Augustlnx/Statistical-Computing-Course-Project02

---

### ✨统计计算01（2024.9-2025.1） ——Bootstrap与Jackknife方法比较

本项目通过理论与实证分析，系统比较了 **Bootstrap** 和 **Jackknife** 两种重抽样方法在不同场景下的性能差异，重点关注 **小样本条件** 和 **复杂统计量估计** 两类问题。

项目链接：https://github.com/Augustlnx/Statistical-Computing-Course-Project01



---

### ✨抽样调查（2024.9-2025.1）——抽样方法综合比较与LGBoost回归插补法效果比较

本项目是XMU大三上课程《抽样调查》课程设计，主要关注**抽样技术**和**填补方法**在调查数据分析中的应用。项目首先涵盖了简单随机抽样、分层抽样、不等概率抽样、整群抽样、系统抽样等多种抽样方法在相同数据集上的估计精度随机模拟结果对比，然后提出了基于Lasso和**LightGBM**的回归填补方法并进一步比较有效性。

项目链接：https://github.com/Augustlnx/Sampling-Survey-Course-Project

---

### ✨博弈论（2024.6-2024.7）——沙滩占位博弈模型
本项目是XMU短学期课程《博弈论》课程论文——关于博弈论在**沙滩占位模型**中的应用研究。项目探讨了在不同顾客分布假设下，多个小贩如何通过选择位置来最大化顾客数量，并分析了不同场景下的**纳什均衡策略**。

项目链接：https://github.com/Augustlnx/Game-theory-Course-Project

---

### ✨随机过程（2023.9-2024.1）——大富翁中的随机过程

<div align=center>
<img src="https://github.com/user-attachments/assets/e9fae56b-96c4-4a33-9439-1c537560cac1" width="400px">
</div>

这是一个XMU大二下课程《应用随机过程》 的课程论文，本文只回顾并详解了经典书籍 ***Essentials of Stochastic Processes (Rick Durrett .2ndEdition)*** 和 ***STOCHASTIC PROCESSES (Ross .2ndEdition)*** 中提到的**大富翁游戏**的经典例题，并通过**马尔科夫链**和**离出概率**分析了一些游戏中的简单情形下的问题，并最后通过**鞅**理论探讨了一种简化的资金流动模型和破产时间估计。

项目链接：https://github.com/Augustlnx/Stochastic-Processes-Course-Project

---

# 大创项目
## 机器学习方法在金融数据中的应用
## AI大模型辅助数学推理及其在本科概率论解题的实践初探


#
