# Transformation Components

| Component | (native) | CData | CozyRoc | Devart | KingswaySoft | Task Factory | ZappySys | Other |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Address Parse |  |  | X[^1] |  | X | X[^2] |  |  | 
| Address Verification |  |  |  |  | X | X |  |  | 
| Aggregate | X |  |  |  | X[^3] | X[^3] |  |  | 
| Audit | X |  |  |  |  |  |  |  | 
| Balanced Data Distributor | X |  |  |  |  |  |  |  | 
| Cache Transform | X |  |  |  |  | X[^3][^4] |  |  | 
| Case Transform |  |  |  |  |  | X |  |  | 
| CDC Splitter | X |  |  |  |  |  |  |  | 
| Character Map | X |  |  |  |  |  |  |  | 
| Checksum |  |  |  |  |  |  |  | X[^5][^6] | 
| Conditional Split | X |  |  |  |  | X[^3][^4] |  | X[^5][^6][^7] | 
| Copy Column | X |  |  |  |  |  |  |  | 
| CSV Generator |  |  |  |  | X[^8] | X[^9] | X |  | 
| CSV Parser |  |  |  |  | X[^10] | X[^11] | X |  | 
| Data Anonymizer |  |  |  |  | X |  |  |  | 
| Data Cleansing | X[^12] |  |  |  |  | X |  | X[^5][^6][^13] | 
| Data Conversion | X |  |  |  | X[^3] |  |  |  | 
| Data Flow Nugget |  |  |  |  |  | X |  |  | 
| Data Mining Query | X |  |  |  |  |  |  |  | 
| Data Profiler |  |  |  |  | X |  |  |  | 
| Data Validation |  |  |  |  |  | X |  |  | 
| Delete Batch |  |  |  |  |  | X[^4] |  |  | 
| Derived Column | X |  |  |  | X[^3] | X[^3] |  |  | 
| Difference Detector |  |  |  |  | X |  |  |  | 
| Duplicate Detector |  |  |  |  | X |  |  |  | 
| Error Output Description |  |  |  |  |  | X |  |  | 
| Export Column | X |  |  |  |  |  |  |  | 
| Filter Rows |  |  |  |  |  | X |  |  | 
| Flow Synchronization |  |  | X |  |  |  |  |  | 
| Fuzzy Grouping | X |  |  |  |  |  |  |  | 
| Fuzzy Lookup | X |  |  |  | X[^14] |  |  |  | 
| Hash |  |  |  |  | X | X |  |  | 
| Import Column | X |  |  |  |  |  |  |  | 
| Javascript Component |  |  | X |  |  |  |  |  | 
| JSON Generator |  |  |  |  | X[^8] | X[^9] | X |  | 
| JSON Parser |  |  | X |  | X[^10] | X[^11] | X[^5] |  | 
| Lookup | X |  | X | X[^15] | X[^14] | X[^3][^4] |  |  | 
| Merge | X |  |  |  |  |  |  |  | 
| Merge Join | X |  |  |  |  |  |  |  | 
| Multicast | X |  |  |  |  |  |  |  | 
| Null Handler |  |  |  |  |  | X |  |  | 
| OLE DB Command | X |  |  |  |  |  |  |  | 
| Percentage Sampling | X |  |  |  |  |  |  |  | 
| Pivot | X |  |  |  |  |  |  |  | 
| Placeholder |  |  |  |  |  | X[^16] |  |  | 
| Query |  |  | X |  |  |  |  |  | 
| Regex Replace |  |  |  |  |  | X |  |  | 
| Replace Unwanted Characters |  |  |  |  |  | X |  |  | 
| Row Count | X |  |  |  |  |  |  | X[^5][^6] | 
| Row Number |  |  |  |  |  |  |  | X[^5][^6] | 
| Row Sampling | X |  |  |  |  |  |  |  | 
| Script Component | X |  | X |  |  |  |  |  | 
| Service Lookup |  |  |  |  | X |  |  |  | 
| Set Variable |  |  |  |  |  |  | X[^5] |  | 
| Slowly Changing Dimension | X |  |  |  | X[^3] | X[^17] |  |  | 
| Sort | X |  | X |  |  |  |  |  | 
| Surrogate Key |  |  |  |  |  | X |  |  | 
| Table Difference |  |  | X |  |  |  |  |  | 
| Template Merge |  |  | X[^18] |  | X[^19] |  | X[^5] |  | 
| Term Extraction | X |  |  |  |  |  |  |  | 
| Term Lookup | X |  |  |  |  |  |  |  | 
| Time Zone Conversion |  |  |  |  | X | X |  |  | 
| Trim Plus |  |  |  |  |  | X |  |  | 
| Union All | X |  |  |  |  |  |  |  | 
| Unpivot | X |  |  |  |  |  |  |  | 
| Update Batch |  |  |  |  |  | X[^4] |  |  | 
| Value Mapping |  |  |  |  | X |  |  |  | 
| Web Service |  |  |  |  | X |  |  |  | 
| XML Generator |  |  |  |  | X[^8] | X[^9] | X |  | 
| XML Parser |  |  |  |  | X[^10] | X[^11] | X[^5] |  | 

## Notes

[^1]: US Postal Addresses

[^2]: Not in Task Factory Azure Data Factory edition

[^3]: Includes enhanced functionality

[^4]: Only in Task Factory Azure Data Factory edition

[^5]: Free

[^6]: From Konesans

[^7]: Regular Expression component

[^8]: Composition Transform

[^9]: Pack Data Transform

[^10]: Decomposition Transform

[^11]: Unpack Data Transform

[^12]: Requires DQS

[^13]: RegexClean component

[^14]: Premium Lookup component combines Lookup and Fuzzy Lookup into one

[^15]: Provides advanced lookup components for Amazon Redshift, Azure SQL DW, DB2, Google BigQuery, MySQL, Oracle, PostgreSQL, and Snowflake

[^16]: Developers can use as a placeholder for future transformations

[^17]: Dimension Merge SCD provides improved performance

[^18]: Uses Apache Velocity templates

[^19]: Components to merge into HTML or Text templates

