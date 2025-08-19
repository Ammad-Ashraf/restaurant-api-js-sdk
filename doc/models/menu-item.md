
# Menu Item

*This model accepts additional fields of type unknown.*

## Structure

`MenuItem`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `string \| undefined` | Optional | - |
| `name` | `string \| undefined` | Optional | - |
| `description` | `string \| undefined` | Optional | - |
| `price` | `number \| undefined` | Optional | - |
| `category` | `string \| undefined` | Optional | - |
| `additionalProperties` | `Record<string, unknown>` | Optional | - |

## Example (as JSON)

```json
{
  "_id": "_id2",
  "name": "name8",
  "description": "description8",
  "price": 18.86,
  "category": "category6",
  "exampleAdditionalProperty": {
    "key1": "val1",
    "key2": "val2"
  }
}
```

