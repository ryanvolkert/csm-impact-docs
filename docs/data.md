# Data

## Sharing
When a new data sharing cadence is established for a customer, DS will create a shared folder on Google Drive where the CSM will deliver updated datasets.

File names should avoid capilatization, special character, and spaces when possible. For example, `bradley_lead_group_data.xlsx` or `blg_data.xlsx` are acceptable file names, while `Bradley Lead Group Data.xlsx` is not.

If there are security requirements from a specific client that require FTP or something similar, DS will attempt to accommodate those needs.

## Examples
Typically, customer share data in one of two formats--call-level data or agent-time level data. Like the name implies, call-level data are records where each observation (or row) is a single call. To use call-level data during an analysis, DS at a bare minimum must know whether the call was successful, whether the call was made using Balto, and the date/time of the call.

Agent-level data are records where each observation represents a single agent-time (e.g. day or week) combination. To use this tupe o data for an analysis, DS must know who the agent is, whether they make calls using Balto, the time unit of observation, and the KPI value for each ahent-time row. Below are example data sets for each general type of data.

### Call-Level
**user\_id**|**line\_of\_insurance**|**call\_date\_pst**|**contact\_id**|**is\_outbound**|**call\_duration\_seconds**|**inbound\_call\_ltv\_bucket**|**is\_transfer**|**policy\_sale**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
1234567|med\_advantage|6/14/21|XXX|FALSE|108|[60, 80)|FALSE|FALSE
2222222|med\_advantage|6/25/21|XXX|FALSE|245|[40, 60)|FALSE|FALSE
3333333|life|6/25/21|XXX|FALSE|40|[0, 20)|FALSE|FALSE
4444444|med\_advantage|6/28/21|XXX|FALSE|297|[40, 60)|FALSE|FALSE
5555555|life|6/28/21|XXX|FALSE|61|[0, 20)|FALSE|FALSE
6666666|med\_advantage|6/28/21|XXX|TRUE|536| |FALSE|FALSE
7777777|med\_advantage|6/29/21|XXX|FALSE|938|[20, 40)|FALSE|FALSE
8888888|life|6/30/21|XXX|FALSE|721|[40, 60)|FALSE|FALSE

### Agent-time level
**CallDate**|**VendorCampaignName**|**Agent**|**AgentLevel**|**DialAttempt**|**GrossConnections**|**HumanContacts**|**Total\_Att\_Transfers**|**UniqueTransferAttempts**|**UniqueConnectedTransfers**|**UniqueTransferSuccess**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
2021-09-01|Allied - Campaign - SQS Lead Screening|allied\_tyler|Specialty|1|1|1|0|0|0|0
2021-09-01|Allied - Campaign - SQS Lead Screening|allied\_tyler|Specialty|2|1|1|0|0|0|0
2021-09-01|Allied - Life Standard|allied\_tyler|Specialty|2|1|1|0|0|0|0
2021-09-01|Allied - Life Standard|allied\_tyler|Specialty|3+|2|1|0|0|0|0
2021-09-01|Allied - Medicare Standard|allied\_tyler|Specialty|1|87|56|5|5|5|5
2021-09-01|Allied - Medicare Standard|allied\_tyler|Specialty|2|7|3|0|0|0|0
2021-09-01|Allied - Medicare Standard|allied\_tyler|Specialty|3+|163|60|4|4|3|2
2021-09-01|Allied - Medicare Standard - Double Dial|allied\_tyler|Specialty|1|11|5|2|2|1|1
2021-09-01|Allied - Medicare Standard - Double Dial|allied\_tyler|Specialty|2|27|11|3|3|3|2
