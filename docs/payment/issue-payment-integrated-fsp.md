---
title: Payment - Issue an instant payment with an integrated local FSP
hide:
  - toc
---

In the 121 Platform, payments can be processed in two different methods: with a manual payment via an FSP portal or an instant payment directly with a FSP integration. Below, you will find the step-by-step instructions to process and execute an instant payment to the list of included People Affected **with a direct FSP integration**

*For manual payments instructions via a FSP portal, please refer to the instructions on the [Manual Payment instructions (FSP portal) page](./issue-payment-fsp-portal.md)*

!!! Important "Who can perform actions in this page?"
    Finance Manager and Finance Officer roles can perform actions in the Payment page.  
    Additional users may be granted only **View** permission on this page. [Learn more about Users & Roles](../users/users-roles-page.md)

### Process and Execute instant payments

The Payment table shows all of the included households in your program ready to receive payment with the status **Included**.
To initiate a payment:

- On the top left of the table, Open the drop down to **Choose action.**
- Select  **Do Payment#**


- Include the People Affected in the payment round as follows.
- After selecting **payment#**, a tick box :material-checkbox-blank-outline: appears on the left of the PA name column.
  - Make an **individual selection** by clicking on the :material-checkbox-outline: on the PA line;
  - Or a **bulk selection** by clicking on the :material-checkbox-multiple-marked-outline: on the upper line **Select**
- **Apply Action** button becomes blue and clickable. Click the button to start paying out to the selected PA.
- A pop-up appears to confirm the sum to be transferred value to each household and the **Maximum amount that will be spend this payment: SUM.**, matching the total sum of the transfers.
- Click on **Start paying now**.
- A message indicates the completion of the action.

Only PAs who have not received the **payment#** round are available for selection. PA’s that have received the max payments will not be applicable (max payment number per household might change as the program continues).

!!! info "Payment process timeframe"
    Once the payment has been processed in the 121 Platform, payment status with integrated FSP are updated instantly. In some cases, it can take a few minutes for the status to be updated (up to 1 hour) as the information needs to be processed from the FSP back to the 121 Platform. Updated payment reports will be available only then.
    Because the payment data is being processed on the server, you can keep using the 121 Platform after initiating a payment round.


### Payment status

The status will be updated automatically for integrated FSP.

| Type | Description | Actions required |
| :---- | :----------- | :----------  |
| **SUCCESSFUL** | The transaction has be sent to the PAs on the preferred payment method. The Bank approved the transaction.| None |
| **WAITING** | The transaction is being processed by the bank. Pending payment reconciliation. The status will be updated automatically by the integrated FSP (successful or failed) | Request an update to the FSP about the reconciliation data. Contact our 121 Support Team if this remains unsolved.|
| **FAILED** | The transaction has failed. The PAs have not received any payment.| Please check the error message provided by your bank. Failed payment can be due to wrong bank details, phone number or ID number depending on the chosen payment methods. Contact our 121 Support Team if this remains unsolved.|

---

### Payment Frequency

Disbursements can be executed at a certain frequency (daily, weekly, monthly or one-off payment). All payments in the 121 Platform must be triggered manually at the required date.

Transfers are not sent automatically at a specific date. This allows the finance manager to review the availability of funds before a payment is issued to the beneficiaries.

[:octicons-arrow-right-24: Program Design metrics](../design/read-change-design-details.md)

### Export payment reports

For financial audit and donor requirements, you can export the payment reports once this is completed.

- In the Payment page, go to **Payment data** on the top left,
- Select the required **payment#**
- Click on **Export Report**


!!! info "Payment Frequency"
    Disbursements can be executed at a certain frequency (daily, weekly, monthly or one-off payment). All payments in the 121 Platform must be triggered manually on a specific date.

    Transfers are not sent automatically at a specific date. This allows the finance manager to review the availability of funds before a payment is issued to the beneficiaries.

    [:octicons-arrow-right-24: Program Design metrics](../design/read-change-design-details.md)


!!! tips "Export payment reports"

    For financial audit and donor requirements, you can export the payment reports once this is completed.

    - In the Payment page, go to **Payment data** on the top left, 
    - Select the required **payment#**
    - Click on **Export Report**

---

Need further assistance? Contact your dedicated Account Manager or reach our [support team via email](mailto:support@121.global).

---
