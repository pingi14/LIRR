# Long Island Railroad OTP Analysis

## Project Background
In our continuous effort to understand and enhance the performance of the Metropolitan Transportation Authority (MTA) Long Island Rail Road (LIRR), we’ve conducted a series of data-driven analysis. These delve into various aspects of on-time performance (OTP), assessing trends, pinpointing weaknesses and identifying opportunities for improvement.

## Executive Summary
The application of SQL queries to analyse the on-time performance data of the MTA and LIRR has provided valuable insights into the operational strengths and areas for improvement within the network. The applied detailed analysis help in making data-informed decisions to enhance the reliability and efficiency of rail services, ultimately benefiting daily commuters and the organisation.

## Technical Project Information
Data Source: https://data.ny.gov/Transportation/MTA-LIRR-On-Time-Performance-Beginning-2015/6kq9-5ikh/about_data

The data was downloaded from LIRR site as a .csv file containing monthly OTP (On-Time Performance) percentage data from all LIRR Branch Lines between 2015-2024.  SQL was applied to cleans the data and was then visualised via Power BI.  [Please refer to SQL Scripts applied](https://github.com/pingi14/LIRR/blob/main/SQL%20Scripts_v2.pdf)

## Key Insights

- Every year except 2022 the Far Rockaway proved to be the most efficient line by OTP Performance (2022 was West Hempstead - 2023 and 2024 was Port Washington)
- 5 out of the 11 Lines (45%) overall OTP performance exceeded the 91.4% by Branch Average
- All lines achieved the highest OTP during Off-Peak Periods
![Picture1a](https://github.com/user-attachments/assets/33411744-3749-4ab8-b820-924c74f9945f)

- The months of April and May experienced the lowest OTP Percentages
![Picture2a](https://github.com/user-attachments/assets/0e84b8ec-4ce7-4bc3-b278-5397aec43a72)

- 2020 experienced the largest decline in OTP Performance (Suspected reason - COVID), but then a rapid incline incurred 12 months later
![Picture3a](https://github.com/user-attachments/assets/28e7e7f3-6b25-4214-9873-2120e250931f)

- as per first dot point, the Far Rockaway line achieved the most months between 2015 to 2024 OTP exceeding 90%.  
- The spike in performance at the end of 2021 showed 7 out of 11 lines (64%) achieving over 90% OTP in all months
![Picture4a](https://github.com/user-attachments/assets/98622903-b610-4884-a6b5-a1aa0820a356)

## Recommendations
- Extensive focus on the Port Jefferson, Montauk and Huntington lines as they have the lowest average OTP for the previous three years

## Assumptions & Caveats
- LIRR data for incidents was not incorporated on this analysis.  Thus, findings on OTP data may not be 100% conclusive.  Incidents surrounding these lines, that may/may not be the cause of runs arriving within 6 minutes of final destination
