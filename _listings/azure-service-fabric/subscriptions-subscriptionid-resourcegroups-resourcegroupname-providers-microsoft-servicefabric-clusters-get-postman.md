{
  "info": {
    "name": "Azure Service Fabric API Clusters List By Resource Group",
    "_postman_id": "7a95c92d-a79c-4d4d-89c0-a739cdf6056b",
    "description": "List cluster resource by resource group",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "clusters resource group",
      "item": [
        {
          "id": "589730fa-4da8-4235-80ea-24a0eaae0f88",
          "name": "Clusters_ListByResourceGroup",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourcegroups/:resourceGroupName/providers/Microsoft.ServiceFabric/clusters"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List cluster resource by resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e382ac0f-7118-4c61-bb08-71c8f4ad8fe5"
            }
          ]
        }
      ]
    }
  ]
}