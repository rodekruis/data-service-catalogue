---
title: Registration - Automatic registration import from KOBO form
hide:
  - toc
---

!!! info "This section explains"
    Steps to link your kobo form with the 121 platform

Kobo Toolbox is directly integrated with 121 so registrations are automatically added to the 121 Platform in real-time. To set-up this integration the 121 Team need to access to your Kobo form to create the link between Kobo and the 121 Platform. After this integration is finalized you may remove access for the 121 Team if preferred. 

**To set-up the Kobo integration with 121**

-   As usual, create your Kobo-form on the [IFRC server](https://kobo.ifrc.org/)
-   Share this Kobo-form with account `nlrc121platform`
-   Inform the 121 team that you have shared the form

Our 121 support team will link the kobo form with the right program in the 121 platform and inform you when it is ready.

Unless you manually import registrations with an excel .CSV file, registrations done with KOBO will automatically be imported within the program registration page.


### View a KOBO registration list

- Go to your program.
- Enter the People Affected page.
- You will see the list of registrations
- 
![Import Registration button](https://raw.githubusercontent.com/global-121/121-platform/main/e2e/tests/__screenshots__/UserManualScreenshots/userManualScreenshots.spec.ts/RegistrationPageOverview.png)


### Empty list

The registration table can be empty for a few reasons :

- No new registrations since last validation round. The table will show "No data"
- No automatic upload has been executed from KOBO form or alternative registration App yet. Often, this is due to lack of internet connexion. Connect to an internet network to start importing new registrations from the registration form.
- Filters are applied to the list. Make sure the filter search barre is empty. Then, check the selected criteria on the filter "by Status" - "Registered", on the right corner of the table .


![Filter Status Registered](https://raw.githubusercontent.com/global-121/121-platform/main/e2e/tests/__screenshots__/UserManualScreenshots/userManualScreenshots.spec.ts/FilterFunctionStatusSearch.png)


!!! warning "Blank page"
    In case the page is fully blank and do not show the registration column, there may be a technical issue with the link connecting with your KOBO form.
    Please contact your dedicated Account Manager or our [support team](mailto:support@121.global) to help fixing the issue.


!!! info "Deduplication"
    Double entries can occur while registering beneficiaries on the field. Deduplication can be made in 121 instance. You can follow the steps on this page.  
    If you need additional explanations, contact your dedicated Account Manager or our support team via email.

___
Need further assistance? Contact your dedicated Account Manager or reach our [support team via email](mailto:support@121.global).
___
