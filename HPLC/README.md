# Daily process
- login openlab
- launch inst.
- creat sequences
- run sequences
- repeat creat-run

#Login
## Domain
RD-&lt;USR&gt;

&lt;PASSWD&gt;

## MSTSC
ANALYSIS\&lt;USR&gt;

&lt;PASSWD&gt;

## Openlab Control Panel
&lt;USR&gt;

&lt;PASSWD&gt;

# Control Panel
Instruments → .. → &lt;inst.&gt; → Launch

exp : Instruments → GD-grou1 → TI-00332 DAD → Launch

# Accquisition
Status → Instrument Status → On

Method → open method → download method

Sequence → new sequence → add injections → save sequence-Result path → Result name → CHECK →Run

|---|---|---|---|---|
|Vial|Acq.Method|Volume|Sample name|Data file|
99 BV-2.. 5 BLANK &lt;S&gt; &lt;D&gt;
47 BV-2.. 5 HCS197.. &lt;S&gt; &lt;D&gt;

Save sequence
dir
/&lt;Project&gt;/Sequences/HPLC/&lt;YYYY&gt;/&lt;YYYYMM&gt;/&lt;YYYYMMDD&gt;
/BVM 17021/Sequences/HPLC/2019/201912/20191205

file name(sqx. title)
&lt;YYYYMMDD&gt;-IPC-&lt;inst.&gt;-&lt;#&gt;.sqx
20191205-IPC-TI00332-01.sqx

..
new sequence

Result path
/&lt;Project&gt;/Results/HPLC/&lt;YYYY&gt;/&lt;YYYYMM&gt;/&lt;YYYYMMDD&gt;
/BVM 17021/Results/HPLC/2019/201912/20191205

Result name
&lt;sqx. title&gt;
