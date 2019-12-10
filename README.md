# IPC Daily 日常 Nichijou

- Login Openlab, launch instrument
- Create&Run sequences
- Repeat Create&Run
- Data analysis

# Openlab

## Control Panel

- Enter Acquisition:

Instruments → &lt;group&gt; → &lt;inst.&gt; → Launch

exp : Instruments → GD-grou1 → TI-00332 DAD → Launch



- Enter Data Analysis:

Projects → &lt;project&gt; → Start data analysis

## Acquisition
Turn on device : Status → Instrument Status → On

Select method : Method → open method → download method

Create&Run sequence : Sequence → new sequence → add injections → save sequence → set Result path&name → CHECK →Run

Add sample : pass



### new Sequence exp

| Vial | Acq.Method | Volume | Sample name | Data file |
| ---- | ---------- | ------ | ----------- | --------- |
|99|BV-2...|5|BLANK|&lt;S&gt; &lt;D&gt;|
|47|BV-2...|5|HCS197...|&lt;S&gt; &lt;D&gt;|

sqx save path and title

sqx path : /&lt;Project&gt;/Sequences/HPLC/&lt;YYYY&gt;/&lt;YYYYMM&gt;/&lt;YYYYMMDD&gt;
exp : /BVM 17021/Sequences/HPLC/2019/201912/20191205

file name(sqx title)
&lt;YYYYMMDD&gt;-IPC-&lt;inst.&gt;-&lt;#&gt;.sqx
20191205-IPC-TI00332-01.sqx



Result path:
/&lt;Project&gt;/Results/HPLC/&lt;YYYY&gt;/&lt;YYYYMM&gt;/&lt;YYYYMMDD&gt;
/BVM 17021/Results/HPLC/2019/201912/20191205



Result name:
&lt;sqx. title&gt;

## Data Analysis

pass

# 流动相配制

# pH计使用 

# 水分测定仪器测定水分

- 每日第一位使用需要标定。
- 步骤：减重法称量，软件平衡-开始，（若浑浊则换液后）加样，待测定结束，换液。
- 重复 2 次，记录样本质量、消耗K氏液体积、平均值、RSD%。
- 固体使用称量舟称量，取 0.5g；液体使用一次性注射器量取 0.5ml。
- 换液操作：停止平衡，手动操作，搅拌速度设定 5，右按钮排液，左按钮进液，50ml（浸没电极）。
- 天平、水分测定仪标定记录本登记。

## 水分测定仪标定

- 方法：KFT-Titer
- 天平室称量
- 步骤：微量注射器吸取 10μl 超纯水，减重法称量，软件平衡-开始，注水，输入水的质量，待测定结束。
- 重复3次，记录水的质量、消耗K氏液体积、平均值、RSD%。
- RSD% < 1 则合格，否则重测。
- 天平室天平、水分测定仪标定记录本登记。