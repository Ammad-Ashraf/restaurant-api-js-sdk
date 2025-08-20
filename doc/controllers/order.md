# Order

```ts
const orderController = new OrderController(client);
```

## Class Name

`OrderController`

## Methods

* [Place a New Order](../../doc/controllers/order.md#place-a-new-order)
* [Get Order History](../../doc/controllers/order.md#get-order-history)


# Place a New Order

```ts
async placeANewOrder(
  body: OrderInput,
  requestOptions?: RequestOptions
): Promise<ApiResponse<OrderResponse>>
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`OrderInput`](../../doc/models/order-input.md) | Body, Required | - |
| `requestOptions` | `RequestOptions \| undefined` | Optional | Pass additional request options. |

## Response Type

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `result` property of this instance returns the response data which is of type [`OrderResponse`](../../doc/models/order-response.md).

## Example Usage

```ts
const body: OrderInput = {
  items: [
    {
      menuItem: 'menuItem0',
      quantity: 22,
    }
  ],
  tableNumber: 0,
  totalAmount: 16.6,
  orderType: OrderType.Dinein,
  customerDetails: {
    contact: 'contact2',
    address: 'address6',
  },
};

try {
  const { result, ...httpResponse } = await orderController.placeANewOrder(body);
  // Get more response info...
  // const { statusCode, headers } = httpResponse;
} catch (error) {
  if (error instanceof ApiError) {
    const errors = error.result;
    // const { statusCode, headers } = error;
  }
}
```


# Get Order History

```ts
async getOrderHistory(
  requestOptions?: RequestOptions
): Promise<ApiResponse<OrderHistoryResponse>>
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `requestOptions` | `RequestOptions \| undefined` | Optional | Pass additional request options. |

## Response Type

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `result` property of this instance returns the response data which is of type [`OrderHistoryResponse`](../../doc/models/order-history-response.md).

## Example Usage

```ts
try {
  const { result, ...httpResponse } = await orderController.getOrderHistory();
  // Get more response info...
  // const { statusCode, headers } = httpResponse;
} catch (error) {
  if (error instanceof ApiError) {
    const errors = error.result;
    // const { statusCode, headers } = error;
  }
}
```

