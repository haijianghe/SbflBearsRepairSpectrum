# SbflBearsRepairSpectrum
Bears的程序谱及静态源代码（计算复杂度）。

Java代码，VirtualBox+Ubuntu环境下收集的程序谱（覆盖数据）和源代码。后续对此研究静态代码对软件错误定位的影响。

https://github.com/bears-bugs/bears-benchmark(数据集来源)


数据集作者的介绍。The Bears-Benchmark, or just Bears, is a benchmark of bugs for automatic program repair studies in Java. The bugs are collected from open-source projects hosted on GitHub through a process that scans pairs of builds from Travis Continuous Integration and reproduces bugs (by test failure) and their patches (passing test suite).


这些压缩文件包，共有3个对象数据集。   
解压后，数据集包含以下内容：
1，XXX_fault.csv，各版本故障语句的行号。
2，XXX.testcase，版本数，测试数目，各版本通过测试用例数、未通过测试用例数。
3，文件夹info，只是保留数据，研究中用不到。
4，profile，我的程序生成结果，程序谱，aep、aef、anp、anf
5, xxx_order.bugid 有的数据集省略了中间版本。版本号并非自然排序结果。
6，SourceCode 各故障版本的源代码。buggy以及fixed.
