# FAQ

### **The DCMS**&#x20;

#### **Question:** What is the DCMS?

The Digital Centre[^1] Management System (DCMS) is an innovative solution developed for the Physical Rehabilitation Program under the Program Humanitarian Impact Investment (PHII). It works collaboratively with Pearl to enhance the efficiency and autonomy of Rehabilitation Centres. The system includes two digital tools: an Electronic Medical Record (EMR) system named "OpenMrs" and an Enterprise Resource Planning (ERP) system called "Odoo." These tools aim to improve service quality and overall management of the centres. The EMR provides an appointment module for Health Service users and DCMS users, while the newly added "SuperSet" application optimizes data collection.

#### Question: What is SuperSet?

Apache Superset is an open-source tool for data visualization and exploration. It offers an intuitive interface for connecting to various datasets and combining them into a single visualization or dashboard. Superset includes a wide range of pre-installed visualizations, making it a powerful and straightforward solution for data analysis.

### **The Patient Management System Update**

#### Question: What is the PMS?

The ICRC Physical Rehabilitation Program developed the Patient Management System (PMS) 25 years ago as a reporting tool. It will be decommissioned soon due to its outdated

#### Question: What is the difference in DCMS?

The Digital Centre Management System (DCMS) is a free tool created with input from ICRC teams, allowing Centres to benefit from it even after ICRC support ceases. It is designed to improve efficiency and support data reporting in Physical Rehabilitation Centres.

#### Question: Can the information within PMS be migrated to DCMS?

When deploying DCMS, data from PMS will be migrated to DCMS, which is supported only by PMS5. Centers using earlier versions must first upgrade to PMS4, then PMS5, before migrating.&#x20;

#### Question: Will the DCMS replace the PMS in all ICRC PRP supported Centres?

The PMS will be decommissioned as it is obsolete; it's unsupported and outdated, relying solely on Internet Explorer, which Microsoft will soon disable. Physical Rehabilitation Centres are not required to change immediately, but the DCMS will gradually implement a new system to replace the PMS where it will be applicable.

### Support model and sustainability&#x20;

#### Question: What is the support model for external users?

The ICRC, with assistance from DCMS, has developed a support model for external partners. They can access this support through a dedicated email: servicedesk@icrc.org. Internally, ICRC will utilize the ServiceNow application for support

#### Question: How can I contact the support?

A mail should be sent to servicedesk@icrc.org with the following subject: “\[DCMS / Location] + issue”. The issue should be further explained in the body of the mail.

### DATA/PMS/REPORT/SUPERSET

#### Question: When the PMS data is migrated to the DCMS, will the EMR recognize the HSU file and data?

Each HSU file registered in the PMS will migrate the history, with the PMS number, the HSU Identity Number, and the last episode of services. It might happen that some information will be missing, it is important to update the information with the HSU.

#### Question: What is happening with the workflow when the PMS is migrated?

The Episode of Service is closed. You must start a new service or follow-up depending on the health service user's condition. An Episode of Service aligns with a rehabilitation cycle, whether it involves a new or follow up service.

#### Question: Are DCMS and the MAD connected, or does the information need to be duplicated?

Answer: DHIS2 (which stands for District health Information System 2), which is an open-source tool. The DCMS report (excel format) and the superset will report the data relevant to DHIS2, but there is not yet a synchronization into the DHIS2 platform.

#### Question: some of the HSU are not seen during the interdisciplinary clinic as they come for a small service like prefabricated device, how will I have the record of these users.

For an efficient service and visibility of the activity every HSU should be registered in the DCMS and going through the workflow even if it is a minor service.

#### Question: the physiotherapy team forgot to record the PT sessions for a HSU who was discharged, can we enter data retroactively and if yes how can we do it?

Yes, it is possible to enter the data (PT session) for a past visit, to enter in the relevant past visit and select the PT session record, enter the information as much it is required.

### HSU assessment and workflow

#### Question: In the form initial assessment, where can I find the condition Congenital deformity or Lower limb discrepancy?

The condition list is based on the ICD 10 logic from WHO; for instance, you can go to the present condition drop down and select “Congenital malformations and deformations of the musculoskeletal system (Q65-Q79)” where you can find “Reduction defects of lower limb” or in the condition drop down “Other joint disorders (M20-M25) and you can select “limb acquired deformity,  unspecified”.

#### Question: can we complete the technical card for bilateral case in the same form?

For each technical card we have the option left or right, each stump should be completed in one card to prevent confusion in the measurement.

#### Question: HSU who received services from other PRCs in the same country could they have the same identification number in OpenMrs?

If the Centres are not synchronized together the HUS id won’t be updated in the OpenMrs in another centre as the HSU data needs to be created.

#### Question: How can we manage a HSU who comes for a new service and a repair during the same visit.

Both workflows are exclusive and need to be entered separately; you can start with the workflow repair and after closing the service you open a new service.

#### Question:Do I need to create a HSU in Odoo if it is created in OpenMRS?

No, there is a synchronization between both applications, the HSU is automatically updated in Odoo.

#### Question: How can we merge an HSU that was created 2 times in OpenMrs?

In the DCMS landing page, you can select the widget data management and the option merge patient/HSU.

![](<../.gitbook/assets/image (133).png>) ![](<../.gitbook/assets/image (134).png>)

&#x20; Question: How are the medical conditions mapped in Openmrs?

Through the electronic medical records (EMRs) for Health Service Users can create and manage the medical records. The conditions mapping is based on the International Classification of Disease 10 from the World Health Organization (WHO).

The ICD 10 is available in the forms “Initial Assessment” and the “Service Follow up Assessment” where all conditions based on the profile HSU coming to Physical Rehabilitation Centres. The ICD 10 drop down options are also based on the DHIS2 data.

### Appointment module and professional dashboards&#x20;

#### Question: Can I see all appointments created and given to any HSU?

Yes, the appointment module is open and visible to every DCMS user. It provides transparency and flexibility for each user to avoid appointment 'conflict.

#### Question: Can I refuse or edit an appointment

&#x20;_To edit an appointment:_

o   Click on the appointment you want to edit.

o   Click on the edit button.

o   Fill in the details of the appointment in the Add new Appointment slider.

o   Required details include selecting a Patient, Service/service type, and Date.

o   Adjust the Date of Appointment, Time slot, Providers, and Location as needed.

o   Save the changes.

_To accept an appointment:_

o   If the appointment status is "Requested," you can accept the appointment, which will change the status to "Accepted."

o   Alternatively, you can edit the appointment and propose a new time; once done, the appointment will have the status "Accepted" by default.

Note: When editing an appointment, if service availability is defined and you choose a day or timing outside the availability, there will be a warning.

· &#x20;



Source document(s): [https://collab.ext.icrc.org/sites/TS\_ASSIST/activities/HEALTH/DigitalHealth/Health%20Solutions%20User%20Guides/DCMS/REFERENCE\_GUIDE\_OPENMRS\_censored.pdf](https://collab.ext.icrc.org/sites/TS_ASSIST/activities/HEALTH/DigitalHealth/Health%20Solutions%20User%20Guides/DCMS/REFERENCE_GUIDE_OPENMRS_censored.pdf)

[^1]: 
