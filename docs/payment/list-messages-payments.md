---
title: Payment - List of payment indication messages in 121 platform
hide:
  - toc
---

!!! info "This section explains"
    How to perform changes of PA status in the payment phase of a program: end inclusion or pause payments.

When performing a payment, 121 platform will notify the Finance Officer and Finance Manager on their actions through a certain number of messages. Here the list of messages and related explanations.


### List of payment notifications to 121 users

| Type | Description |
| ---- | ----------- |
| **SUCCESSFUL** | The transaction has be sent to the PAs on the preferred payment method. The Bank confirmed the transaction to be approved.  |
| **WAITING** | The transaction is being processed by the bank. Pending payment reconciliation. The status will be updated automatically for integrated FSP when successful, or after manual reconciliation when the FSP shared the payment reconciliation file back to your finance team. |
| **FAILED** | The transaction has failed. The PAs will not receive any Cash support. Please check the error message provided by your bank. Failed payment can be due to wrong bank details or phone number, depending on the chosen payment methods. |
___
Need further assistance? Contact your dedicated Account Manager or reach our [support team via email](mailto:support@121.global).
___
