---
title: Description of role-based permissions
hide:
  - toc
---

!!! info "This section explains"
    Overview of standard users permissions and tasks that can be performed

No single user can take all actions in the 121 platform. The 121 platform follows **role-based segregation of duties**, which improves task **accountability**. For example, users with a CVA profile will not be able to make payments but are able to make updates to beneficiary data. Users with a finance profile can make payments, but are not able to update beneficiaries’ personal information. The following standard roles are configured in the 121 platform.

### Standard 121 user Roles

| Type                | Description                                                          |
| :------------------ | :------------------------------------------------------------------- |
| **Program Admin**   | Program Administrator, responsible for overall program management    |
| **Finance Officer** | Officer for Finance operations                                       |
| **Finance Manager** | Manager for Finance operations, payment instructions                 |
| **CVA Officer**     | Officer for Cash and Voucher Assistance                              |
| **CVA Manager**     | Manager for Cash and Voucher Assistance                              |
| **View**            | Portal Users who are allowed to view only and cannot perform actions |

### Permissions per role

| Permissions                                                     |           **Program Admin**           |          **Finance Officer**          |          **Finance Manager**          |            **CVA Officer**            |            **CVA Manager**            |
| :-------------------------------------------------------------- | :-----------------------------------: | :-----------------------------------: | :-----------------------------------: | :-----------------------------------: | :-----------------------------------: |
| Overview Users and Roles                                        | :octicons-check-circle-fill-24:{.yes} |                                       |                                       |                                       |                                       |
| Add and create new user accounts                                |  :material-progress-question:{.req}   |                                       |                                       |                                       |                                       |
| Overview all active programs                                    | :octicons-check-circle-fill-24:{.yes} |                                       |                                       |                                       |                                       |
| Create new programs in 121                                      |  :material-progress-question:{.req}   |                                       |                                       |                                       |                                       |
| View Program design                                             | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} |
| Manage Team members and assign roles in program                 | :octicons-check-circle-fill-24:{.yes} |                                       |                                       |                                       | :octicons-check-circle-fill-24:{.yes} |
| Overview registration list                                      | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} |
| Register, manage and edit PA profile                            | :octicons-check-circle-fill-24:{.yes} |                                       |                                       | :octicons-check-circle-fill-24:{.yes} |                                       |
| Confirm or Select preferred PA communication and payment method | :octicons-check-circle-fill-24:{.yes} |                                       |                                       | :octicons-check-circle-fill-24:{.yes} |                                       |
| Validate, Reject PA profiles                                    | :octicons-check-circle-fill-24:{.yes} |                                       |                                       | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} |
| Include PA in program                                           | :octicons-check-circle-fill-24:{.yes} |                                       |                                       |                                       | :octicons-check-circle-fill-24:{.yes} |
| Access and manage reporting on PA registration                  | :octicons-check-circle-fill-24:{.yes} |                                       |                                       | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} |
| Include and validate PA in payment rounds                       | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} |                                       |                                       |                                       |
| Issue Payment                                                   | :octicons-check-circle-fill-24:{.yes} |                                       | :octicons-check-circle-fill-24:{.yes} |                                       |                                       |
| Send notification to PA (1-way SMS)                             | :octicons-check-circle-fill-24:{.yes} |                                       | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} | :octicons-check-circle-fill-24:{.yes} |
| Export Payment instructions and reports                         | :octicons-check-circle-fill-24:{.yes} |                                       | :octicons-check-circle-fill-24:{.yes} |                                       |                                       |
| Overview Evaluation page (PDM)                                  | :octicons-check-circle-fill-24:{.yes} |                                       |                                       |                                       |                                       |

:octicons-check-circle-fill-24:{.yes} Feature available.  
:material-progress-question:{.req}  Feature not available, upon request to 121 support team.

### Additional roles

Existing roles can be adjusted with additional permissions to fit your requirements. Additional roles and permissions can be configured upon request. Contact your dedicated Account Manager reach out to our [support team via email](mailto:support@121.global).


!!! note "add users to a program"
    You can follow these instructions to [add team members to a program and assign a role](../team/add-team-members.md).

___
Need further assistance? Contact your dedicated Account Manager or reach our [support team via email](mailto:support@121.global).
___
