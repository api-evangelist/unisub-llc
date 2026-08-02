---
generated: '2026-07-21'
method: searched
source: https://github.com/Unisub-io/subscription-app/blob/main/subgraph/schema.graphql
---

# UniSub Subscription-App Subgraph (GraphQL)

UniSub's on-chain subscription engine is indexed by a The Graph subgraph whose GraphQL schema is published in the company's public GitHub repository. The schema models the full recurring-crypto-payment domain: merchants, customer wallets, subscription orders, per-interval charges, payment history (successful and failed), gas-saving deposits, ERC20 token balances/allowances, and extra-budget request/settlement/refund records.

- **Schema (verbatim copy):** [unisub-llc-schema.graphql](unisub-llc-schema.graphql)
- **Source repository:** https://github.com/Unisub-io/subscription-app (subgraph/ directory)
- **Indexed contract:** `0xA5e2408D048Eb4ad52aA212Fc9Fd64F9e0054adb` (SubscriptionApp) on Polygon (`matic`), per `subgraph/subgraph.yaml`
- **Entities:** Order, CustomerOrder, CustomerOrderPaymentHistory, CustomerGasSavingDepositHistory, ERC20Token, CustomerERC20ApprovalAndBalance, Merchant, CustomerWallet, Wallet, Customer, SuccessfulPayment, FailedPayment, OwnerERC20DepositsBalance, MerchantERC20DepositsBalance, OwnerWithdrawalHistory, MerchantWithdrawalHistory, ExtraBudgetRequest, ExtraBudgetPaidOutRecord, ExtraBudgetRefundedRecord

No hosted public GraphQL query endpoint is documented by UniSub; the subgraph manifest references The Graph deployment tooling (`onigiri-x/subscription-app2`), but no live endpoint URL is published, so none is recorded here.
