---
title: Data Protection
hide:
  - toc
---




??? "1. How is the data protected? What is the data protection policy?"

      510, digital and data unit, is part of the The Netherlands Red Cross (NLRC). The NLRC has a **Data Protection Policy** enforced since 2018. **Both the NLRC and the 121 platform adhere to the European General Data Protection Regulation (GDPR)**. The GDPR also specified data breach reporting, which has to be reported to Dutch Autoriteit Persoonsgegevens. NLRC employs a legal officer specialized in data protection. NLRC is a data processor for the client, and this is agreed in the Service Level Agreement (SLA). For more information about data processor: https://www.gdpreu.org/the-regulation/key-concepts/data-controllers-and-processors/ 

      The partner remains the data controller and is therefore responsible for any data entered into the platform. The partner should therefore be informed and in compliance with their data protection legislation.

      Please, contact our Account Manager Team to **discuss any requirements and questions** in regard to our GDPR at <info@121.global>.

??? "2. Where and how do you store and process data?"

    The 121 Platform and The Netherlands Red Cross (NLRC) adheres to the General Data Protection Regulation (GDPR), which is the most comprehensive and restrictive of the jurisdiction. Data is stored, hosted and processed in West Europe. Any National Societies and NGOs using the 121 Platform outside of Western Europe are responsible for handling the data of their beneficiaries themselves.
  
    If you use KOBO toolbox for registration, the data will remain stored in the KOBO server. Kindly note this is separate from 121 platform data process and outside of our control.


??? "3. What is your cloud server and host provider?"

    The 121 Platform runs in Microsoft Azure Cloud. By default, the location for all resources is Western Europe. Optionally, and upon request to our team, it may be possible to host and store the data in a different region. Please, contact our team for further information <info@121.global>.

    It may be possible to host the 121 platform in the country which data storage and processing is happening but this depends on location availability of Azure datacenters. 


??? "4. Can you host the data in-country?"

    Depending on availability of Azure datacenters, data storage and processing may be possible in-country. Alternative options can be discussed with our team, such as alternative IaaS or PaaS providers, or an on-premise hosting solutions. 
   
    Note that hosting data on-premise servers, or on third-party servers for which we have no agreement contract, may affect the 121 platform maintenance. It may require your team to support the maintenance of your 121 instance.
    
    Please contact us to discuss best alternatives and solutions on <info@121.global>.


??? "5. In which geographical locations do you store or process data?"

    Data is stored, hosted and processed in West Europe on Azure Cloud servers. Any National Societies and NGOs using the 121 Platform outside of Western Europe are responsible for handling the data of their beneficiaries themselves.
  
    If you use KOBO toolbox for registration, the data will remain stored in the KOBO server. Kindly note this is separate from 121 platform data process and outside of our control.


??? "6. How long do you store the data?"

    The data is stored for a maximum of 7 years on our Azure cloud server after the last update. Data that has not been updated in the last 7 years will be deleted from the cloud server. If your programmes require a shorter storage period, this can be requested from our team. 

    Upon closure of your instance, your data will be deleted and erased from our cloud server - including users, programs and beneficiary details. Beware that this action is irreversible and data cannot be recovered afterwards. We kindly ask you to save any necessary recordings beforehand.

    **Data collected with third party tool** integrated with 121 platform are not hosted on our servers. Third party handle the data storage. For instance, data collected with KOBO tool will be stored on KOBO servers and fall under their data protection policy. Kindly note this is separate from 121 platform data process and outside of our control.

??? "7. How do you ensure data confidentiality, integrity and protection?"

    **Confidentiality** is protected by allowing only a limited, controlled, set of administrators access the production-related resources in Azure. Also, confidentiality is protected by having separate 121 instances with seperate databases and credentials for each client, and for each client having individual user accounts with role-based access to the data, including the technical administrator.

    **Availability** is protected by using an optimized configuration of resources in Microsoft Azure, including automated back-ups and health checks. Furthermore, automated exception reports are set up, so that in case of service unavailability, the DevOps team can quickly respond. Also, any new code is thoroughly tested using both automated tests and manual tests before going into production.

    **Integrity** is protected by extensive testing of the software using various types of automated and also manual tests, and using DBMS-provided integrity functionality with an ERD in 3rd normal form (primary key-foreign key relationships, unique contraints, not null columns, and the like). Malicious attempts at accessing the data are mitigated by daily monitoring of logs and resources and by regular pentests performend by an external company. The whole The Netherlands Red Cross (NLRC) has undersigned the IFRC Code of Conduct and also external contractors do so.

___
Need further assistance? Contact your dedicated Account Manager or reach our [support team via email](mailto:support@121.global).
___
