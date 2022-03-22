# FAQ
## What is DS's specific methodology for conducting playbook analyses?
- We use call data, desktop events data (such as Checklist & Deck triggers), thumbs feedback data within the time period specified to generate plots which present a high-level visual overview of how the playbook is performing. 
This gives specific insights like- 
    - Checklist usage percentages by agents during the period
    - Displaying win probabilities for individual checklists and top checklist progression sequence in winning calls.
    - Identifying checklists which are potential sticking points in conversations and hard to move past in calls.
    - Deck trigger analysis displaying top performing deck items and also identifying which decks have decklist items thats are rarely used by agents in response to the deck trigger. 
    - Thumbs feedback data as provided by agents. 
  
## What can a CSM do with the report? 
The goal of the report is to show more detailed analysis on playbook usage and adoption by the agents than what is present in Balto Cloud. CSMs can use the plots to quickly identify pain points in Checklists and Decks and potentially provide feedback to the managers to modify/revise their playbooks to better assist agents. 

## How should the plots in the report be interpreted by the CSMs?
Each plot within the report has accompanying text to help the CSMs understand the bars/trends visualized in the plot. If any further explanation or breakdown of the plots are required, a DS team member can be contacted and will be happy to help the CSM. 

## Can a combined report be generated for multiple playbooks for an organization? 
Unfortunately, No. The way DS currently produces these reports is by extracting data from multiple database tables to link checklist and deck items from the playbook to trigger events in the calls and combining data from two separate playbooks is not possible with our current approach.
