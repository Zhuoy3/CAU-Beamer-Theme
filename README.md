<!--
 * @Author: Zhuo Yue
 * @LastEditTime: 2023-03-06 23:10
 * @FilePath: \CAU-Beamer-Theme\README.md
-->
# CAU-Beamer-Theme

基于THU-Beamer-Theme进行进一步修改的。

提供了学校和大部分学院的配色，可以使用类似下面的指令导入

    \usepackage[color=CAU]{CAU}

或者

    \usepackage[color=CAU-CAST]{CAU}

更多的可以看sty文件里面。除了学校的给出了明确的RGB值，各个学院的是从官网提取的颜色，不一定准确。官网名字用了拼音的学院提供了两种调用方式（拼音和英文名缩写）。

除了颜色，主要修改了

- [x] 调整了页眉和页脚的外观
- [x] 参考文献等不列入目录（直接在tex改了）
- [ ] 有子章节的章节不显示第一张章节目录
  - 类似于第八页和第九页有点重复了，移除第八页
