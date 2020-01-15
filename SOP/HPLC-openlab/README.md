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

| Vial | Acq.Method | Volume | Sample name | Data file           |
| ---- | ---------- | ------ | ----------- | ------------------- |
| 99   | BV-2...    | 5      | BLANK       | &lt;S&gt; &lt;D&gt; |
| 47   | BV-2...    | 5      | HCS197...   | &lt;S&gt; &lt;D&gt; |

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