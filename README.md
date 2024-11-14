# Walkable Accessibility Score
This repository contains the code and downloadable data for calculating an open source Walkable Accessibility Score (WAS), a spatially-granular measure of walkability based on point of interest (POI) data from 1997 to 2019. The method in the supplied Jupyter Notebooks can be applied from any set of demand units to any set of supply points; in this case we have used US Census block groups as the demand units and InfoUSA business points (in addition to school and park locations) as the supply points. The paper describing parameter fine-tuning and comparison to proprietary walkability metrics is forthcoming; an extended abstract for the paper appears in the proceedings for the [2024 GISRUK Conference](https://zenodo.org/communities/gisruk2024/records?q=&l=list&p=1&s=10&sort=newest). 

This repository contains two main notebooks:
- [Comparing the 2011 Walkscore data with the Walkable Accessibilty Score](https://github.com/kcredit/Walkable-Accessibility-Score/blob/main/src/Walkscore%20and%20Walkable%20Accessibility%20Score.ipynb)
- [Running the Walkable Accessiblity Score for all years from 1997 to 2019](https://github.com/kcredit/Walkable-Accessibility-Score/blob/main/src/for_all_years.ipynb)

Please note that you will not be able to replicate the analysis if you do not have InfoUSA data. However, you can replicate the analysis using your own POI data.
For this reason, we created two [tutorials](https://github.com/kcredit/Walkable-Accessibility-Score/tree/main/tutorials) with public open data so that you can follow along the code and make sure it is working correctly in your computer.

The full set of aggregated WAS values at the block group level for the continental US from 1997-2019 are provided for download in the shapefile 'US_WAS_1997_2019.shp.zip' in the [output folder](https://github.com/kcredit/Walkable-Accessibility-Score/tree/main/output).

Please cite the conference paper when using the aggregate data or code:

Credit, K., Farah, I., Talen, E., Anselin, L., & Ghomrawi, H. (2024). The Walkable Accessibility Score (WAS): A spatially-granular open-source measure of walkability for the continental US from 1997-2019. *Proceedings of the 32nd GISRUK Conference*. Available from: https://zenodo.org/records/10899286.
