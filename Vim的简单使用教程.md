# Vim简单使用教程 #
**之前从未过Vim，最近学习前端，需要学习一些简单的使用规则，遂决定百度寻找一波。** 
## 一、快速定位 ##
 - ) ：光标移至句尾 
- ( ：光标移至句首 }：
- 光标移至段落最后一个字母 
- {：光标移至段落第一个字母 
- nG：光标移至第n行首 
- n+：光标下移n行
-  n-：光标上移n行 
-  n$：光标移至第n行尾 
-  H ：光标移至屏幕顶行
-   M ：光标移至屏幕中间行 
-   L ：光标移至屏幕最后行 
-   0：（注意是数字零）光标移至当前行首

## 二、快速翻页 ##
- 整页翻页 ctrl-f ctrl-b f就是forword b就是backward
- 翻半页 ctrl-d ctlr-u d=down u=up 滚一行 ctrl-e ctrl-y
- zz 让光标所杂的行居屏幕中央 zt 让光标所杂的行居屏幕最上一行 t=top
- zb 让光标所杂的行居屏幕最下一行 b=bottom

## 三、复制粘贴操作 ##
 首先，可以在命令模式下输入v进入自由选取模式，选择需要剪切的文字后，按下d就可以进行剪切了。 

其他命令模式下剪切命令：

-  yy：复制当前行 
-  nyy：n表示大于1的数字，复制n行 
-  yw：从光标处复制至一个单子/单词的末尾，包括空格 
-  ye：从光标处复制至一个单子/单词的末尾，不包括空格
-  y$：从当前光标复制到行末
-  y0：从当前光标位置（不包括光标位置）复制之行首 
-  y3l：从光标位置（包括光标位置）向右复制3个字符
-  y5G：将当前行（包括当前行）至第5行（不包括它）复制
-  y3B：从当前光标位置（不包括光标位置）反向复制3个单词

单独按y是复制2行，ny是复制n+1行 至于粘贴命令最简单，在需要粘贴的光标处按下p即可。

## 四、查找某个字符串 ##
 - 1、用/和？的区别： /后跟查找的字符串。vim会显示文本中第一个出现的字符串。 ?后跟查找的字符串。vim会显示文本中最后一个出现的字符串。 
- 2、注意事项： 不管用/还是？查找到第一个字符串后，按回车，vim会高亮所有的匹配文
