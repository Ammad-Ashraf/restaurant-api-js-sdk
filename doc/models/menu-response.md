
# Menu Response

*This model accepts additional fields of type unknown.*

## Structure

`MenuResponse`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `success` | `boolean \| undefined` | Optional | - |
| `count` | `number \| undefined` | Optional | - |
| `data` | [`MenuItem[] \| undefined`](../../doc/models/menu-item.md) | Optional | - |
| `additionalProperties` | `Record<string, unknown>` | Optional | - |

## Example (as JSON)

```json
{
  "success": false,
  "count": 222,
  "data": [
    {
      "_id": "_id4",
      "name": "name0",
      "description": "description0",
      "price": 148.58,
      "category": "category8",
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

