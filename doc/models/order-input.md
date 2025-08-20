
# Order Input

*This model accepts additional fields of type unknown.*

## Structure

`OrderInput`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `items` | [`Item[]`](../../doc/models/item.md) | Required | - |
| `tableNumber` | `number` | Required | - |
| `totalAmount` | `number` | Required | - |
| `orderType` | [`OrderType`](../../doc/models/order-type.md) | Required | - |
| `customerDetails` | [`CustomerDetails`](../../doc/models/customer-details.md) | Required | - |
| `additionalProperties` | `Record<string, unknown>` | Optional | - |

## Example (as JSON)

```json
{
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
  "tableNumber": 78,
  "totalAmount": 164.3,
  "orderType": "dine-in",
  "customerDetails": {
    "contact": "contact2",
    "address": "address6",
    "exampleAdditionalProperty": {
      "key1": "val1",
      "key2": "val2"
    }
  },
  "exampleAdditionalProperty": {
    "key1": "val1",
    "key2": "val2"
  }
}
```

