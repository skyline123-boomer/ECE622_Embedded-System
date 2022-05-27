可达性分析目前有两种主流方法：随机执行(random execution)与符号化检验(symbolic reachability)，本项目首先用
Verilog编写的testbench来验证有限状态机的可达性(随机执行）；然后把有限状态机转化为CNF公式形式后，在linux虚拟
机中运用Picosa(SAT slover)来验证状态的可达性(符号化检验）。通过记录执行时间，得出了符号化检验比随机执行方法
更好的结论。
