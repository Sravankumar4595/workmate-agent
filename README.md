# workmate-agent
Build an agent for Employee self-service assistant for IT, HR and Asset requests using Copilot Studio and Power Automate.


## Features

- IT Support Requests
- Asset Requests
- HR FAQ using Generative Answers

## Architecture

Employee -> Copilot Studio -> Power Automate -> SharePoint List
<img width="1766" height="1036" alt="Image" src="https://github.com/user-attachments/assets/452688eb-6fa4-48ac-b63c-83972ba21593" />

## Prerequisites

- Microsoft 365
- Copilot Studio
- Power Automate
- SharePoint Online


## Deployment Steps

1. Download the solution:  `WorkmateAssistant_1_0_0_1.zip`.
2. Import solution into Power Platform.
3. Create SharePoint list `WorkMateRequests`.
   - Employee (PeoplePicker)
   - RequestType (Choice)
   - Category (Choice)
   - Priority (Choice)
   - Description (Multiple lines of text)
4. Configure connection references, provide the ENV_SharePointSiteURL and ENV_SharePointList
5. Publish the agent.


## Technologies

- Microsoft Copilot Studio
- Power Automate
- SharePoint Online
- Adaptive Cards
- Generative AI
