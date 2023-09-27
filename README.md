
# Week1笔记整理
>学习资料非常多，尽量梳理清楚并且多处建立直接跳转的链接

## 快捷资料导航
- 主要教材：生物信息学实践教程 [Bioinformatics Tutorial](https://book.ncrnalab.org/teaching/)
- Bioinformatics Tutorial[配套云盘资料](https://cloud.tsinghua.edu.cn/d/ad22768345664924b202/?p=%2F&mode=list)
- [Courses](https://www.ncrnalab.org/courses/#bioinfo2)课程说明
- [Git教程](https://www.liaoxuefeng.com/wiki/896043488029600)
- [Markdown教程](https://cloud.tsinghua.edu.cn/d/ad22768345664924b202/files/?p=%2FVideo%2FI.%20Basic%20Skills%2F0.%20Getting%20Started%2Fmarkdown-7min.mp4)
- 基因基础知识需要看的[Basic Knowledge](https://cloud.tsinghua.edu.cn/d/ad22768345664924b202/?p=%2FVideo%2F0.1%20Basic%20Knowledge&mode=list)
- [创建github pages站点 ](https://docs.github.com/zh/pages/getting-started-with-github-pages/creating-a-github-pages-site)教程
- 印象笔记[教案](https://app.yinxiang.com/fx/b46306ff-4e70-456b-9185-e0afb3e55bd4)
- 上课[第一部分介绍课件](https://cloud.tsinghua.edu.cn/d/dcbb0944631a4291b34c/?p=%2F&mode=list)主要关于工具介绍
- 上课[第二部分课件](https://cloud.tsinghua.edu.cn/d/4c56bf659c1b4ec3a004/?p=%2F%E7%AC%AC%E4%B8%80%E5%91%A8&mode=list) 主要关于基因介绍

**模型和算法的区别**
- **模型**是将现实中的实际问题进行适当的简化，用数学、符号或者单词来对其实体、过程或者属性之间相互关系的一种描述，一般模型的主要功能就是用来预测。
- **算法**则是求解模型的方法，是解决问题或者执行任务的逐步过程。

**本学期的学习计划**
- 掌握生物信息学的基本技能，尤其是争取学期结束后可以熟练掌握python、linux、R语言用于信息学的数据分析
- 掌握基础的生物基因的基本知识
- 深入的了解几种机器学习算法，比如神经网络、随机森林、向量机等等，并且尝试在实际的分析中使用机器学习算法
- 熟悉基因序列分析实验的基本流程，可以实现独立的取样、测样、送样以及后续的数据分析

## 学习Markdown笔记
# 一级标题
## 二级标题
### 三级标题

> 这是一段引用

有序列表（英文数字加点再空格）
1. 第一步
2. 第二步
3. 第三步

无序列表（短横线加空格）
- 第一步
- 第二步
- 第三步

任务列表 （横杠+空格+方括号里面也要空格）明天要做的事
- [ ] 吃饭
- [x] 睡觉
- [ ] 写作业

代码块(三个反引号+语言的名称，反引号在键盘左上角波浪线下面,三个反引号结束)
```python
if a>10: 
	print("good")
else
	print("not good")
```

表格
|姓名|年龄|成绩|
|:---|---:|:---:|
|张三|23|100|
|李四|53|90|
>冒号在左左对齐，冒号在右右对齐，冒号两边都有中间对齐

脚注
一键三连[^三连]


横线分割文章用
---

链接（方括号里面加文本，后面英文括号加**地址**）

[百度](https://www.baidu.com)
>注意这个地址必须是全的从https开始啊

引用链接（id写在前面，到时改id对应地址就可以全部改了）

[id]: https://www.baidu.com
[百度][id]

[点击这里][id]

[百度][id]


请参考[标题2](#二级标题)
>名字要对上，一点就跳转

url: www.baidu.com

展示图像
>[替代的文本随便写]
https://pss.bdstatic.com/static/superman/img/logo/bd_logo1-66368c33f8.png
直接放图片地址显示不出来，注意格式，前面有个感叹号

![百度](  https://pss.bdstatic.com/static/superman/img/logo/bd_logo1-66368c33f8.png)

- *一对星号表示斜体*
- **两对星号表示加粗**
- `一对反引号编写行内代码 print()`
- <u>下划线</u>
- :smile: 表情 参考国际通用表情代码
- 行内数学公式 $\theta=x^2$


[^三连]:点赞、投币、加收藏






