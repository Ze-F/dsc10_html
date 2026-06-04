# DSC10 系统性 walkthrough

UCSD **DSC10 (Principles of Data Science)** 的自学复习材料——按考试节点把课程拆成 5 个模块，逐 section 输出独立 HTML 学习页。

🌐 **在线访问**：<https://ze-f.github.io/dsc10_html/>

## 模块概览

| 模块 | 范围 | 内容 |
|---|---|---|
| 📘 Midterm | Lec 1-12 | DataFrame、`groupby`、可视化、函数、merge、概率与模拟。基于 6 份历年 midterm 提炼考点 |
| 📗 Quiz 3 | Lec 13-18 | Sampling、bootstrap CI、CI 解读、Chebyshev / normal、CLT、sample size。基于 7 份历年 Quiz 3 |
| 📕 Quiz 4 | Lec 18-22 | Hypothesis testing、p-values、TVD、permutation testing。基于 8 份历年 Quiz 4/5 |
| 📗 Final | Lec 23-25 + 综合 | Correlation、regression、residuals & inference + Mock final。基于 17 套历年 Final |
| 🛠 Practice | Lab 2-7 + HW 2-6 + Projects | 本学期作业的逐题 walkthrough（思路 + 代码 + 易错点 + 知识点回链） |

## 每节 HTML 结构

1. 📋 考点速览（Tier ⭐⭐⭐/⭐⭐/⭐ 标记）
2. 📚 知识点（中文讲解 + 英文术语 + Python 代码）
3. ⚠️ 常见陷阱与考点
4. 📝 往年真题（按知识点分组，默认折叠答案，标注 "Fall 2024 Q3" 等来源）
5. ✅ 自我讲解 checklist

## 技术

- 纯静态 HTML，单文件内嵌 CSS/JS，**无任何外部依赖**（离线可用）
- 🌙/☀️ 跟随系统的深色模式 + 右上角手动切换按钮（localStorage 持久化）
- 用 `file://` 协议直接浏览器打开亦可

## 声明

学习者整理。所有内容基于 UCSD DSC10 公开课程材料与历年 practice exam（来源：[practice.dsc10.com](https://practice.dsc10.com)）。仅供学习交流使用。
