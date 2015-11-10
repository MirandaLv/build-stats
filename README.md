# build-stats
This repo houses build-stats for dataset creation

**JSON Legend:**

| Key   |      Definition      |
|----------|:-------------:|
| donors | the # of donors participating in development projects |
| runs |    records # of builds  |
| geocoded_projects | # of projects that are geocoded |
| geocoded_commitments | the total sum of commitments (USD2011) for geocoded projects  |
| locations  | # of locations across all projects |
| years | year range that all projects occur across  |
| geocoded_disbursements | the total sum of disbursements (USD) for geocoded projects |
| total_projects | # of projects in the dataset |
| scores | holds an array of scores relevant to the dataset type |
| total_commitments | the total sum of commitments (USD2011) for projects in the dataset |
| total_disbursements | the total sum of disbursements (USD) for projects in the dataset |
| date_coverage | percentage of projects that have start date |
| geographic_coverage | the percentage of projects that are geocoded |
| geographic_precision | percentage of all locations that have a subnational locations |
| compare_financials | compares the sum of commitments from the projects table to the sum of commitments from the AidData Core Database |
| sector_detail | percentage of projects that DO NOT have ambiguous sector information (codes of 430, 43010, 988, 99810) |


    
