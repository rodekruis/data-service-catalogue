---
title: Payment - Failed and retry payments
hide:
  - toc
---

When processing the payments, the statuses will be updated with **Successful**, **Waiting** and **Failed**.
Below, you will find the step-by-step instructions to understand the reasons of **failed payments** and retry payments.

*For payment statuses description, please refer to this [page listing the statuses.](./list-status-payment-page.md)

!!! Important "Who can perform actions in this page?"
    Finance Manager and Finance Officer roles can perform actions in the Payment page.  
    Additional users may be granted only **View** permission on this page. [Learn more about Users & Roles](../users/users-roles-page.md)

### Reasons for failed payments

Failed payments occur due to an error in data. Depending on how the payment is processed in your instance, you may look at different errors.

**1. Incorrect payment details**
    The KYC required is incorrect and cannot match the information required by the FSP to process the payment. The incorrect details can be as follows:

- PA full name
- Phone numbers
- Bank account number
- Id number
- Location

Once you have identified the incorrect data, you can correct the information within the PA profile. Follow the instructions [on this page.](../registration/edit-pa-profile.md)

**2. Wrong format of the reconciliation file**
    For manual payment, the imported reconciliation file is not formatted correctly. The data cannot match within the platform. Check the instructions on formatting your [manual reconciliation file.](./manual-payment-reconciliation.md)

**3. PAs changed their payment details**
    In case the failed payment occurs while the PAs have received successfully the payment in the past, this can be due to the fact that PAs have changed their payment details or phone number. Consequently, the FSP cannot match and process the payment.


**4. Updating payment between FSP-121 is failing**
    If your instance is integrated with an FSP, the integration may encounter issues. Please contact the 121 Support Team to verify if this can be due to an integration error.

### Retry payments

!!! Important "Good to know"
    Payments can only be retried within the current payment round. Consequently, if you start a new payment round, any retries for payments from the previous round must be done individually rather than in bulk. We strongly advise reconciling the data for the ongoing payment before proceeding with the next transaction.

    Please contact your Financial Service Provider (FSP) if the payment reconciliation has not yet been provided to your finance team.


Once you have identified the reason, you can proceed with retrying the payments:

- Go in the **Payment** page
- Click on the button **Retry payments** highlighted in red
- The transaction will be automatically retried for beneficiaries identified with a **failed payment** status
- The payment status will be updated

**What if payments remain failing?**

We recommend getting in contact with our support team to verify the reasons of payment failing together with your finance team. We will provide guidance in the next steps.

___
Need further assistance? Contact your dedicated Account Manager or reach our [support team via email](mailto:support@121.global).
___
