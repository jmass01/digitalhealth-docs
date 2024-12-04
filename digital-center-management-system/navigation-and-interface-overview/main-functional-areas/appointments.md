# Appointments

## Appointment

### About the Feature

ICRC Programs offers multiple services to Health Service Users (HSU). These services may have defined days and times when they are offered. For e.g Casting runs every Monday 10.00 AM - 12. PM. Further, we have providers in the hospital who provide these specific services to HSU. Appointments are the means by which providers tend to manage their resources and time to offer services to a HSU.

Appointment scheduling feature is intended to provide the users the ability to schedule and manage appointments for HSU in a typical ICRC Program set up. With the help of this feature one will be able to:

1. Set up services for a program
2. Create and manage appointments for an HSU

### Used By

Appointment feature can be used by any users within ICRC Program and the level of access is defined based on the below set of privileges:

1. **Manage Everyone Appointments** : Create, Edit and Delete appointments for everyone
2. **Manage Own Appointments** : Create, Edit and Delete appointments only for self 3: **Manage Appointment Services** : Create, Edit and Delete Services (This is to add new service types or make changes to service types in appointments)

Ex:

In PHII, Receptionist has Manage Everyone Appointments - So receptionist should be able to schedule, modify appointments with all providers

Hospital Project Manager in WTTC Program has all of the above privileges - so hospital project manager can create or modify any appointments and has the ability to create new services or modify the existing services

### How is it used?

The Appointment scheduling App is available on the Home page

<figure><img src="../../.gitbook/assets/image (63) (1).png" alt=""><figcaption></figcaption></figure>

## Services and Service Type

### About the Feature

A service is that entity which is offered to a HSU by a provider. Users are expected to select a service when scheduling their appointment: Cast, Physiotherapy

### Used By

Typically creating/updating services and specialties are Admin activities. Users will privilege “Manage Appointment Services” will be able to create a new service or edit an existing service

### How is it used?

Click on the Appointment Scheduling App on the Home page. Under the Admin tab of the app, the user will be able to define and edit services.

### Adding a new Service

1. Click on the "Add new Service" button on the screen to access the Services Screen

<figure><img src="../../.gitbook/assets/image (64) (1).png" alt=""><figcaption></figcaption></figure>

### Adding a new Service

1. Click on the "Add new Service" button on the screen to access the Services Screen

The User would be required to provide the following details to create a new service: a. **Name** : Unique name for the service. Mandatory field b. **Initial Appointment Status** : To have options Scheduled , Requested.

i. In case of Scheduled: Appointment with this initial status by default moves to scheduled state ii. In case of Requested: Appointment with this initial status by default goes to request state and users have the option to accept or propose a new time. Once after the new time proposed, appointment by default goes to scheduled state

&#x20;c. **Description** : Describe the service&#x20;

d. **Duration of service** : Consultation time required to offer the service to a patient.

&#x20;e. **Start Time & end time** : The working hours for a service or availability of a service&#x20;

i. For example, if the casting happens from 9.00 AM to 11.00 AM, then start time would be 9.00 AM and end time would be 11.00 AM&#x20;

f. **Max Load:** This is the indicative maximum no. of appointments that can be booked for a service, for a given availability (start and end time mentioned above)

&#x20;i. For example, the casting session can take a maximum of 10 HSU between 9.00 AM - 11.00 AM g. **Location** : A default location where a service is expected to be offered to the HSUs.

&#x20;i. All locations marked as "appointment locations" in openMRS will be available in the dropdown to choose from&#x20;

h. **Label Color:** The services can be assigned colors. On the calendar view, all the appointments booked for this service, will be displayed in this chosen color.&#x20;

i. For a service with label color, when appointment is scheduled for this service and viewed from calendar view will have the color displayed (shown below are appointment with service types marked with Color)

<figure><img src="../../.gitbook/assets/image (65) (1).png" alt=""><figcaption></figcaption></figure>

i. **Service Appointment Type:** i. Service appointment types are the further granular categories under a service. One service may have different types of appointment types under a service For example, Initial assessment, Follow-Up Consultation under Casting service ii. Duration: Each of these types are associated with a particular duration. This will override the service duration iii. Service Appointment types can also be deleted, by clicking on the cross button beside the Service appt. type.

<figure><img src="../../.gitbook/assets/image (66) (1).png" alt=""><figcaption></figcaption></figure>

```
j. Service Availability :
i. One can either mention a global availability for a service as mentioned in
point d above or could specify a more granular availability.
ii. In case of no availability defined, by default service is available on all days of
the week at all times. Multiple availability can be tied to one service.
iii. Example of service availability:
Physiotherapy session is happening on Monday and Friday from 10 AM to 12
PM and Wednesday 2 PM to 4 PM. Then the user will have 2 availabilities
defined:
For Monday & Friday; with a start and end time of 10 AM to 12 PM
For Wednesday; with a start and end time of 2 PM to 4 PM
iv. Max load for that availability (day)
```

1. The max number of HSUs that can be scheduled for a service for a defined duration in the day i.e. limit to the no.of appointments that can be booked.
2. This value will be displayed to the user when they are booking an appointment for the service.

The screenshot below shows the Service availabilities and the Service Appointment Types defined:

<figure><img src="../../.gitbook/assets/image (67) (1).png" alt=""><figcaption></figcaption></figure>

## Creating and Managing Appointments

### How is it Used?

Click on the Appointment Scheduling App on the Home page. Under the "Manage Appointments" tab of the app, click on Appointments List tab.

### Create Appointments

1. Click on the "Add new Appointment" on the Appointments list Tab

<figure><img src="../../.gitbook/assets/image (68).png" alt=""><figcaption></figcaption></figure>

2. The user will have to fill the details of the appointment in the Add new Appointment slider

<figure><img src="../../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>

The following details are required to create an appointment:

```
Note: Selecting a Patient, Service/service type and Date is mandatory to create an appointment.
```

* **Patient** : The Patient can be searched for using Patient name or ID
* **Service** : The service is selected from the dropdown. This will further filter the appointment types under it.
* **Service Appointment Type** : The service appt. type will be selected from a dropdown.
* **Walk-in Appointment** : Users can mark an appointment as a walk-in. By default, appointments are marked as Scheduled.
* **Date of Appointment:** This will be chosen from a date picker. Only current and future dates are allowed.
* **Time slot** : Select the time slot for an appointment.

```
▪ The dropdown will suggest possible slot times based on service availability.
▪ End time will auto populate based on the duration of the service/ service
appointment type. Default of 30 mins if no durations are mentioned.
▪ Users can override the suggested times.
```

* **Providers:** Select the provider for the appointment from the dropdown. Only those providers with provider attribute Available for appointments set to true will be shown. This setting is available in OpenMRS>Administration>Providers>Manage Providers
* **Location:** By default the location will be Service location. User can change the location as applicable.

**Warnings to the user**

* If service availability is defined, if the user chooses a day or timings outside the availability, there will be a warning to the user.
* Booking a patient simultaneously in overlapping times will warn the user of the conflict.
* In both cases mentioned above, the user can still go ahead and book an appointment by ignoring the warning

Screenshot below showcasing the warning message when scheduling an appointment outside of the slot availability time

<figure><img src="../../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

### Manage Appointments

#### Edit Appointments

1. Click on the appointment that you want to edit.
2. Click on the edit button on the Button below

<figure><img src="../../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

3.In case of scheduled appointment when user selects Edit, then appointment opens as shown below, where user have the option to edit Location, Provider and the Date/time of the appointment.

<figure><img src="../../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

4. In case of past appointments or appointments that have been marked as Missed/Canceled/Completed, only Notes field can be edited.

#### Accept Appointments

In case of appointment status as Requested - User will be able to accpet the appointment and doing so will change the appointment status to accepted.

Or user can Edit the appointment and propose the new time and once done an appointment by default will have the status accepted.

<figure><img src="../../.gitbook/assets/image (73).png" alt=""><figcaption></figcaption></figure>

#### Status of Appointment

Appointments can be marked as Checked-in, Cancelled, Missed or Complete.

Check -in - Will mark the appointment status as Checked -In

Complete - Will mark the appointment status as completed

Cancel - Will mark the appointment as cancelled. Once marked as cancelled appointment gets removed from the calendar

Missed - Will mark the appointment as Missed as shown below

<figure><img src="../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>
