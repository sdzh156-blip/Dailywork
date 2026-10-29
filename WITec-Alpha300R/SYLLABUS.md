# 12 周课程总览（48 节）

> 说明：此课程按 **Control FIVE + Project FIVE** 及用户实机配置设计。每个操作都应经过仪器管理员授权；本仓库不包含内部 SOP 的原文或扫描件。

时间建议：每周 4 节，每节理论/软件学习约 45–60 分钟，另安排 1–2 次上机或离线练习。前六周重点为物理与采集，后六周重点为 Raman TV、Filter、Fitting、Analyze、图像处理与综合实验。未授权上机时可用离线数据完成练习。

## [W01 拉曼光谱的物理基础](weeks/W01.md)

**目标：** 能从光子与振动理解为什么会出现拉曼峰，而非只背定义。

- [W01-L01｜光与物质相互作用](weeks/W01.md#w01-l01)
- [W01-L02｜瑞利、Stokes 与 Anti-Stokes](weeks/W01.md#w01-l02)
- [W01-L03｜拉曼位移与激发波长](weeks/W01.md#w01-l03)
- [W01-L04｜拉曼活性与选择定则入门](weeks/W01.md#w01-l04)

## [W02 拉曼光谱识读与材料信息](weeks/W02.md)

**目标：** 能从一条真实光谱辨认可用信息、噪声和过度解读。

- [W02-L01｜光谱横纵轴、峰位与峰强](weeks/W02.md#w02-l01)
- [W02-L02｜峰宽、峰型与材料性质](weeks/W02.md#w02-l02)
- [W02-L03｜背景、荧光、噪声与宇宙射线](weeks/W02.md#w02-l03)
- [W02-L04｜多光谱比较与结果判读](weeks/W02.md#w02-l04)

## [W03 WITec Alpha300R 硬件与实际光路](weeks/W03.md)

**目标：** 认识每个部件及光从哪里来、如何回到探测器。

- [W03-L01｜整机光路图与安全边界](weeks/W03.md#w03-l01)
- [W03-L02｜物镜与共聚焦原理](weeks/W03.md#w03-l02)
- [W03-L03｜光栅、光谱仪与探测器](weeks/W03.md#w03-l03)
- [W03-L04｜偏振、位移台与光学模式](weeks/W03.md#w03-l04)

## [W04 Control FIVE 界面逐项认识](weeks/W04.md)

**目标：** 打开软件知道每个主要窗口在哪里以及信息如何流动。

- [W04-L01｜主界面、菜单和 Project Manager](weeks/W04.md#w04-l01)
- [W04-L02｜光谱仪设置逐项解释](weeks/W04.md#w04-l02)
- [W04-L03｜Video Control、物镜与对焦](weeks/W04.md#w04-l03)
- [W04-L04｜Oscilloscope 与快捷采集界面](weeks/W04.md#w04-l04)

## [W05 基础上机：校准、单谱与重复性](weeks/W05.md)

**目标：** 经设备管理员授权后规范取得可用的单点拉曼光谱。

- [W05-L01｜开机、装样、对焦与安全检查](weeks/W05.md#w05-l01)
- [W05-L02｜硅片标准峰与校准判据](weeks/W05.md#w05-l02)
- [W05-L03｜单谱参数与信噪比优化](weeks/W05.md#w05-l03)
- [W05-L04｜实验重复性、命名与停机](weeks/W05.md#w05-l04)

## [W06 线扫、Mapping、3D 与扫描设计](weeks/W06.md)

**目标：** 能够自主设计扫描范围、点数、时间和有效空间分辨率。

- [W06-L01｜线扫描 Line Scan / Raster](weeks/W06.md#w06-l01)
- [W06-L02｜XY Mapping / Large Area Scan](weeks/W06.md#w06-l02)
- [W06-L03｜XZ 深度扫描与 3D Raman](weeks/W06.md#w06-l03)
- [W06-L04｜扫描质量和时间/容量优化](weeks/W06.md#w06-l04)

## [W07 Project FIVE 入门与光谱基础处理](weeks/W07.md)

**目标：** 能够从原始 .wip 数据重建完整且可追溯的处理链。

- [W07-L01｜Control FIVE 与 Project FIVE 数据流](weeks/W07.md#w07-l01)
- [W07-L02｜CRR、Repair 和 Average](weeks/W07.md#w07-l02)
- [W07-L03｜Sub BG、Crop、Smooth](weeks/W07.md#w07-l03)
- [W07-L04｜Calc、Demixer 与导出](weeks/W07.md#w07-l04)

## [W08 Raman TV 与 Filter：从光谱生成拉曼图像](weeks/W08.md)

**目标：** 掌握拉曼成像的核心计算和所有已确认的相关窗口参数。

- [W08-L01｜拉曼超光谱数据立方体](weeks/W08.md#w08-l01)
- [W08-L02｜Raman TV 逐按钮专项](weeks/W08.md#w08-l02)
- [W08-L03｜Filter 创建特征图像](weeks/W08.md#w08-l03)
- [W08-L04｜峰强比、峰位和峰宽 Mapping 判读](weeks/W08.md#w08-l04)

## [W09 拉曼图像操作、统计与多图融合](weeks/W09.md)

**目标：** 熟练完成图像窗口的区域、颜色、统计和比较操作。

- [W09-L01｜图像窗口与色条/比例尺](weeks/W09.md#w09-l01)
- [W09-L02｜Section、Crop、Image Calc](weeks/W09.md#w09-l02)
- [W09-L03｜Combine、Stitching、Transform](weeks/W09.md#w09-l03)
- [W09-L04｜Stat、Histogram、Correlate、Fourier/Filter](weeks/W09.md#w09-l04)

## [W10 峰型拟合与化学组分分析](weeks/W10.md)

**目标：** 能正确拟合重叠峰并用参考谱做组分分解。

- [W10-L01｜Fitting 界面和常用函数](weeks/W10.md#w10-l01)
- [W10-L02｜多峰拟合与谱峰归属](weeks/W10.md#w10-l02)
- [W10-L03｜Analyze 已知参考谱分析](weeks/W10.md#w10-l03)
- [W10-L04｜Analyze 自动分量与结果验证](weeks/W10.md#w10-l04)

## [W11 聚类、PCA、NMF 与科研质量控制](weeks/W11.md)

**目标：** 理解高级统计算法的假设及如何防止对图像过度解释。

- [W11-L01｜Cluster 聚类与类别验证](weeks/W11.md#w11-l01)
- [W11-L02｜PCA 主成分分析](weeks/W11.md#w11-l02)
- [W11-L03｜NMF 非负矩阵分解](weeks/W11.md#w11-l03)
- [W11-L04｜科研绘图与处理质量控制](weeks/W11.md#w11-l04)

## [W12 TrueSurface、异常诊断与综合实战](weeks/W12.md)

**目标：** 把物理、硬件、采集、软件及结果解释连成闭环。

- [W12-L01｜TrueSurface 原理、物镜和参数](weeks/W12.md#w12-l01)
- [W12-L02｜硬件/光谱异常排查](weeks/W12.md#w12-l02)
- [W12-L03｜综合实验：从样品到数据集](weeks/W12.md#w12-l03)
- [W12-L04｜综合实验：复现分析与结业考核](weeks/W12.md#w12-l04)

## 可选后续专项（不计入 48 节）

- AFM 接触/轻敲模式、力学反馈与 AFM-Raman 联用（实机有相关硬件和权限时）。
- SHG、偏振拉曼、PMT、荧光寿命与显微图像模式（必须先核实实机光路/探测器配置）。
- 低温/高温原位、透射拉曼、ParticleScout 等（取决于设备授权，不能照搬其他 SOP）。
- 面向半导体和硅光/光子器件的案例：Si 应力映射、SiN 材料、石墨烯及二维材料缺陷分析。

## 课程验收等级

- **理解通过：** 能复述原理、变量和参数关系，回答反例。
- **操作通过：** 能用截图和数据复现流程，遵守设备安全边界。
- **解释通过：** 能给出物理意义、误差来源及结论限制。
- **记录完备：** 提交原始/派生数据、参数和日期。

只有以上四项均满足，才在 [PROGRESS.md](PROGRESS.md) 勾选。
