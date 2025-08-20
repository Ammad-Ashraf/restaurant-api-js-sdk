
# Item 1

*This model accepts additional fields of type unknown.*

## Structure

`Item1`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `menuItem` | `string \| undefined` | Optional | - |
| `quantity` | `number \| undefined` | Optional | - |
| `additionalProperties` | `Record<string, unknown>` | Optional | - |

## Example (as JSON)

```json
{
  "menuItem": "menuItem6",
  "quantity": 78,
  "exampleAdditionalProperty": {
    "key1": "val1",
    "key2": "val2"
  }
}
```

