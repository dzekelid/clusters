{
  "info": {
    "name": "Azure Service Fabric API Clusters Get",
    "_postman_id": "cb94d413-3021-44ac-8819-db7e65dff8a4",
    "description": "Get cluster resource",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "clusters",
      "item": [
        {
          "id": "1cf94042-f16c-474f-8685-4b1b18f95019",
          "name": "Clusters_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ServiceFabric/clusters/:clusterName"
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
                },
                {
                  "id": "clusterName",
                  "value": "clusterName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get cluster resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "56ed3d12-efe9-4954-9f59-1f345ea7a378"
            }
          ]
        }
      ]
    }
  ]
}