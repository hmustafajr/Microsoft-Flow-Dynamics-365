{
    "inputs": {
        "host": {
            "connection": {
                "name": "@parameters('$connections')['shared_dynamicscrmonline']['connectionId']"
            }
        },
        "method": "get",
        "path": "/datasets/@{encodeURIComponent(encodeURIComponent('org0c4ba32d.crm'))}/tables/@{encodeURIComponent(encodeURIComponent('incidents'))}/ondeleteditems",
        "authentication": "@parameters('$authentication')"
    },
    "recurrence": {
        "interval": 1,
        "frequency": "Minute"
    },
    "metadata": {
        "flowSystemMetadata": {
            "swaggerOperationId": "GetOnDeletedItems"
        }
    },
    "splitOn": "@triggerBody()?['value']"
}
