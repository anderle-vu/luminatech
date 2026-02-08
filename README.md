**Luminatech Data Cleaning**

A reproducible Python-based data cleaning and preprocessing workflow for the Luminatech Australia Sales Analytics Project, used to transform raw B2B transactional datasets into analysis-ready files for SQL modelling, and dashboard development via Tableau.

**Project Overview**

This repository contains the full data preparation workflow for the Luminatech analytics project.
The goal of this pipeline is to:
- Import and validate large multi-table datasets
- Clean and standardise sales, customer, product, and salesperson information
- Handle missing values, inconsistent formats, and currency conversions
- Generate cleaned datasets ready for analytics and dashboards
  
**Executive Summary**

Luminatech Australia has demonstrated clear and predictable sales seasonality across 2021–2024, with strong mid-year and late-year demand cycles driving revenue, average order value (AOV), and order volume. Sales revenue peaks reached **$48.76M**, while troughs fell to **$26.24M**, consistently following structured procurement patterns from B2B customers. AOV movements aligned with these cycles, fluctuating between **$1,526** and **$2,169**, driven largely by shifts in product mix and promotional uptake. Order volume followed the same pattern with peaks of **3.87M** orders, confirming that revenue swings are primarily driven by changes in demand intensity rather than irregular market shocks.

Product-level performance:

- **STAR1** and **STARBURSTEC01** show the strongest seasonal sensitivity, with major demand spikes in 2024 that significantly lifted total revenue while maintaining high and stable profit margins.
- **JS97KE01L** and **FFRLED** maintained steadier performance, with moderate increases in months where STAR1 and STARBURSTEC01 drops but experienced margin declines, indicating cost pressures or pricing issues and weakening demand in late-year quarters.
- **PND236EL** stands out as a high-potential product, combining strong sales growth since 2022 with improving profit margins in 2024, making it a reliable contributor to both volume and profitability.

Evaluation of Luminatech’s loyalty program shows that loyalty customers are the core revenue engine, generating monthly peaks above **$140M**, compared with non-loyalty customers whose sales remained below **$50M**. Although AOV patterns for both groups track similarly, non-loyalty customers occasionally exceed loyalty AOV in select months, indicating targeted opportunities to convert high-value non-loyalty buyers into recurring loyalty members.

Overall, Luminatech’s performance is shaped by predictable seasonality, concentrated SKU-level revenue drivers, and a strong loyalty customer base. These insights provide a clear pathway for optimising demand planning, targeting high-potential products, enhancing pricing strategies, and strengthening loyalty engagement to support sustainable future growth.
