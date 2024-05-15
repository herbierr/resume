# Herbie-Resume

中文LaTeX简历模板

主要参考：

*   [billryan/resume](https://github.com/billryan/resume)

*   [hijiangtao/resume](https://github.com/hijiangtao/resume)

LaTex语法内容以及框架基本上参照[Htallone/myCV](https://github.com/Htallone/myCV), 宏主要参照[herbierr/resume](https://github.com/herbierr/resume), 集各家之所长后做了些小修改, 方便直接编译.

### 使用步骤

1.  Download ZIP

2.  选择complier为`XeLaTeX`

3.  模块化各个单元，为定制个人模板做简单参考

### 宏(newcommand)

*   `\name`: 姓名

*   `\logosection{fontawesome command}{小节}`: 用于分节, 如教育背景, 实习项目经历等

*   `\dateRange{起始日期}{终止日期}`: 时间区间, 其中使用了特殊对齐策略, 便于在`终止日期`处填写**至今**

*   `\dateline{内容1}{内容2}{日期}`: 第一项左对齐，第二项居中，第三项右对齐， 嵌套`\dateRange`使用效果更佳

*   `\datedline{内容}{日期}`: 第二项自动右对齐,  嵌套`\dateRange`使用效果更佳

*   `\itemize`: 清单列表，简历中应用最广

### 效果示例

**纯享版:**
![resume-zh](https://github.com/herbierr/resume/assets/80444681/0beaac03-e7ec-4611-97d7-531e32c7ac83)
