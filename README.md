# <div style="position: absolute; top: 120px; left: 40%; transform: translate(-50%, -50%); z-index: 2; font-family: 'Times New Roman', serif; font-size: 48px; color: Black; text-align: center;">Welcome to Wang Cong's homepage!</div>

## </br></br></br></br></br></br></br><div style="font-family:'仿宋'; font-size:25px">一、生物信息学笔记</div>
==特别注意==：本门课并非教授编程技能，而是训练学生**如何使用编程解决实际问题**。
### <font size=4>(一) **课程基本信息介绍**</font>
  1. 先修课程要求：实际上并无硬性要求，只要具有**高数基础**，有一定**编程能力**，**接触过Linux**即可。
  2. 后续课程推荐：**《基于Python的科学与数值计算》**、《计算机程序设计基础 (Python)》、《Python程序设计进阶》。
  3. 课程基本安排
        | 周数 | 内容 |
        | :---: | :---: |
        | 1-4|Linux(bash)|
        |5-16|R|
        |11-16|Python|
  4. 参考资料以及实践教程：详见[教学大纲](https://365.kdocs.cn/l/caAbfIt5y8Fk)
   </br>
 
### <font size=4>(二) **课程特色**</font>
  1. 教学目标
     * 介绍基本概念和原理；
     * 介绍生物信息可以研究的问题和方向，从而引发实践和研究的兴趣；
     * ==构建学习和实践的框架==
  2. 学习方法（Peer Learning）——基于费曼学习法

  <div align=center>
    <img src=image.png width=400px>
  </div>
  </br>

### <font size=4>(三) **生物信息学（bioinformatics）与传统生物学**</font>
   
<table>
  <tr>
    <th>生物信息学四步走</th>
    <td>Information</td>
    <td>Analysis</td>
    <td>Modeling</td>
    <td><strong>Question</strong></td>
  </tr>
  <tr>
    <th>传统生物学四步走</th>
    <td><strong>Question</strong></td>
    <td>Information</td>
    <td>Analysis</td>
    <td>Modeling</td>
  </tr>
</table>

&emsp;&emsp;如下图，传统生物学属于科学发展第三范式，生物信息学作为数据时代的产物则是进入到第四范式。
![alt text](image-1.png)

### <font size=4>(四) ==**算法(algorithm)与模型(model)**==</font>
  1. 算法：
      * 排序算法： 快速排序、归并排序等
      * 动态规划算法： 矩阵链乘法、最长公共子序列等
  2. 模型：
      * 概率模型： 隐马尔可夫模型（HMM）、贝叶斯网络等
      * 机器学习模型： 线性回归、逻辑回归、神经网络等
  3. 算法与模型的区别：
      * **算法**是一种解决问题的步骤或方法
      * **模型**是算法作用于数据后对现实世界某种现象的抽象表示
      * 算法可以用来训练模型，模型可以用来预测和分析数据
### <font size=4>(五) **生物信息学应用**</font>
  * 基因组学： 基因组测序、基因功能预测、变异分析等
  * 转录组学： RNA 测序、基因表达分析、可变剪接等
  * 蛋白质组学： 蛋白质结构预测、功能注释等
  * 代谢组学： 代谢物鉴定、代谢通路分析等
### <font size=4>(六) **生物信息学工具**</font>
  * 序列分析工具： BLAST、Clustal Omega 等
  * 结构预测工具： PhyreStorm、AlphaFold 等
  * 功能注释工具： GO、KEGG 等
### <font size=4>(七) **生物信息学发展趋势**</font>
  * 大数据驱动： 利用海量数据进行科学研究和临床应用
  * 人工智能： 利用深度学习等技术进行更精准的预测和分析

## <font face="仿宋" size=5>二、生物信息学习计划</font>

### <font size=4>第 1-4 周：Linux 基础与生物信息学应用</font>
- **目标**：掌握 Linux 基本操作和生物信息学工具。
- **内容**：
  - 第 1 周：Linux 文件系统与基本命令（`ls`, `cd`, `mkdir`, `cp`, `mv`, `rm`）。
  - 第 2 周：文本处理工具（`grep`, `awk`, `sed`, `cut`, `sort`）。
  - 第 3 周：Shell 脚本编写与自动化。
  - 第 4 周：生物信息学工具安装与使用（如 FastQC、BLAST）。

### <font size=4>第 5-10 周：R 语言基础与生物信息学分析</font>
- **目标**：掌握 R 语言基础及其在生物信息学中的应用。
- **内容**：
  - 第 5 周：R 语言基础（变量、数据类型、函数、包管理）。
  - 第 6 周：数据导入与处理（`read.table`, `dplyr`）。
  - 第 7 周：数据可视化（`ggplot2`）。
  - 第 8 周：RNA-Seq 数据预处理（质量控制、标准化）。
  - 第 9 周：差异表达分析（`DESeq2`）。
  - 第 10 周：功能富集分析（`clusterProfiler`）。

### <font size=4>第 11-16 周：高级分析与 Python 选择性使用</font>
- **目标**：深入学习生物信息学分析，选择性使用 Python。
- **内容**：
  - 第 11 周：单细胞 RNA-Seq 数据分析（`Seurat`）。
  - 第 12 周：基因组变异分析（`VCFtools`, `snpEff`）。
  - 第 13 周：Python 基础（变量、数据类型、函数）。
  - 第 14 周：Python 数据处理（`pandas`, `numpy`）。
  - 第 15 周：Python 数据可视化（`matplotlib`, `seaborn`）。
  - 第 16 周：项目实践与总结（srt）。

---
<div style="font-family: '楷体'; font-size: 20px;">
清华大学  致理书院</br>
王聪</br>
cong-wan23@mails.tsinghua.edu.cn
</div>

<div class=container>
    <div align=center class=background>
        <img src=background.png>
    </div>
</div>

<div class=picture>
        <img src=商务2.jpeg width=20%>
</div>

<style>
    .background {
        position: absolute;
        top: 0;
        left: 10%;
        width: 80%;
        z-index: 1;
    }

    .picture {
        z-index: 2;
        position: absolute;
        top: var(--pos-y, 100px);
        left: var(--pos-x, 60%);
    }

    .container {
        display: flex;
        justify-content: center;
        align-items: flex-start;
        height: 100vh;
    }

    body {
        margin: 0;
        padding: 0;
        background: linear-gradient(to right, rgb(237, 244, 242), rgb(74, 204, 204));
    }
</style>