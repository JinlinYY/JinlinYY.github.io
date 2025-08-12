---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume

---

{% include base_path %}

我是河北工业大学人工智能与数据科学学院控制科学与工程专业在读博士生，我的研究方向是多模态数据融合与智能计算。

## 教育经历

* **2022.9 - 今**：河北工业大学，控制科学与工程专业，硕博连读生，预计2028年毕业
* **2018.9 - 2022.6**：天津中德应用技术大学，自动化专业，学士

## 技能

* **硬件开发**：ZYNQ开发（ARM+FPGA异构开发、HLS、Verilog），单片机开发（STM32、GD32），电路设计（AD）等
* **人工智能**：图神经网络、卷积神经网络、Transformer、多模态融合、FPGA加速、神经网络轻量化（剪枝、蒸馏、量化）等

## 论文

1.  **Jinlin Ye**, Yuhan Liu, Shangjie Ren, Changjun Wang\*, Yidong Zhou\*, Liang Yang\*, Wei Zhang\*, “A multimodal information-interconnected network for medication guidance in HR+/HER2- breast cancer treatment,” *Information Fusion*, vol. 124, p. 103326, 2025, doi: 10.1016/j.inffus.2025.103326.（中科院1区Top，影响因子15.5）
2.  **Jinlin Ye**, Yuhan Liu, Haiyong Chen, Changjun Wang\*, Yidong Zhou\*, Liang Yang\*, Wei Zhang\*, “Edge Computing Accelerator for Real-Time Defect Detection of Photovoltaic Panel on Lightweight FPGAs,” *IEEE Transactions on Instrumentation and Measurement*, vol. 74, pp. 1–15, 2025, doi: 10.1109/TIM.2025.3563001.（中科院2区，影响因子5.9）
3.  **Jinlin Ye**#, Yuhan Liu#, Liang Yang\*, Haiyong Chen, Changjun Wang\*, Yidong Zhou\*, Wei Zhang\*, “A Lightweight Edge Computing Neural Network for Online Photovoltaic Defect Inspection,” *IEEE Transactions on Instrumentation and Measurement*, vol. 74, pp. 1–14, 2025, doi: 10.1109/TIM.2025.3546382.（中科院2区，影响因子5.9）
4.  Yuhan Liu#, **Jinlin Ye**#, Zecheng He, Mingyue Wang, Changjun Wang\*, Jie Lang\*, Yidong Zhou\*, Wei Zhang\*, “Deep learning assisted non-invasive lymph node burden evaluation and CDK4/6i administration in luminal breast cancer,” *iScience*, vol. 28, p. 112849, 2025, https://doi.org/10.1016/j.isci.2025.112849.（中科院2区，影响因子4.1）
5.  Song He#, Changjun Wang#*, **Jinlin Ye**, Yuhan Liu, Mingyue Wang, Yidong Zhou∗, Wei Zhang∗, “IHPE: A Lightweight Hand Pose Estimation Network for Surgical Motion Capture in Medical Education,” IEEE Sensors Journal, vol. 25, no. 15, pp. 28503-28517, 2025, doi: 10.1109/JSEN.2025.3577665. （中科院3区，影响因子4.5）
6.  **Jinlin Ye**, Wei Zhang*, “A Scalable ARM+FPGA-Based CNN Accelerator with Limited Hardware Resources,” 2023 42nd Chinese Control Conference (CCC), 2023, pp.2498-2503, doi: 10.23919/CCC58697.2023.10241078. （会议论文）
7.  **Jinlin Ye**, Wei Zhang*, “FCSA: An ARM+FPGA-based Software and Hardware Collaboration DNN Classifier,” 2024 8th International Symposium on Computer Science and Intelligent Control (ISCSIC), 2024, pp.496-500, doi: 10.1109/ISCSIC64297.2024.00106. （会议论文）
8.   Shouhang Yuan, **Jinlin Ye** and Wei Zhang*, “High Intensity and Uniform Magnetic Field Sensor for Trenchless Underground Cable Detection," 2024 China Automation Congress (CAC), 2024, pp. 4728-4732, doi: 10.1109/CAC63892.2024.10864749. （会议论文）


## 专利：
1. 张潍, **叶金霖**, 陈亚东, 一种基于Winograd的异构目标检测网络算子加速器, 202410370903.2, 2024-08-09.
2. 张潍, **叶金霖**, 一种基于ARM和FPGA的通用标准卷积算子加速器, 202310789376.4, 2023-08-29.


## 项目经历

* **原材料关键质量指标对生产成本的量化影响测算模型构建** (2025年-至今)
    * **项目概览**：围绕“原料质量 → 工艺参数 → 成本/能耗”的因果链，建立机理—数据协同框架，量化石灰石/碳材等关键指标（CaO、MgO、SiO₂、固定碳等）对生产成本与效率的影响，并支撑质量验收与采购决策；
    * **技术方案**：先构建电石法生产的机理模型（物料/能量守恒、理论用量与吸热估算），再以Transformer模型构建残差对机理偏差进行数据驱动校正；
    * **个人职责**：与甲方沟通需求、总体方案设计、代码实现。


* **手术动作视觉捕捉与教学评估** (2024年-2025年)
    * **项目概览**：面向传统“师带徒”教学纠错不及时的问题，提出低成本、可移动部署的手术手部姿态估计方法，实时捕捉结扎等关键动作并给出客观反馈，用于教学与术中辅助；
    * **系统实现**：基于关键点检测算法，构建教学评估系统，从视频流提取手部关键点、重建轨迹，利用 快速傅里叶变换评估打结动作周期性，并以加速度标准差衡量平滑性，支持教师和学生对比演示；
    * **个人职责**：方案设计、技术路线设计、代码实现、论文撰写。

* **管段式电磁流量计研发** (2022年-2025年)
    * **项目概览**：本项目致力于基于法拉第电磁感应定律，开发一款高精度管段式电磁流量计。通过在管段中施加精确控制的交变磁场，感应并采集流体产生的微弱电动势，经信号放大与数据处理，实现流速及流量的精准测量。
    * **技术核心**：系统采用Buck电路、H桥及PI控制算法构建低频矩形波恒流励磁方案，主控芯片选用GD32系列微控制器，采集电路采用仪表放大器、带通滤波器及单片机内部ADC方案。
    * **通信集成**：内置RS485 (Modbus-RTU协议)、4-20mA模拟输出以及蓝牙等多模通信接口，满足不同工业场景的数据传输需求。
    * **个人职责**：**本人负责该项目全部内容**，方案设计、原理图设计、PCB设计、采购、电路焊接、电路调试、单片机程序开发、系统调试、现场测试、文档撰写全部环节。

* **光伏板缺陷检测与FPGA部署** (2022年-2024年)
    * **项目概览**：面向无人机光伏电站巡检与光伏板工厂产线的边缘场景，构建轻量级缺陷检测网络，设计FPGA加速器，实现可落地的在线缺陷检测；
    * **算法核心**：设计轻量检测器，采用结构重参数化（训练多分支、推理单分支）去冗余，结合结构化剪枝压缩模型，并以知识蒸馏稳定精度，在基本保持 mAP 的前提下显著下降参数量与 FLOPs、提升端侧 FPS；
    * **硬件核心**：基于 ZYNQ7020（ARM+FPGA） 自研实时检测加速器，ARM 侧负责任务调度与数据搬运，FPGA 侧实施算子级加速。以 Winograd 卷积为核心，构建可配置的处理单元阵列，配合行缓冲、乒乓缓冲和分块因子实现算传并行与带宽复用，通过 AXI4-Stream和DMA高速通道与片上/片外存储协同；
    * **个人职责**：负责全部内容，包括方案设计、算法研发、代码实现、硬件系统架构设计、模型部署、论文撰写。


