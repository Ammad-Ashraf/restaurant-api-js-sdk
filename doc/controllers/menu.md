# Menu

```ts
const menuController = new MenuController(client);
```

## Class Name

`MenuController`


# Get All Menu Items

```ts
async getAllMenuItems(
  requestOptions?: RequestOptions
): Promise<ApiResponse<MenuResponse>>
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `requestOptions` | `RequestOptions \| undefined` | Optional | Pass additional request options. |

## Response Type

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `result` property of this instance returns the response data which is of type [`MenuResponse`](../../doc/models/menu-response.md).

## Example Usage

```ts
try {
  const { result, ...httpResponse } = await menuController.getAllMenuItems();
  // Get more response info...
  // const { statusCode, headers } = httpResponse;
} catch (error) {
  if (error instanceof ApiError) {
    const errors = error.result;
    // const { statusCode, headers } = error;
  }
}
```

