# Medicare Fraud Rings
Databases used for a research project testing the effect of adding OSINT relationships to medicare claims on community detection of fraud rings. There are 4 databases

* Base - Vanilla Medicare claims import (2019-2021 claims Parts B and D)
https://1drv.ms/u/s!ApppGSjeYcTxifMJs9aB0HXa9z9K7w?e=s1u82G
  
* Base_KNN - Medicare claims import (2019-2021 claims Parts B and D) with FastRP embeddings and KNN-derived relationships
https://1drv.ms/u/s!ApppGSjeYcTxifMIxpn4mCoAdUv5Dw?e=b2XHwB
  
* OSINT - Medicare claims import (2019-2021 claims Parts B and D) with confirmed business relationships added between 100 labeled nodes
https://1drv.ms/u/s!ApppGSjeYcTxifJ9WTEdgeP7_MXfcw?e=bmajWd

* OSINT_KNN - Medicare claims import (2019-2021 claims Parts B and D) with both OSINT-derived and KNN-derived edges added
https://1drv.ms/u/s!ApppGSjeYcTxifJ-aNyo0oECjQ8cTg?e=dZkCed

![image](https://github.com/user-attachments/assets/898620c3-9a45-4341-87b5-79bc17557410)

![image](https://github.com/user-attachments/assets/473028ab-6fb8-4100-93d2-a1a72d0479e2)

|Data Set Name|Description|Year|Version|Rows|Columns|
|:----|:----|:----|:----|:----|:----|
|Medicare Part B Outpatient|Physician & Other Practitioners - by Provider and Service|2019|867b8ac7-ccb7-4cc9-873d-b24340d89e32|10,140,228|28|
|Medicare Part B fee-for-service|Physician & Other Practitioners - by Provider and Service|2020|c957b49e-1323-49e7-8678-c09da387551d|9,449,361|28|
|Medicare Part B fee-for-service|Physician & Other Practitioners - by Provider and Service|2021|31dc2c47-f297-4948-bfb4-075e1bec3a02|9,886,177|28|
|Medicare Part B - DMEDS|Medicare Durable Medical Equipment, Devices & Supplies - by Referring Provider and Service|2019|eb0019f6-791d-4065-ae4e-4761d2f6c9f2|1,656,449|33|
|Medicare Part B - DMEDS|Medicare Durable Medical Equipment, Devices & Supplies - by Referring Provider and Service|2020|323df359-ceac-4525-a350-e2cd9eb128fe|1,607,435|33|
|Medicare Part B - DMEDS |Medicare Durable Medical Equipment, Devices & Supplies - by Referring Provider and Service|2021|46ae675c-bc81-40ca-aa79-64da1c1ec9d9|1,516,153|33|
|Medicare Part D Prescribers|Part D Prescribers by provider and Drug|2019|2a6705e6-7a1e-460c-ba22-35249a531918|25,401,870|22|
|Medicare Part D Prescribers|Part D Prescribers by provider and Drug|2020|7795fe20-e80e-435a-a9ed-d2d65e05feeb|25,209,729|22|
|Medicare Part D Prescribers|Part D Prescribers by provider and Drug|2021|ab29d858-269a-4d97-908f-a26b1cf95f61|25,231,862|22|
|Medicare Part B DME|Medicare Durable Medical Equipment, Devices & Supplies - by Supplier and Service|2019|5165dbdd-eae3-4b94-82cd-da635e00e0fa|575,223|32|
|Medicare Part B DME|Medicare Durable Medical Equipment, Devices & Supplies - by Supplier and Service|2020|1fe3a8c3-ecfd-44b9-9418-fda1843f72a5|542,090|32|
|Medicare Part B DME|Medicare Durable Medical Equipment, Devices & Supplies - by Supplier and Service|2021|e531ffc9-57ad-48db-8d88-f686edb8b8e1|508,052|32|
|LEIE Database|https://oig.hhs.gov/exclusions/exclusions_list.asp|2025|February 2025|Only matched NPIs| |
|NPI Database|https://download.cms.gov/nppes/NPI_Files.html|2025|NPPES|Only addresses for matched NPIs| |




