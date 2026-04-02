\# 招聘数据分析项目（Job Data Analysis）



\## 一、项目背景



基于公开招聘数据，对数据分析岗位的薪资水平、技能需求及城市分布进行分析，帮助理解当前就业市场情况。



\---



\## 二、数据来源



\* 数据来源：Glassdoor 招聘数据（Kaggle）

\* 数据规模：约 \*\*2000+ 条\*\*



\---



\## 三、分析内容



\### 1. 薪资分布分析



对 `Salary Estimate` 字段进行清洗，将薪资区间转换为平均值（如 $50K-$80K → 65K），分析整体薪资分布情况。



!\[salary](./images/salary.png)



\---



\### 2. 技能需求分析



基于 `Job Description` 字段，统计关键词（Python、SQL）的出现频率，分析企业对核心技能的需求情况。



!\[salary](./images/salary.png)



\---



\### 3. 城市薪资对比



提取 `Location` 字段中的城市信息，计算不同城市的平均薪资水平，并进行对比分析。



!\[city](./images/city.png)



\---



\## 四、技术栈



\* Python

\* pandas（数据处理）

\* matplotlib（数据可视化）



\---



\## 五、项目亮点



\* 对薪资区间数据进行结构化处理（区间 → 均值）

\* 基于文本数据提取技能关键词（Python / SQL）

\* 完成从数据清洗 → 分析 → 可视化的完整流程



\---



\## 六、分析结论



\* 数据分析岗位薪资存在明显区间分布，高薪岗位集中在部分城市

\* Python 与 SQL 为招聘中最核心的技能要求

\* 不同城市之间薪资水平存在明显差异



\---



\## 七、项目结构



```text

job-data-analysis/

├── data/

│   └── raw\_data.csv

├── notebook/

│   └── analysis.ipynb

├── images/

│   ├── salary.png

│   ├── skills.png

│   └── city.png

└── README.md

```



