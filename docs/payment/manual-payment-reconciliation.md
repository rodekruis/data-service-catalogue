---
title: Payment - Manual payment reconciliation
hide:
  - toc
---
In the 121 Platform, payments can be processed in two different methods: with a manual payment via a FSP portal or directly with a FSP integration. Below, you will find the step-by-step instructions to execute the manual reconciliation into the program, once you have received the payment instructions back from the FSP.

*For payments instructions with an integrated Financial Service Provider, please refer to the instructions on the [Payment with an integrated FSP page](./issue-payment-integrated-fsp.md)*

!!! Important "Who can perform actions in this page?"
    Finance Manager and Finance Officer roles can perform actions in the Payment page.  
    Additional users may be granted only **View** permission on this page. [Learn more about Users & Roles](../users/users-roles-page.md)

### Check the reconciliation data file

Before uploading the reconciliation data file, there is a few labels that must be adjusted according to the 121 platform. This relates to the payment statuses.
The below table indicate the correct label names that must be filled in the payment status of your reconciliation data. The FSP may write the statuses differently than the 121 Platform. Therefore, you should overwrite the status with the data indicated in the below table, column **121 Data**


| Description | 121 Data |
| :---- | :---- |
| Successful or confirmed payments | **success** |
| Payments is not distributed yet or cannot be sent yet | **waiting** |
| Failed payment, not received by PA due to wrong data | **error** |

If these labels are not correctly matching, three errors can occur in the 121 Platform:

- An error message appear to warn the data cannot be uploaded,
- Payment statuses are not correctly updated, showing more failed or waiting payments as the system cannot match the status with the imported file,
- The format is not recognized in the platform and show an error page.

*Some data may be specific to your FSP, our team will advice you when implementing your 121 instance.*

### Format your file in .csv

Once your labels are updated, you can save the file as a .csv format:

- Click on **Save File** in your file
- Add a file name, if required
- Select **.csv** format in the dropdown list
- **Save**

### Import the reconciliation file

Once your updated file is saved as a .csv format, you can import the payment reconciliation file:

- Go to **Payment** page
- In **Payment data**, select the **payment #** number you want to reconcile the data.
  Note that the payment must be shown as **CLOSED**
- Click on the button **Import payment reconciliation data**
- A pop-up window appears. Click on **Choose File** and select the required file
- **OK**

!!! info "Payment statuses"
    All payment statuses will be updated for the beneficiaries. You can then overview the number of successful, waiting and failed payments within the beneficiaries list. Read more about the payment statuses in [this page](./list-status-payment-page.md)
