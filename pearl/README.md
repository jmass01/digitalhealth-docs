# Introduction

## Introduction

### **1. Overview**

PEARL is a case management system integrated into the International Committee of the Red Cross (ICRC)’s Health Information Systems. Designed to support the collection of personal data, PEARL is currently used for data management in four key health programs: the Hospital Services Program (HSP), Physical Rehabilitation Program (PRP), Mental Health and Psychological Support (MHPSS), and Healthcare in Detention (HCD). PEARL aims to enhance the efficiency of clinical procedures, leading to improved sustainability and effectiveness, which ultimately improves the quality of care for Health Service Users (HSUs).

The system is composed of two primary components:

* **OpenMRS** (Medical Record System): Used for the collection and analysis of individual HSU data.
* **DHIS2** (District Health Information System 2): Used for the visualization and analysis of aggregated data.

This user guide focuses on providing an overview of **OpenMRS** functionalities for clinical data entry.

**Data-entry sequence**

1. To ensure a suitable data entry sequence, it is advisable to take into account the following guidelines:
2. HSUs should always have an **assessment form** before being able to ll anything else. A patient can only be admitted via an assessment form. There should be 1 assessment form entered first.
3. **Follow up forms** can only be entered after an assessment form has been submitted and before the closure form is submitted.
4. **Scales forms** can be submitted between the assessment and the closure forms. It is not possible to create a scales encounter without having an assessment form first.
5. The **closure form** is the last form submitted for the patient. It is required to be able to readmit the patient subsequently. It is not possible to create a closure encounter without having an assessment form first. If a patient has a unique session, the date of the closure should be the same as the date of the assessment, and the reason for closure in the closure form 2.1 should be "single session". No other form can be submitted after that, unless the patient is readmitted again.

### **2. Purpose of the Guide**

This guide serves as a comprehensive manual for users of the PEARL system, specifically focusing on the **OpenMRS** module. Its purpose is to help users effectively navigate the data-entry and case management processes, ensuring correct and efficient use of the system. The guide will provide step-by-step instructions on how to complete forms, follow the prescribed data-entry sequence, and utilize the system’s features to improve workflow in managing Health Service User data.

### **3. Target Audience**

This guide is designed for healthcare professionals and case managers involved in the ICRC's Health Programs, who are responsible for collecting and managing data related to Health Service Users (HSUs). The target audience includes, but is not limited to:

* **Medical professionals** working in the Hospital Services Program, Physical Rehabilitation Program, Mental Health and Psychological Support, and Healthcare in Detention.
* **Case managers** who are tasked with entering, reviewing, and maintaining HSU data.
* **Data entry personnel** who are responsible for ensuring that forms are filled out in accordance with the prescribed data-entry sequence.
* **Health program administrators** who oversee the clinical data collection process.&#x20;



### **4. Key Features**

PEARL’s OpenMRS system offers several key features that streamline the data-entry process and improve clinical efficiency:

* **Health Service User Data Entry** : OpenMRS allows for the collection and management of personal health data for each Health Service User (HSU), ensuring comprehensive documentation.
* **Assessment Forms** : A required first step in the data-entry sequence, used to collect initial health data about the HSU before further information can be recorded.
* **Follow-Up Forms** : These forms are used after the initial assessment and can only be entered after the assessment form is submitted.
* **Scales Forms** : These are submitted between the assessment and closure forms, providing additional details on specific health measurements.
* **Closure Forms** : The final form in the data-entry sequence, marking the closure of a patient's case. A closure form is necessary before a patient can be readmitted.
* **Single Session Handling** : Special handling for patients with unique, one-time sessions, where the closure form and assessment form share the same date and the reason for closure is marked as "single session."

The guide will walk you through how to use these features effectively to ensure data integrity and compliance with the ICRC’s protocols for health service management.
