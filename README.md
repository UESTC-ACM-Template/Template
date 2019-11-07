# Template

由于 $ICPC/CCPC$ 比赛题目所涉及的算法知识范围过于广泛，且相当多的算法内容难以在限定时间范围内手动实现。所以希望能够整理模版，使竞赛过程更注重于对于算法问题的分析上，而非对已有算法的代码实现上。

## Template 的编写标准
1. 请在模版代码前注明接口，用以表明输入参数含义和输出参数含义及其时空复杂度。如: 
> $Exkmp$ ($z$ 函数) \
> *s &nbsp; : &nbsp; 模板串(从下标 $0$ 开始)  \
> *z &nbsp; : &nbsp; $Z$ 函数，$Z_i$表示以 $i$ 号下标作为开头的子串，与 $s$ 串所能匹配的最长长度.  \
> 时间复杂度: $O(n)$,    空间复杂度: $O(n)$ \
> void z_function(char *s, int *z){ ... }
2. 如果您觉得该模板并不常见，则请在使用模板通过了题目后，将题目链接粘贴在该算法末尾。 

(此标准尚未确定，如果您有好的想法，请在 $issue$ 里提出)

另，由于 $Github$ 的网页不提供对数学公式的解析，有需要请自行安装插件: \
https://chrome.google.com/webstore/detail/mathjax-plugin-for-github/ioemnmodlmafdkllaclgeombjnmnbima/related