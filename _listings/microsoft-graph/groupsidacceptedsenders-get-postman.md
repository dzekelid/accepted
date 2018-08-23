{
  "info": {
    "name": "Microsoft Graph API List Accepted Senders",
    "_postman_id": "6fbdc2bb-ff80-447b-bcb7-add122223b21",
    "description": "List acceptedSenders Get a list of users or groups that are in the acceptedSenders list for this group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "list",
      "item": [
        {
          "id": "1d1b9b82-8c1c-4093-8f48-1faa7fc7950e",
          "name": "ListAcceptedSenders",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/acceptedSenders"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List acceptedSenders Get a list of users or groups that are in the acceptedSenders list for this group"
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "c632216d-570d-44ef-957c-af378c1fe4f6"
            }
          ]
        }
      ]
    }
  ]
}