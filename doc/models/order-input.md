
# Order Input

*This model accepts additional fields of type unknown.*

## Structure

`OrderInput`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `items` | [`Item[]`](../../doc/models/item.md) | Required | - |
| `tableNumber` | `number` | Required | - |
| `additionalProperties` | `Record<string, unknown>` | Optional | - |

## Example (as JSON)

```json
{
  "items": [
    {
      "menuItemId": "menuItemId6",
      "quantity": 22,
      "exampleAdditionalProperty": {
        "key1": "val1",
        "key2": "val2"
      }
    }
  ],
  "tableNumber": 78,
  "exampleAdditionalProperty": {
    "key1": "val1",
    "key2": "val2"
  }
}
```

