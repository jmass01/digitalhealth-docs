# PRP Forms & Attachment

## PRP programme forms

To access the PRP form you need to go to the “PRP form dashboard”

* Form recent visit dashboard

<figure><img src="../../.gitbook/assets/image (44) (1).png" alt=""><figcaption></figcaption></figure>

* From PRP dashboard

<figure><img src="../../.gitbook/assets/image (46) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (47) (1).png" alt=""><figcaption></figcaption></figure>

#### Workflow and states (see annex 1)

To complete an PRP HSU workflow, a certain number of forms need to be documented to allow the continuation of the process.

If the user is trying to use one of the essential forms at a wrong time in the workflow an error message will be shown and the save function will be disabled:

For example, if trying to document Assessment Outcome and Goal Setting when services are already started

<figure><img src="../../.gitbook/assets/image (48) (1).png" alt=""><figcaption></figcaption></figure>

### **For Service delivery,**

The following forms have to be filled in, validate and save. The forms in Bold are mandatory to support

**the HSU workflow and the well-functioning of the process**

* **Initial Decision After Registration – Decision IDTA** – Receptionist
* **Initial Assessment** – Interdisciplinary team
* **Initial Assessment Outcome and Goal Setting** – Interdisciplinary team
* **Basic Service Plan** – Interdisciplinary team
* Additional assessment forms (like stump assessment, pain assessment) - Interdisciplinary team or clinician. These forms are not mandatory and can be documented more than once throughout the services
* **Financial Capacity Assessment** – Social worker
* Socio – Economic Assessment and **Financing Decision** if HSU cannot pay – Social worker
* **The first Services Delivery form** (to be selected depending services) – One of the clinician o Any of the technical card o Basic and Intermediate Wheelchair Assessment o Walking Aid Measurement Card o Physiotherapy assessment and treatment plan o Club foot treatment record assessment & Cast follow up o Service Follow up assessment
* Additional Services Delivery form (to be selected depending on the services) – Clinicians
* **Final Assessment Outcome and Goal Setting -** Interdisciplinary team

Remark 1 : If needed after the services have started, an intermediate assessment can be done. Depending on the decision (adjust services), the financial capacity assessment will be mandatory.

Remark 2: Decision initial Assessment Outcome and Goal setting.

<figure><img src="../../.gitbook/assets/image (49) (1).png" alt=""><figcaption></figcaption></figure>

1. Plan services - Continue workflow
2. Referral – Document referral form with _Orthopaedic consultation or stump revision_. Episode of service automatically closed
3. Refer to additional examination – No change in workflow status. Decision can be changed when HSU comes back with result. Document referral form
4. Not eligible for services – Episode of service closed

### **- For Follow up**

* **Initial Decision After Registration – Decision MIA** – Receptionist
* **Service Follow up Assessment** – Follow up in charge
* **Financial Capacity Assessment – Follow up** – Social worker
* AT Record repair done – Follow up in charge

### Attachments

#### Viewing attachments

1. In the PRP dashboard, scroll down to the ‘ _Attachments’_ option (last option at the bottom of the dashboard).
2. To view a previously uploaded attachment, click on the relevant attachment.

<figure><img src="../../.gitbook/assets/image (50) (1).png" alt=""><figcaption></figcaption></figure>

### Adding attachments

1. On the PRP dashboard, click on the icon next to _‘Attachments’_.
2. To select a file: a. click and drag the file from your computer to the ‘ _File_ ’ area or b. click anywhere in the ‘ _File’_ area. This will redirect to your computer’s file storage system. Navigate to the desired file and click ‘ _Open’_ ; c. enter a file name in the ‘ _Caption’_ text box.

_NOTE: Whatever is entered in the ‘Caption’ text box will become the file name in OpenMRS._

3. Click ‘ _Upload file’_.

```
It is currently not possible to delete an attachment.
```

<figure><img src="../../.gitbook/assets/image (51) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (52) (1).png" alt=""><figcaption></figcaption></figure>

### Generic Form Features

* Encounter Date and Validation

Forms have an “encounter date” – Date Automatically populated when opening forms and a “validated by” check box

<figure><img src="../../.gitbook/assets/image (53) (1).png" alt=""><figcaption></figcaption></figure>

If the form is validated + saved, it is not editable anymore

If the form is saved without checking the validated by, it stays editable.

```
Exception to the “validated by rule”: Financing Decision ( Editing ):
```

* Financing Decision\* section **Editable** if NOT Approve for Services (even with Validated By fulfilled)
* Financing Decision\* section **Read-only** if Approve for Services (and with Validated By fulfilled)

**Exception to the “validated by rule”: Technical cards**

* Date below the validated \* stay **Editable** even after form validated and saved
* Date picker: Allow to document dates in a form but is not recorded as the encounter date (the day the form was done)

For example, on the technical cards:

<figure><img src="../../.gitbook/assets/image (55) (1).png" alt=""><figcaption></figcaption></figure>

* Information and Visual guides: Used to support the user in making sure he/she is documenting the right thing.

For example, on the Wheelchair assessment:

<figure><img src="../../.gitbook/assets/image (54) (1).png" alt=""><figcaption></figcaption></figure>

* Difference between radio button and check boxes

A radio button is used when you can select **only one option** in a list

For example, questions in the General Information, Initial Assessment

<figure><img src="../../.gitbook/assets/image (56) (1).png" alt=""><figcaption></figcaption></figure>

* A check box is used to allow **a multiple-choice** selection (one or more)

For example, the Comorbidity and Past Medical History list in the Condition form, Initial Assessment.

<figure><img src="../../.gitbook/assets/image (57) (1).png" alt=""><figcaption></figcaption></figure>

* **+ /-** sign inside a form to add same group of information more than once

<figure><img src="../../.gitbook/assets/image (58) (1).png" alt=""><figcaption></figcaption></figure>

By clicking on the “+” you can add a line (or a group of line) and document it multiple time.

By clicking on the “-“ you can remove a line that you have added and you decide is not relevant.

* Auto populated field are fields automatically populated with information coming from another form or from an automatic calculation. These fields are pasted in grey color and cannot be changed.

Example, 1 , the field assessment outcome (summary) in the Final Assessment Outcome and Goal Setting contain the information from the last assessment done (initial or intermediate).

<figure><img src="../../.gitbook/assets/image (59) (1).png" alt=""><figcaption></figcaption></figure>

Example 2, the field “Follow-up date according to HSU Age is automatically documented with a calculation rule:

**• If the user age is under 6 years, then appointment date will be after 3 months**

**• If user age is from 6 years to 15 years, then the appointment date will be after 6 months**

**• If the user age is more than 15, then the appointment date will be after a year**

<figure><img src="../../.gitbook/assets/image (60) (1).png" alt=""><figcaption></figcaption></figure>

* Mandatory fields are fields that need to be documented before the form can be saved. They are marked with a “\*”.

If the user is trying to save a form forgetting some fields, it will be impossible to save and an error message will be showing.

For example, in the stump assessment:

<figure><img src="../../.gitbook/assets/image (61) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (62) (1).png" alt=""><figcaption></figcaption></figure>
