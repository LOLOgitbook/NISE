# NISE

## 文献整理

Page actionsJoint Near Field Uplink Communication and Localization Using Message Passing-Based Sparse Bayesian LearningComment系统模型和问题表述：Comment多个基站 (BS) 覆盖的区域，其中每个基站都有一个大的天线阵列，用户在这些天线阵列的近场。 假设每个基站都装备了具有 R 个天线的阵列，用户传输信号到基站，基站进行多用户检测和用户定位。平面波假设 不再适用于近场，因此引入了 近场阵列响应 NF array response。没考虑宽窄带。Comment目标：Comment定位所有用户，并同时**恢复他们传输的稀疏信号**。 通过分块稀疏信号的估计来解决问题，同时利用 差分调制 避免频繁使用导频信号。Based on the estimated locations of the nonzero blocks, we can determine the locations of the users。Comment

**Maximum-Likelihood Source Localization and Unknown Sensor Location Estimation for Wideband Signals in the Near-Field**

Comment文章提出了一种用于宽带信号的最大似然(ML)定位估计器，该估计器优化了整个传感器阵列的源位置。在多源情况下，提出了一种基于序贯迭代搜索的算法，并且展示了其相对于现有方法（例如宽带MUSIC算法）的优越性能。Comment目标：Comment在近场条件下对宽带信号的源进行定位。 过频域转换 (DFT) 将时间域信号转化为频域信号，并推导了信号在频域中的最大似然解。Comment

**Near-Field Velocity Sensing and Predictive Beamforming**

Comment方法：近场速度感知的最大似然方法。在此基础上，进一步提出了一种感知辅助的预测波束形成方法，用于通信，这消除了目标运动模型的先验知识要求，并促进了无缝的数据传输。Comment

**Near-Field Localization and Sensing with Large-Aperture Arrays: From Signal Modeling to Processing**

Comment

**Modeling and Analysis of Near-Field ISAC**

Comment一个更加准确的近场ISAC框架，涵盖了下行链路和上行链路场景，通过考虑有效天线孔径和极化失配等因素，提供了对比传统模型更为合理的性能评估。数值结果进一步验证了该模型在实际应用中的有效性和必要性。Comment

**Localization with monostatic ISAC system: LOS detection and parameter estimation**

Comment在存在多路径场景下，基于同址多输入多输出（MIMO）技术的单基地集成感知与通信（ISAC）系统中的视距（LOS）定位问题。Comment

**Channel Estimation for Extremely Large-Scale MIMO: Far-Field or Near-Field?**

Comment利用极坐标域的稀疏性研究了近场信道估计。 同时考虑角度和距离信息。通过这种方式，近场信道也在极坐标域中表现出稀疏性，基于此，本文提出了基于网格和非网格的近场XL-MIMO信道估计算法。首先，提出了一种基于网格的极坐标域同步正交匹配追踪（P-SOMP）算法来高效估计近场信道。此外，提出了一种非网格的极坐标域同步迭代无网格加权（P-SIGW）算法来提高估计精度。Comment文章提出了“极域表示”方法。与仅考虑角度信息的传统角域表示不同，极域表示同时考虑了角度和距离信息。这种方法通过在极坐标系下对信道进行稀疏表示，可以更好地捕捉近场信道的特性，避免了传统角域表示中的“能量扩展效应”，即单一近场路径成分的能量会扩展到多个角度中，导致信道不再稀疏。Comment​Comment​Comment​Comment​
