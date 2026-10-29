# Control FIVE + Project FIVE 软件功能核对清单

**目的：** 对着实机逐窗口核实每个可见菜单、选项、参数、快捷动作及输出，避免“教过功能大类但漏了具体按钮”。本清单是**待逐项验收的清单**，并不代表已经检查了软件全部菜单。无法在当前截图中确定的内容明确标为“待实机确认”。

说明：□未核实，☑仅在实机截图和解释完成后手动勾选。可在学习通过后同时更新本文件与 [PROGRESS.md](PROGRESS.md)。

## A. Control FIVE：仪器控制与采集

- [ ] 窗口/菜单：主菜单、Control、Message、Project Manager、WITec Video Control、保存与工程参数、日志和状态。
- [ ] 光谱仪：Grating G1/G2/G3、Spectral Unit、Spectral Center、Excitation/Laser Wavelength、CCD1、光栅中心与谱宽、相机/光路参数（选项以实机为准）。
- [ ] 视频界面：物镜选择、相机视频、比例尺、鼠标交互、ROI、照明、焦点与标定、功率区域。
- [ ] Laser Control：532/633/785 选择、打开/关闭条件、显示值单位及实测功率、强度按钮、光束状态。
- [ ] 定位与对焦：X/Y/Z、Goto Surface、Auto Focus、机械限位/避让、软件运动参数。
- [ ] 采谱：Oscilloscope、Integration Time、Accumulations、Single Spectrum、Stop 和采谱数据状态。
- [ ] 线扫：Start Line Scan、Raster、Once/Multiple、点数与步距、路径、积分时间。
- [ ] Mapping：Image Scan、Large Area Scan、Scan Method、Geometry、Points/Lines、Retrace、XY/XZ/3D、数据保存。
- [ ] 光谱/图像窗口：缩放、拖拽、ROI、谱峰标记、标尺、调色、导出、对象交互和径向菜单。
- [ ] 其他软件入口与附加模式：PMT/相机、偏振、AFM、SHG、透射、原位、TS（只登记实际上能看到和获得授权的功能）。

## B. Project FIVE / Control FIVE 内置数据处理（按按钮逐项学习）

### B1. 对象与导航
- [ ] Project Manager 的 Graph/Image/Bitmap/Text、原始扫描、Drop Actions、径向操作、保存、Undo/数据派生关系。
- [ ] Graph Viewer／光谱坐标/峰搜索/标注/单位/缩放；Image Viewer／颜色比例尺/ROI/比例尺/导出。

### B2. 光谱处理
- [ ] Cosmic Ray Removal (CRR)：异常尖峰识别与替换。
- [ ] Average：单谱/空间/时间平均。
- [ ] Smooth：窗口宽度、算法与避免过平滑。
- [ ] Sub BG：Polynomial、Shape、保护峰区与背景预览。
- [ ] Crop：谱区选择及裁剪。
- [ ] Repair：坏点/异常谱修复。
- [ ] Calc / Demixer：光谱计算、加减、权重。
- [ ] Fitting：函数、Vary、参数、残差、峰中心/峰宽/峰面积。

### B3. 从光谱到图像
- [ ] **Raman TV**：Position [Pixel]、Spectral Filter Size、Spatial Average Spectrum Area Size、Spectral Filter Kind、Extract Image/Graph。
- [ ] **Filter**：Create Filters、Sum/Average、Peak Position、Peak Width、Width、Background Subtraction、Quick Filters、Spatial Average、Extract/All。
- [ ] 峰面积、峰高、峰位、FWHM、峰比、信噪/无效像素、伪彩色尺度。

### B4. 图像处理
- [ ] Image Calc、Crop、Section、Stat、Histogram。
- [ ] Combine 彩色组分融合、Stitching 拼接、Transform 空间关联/校正。
- [ ] Fourier/Filter/Correlate/Repair 等滤波与相关功能。
- [ ] 图像比例尺、颜色条数值范围、ROI 统计、2D/3D 导出与图注。

### B5. 高级分析（功能和许可证须先核实）
- [ ] Analyze：参考谱混合分解、自动识别分量、残差图。
- [ ] Cluster：类别数、平均谱、类别分布图。
- [ ] PCA：得分/载荷/解释方差。
- [ ] NMF：非负成分谱、空间权重、误差。

## C. 对每个控件的统一验收方法

记录：

| 功能/按钮 | 窗口位置及截图 | 参数/单位/默认值 | 调节后物理/数学效果 | 输出对象及适用场景 | 已验收日期 |
|---|---|---|---|---|---|
| Raman TV | 待从实机/资料核对 | 详见 W08-L02 | 待实验 | 特征图像/光谱 | — |
| Filter | 待从实机/资料核对 | 详见 W08-L03 | 待实验 | 峰面积/峰位/峰宽等图 | — |

> 软件版本之间同名按钮可能选项不同。请通过**实际软件截图 + 课堂逐项解释**补齐每个菜单和子选项，不以新版 Suite SEVEN 界面替代 FIVE。
