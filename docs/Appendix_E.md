# Appendix E　Data Sources, Licenses, and Usage Notes

To fully respect the intellectual property and labor of data providers, this study strictly complies with academic ethics and the usage agreements of each database. All data are used solely for academic paper writing and are not for commercial use, redistribution, or modification of original files.

### E.1 Macro-Level Data
- **World Inequality Database (WID.world)**  
  Source: Paris School of Economics, World Inequality Lab  
  Files: `WID_Data_03052026-135127.csv`, `WID_Data_21042026-163112.csv`  
  Version: 2026 update (wealth share series 1995–2023)  
  Usage restrictions: Free for academic research; must cite WID.world completely and note download date. Commercial use or large-scale redistribution is prohibited.  
  Notes: Missing values were handled with MICE multiple imputation.

- **Edelman Trust Barometer**  
  Source: Edelman Trust Institute  
  Files: `2025 Edelman Trust Barometer Global Report_01.23.25.pdf`, `2026 Edelman Trust Barometer Global Report_01.21.26.pdf`  
  Version: 2025 and 2026 editions (28 countries, 33,938 respondents)  
  Usage restrictions: Reports and data are for academic citation only; must fully cite report title, year, and official Edelman source.  
  Notes: Trust indices may be affected by short-term events (pandemics, wars, leadership changes); robustness checks excluding exogenous shock years were performed in Section 8.8.1.

- **World Inequality Report 2026 Country Sheets**  
  Source: World Inequality Lab  
  File: `WIR26_Country_Sheets资料1.pdf`  
  Usage restrictions: Must cite the WIR 2026 report when used.

- **Figure 1 Data**  
  Source: Author-compiled (based on WID and WIR 2026)  
  File: `图1数据.csv` (39 countries, ε + CRJ)  
  Usage restrictions: Author-derived data for this paper only.

### E.2 Meso-Level Data
- **World Input-Output Database (WIOD)**  
  Source: WIOD Consortium (University of Groningen et al.)  
  File: `WIOT2014_Nov16_ROW.xlsb`  
  Version: 2016 Release (2014 data, 43 countries + RoW, 56 sectors)  
  Usage restrictions: For academic research only; must cite official publications (Timmer et al., 2015; 2016). Commercial use and redistribution of raw data are prohibited.  
  Notes: Large binary file used only for network structure analysis; no modifications were made.

- **OECD TiVA (Trade in Value Added)**  
  Source: OECD Statistics and Innovation Directorate  
  Files: Multiple TiVA 2025 CSV files (Principal Indicators)  
  Version: 2025 edition (including 2023–2024 nowcasting)  
  Usage restrictions: Public academic resource; must fully cite OECD TiVA database and version.  
  Notes: Nowcasting data carry some uncertainty; sensitivity analysis was conducted in Section 8.8.1.

### E.3 Micro-Level Data
- **Zenodo 2026 Global Behavioral Economics Experiments Dataset**  
  Source: Zenodo platform (DOI: 10.5281/zenodo.19152662)  
  File: `19210655.zip`  
  Version: March 2026 release (1990–2025 meta-analysis of four paradigms)  
  Usage restrictions: CC BY 4.0 license; must cite the dataset DOI.  
  Notes: Meta-analysis of laboratory experiments; not longitudinal field panel data.

- **PSID-SCF Joint Wealth Dynamics Data**  
  Source: Panel Study of Income Dynamics (University of Michigan) + Survey of Consumer Finances (Federal Reserve Board)  
  File: `PSID-SCF.xlsx`  
  Version: 2007–2019 waves  
  Usage restrictions: Must cite official PSID User Guide and SCF reports.  
  Notes: Author-compiled summary table of wealth percentiles and composition; raw microdata must be requested from official PSID/SCF websites.

- **FRED U.S. Macro History Data**  
  Source: Federal Reserve Economic Data (St. Louis Fed)  
  Files: `fred-us-macro-history.json` and related series  
  Version: Updated to 2026 (1913–2026)  
  Usage restrictions: Fully public and free; citation of St. Louis Fed is recommended.

### E.4 General Data Usage Statement
1. All raw data come from public academic channels and involve no confidential or restricted materials.
2. All data processing (imputation, Winsorization, HP filtering, Bootstrap) was performed locally in a Jupyter environment; no raw files were uploaded or shared.
3. Upon final publication, the paper’s data availability statement will provide official access links and DOIs for each database.
4. For complete raw datasets, please contact the respective data providers directly (WID.world, OECD, WIOD, PSID, SCF, Edelman, Zenodo, FRED).
5. This study adheres to the Declaration on Research Assessment (DORA) and open science principles.

The authors express sincere gratitude to all data providers and research teams. Without their long-term, rigorous data collection and open sharing, this research would not have been possible.

**End of Appendix E**
