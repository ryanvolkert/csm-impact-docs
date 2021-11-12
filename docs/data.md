# Data

## Sharing
When a new data sharing cadence is established for a customer, DS will create a shared folder on Google Drive where the CSM will deliver updated datasets.

File names should avoid capitalization, special characters, and spaces when possible. For example, `bradley_lead_group_data.xlsx` or `blg_data.xlsx` are acceptable file names, while `Bradley Lead Group Data.xlsx` is not.

If there are security requirements from a specific client that require FTP or something similar, DS will attempt to accommodate those needs.

## Examples
Customers should share data at the agent-time level. Agent-time data are records where each observation represents a single agent-time (e.g. day or week) combination. To use this type of data for an analysis, DS must know who the agent is, whether they make calls using Balto, the time unit of observation, and the KPI value for each agent-time row. Sharing data in this format allows us to line up customer data with what we can pull from our database. Below is an example data sets.

**CallDate**|**VendorCampaignName**|**Agent**|**AgentLevel**|**DialAttempt**|**GrossConnections**|**HumanContacts**|**Total\_Att\_Transfers**|**UniqueTransferAttempts**|**UniqueConnectedTransfers**|**UniqueTransferSuccess**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
2021-09-01|Allied - Campaign - SQS Lead Screening|allied\_tyler|Specialty|1|1|1|0|0|0|0
2021-09-01|Allied - Campaign - SQS Lead Screening|allied\_pamala|Specialty|2|1|1|0|0|0|0
2021-09-01|Allied - Life Standard|allied\_stephen|Specialty|2|1|1|0|0|0|0
2021-09-01|Allied - Life Standard|allied\_marge|Specialty|3+|2|1|0|0|0|0
2021-09-01|Allied - Medicare Standard|allied\_tim|Specialty|1|87|56|5|5|5|5
2021-09-01|Allied - Medicare Standard|allied\_evelyn|Specialty|2|7|3|0|0|0|0
2021-09-01|Allied - Medicare Standard|allied\_john|Specialty|3+|163|60|4|4|3|2
2021-09-01|Allied - Medicare Standard - Double Dial|allied\_catherine|Specialty|1|11|5|2|2|1|1
2021-09-01|Allied - Medicare Standard - Double Dial|allied\_jack|Specialty|2|27|11|3|3|3|2
