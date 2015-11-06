# build-stats
This repo houses build-stats for dataset creation

**JSON Legend:**

| Key   |      Definition      |
|----------|:-------------:|
| donors | the # of donors participating in development projects |
| runs |    records # of builds in jenkins   |
| geocoded_projects | # of projects that are geocododed |
| geocoded_commitments | the total sum of commitments (USD) for geocoded projects  |
| locations  | # of locations across all projects |
| years | year range that all projects occur across  |
| geocoded_disbursements | the total sum of disbursements (USD) for geocoded projects |
| total_projects | # of projects in the dataset |
| scores | holds an array of scores relevant to the dataset type |
| total_commitments | the total sum of commitments (USD) for projects in the dataset |
| total_disbursements | the total sum of disbursements (USD) for projects in the dataset |
| date_coverage | percentage of projects that have full date information (starting and ending date) |
| geographic_coverage | finds the percentage of projects that are geocoded |
| geographic_precision | percentage of all locations that have a precision code 1,2, or 3 value |
| compare_financials | compares the bulk sum of commitments from the projects table to the bulk sum of commitments from the AidData API |
| sector_detail | percentage of projects that DO NOT have ambiguous sector information (codes of 430|43010|988|99810) |


    
