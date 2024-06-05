---
title: People Affected - Import registration list from excel
hide:
  - toc
---

If you are not collecting registrations with a Kobo form or equivalent, which automatically transfers the registrations into the 121 Platform, a registration list can be manually imported from an excel file (.csv format).

!!! info "Automatic Import of registration"

    KOBO Toolbox App is integrated with the 121 Platform, enabling automatic import of new registrations of beneficiaries. Follow the instructions on this page.
    Want to integrate your KOBO form or alternative registration App with the 121 Platform ? Please, contact our team.

If you want to import your registration list using an excel file (.csv format), you first need to make sure that this file matches the format accepted by 121. To match these, first download the .csv template file from the 121 Platform, then you can upload your matching file with the registration information to 121.

### **Download the template registration file**

The template is automatically generated in the 121 Platform, based on the program registration form.
For example, the program registration form may include selection criteria such as name, phone number, amount of household members, province and IBAN number. The template will automatically include these per criteria, matching the registration form questions. Below, you can find an example of a template based on a KOBO registration form.

- **Select the Program** you will be uploading registrations for.
- Go to the **People Affected** page.
- Click on the **Import Registrations** button on the left side of the screen.
- Select **Download template CSV-file**.
- Open the downloaded CSV template in Excel.
- Copy the registration data you have in excel to match this format.

### **Import a registration list**

![Import Registration button](https://raw.githubusercontent.com/global-121/121-platform/main/e2e/tests/__screenshots__/UserManualScreenshots/userManualScreenshots.spec.ts/RegistrationPageOverview.png)

![Import Registration pop-up](https://raw.githubusercontent.com/global-121/121-platform/main/e2e/tests/__screenshots__/UserManualScreenshots/userManualScreenshots.spec.ts/RegistrationImportFile.png)

- **Select the Program** you will be uploading registrations for.
- Go to the **People Affected** page.
- Click on the **Import Registrations** button on the right side of the screen.
- Click to chose the CSV file from your computer that you have **already matched to the format required by 121**.
- After uploading the file, click **OK** to apply the action.
- Another pop up will appear with confirmation that the import was successful. *Please note this can take some time depending on the number of registrations that are being uploaded.*

!!! warning "Unsuccessful import"
    In case the import is unsuccessful or show an error message, kindly check your excel file is correctly formatted and saved as .CSV file.
    Should you need further guidance or support, Please do not hesitate to contact our [support team](mailto:support@121.global).

!!! info "Deduplication"
    Double entries can occur while registering beneficiaries on the field. Duplicate PAs can be checked in the 121 Platform. You can follow the steps on [this page.](./registration-deduplication.md)  
    If you need additional explanations, contact your dedicated Account Manager or our support team via email.

___
Need further assistance? Contact your dedicated Account Manager or reach our [support team via email](mailto:support@121.global).
___
