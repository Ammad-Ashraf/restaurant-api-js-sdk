
# Order

*This model accepts additional fields of type unknown.*

## Structure

`Order`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `string \| undefined` | Optional | - |
| `items` | [`Item[] \| undefined`](../../doc/models/item.md) | Optional | - |
| `tableNumber` | `number \| undefined` | Optional | - |
| `status` | `string \| undefined` | Optional | - |
| `createdAt` | `string \| undefined` | Optional | - |
| `additionalProperties` | `Record<string, unknown>` | Optional | - |

## Example (as JSON)

```json
{
  "_id": "_id6",
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
  "tableNumber": 60,
  "status": "status4",
  "createdAt": "2016-03-13T12:52:32.123Z",
  "exampleAdditionalProperty": {
    "key1": "val1",
    "key2": "val2"
  }
}
```

