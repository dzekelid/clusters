{
  "info": {
    "name": "Azure Service Fabric API Clusters List",
    "_postman_id": "f9ac8ca4-9993-436a-bb03-9e0b94713a16",
    "description": "List cluster resource",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "clusters",
      "item": [
        {
          "id": "9ec227e0-715f-455d-ba4a-5fbdd7f238e7",
          "name": "Clusters_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/providers/Microsoft.ServiceFabric/clusters"
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List cluster resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c17a87d8-799e-45c7-bdb2-ad8b835c747e"
            }
          ]
        }
      ]
    }
  ]
}