# Plaid::TransactionsGetRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **client_id** | **String** | Your Plaid API &#x60;client_id&#x60;. | [optional] |
| **options** | [**TransactionsGetRequestOptions**](TransactionsGetRequestOptions.md) |  | [optional] |
| **access_token** | **String** | The access token associated with the Item data is being requested for. |  |
| **secret** | **String** | Your Plaid API &#x60;secret&#x60;. | [optional] |
| **start_date** | **Date** | The earliest date for which data should be returned. Dates should be formatted as YYYY-MM-DD. |  |
| **end_date** | **Date** | The latest date for which data should be returned. Dates should be formatted as YYYY-MM-DD. |  |

## Example

```ruby
require 'plaid'

instance = Plaid::TransactionsGetRequest.new(
  client_id: null,
  options: null,
  access_token: null,
  secret: null,
  start_date: null,
  end_date: null
)
```

