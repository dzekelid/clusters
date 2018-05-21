{
  "info": {
    "name": "Azure Service Fabric API Clusters Delete",
    "_postman_id": "42a03855-2621-4736-aa57-95b9737f6701",
    "description": "Delete cluster resource",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "clusters",
      "item": [
        {
          "id": "e4d65d7f-260f-4a62-a1fe-9566b7853212",
          "name": "Clusters_Delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete cluster resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7318cf3d-11e9-401e-8fc2-02daa664db42"
            }
          ]
        }
      ]
    }
  ]
}