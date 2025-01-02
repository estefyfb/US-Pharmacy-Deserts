# US-Pharmacy-Deserts  
**Identifying Pharmacy Deserts in the United States Using Census Data**  

The `PharmacyDeserts_UnitedStates_GetData` notebook demonstrates a Python-based data pipeline developed to retrieve, transform, and merge six datasets from the U.S. Census Bureau. The processed data is stored in a SQL Server database for analysis.  

### Datasets Used:
- **State FIPS Codes**: Standardized state identifiers.  
- **Centers of Population at Block-Group Level (2020)**: Geographic coordinates representing population centers.  
- **ACS 2020 5-Year Estimates: Block Group Population**: Demographic data at the block group level.  
- **ACS 2020 5-Year Estimates: Housing Units**: Housing data at the block group level.  
- **TIGER/Line Block Group Shapefiles (2020)**: Geographic shapefiles with geolocation data.  
- **2020 to 2010 Block Group Relationship File**: Links 2020 block groups to 2010 block groups for temporal comparisons.  

This pipeline facilitates a comprehensive analysis of pharmacy access across the United States, enabling the identification of underserved areas, commonly referred to as "pharmacy deserts."
