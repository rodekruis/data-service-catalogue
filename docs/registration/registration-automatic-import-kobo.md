---
title: People Affected - Automatic registration import from KOBO form
hide:
  - toc
---

**Kobo Toolbox is directly integrated with 121 platform**. Registrations are automatically added to the 121 Platform in real-time. To set-up this integration the 121 Team need to access to your Kobo form to create the link between Kobo and the 121 Platform. After this integration is finalized you may remove access for the 121 Team if preferred.

## To set-up the Kobo integration within your 121 program

Unless you manually import registrations with an excel .CSV file, registrations done with KOBO will automatically be imported within your 121 program, in the **People Affected** page.

- Create your Kobo-form on the KOBO tool
- Share this Kobo-form with account `nlrc121platform`
- Inform the 121 team that you have shared the form

Our 121 support team will link the kobo form with the right program in the 121 platform and inform you when it is ready. Unless some additional changes are required, the mapping of your form to 121 platform will be performed within 1 to 2 business days upon receipt.

!!! info "KOBO for Red Cross Red Crescent National Societies"
  121 platform is a product of the Netherlands Red Cross. Red Cross Red Crescent National Societies can create their kobo form via [IFRC server](https://kobo.ifrc.org/). Once created, you can share this Kobo-form with the account `nlrc121platform`.

### View a KOBO registration list


- Go to your program.
- Enter the People Affected page.
- You will see the updated list of registered PA any time a new form is completed and sent (when connected to the internet).

Note that KOBO toolbox can be used offline, while on the field. Nevertheless, the registration list can be imported into 121 platform only when an internet connection is established.

![Import Registration button](https://raw.githubusercontent.com/global-121/121-platform/main/e2e/tests/__screenshots__/UserManualScreenshots/userManualScreenshots.spec.ts/RegistrationPageOverview.png)


### Empty list

The registration table can be empty for a few reasons :

- No new registrations since last validation round. The table will show "No data"
- No automatic upload has been executed from KOBO form or alternative registration App yet. Often, this is due to lack of internet connexion. Connect to an internet network to start importing new registrations from the registration form.
- Filters are applied to the list. Make sure the filter search barre is empty. Then, check the selected criteria on the filter "by Status" - "Registered", on the right corner of the table .


![Filter Status Registered](https://raw.githubusercontent.com/global-121/121-platform/main/e2e/tests/__screenshots__/UserManualScreenshots/userManualScreenshots.spec.ts/FilterFunctionStatusSearch.png)


!!! warning "Blank page"
    In case the page is fully blank and does not show the registration table, there may be a technical issue with the link connecting with your KOBO form.
    Please contact your dedicated Account Manager or our [support team](mailto:support@121.global) to help fixing the issue.


!!! info "Deduplication"
    Double entries can occur while registering beneficiaries on the field. Deduplication can be made within 121 Platform. You can follow the steps on [this page.](./registration-deduplication.md)  
    If you need additional explanations, contact your dedicated Account Manager or our support team via email.

___
Need further assistance? Contact your dedicated Account Manager or reach our [support team via email](mailto:support@121.global).
___
