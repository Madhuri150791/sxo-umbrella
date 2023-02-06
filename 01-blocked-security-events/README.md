# SXO-Umbrella Integration for Blocked Security Events

This json file will help users to create a scheduled email notification to list down blocked security events listed in Umbrella. 

## Pre-Requisites

To be able to use SecureX for sending email notification, following must be present

1. Connectivity Between SecureX to Email Server, for SecureX to be able to send the email notification. If there are restriction on SecureX communication with email server, you can use SecureX to [GMail connectivity](https://docs.securex.security.cisco.com/Orchestration-Help/Content/targets-smtp.html)
2. Umbrella API Key and Secret
3. Schedule

## How to 

To use this json, you can import the json to your SecureX and Provide the necessary details as follows:

1. Login to SecureX Orchestration(SXO)
2. Navigate to My Workflows.
3. Click on Import Workflows.

<img width="1465" alt="Screenshot 2023-02-06 at 12 30 13 PM" src="https://user-images.githubusercontent.com/58934092/216904287-41699d94-865d-4935-b85d-32f753c350f7.png">

4. Select Browse.

<img width="761" alt="Screenshot 2023-02-06 at 1 13 31 PM" src="https://user-images.githubusercontent.com/58934092/216913453-9f26d4c0-e758-4a97-a730-5975cd5a09c4.png">

5. Select the sxo.json 
6. You will receive following notification, to update the variable.
<img width="761" alt="Screenshot 2023-02-06 at 1 20 07 PM" src="https://user-images.githubusercontent.com/58934092/216914662-c3b06eb8-f0db-487a-9cfa-ec2a5f28fe2f.png">
7. Update the variables.
8. It will import the workflow in your SXO account.

