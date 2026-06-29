# 中文数据分析与可视化工具箱

![preview](assets/preview.png)

数据工具不应该只为画一张好看的图服务。真正省时间的是从清洗、分析、查询到展示能连成一条线。

小数据别过度工程化，大数据别硬塞进 Pandas。面向别人展示时，交互和权限会比图表样式更重要。

## 先看这几个

Jupyter / Pandas / Polars / DuckDB

Notebook 探索，DuckDB/Polars 处理，Plotly/ECharts 展示，Streamlit/Superset 交付。

## 入口

| 名称 | 我为什么留它 |
| --- | --- |
| [Jupyter](https://jupyter.org/) | Notebook 数据分析环境。 |
| [Pandas](https://pandas.pydata.org/) | Python 数据分析基础库。 |
| [Polars](https://pola.rs/) | 高性能 DataFrame。 |
| [DuckDB](https://duckdb.org/) | 嵌入式分析数据库。 |
| [Plotly](https://plotly.com/python/) | 交互式图表。 |
| [Apache ECharts](https://echarts.apache.org/) | 强大的开源可视化图表库。 |
| [Streamlit](https://streamlit.io/) | 快速构建数据 App。 |
| [Apache Superset](https://superset.apache.org/) | 开源 BI 平台。 |

## 我的使用顺序

- 小数据先 Pandas，大数据/本地分析试 DuckDB/Polars。
- 展示给别人看时用 Streamlit 或 Superset。
- 论文图表先保证可复现。

## 别踩坑

- 不要把图做得比数据更复杂。
- dashboard 上线前要处理权限和数据脱敏。

## 截图来源

这张图来自公开页面：[https://github.com/apache/echarts](https://github.com/apache/echarts)。如果页面改版，截图可能会和当前官网略有出入。

## 维护方式

链接数据放在 [`data/links.json`](data/links.json)。我倾向于少而准：入口失效就换，说明过时就改，不把这里做成什么都往里塞的大杂烩。

## License

MIT. 第三方商标、页面截图和网站内容归原权利方所有；本仓库只做中文导航和使用笔记。
