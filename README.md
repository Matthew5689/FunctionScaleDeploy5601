# FunctionScaleDeploy5601

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMatthew5689%2FFunctionScaleDeploy5601%2Fmain%2Fazuredeploy.json)

1. Click the **Deploy to Azure Button** to deploy the solution
2. The solution will deploy a Service Bus Triggered Function App into Azure on an Event Driven App Service Plan
3. Hitting the Function App in the Azure Portal's **Code + Test** blade will start the scaling process

Ensure to delete / stop the Function App after testing, as the number of instances can increase quickly leading to costly executions if left unsupervised.
