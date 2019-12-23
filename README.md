# IPC Daily | 日常 | Nichijou

- 又名《一个实习分析师的自我修养》。
- 好好学习，天天向上。

- Login Openlab, Launch instrument, Create&Run sequences, Data analysis.

[TOC]

# HPLC

## 编辑&运行序列

- 在平衡（信号平稳？）15min 后运行序列。

## 提交空白样本

洗柱或换 Acq. Method 后需要在序列首位提交空白样本。

## 后续处理

序列走完而后无送样，降流速。

中午下班无样降流速。

下午下班提交关机洗柱。

## 洗柱

0.5 ml/min

## 排气泡

松阀门，流速 3 ml/min。

# Openlab

## Control Panel

- Enter Acquisition:

Instruments → &lt;group&gt; → &lt;inst.&gt; → Launch

exp : Instruments → GD-grou 1 → TI-00332 DAD → Launch



- Enter Data Analysis:

Projects → &lt;project&gt; → Start Data Analysis

exp : Projects → Generic drug → GD-group 1  → BVM17021 → Start Data Analysis

## Acquisition

- Turn on device : Status → Instrument Status → On

- Select method : Method → open method → download method

- Create&Run sequence : Sequence → new sequence → add injections → save sequence → set Result path&name → CHECK →Run

- Add sample : pass



### new Sequence exp

| Vial | Acq.Method | Volume | Sample name | Data file |
| ---- | ---------- | ------ | ----------- | --------- |
|99|BV-2...|5|BLANK|&lt;S&gt; &lt;D&gt;|
|47|BV-2...|5|HCS197...|&lt;S&gt; &lt;D&gt;|

.sqx save path and title

.sqx path : /&lt;Project&gt;/Sequences/HPLC/&lt;YYYY&gt;/&lt;YYYYMM&gt;/&lt;YYYYMMDD&gt;
exp : /BVM 17021/Sequences/HPLC/2019/201912/20191205

file name(sqx title)
&lt;YYYYMMDD&gt;-IPC-&lt;inst.&gt;-&lt;#&gt;.sqx
exp : 20191205-IPC-TI00332-01.sqx



Result path:
/&lt;Project&gt;/Results/HPLC/&lt;YYYY&gt;/&lt;YYYYMM&gt;/&lt;YYYYMMDD&gt;
/BVM 17021/Results/HPLC/2019/201912/20191205



Result name:
&lt;sqx. title&gt;

## Data Analysis

pass

# 流动相配制

- 溶剂水为超纯水。
- 步骤：称量/量取，溶解/稀释，（调 pH，抽滤，）装瓶，标签，洗容器。
- 登记本：天平、pH 计、流动相配制登记本（天平、pH 计型号、试剂厂家批号、配制方法）。

## 有机溶剂占比与试剂保存时间

|有机溶液占比|保质期|
|---|---|
|5~10%|1W|
|20~30%|1M|
|50~60%|3M|
|70~80%|6M|
|100%|1Y|

# 使用 pH 计调节溶液 pH 

- 每日第一位使用需要校正。
- 步骤：纯化水洗电极，开磁搅，KOH/H<sub>3</sub>PO<sub>4</sub> 调节 pH。

## pH计校正



# 水分测定仪器测定水分

- 每日第一位使用需要标定。
- 步骤：，减重法称量，软件方法KFT，平衡-开始，（若浑浊则换液后）加样，待测定结束，换液，清理。
- 重复 2 次，记录样本质量、消耗K氏液体积、平均值（保留两位小数）、RSD%。
- 固体使用称量舟称量，取 0.5g；液体使用一次性注射器量取 0.5ml。
- 换液操作：停止平衡，手动操作，搅拌速度设定 5，右按钮排液，左按钮进液，50ml（浸没电极）。
- 登记本：天平、水分测定仪标定记录本。
- 针头特定回收。

## 助溶剂

## 水分测定仪标定

- 方法：KFT-Titer
- 天平室称量
- 步骤：微量注射器吸取 10μl 超纯水，减重法称量，软件平衡-开始，注水，输入水的质量，待测定结束。
- 重复 3 次，记录水的质量、消耗K氏液体积、平均值、RSD%。
- RSD% < 1 则合格，否则重测。
- 天平室天平、水分测定仪标定记录本登记。

# 氧化还原滴定

# 旋光仪测定溶液旋光度
