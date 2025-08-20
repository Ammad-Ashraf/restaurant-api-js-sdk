
# Order History Response

*This model accepts additional fields of type unknown.*

## Structure

`OrderHistoryResponse`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `success` | `boolean \| undefined` | Optional | - |
| `count` | `number \| undefined` | Optional | - |
| `data` | [`Order[] \| undefined`](../../doc/models/order.md) | Optional | - |
| `additionalProperties` | `Record<string, unknown>` | Optional | - |

## Example (as JSON)

```json
{
  "success": false,
  "count": 140,
  "data": [
    {
      "_id": "_id4",
      "items": [
        {
          "menuItem": "menuItem0",
          "quantity": 22,
          "exampleAdditionalProperty": {
            "key1": "val1",
            "key2": "val2"
          }
        },
        {
          "menuItem": "menuItem0",
          "quantity": 22,
          "exampleAdditionalProperty": {
            "key1": "val1",
            "key2": "val2"
          }
        },
        {
          "menuItem": "menuItem0",
          "quantity": 22,
          "exampleAdditionalProperty": {
            "key1": "val1",
            "key2": "val2"
          }
        }
      ],
      "tableNumber": 18,
      "totalAmount": 236.94,
      "orderType": "orderType8",
      "exampleAdditionalProperty": {
        "key1": "val1",
        "key2": "val2"
      }
    },
    {
      "_id": "_id4",
      "items": [
        {
          "menuItem": "menuItem0",
          "quantity": 22,
          "exampleAdditionalProperty": {
            "key1": "val1",
            "key2": "val2"
          }
        },
        {
          "menuItem": "menuItem0",
          "quantity": 22,
          "exampleAdditionalProperty": {
            "key1": "val1",
            "key2": "val2"
          }
        },
        {
          "menuItem": "menuItem0",
          "quantity": 22,
          "exampleAdditionalProperty": {
            "key1": "val1",
            "key2": "val2"
          }
        }
      ],
      "tableNumber": 18,
      "totalAmount": 236.94,
      "orderType": "orderType8",
      "exampleAdditionalProperty": {
        "key1": "val1",
        "key2": "val2"
      }
    },
    {
      "_id": "_id4",
      "items": [
        {
          "menuItem": "menuItem0",
          "quantity": 22,
          "exampleAdditionalProperty": {
            "key1": "val1",
            "key2": "val2"
          }
        },
        {
          "menuItem": "menuItem0",
          "quantity": 22,
          "exampleAdditionalProperty": {
            "key1": "val1",
            "key2": "val2"
          }
        },
        {
          "menuItem": "menuItem0",
          "quantity": 22,
          "exampleAdditionalProperty": {
            "key1": "val1",
            "key2": "val2"
          }
        }
      ],
      "tableNumber": 18,
      "totalAmount": 236.94,
      "orderType": "orderType8",
      "exampleAdditionalProperty": {
        "key1": "val1",
        "key2": "val2"
      }
    }
  ],
  "exampleAdditionalProperty": {
    "key1": "val1",
    "key2": "val2"
  }
}
```

