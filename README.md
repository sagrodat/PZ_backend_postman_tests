# PZ_backend_postman_tests
This repository contains all Postman API tests for PZ_backend. It is an additional repository to maintain a clean structure of the main repository and avoid cloning unnecesary files.
# Requirements 
https://www.postman.com/downloads/
# Usage
Postman supports importing and exporting environments and collections through .JSON files.
After logging into the desktop application drag and drop the .JSON files into corresponding tabs of your workspace.

**PZ Collection.postman_collection.json** into the **Collections** tab.
This file contains a structure of requests to the API that ensure comprehensive testing of the application. To test the application run certain folders or singular requests.
Names of requests were chosen to be as self-explanatory as possible.


**PZ Environment.postman_environment.json** into the **Environments** tab.
This file contains a list of environment variables required for the requests to run. Some requests need to store 
information (variables) in order to then communicate with other sequentially-run requests.

# Completion progress
The application currently provides access to 3 endpoints. Seperate tests will be created for each one.
- User :white_check_mark:
- Inventory :hourglass:
- InventoryItem :hourglass:
