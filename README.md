# azure_flask_deployment
This is the azure flask deployment repo.

# Deployed URL of application:
 https://maliha-504-flask.azurewebsites.net/

## Step by Step guide to set up and deploy application:
1. Create github repo in this case it was "azure_flask_deployment'
2. Copy and paste flaskapp_0 from WK2 
3. Copy repo (git clone) include copied url. cd into azure_flask_deployment 
4. Copy and paste over app.py (make new file and copy over the code in google colab) 
5. Ensure that routes line up with the corresponding .html folders and update base
6. Include templates folder
7. Copy templates information from WK2
8. Run python app.py in google colab 
9. Click on the link and the application should run
10. Install Azure CLI and copy and paste 'curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash' into the google shell terminal 
11. Then type in 'az'
12. then 'az login --use-device-code'
14. Log in to microsoft and enter your authentication code
15. Make sure to make resource group in Azure
16. Review and create resource group 
17. Type 'az webapp up --runtime PYTHON:3.9 -- sku B1' into terminal 
18. Type 'az account list -- output table' into terminal 
19. TYpe ' az account set -- subscription XXXXX' ( the XXXX represent the subscription ID for Azure for Students)
20. Type " az group list"
21. Type 'az webapp up --resource-group <groupname> --name <app-name> --runtime <PYTHON:3.9> --sku <B1>'
22. Ensure app name is unique
23. This must be deloyed from the right directory 'azure_flask_deployment'
24. There should be an link in the app services portion of Azure 
25. Type 'az wepapp up' into terminal 
26. make sure you have requirements.txt file that has faker,pandas, and flask
27. Type "git add ."
28. Type "git commit -m ' include ur update message here"
29. Type "git push"
30. Changes should be saved to your github repo and ensure all files are organized

