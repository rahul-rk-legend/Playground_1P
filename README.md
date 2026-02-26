# GitSync

## Visual Families
|Name|Description|
|----|-----------|
|Playground_1P_Visual_Families_1|Playground_1P_Visual_Families_1|
|Playground_1P_Visual_Families_2|Playground_1P_Visual_Families_2|


## Jobs
|Name|Description|
|----|-----------|
|projects/spsstg-tsjkk/locations/global/instances/397fdff2-4666-4fa9-bab9-9ca374e6ab88/integrations/GoogleChronicle/jobs/1/jobInstances/4|This job will synchronize information about Chronicle SOAR Cases and Chronicle SOAR Alerts with Chronicle SIEM. Note: This job is only supported from Chronicle SOAR version 6.1.44 and higher.|
|projects/spsstg-tsjkk/locations/global/instances/397fdff2-4666-4fa9-bab9-9ca374e6ab88/integrations/GoogleChronicle/jobs/2/jobInstances/5|This job will sync new SOAR alerts with Chronicle SIEM.Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.|
|projects/spsstg-tsjkk/locations/global/instances/397fdff2-4666-4fa9-bab9-9ca374e6ab88/integrations/MicrosoftAzureSentinel/jobs/42/jobInstances/7|This job synchronizes Google SecOps Alerts and Microsoft Sentinel Incidents. It ensures that comments, status, and tags are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the “Microsoft Sentinel Incident” tag. If the alert didn’t originate from “Microsoft Azure Sentinel Incident Connector v2”,  you will need to add an “Incident_ID” context value to the case for the job to be able to find the correct information.|
|projects/spsstg-tsjkk/locations/global/instances/397fdff2-4666-4fa9-bab9-9ca374e6ab88/integrations/MicrosoftGraphMailDelegated/jobs/43/jobInstances/8|Token renewal job should be used to periodically update the refresh token configured for the integration. By default, the refresh token expires every 90 days, making integration unusable upon expiration. It is recommended to run this job every 7 or 14 days to make sure that refresh token will be up to date.|

