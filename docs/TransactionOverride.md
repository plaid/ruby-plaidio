# Plaid::TransactionOverride

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **transaction_date** | **String** | The date of the transaction, in ISO8601 (YYYY-MM-DD) format. Transaction dates in the past or present will result in posted transactions; transaction dates in the future will result in pending transactions. Transactions in Sandbox will move from pending to posted once their transaction date has been reached. |  |
| **posted_date** | **String** | The date the transaction posted, in ISO8601 (YYYY-MM-DD) format |  |
| **amount** | **Float** | The transaction amount. Can be negative. |  |
| **description** | **String** | The transaction description. |  |
| **currency** | **String** | The ISO-4217 format currency code for the transaction. | [optional] |

## Example

```ruby
require 'plaid'

instance = Plaid::TransactionOverride.new(
  transaction_date: null,
  posted_date: null,
  amount: null,
  description: null,
  currency: null
)
```

