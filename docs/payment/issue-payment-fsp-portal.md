---
title: Payment - Issue a payment via the FSP portal
hide:
  - toc
---

In the 121 Platform, payments can be processed in two different methods: with a manual payment via a FSP portal or directly with a FSP integration. Below, you will find the step-by-step instructions to execute the manual payment via a FSP portal, to export the payment instructions and reconcile payments into your program.

*For payments instructions with an integrated Financial Service Provider, please refer to the instructions on the [Payment with an integrated FSP page](./issue-payment-integrated-fsp.md)*

!!! Important "Who can perform actions in this page?"
    Finance Manager and Finance Officer roles can perform actions in the Payment page.  
    Additional users may be granted only **View** permission on this page. [Learn more about Users & Roles](../users/users-roles-page.md)


### Include People Affected in the payment round

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
- A message indicates the completion of the action and **next steps to download the payment instructions**.

Only PAs who have not received **payment#** round are available for selection. PA’s that have received the max payments will not be applicable (max payment number per household might change as the program continues).

### Export the payment instructions

Once you have selected and included the People Affected in your payment round, you can download the payment instructions.
The file will provide the necessary instructions for the FSP to issue the payments.

- On the top left of your **payment page**, go into the **Payment data** dropdown list
- Click on **Choose Payment** and select the **payment#** round matching your selection
- **Export payment instructions** (right) becomes blue and clickable
- Click on the export button to download the file
- The file will be available in your downloaded folder
- Review the file if required. *Based on your agreement with the FSP, share the file to your FSP or import it into the FSP portal (if available).

!!! info "Payment instructions excel template"
    The payment instructions excel file should only contain the criteria needed for the FSP to confirm the beneficiaries' identity and issue the payments, such as names, phone number and ID number or any other criteria based on your program SOPs. For data privacy, we recommend to only export the minimum criteria to verify the PA identity. All other irrelevant data for the payment process should be excluded from the payment instructions file.

    Each program may require a different template depending on the FSP you work with in the region of your operations. Our Team will create a template specifically for the program requirements and adapted to upload into each FSP portal. 

    To export a payment report, the payment status should be shown as **closed** in the dropdownlist.

### Reconcile payments in 121 platform

Once the FSP shared the updated payment instructions back to you, you can reconcile payments in 121 Platform to update the People Affected payment status by uploading the file in the **payment page**.

- On the top left of your **payment page**, go to the **Payment data** dropdown list
- Click on **Choose Payment** and select the **payment#** round matching your selection
- **Import payment reconciliation data** (right) becomes blue and clickable
- Click on the import button to upload the FSP file, *the file must be in .csv format*
- Drag and drop the file; or use the 'Choose file' function.
- Click on OK. The PA status will be updated according to whether the transfer was marked as Successful, Waiting or Failed by the FSP.

### Payment status

The payment status displayed in the payment page will be updated depending on the program payment phase.

| Status | Description | Actions required |
| :------| :-----------| :----------------|
| **SUCCESSFUL** | The transfer have been sent to the People Affected or Household and they can now use it. | None.|
| **WAITING** | The payment is waiting for approval of one or more financial officers. The transfer is not yet sent to the People Affected or Household selected for this payment round. | Import the reconciliation file into 121 Platform to update the status (.csv Format) |
| **FAILED** | The transaction has failed. The PAs have not received any payment.| Please check the error message provided by your bank. Failed payment can be due to wrong bank details, phone number or ID number depending on the chosen payment methods. You can try again. Contact our 121 Support Team if this remains unsolved.|

<<<<<<< HEAD
!!! info "Payment Frequency"
    Disbursements can be executed at a certain frequency (daily, weekly, monthly or one-off payment). All payments in the 121 Platform must be triggered manually on a specific date.
=======
---

### Payment Frequency

Disbursements can be executed at a certain frequency (daily, weekly, monthly or one-off payment). All payments in the 121 Platform must be triggered manually at the required date.

Transfers are not sent automatically at a specific date. This allows the finance manager to review the availability of funds before a payment is issued to the beneficiaries.

[:octicons-arrow-right-24: Program Design metrics](../design/read-change-design-details.md)
>>>>>>> 8e0809d8f1077e265698249dee93d4cb00cd82fa

### Export payment reports

For financial audit and donor requirements, you can export the payment reports once this is completed.

<<<<<<< HEAD

!!! tips "Export payment reports"

    For financial audit and donor requirements, you can export the payment reports once this is completed.

    - In the Payment page, go to **Payment data** on the top left, 
    - Select the required **payment#**
    - Click on **Export Report**

___
Need further assistance? Contact your dedicated Account Manager or reach our [support team via email](mailto:support@121.global).
___
=======
- In the Payment page, go to **Payment data** on the top left
- Select the required **payment#**
- Click on **Export Report**

---

Need further assistance? Contact your dedicated Account Manager or reach our [support team via email](mailto:support@121.global).

---
>>>>>>> 8e0809d8f1077e265698249dee93d4cb00cd82fa
