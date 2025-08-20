
# Customer Details 1

*This model accepts additional fields of type unknown.*

## Structure

`CustomerDetails1`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `contact` | `string \| undefined` | Optional | - |
| `address` | `string \| undefined` | Optional | - |
| `additionalProperties` | `Record<string, unknown>` | Optional | - |

## Example (as JSON)

```json
{
  "contact": "contact8",
  "address": "address0",
  "exampleAdditionalProperty": {
    "key1": "val1",
    "key2": "val2"
  }
}
```

