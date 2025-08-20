
# Order

*This model accepts additional fields of type unknown.*

## Structure

`Order`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `string \| undefined` | Optional | - |
| `items` | [`Item1[] \| undefined`](../../doc/models/item-1.md) | Optional | - |
| `tableNumber` | `number \| undefined` | Optional | - |
| `totalAmount` | `number \| undefined` | Optional | - |
| `orderType` | `string \| undefined` | Optional | - |
| `customerDetails` | [`CustomerDetails1 \| undefined`](../../doc/models/customer-details-1.md) | Optional | - |
| `status` | `string \| undefined` | Optional | - |
| `createdAt` | `string \| undefined` | Optional | - |
| `additionalProperties` | `Record<string, unknown>` | Optional | - |

## Example (as JSON)

```json
{
  "_id": "_id6",
  "items": [
    {
      "menuItem": "menuItem0",
      "quantity": 22,
      "exampleAdditionalProperty": {
        "key1": "val1",
        "key2": "val2"
      }
    }
  ],
  "tableNumber": 60,
  "totalAmount": 211.76,
  "orderType": "orderType0",
  "exampleAdditionalProperty": {
    "key1": "val1",
    "key2": "val2"
  }
}
```

