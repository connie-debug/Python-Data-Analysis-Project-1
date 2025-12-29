# Palmer Archipelago Penguin Data Analysis & Visualization
# 帕莫群岛企鹅数据分析与可视化

## Project Description / 项目描述
This project performs a comprehensive data cleaning, exploratory data analysis (EDA), and visualization on the Palmer Archipelago penguin dataset. The goal is to explore the relationships between penguin species, sex, island location, and their physical attributes (body mass, culmen dimensions, flipper length) through statistical analysis and visual representations.

本项目对帕莫群岛企鹅数据集进行了全面的数据清洗、探索性数据分析（EDA）和可视化。目标是通过统计分析和可视化展示，探索企鹅物种、性别、岛屿位置与其物理特征（体重、喙部尺寸、鳍肢长度）之间的关系。

## Current Status / 当前状态
✅ **Completed / 已完成**: Data loading, assessment, cleaning (handling missing values, correcting inconsistencies, removing invalid data), species distribution visualization
✅ **已完成**: 数据加载、评估、清洗（处理缺失值、纠正不一致数据、移除无效数据）、物种分布可视化
🔄 **In Progress / 进行中**: Exploratory Data Analysis (EDA) and building comprehensive visualizations
🔄 **进行中**: 探索性数据分析（EDA）与构建全面的可视化图表
📅 **Future Plan / 计划中**: Advanced statistical analysis and interactive dashboard creation
📅 **计划中**: 高级统计分析与交互式仪表盘制作

## Dataset Overview / 数据集概览
The dataset contains 344 penguin samples from three islands in Antarctica's Palmer Archipelago. Variables include:
- **species**: Penguin species (Adelie, Gentoo, Chinstrap)
- **island**: Island where found (Torgersen, Biscoe, Dream)
- **culmen_length_mm**: Culmen (bill) length in millimeters
- **culmen_depth_mm**: Culmen depth in millimeters
- **flipper_length_mm**: Flipper length in millimeters
- **body_mass_g**: Body mass in grams
- **sex**: Penguin sex (MALE, FEMALE)

数据集包含来自南极帕莫群岛三个岛屿的344只企鹅样本。变量包括：
- **species**: 企鹅物种（阿德利企鹅、巴布亚企鹅、帽带企鹅）
- **island**: 发现岛屿（托格森岛、比斯科岛、梦想岛）
- **culmen_length_mm**: 喙长度（毫米）
- **culmen_depth_mm**: 喙深度（毫米）
- **flipper_length_mm**: 鳍肢长度（毫米）
- **body_mass_g**: 体重（克）
- **sex**: 企鹅性别（雄性、雌性）

## Tech Stack / 技术栈
- **Language / 语言**: Python
- **Core Libraries / 核心库**: Pandas, NumPy, Matplotlib, Seaborn
- **Environment / 环境**: Jupyter Notebook
- **Visualization / 可视化**: Pie charts, statistical plots, exploratory graphs

## Key Analysis Objectives / 主要分析目标
1. **Data Quality Assessment**: Identify and handle missing values, inconsistencies, and invalid data
   **数据质量评估**: 识别并处理缺失值、不一致数据和无效数据
2. **Species Distribution Analysis**: Understand penguin species composition across islands
   **物种分布分析**: 了解各岛屿企鹅物种组成
3. **Physical Attribute Exploration**: Analyze relationships between physical measurements
   **物理特征探索**: 分析物理测量值之间的关系
4. **Comparative Analysis**: Compare attributes across species, sex, and islands
   **比较分析**: 跨物种、性别和岛屿比较特征

## Data Cleaning Process / 数据清洗流程
1. **Data Loading**: Import raw CSV data into Pandas DataFrame
   **数据加载**: 将原始CSV数据导入Pandas DataFrame
2. **Data Assessment**: Evaluate structure and content issues
   **数据评估**: 评估结构和内容问题
3. **Missing Data Handling**: Remove observations with complete missing values
   **缺失数据处理**: 移除完全缺失的观测值
4. **Data Type Conversion**: Convert categorical variables to appropriate types
   **数据类型转换**: 将分类变量转换为适当类型
5. **Inconsistency Correction**: Fix invalid values in categorical columns
   **不一致性纠正**: 修复分类列中的无效值
6. **Data Export**: Save cleaned dataset for analysis
   **数据导出**: 保存清洗后的数据集用于分析

## How to Use / 如何使用
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/connie-debug/Python-Data-Analysis.git
   ```
   克隆本仓库到本地。

2. Ensure you have Python and required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
   确保安装了Python及必要的库。

3. Open and run the Jupyter Notebook to reproduce the analysis:
   ```bash
   jupyter notebook "可上传到github（最后在这里练习整理上传）.ipynb"
   ```
   打开并运行Jupyter Notebook文件，重现整个分析流程。

4. The notebook contains:
   - Complete data loading and cleaning pipeline
   - Exploratory data analysis with visualizations
   - Statistical summaries and insights
   
   笔记本包含：
   - 完整的数据加载和清洗流程
   - 带有可视化的探索性数据分析
   - 统计摘要和洞察

## Visualizations Included / 包含的可视化
- **Species Distribution Pie Chart**: Shows percentage distribution of penguin species
  **物种分布饼图**: 显示企鹅物种的百分比分布
- **Island Distribution Analysis**: Visual representation of penguins across islands
  **岛屿分布分析**: 各岛屿企鹅分布的可视化表示
- **Sex Distribution Analysis**: Gender composition of the penguin population
  **性别分布分析**: 企鹅种群的性别组成

## Key Findings / 主要发现
1. The dataset contains three penguin species with Adelie being the most common
   **数据集包含三种企鹅物种，阿德利企鹅最为常见**
2. Data cleaning revealed missing values in physical measurements and sex columns
   **数据清洗发现了物理测量值和性别列中的缺失值**
3. Inconsistencies were found and corrected in the sex column
   **在性别列中发现并纠正了不一致数据**
4. Statistical summaries provide baseline understanding of penguin physical attributes
   **统计摘要提供了对企鹅物理特征的基线理解**

## Next Steps / 下一步计划
1. **Advanced Visualizations**: Create scatter plots, box plots, and heatmaps to explore relationships
   **高级可视化**: 创建散点图、箱线图和热力图来探索关系
2. **Statistical Testing**: Perform ANOVA and correlation analysis
   **统计测试**: 执行方差分析和相关性分析
3. **Interactive Dashboard**: Build a Streamlit or Plotly dashboard for interactive exploration
   **交互式仪表盘**: 构建Streamlit或Plotly仪表盘进行交互式探索
4. **Predictive Modeling**: Explore machine learning models for species classification
   **预测建模**: 探索用于物种分类的机器学习模型

## Viewing the Notebook / 查看笔记本说明
**Note for GitHub Preview**: Some visualizations in the Jupyter notebook may not render properly in GitHub's built-in preview due to technical limitations.

**GitHub预览说明**: 由于技术限制，Jupyter笔记本中的部分可视化内容可能无法在GitHub内置预览中正常显示。

**To view the full notebook with complete outputs:**
**完整查看笔记本的方法：**

1. **Download** the `.ipynb` file and open it locally with Jupyter Notebook or VS Code
   **下载** `.ipynb` 文件，并在本地的 Jupyter Notebook 或 VS Code 中打开

2. **OR use the online Nbviewer service:**
   **或 使用在线的 Nbviewer 服务：**
   - Go to https://nbviewer.jupyter.org/
   - Paste this notebook's URL
   - Click "Go!"
   
   - 访问 https://nbviewer.jupyter.org/
   - 粘贴此笔记本的链接
   - 点击 "Go!"

## Dependencies / 依赖项
- Python 3.7+
- Pandas 1.3+
- NumPy 1.21+
- Matplotlib 3.4+
- Seaborn 0.11+

## File Structure / 文件结构
```
├── README.md                          # This file / 本文件
├── penguins.csv                       # Raw dataset / 原始数据集
├── cleaned_data_1.csv                 # Cleaned dataset / 清洗后的数据集
└── 可上传到github（最后在这里练习整理上传）.ipynb  # Main analysis notebook / 主分析笔记本
```

## License / 许可证
This project is for educational and portfolio purposes. The penguin dataset is publicly available for academic use.

本项目用于教育和作品集展示目的。企鹅数据集公开可用于学术用途。

---
**Author**: Connie-debug  
**Last Updated**: December 2023  
**作者**: Connie-debug  
**最后更新**: 2023年12月
