# IotImageAnalysis
1. Login to your IBM CLoud Account
2. Goto Catalog and create the following services:
* Internet of things Platform starter
* Visual Recognition
3. Goto connections tab and open IotF Service and Launch Watson Iot Platform
4. Navigate to Devices tab and Add Device
5. Once the Starter app is running,visit app url and configure Node-red
6. Login to your node-red flows dashboard and import flow from flows.json
7. Create new visual recognition credentials
8. Update api key in the visual recognition node-red flow
9. Update the device details in IBM Iot device node
10. Visit <app_url>/upload and upload required image
11. Change the string inside includes from trigger action function to set a different trigger
