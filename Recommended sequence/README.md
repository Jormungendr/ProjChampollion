# Recommended sequence
## 1. Challenge Translation
在这个挑战中，你的目标是解压一个压缩好的字符串。  
你的输入是一个被压缩好的字符串，你的输出应是一个解压好的字符串，样例如下：  
输入：  
<code class=" language-c">3[abc]4[ab]c</code>  
输出:  
<code class=" language-c">abcabcabcababababc</code>  
### 1.其他规则
数字可以大于个位，例如<code class=" language-c">10[a]</code>是被允许的，它代表<code class=" language-c">aaaaaaaaaa</code>  
一次递归压缩是被允许的，例如<code class=" language-c">2[3[a]b]</code>，它代表<code class=" language-c">aaabaaab</code>  
被压缩的字符串可以包括数字，小写英文字母和中括号。  
数字仅仅被用来表达重复的次数。  
字母仅仅是字母。  
括号只是格式的一部分。  
输入永远是合法的，所以不必检查输入是否合法。
### 2.学习对象
这个问题可以给你练习字符串，递归，算法，编译器，自动化以及循环的机会。这也是能够帮助你使工作中的代码变得更有效率的契机。