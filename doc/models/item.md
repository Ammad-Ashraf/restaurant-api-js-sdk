
# Item

*This model accepts additional fields of type unknown.*

## Structure

`Item`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `menuItemId` | `string \| undefined` | Optional | - |
| `quantity` | `number \| undefined` | Optional | - |
| `additionalProperties` | `Record<string, unknown>` | Optional | - |

## Example (as JSON)

```json
{
  "menuItemId": "menuItemId0",
  "quantity": 62,
  "exampleAdditionalProperty": {
    "key1": "val1",
    "key2": "val2"
  }
}
```

