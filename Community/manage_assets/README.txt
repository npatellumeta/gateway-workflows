Workflow Version: 1.0
Project Title: manage_assets
Author: Lumeta/FireMon
Date: 11-25-2019
Gateway Version: 
Dependencies: None
Installation Directions: 1. Import Workflow into Gateway
                         2. Restart Gateway
                         3. Add needed permissions
Known Errors and Bugs: None
Description: This workflow allows you to retrieve a list of assets managed by BAM, retrieve a list of configurations that exist in BAM
and also to add ip address to BAM. Depending on the flag in the payload, API creates network block and/or Address Block
if containing network or address block does not exist. 

/lumeta/getiplist
/lumeta/getnetworklist
/lumeta/addiplist
