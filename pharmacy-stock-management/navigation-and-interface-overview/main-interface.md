# Main interface

## 1 OVERVIEW OF THE PHARMACY STOCK MANAGEMENT APPLICATION

## 1.1  Overview of the Pharmacy Stock Management application

The PSM project provides a web and mobile app-based tool (with off-line capability), real-time digital solution for stock and order management as well as detailed business analytics at and for assisted health care facilities. It is fully integrated with the ICRC ICT environment (IRIS and Tableau Business Analytics) and provides global, real-time stock and data visibility to all pharmacy staff as well as ICRC Health programme managers, logistics services and general management with access from any computer or mobile device connected to the ICRC network anywhere in the world.

Staff at ICRC assisted health care facilities replaces data collection on paper or with spreadsheet applications by recording data directly on mobile devices on-line (with off-line capability) using a dedicated mobile device application specifically adapted to the Imprest System. And Health staff will no longer have to re-enter data provided by pharmacies into Excel files (or any other application) for calculating monthly replenishment orders.

The current, paper- (or spreadsheet) based, workflow for replenishing pharmacies at assisted health care facilities is replaced by a fully digital, integrated and systematic workflow which is standardized across all assisted health care facilities in the ICRC using the Imprest System. Health program managers can manage and control Imprest Levels at the item level for each facility without any other users having access and being able to modify replenishment calculations.

A dedicated IRIS Imprest Order management application will access pharmacy data as well as data from JDE (stock on order) for correctly calculating monthly orders based on the Imprest System and placing orders directly in IRIS (JDE front-end, user interface for the ICRC Logistics Information System) like any other order.

Health and management staff at all levels will have access to all data from assisted health care facilities through the ICRC Business Analytics application (Tableau) and be able to visualize and analyse data of individual or across several health care facilities.

For health care facilities using the “Advanced mode”, Health managers, logistics planners and management staff will have access to global, real-time stock and stock management data across all assisted health care facilities as well as a complete history of all data at the level of supplied wards and services within health care facilities.

The PSM serves as a mobile data collection tool for recording (entering/changing/managing) logistics data (Imprest Level, Stock on Hand and Stock distributed) at ICRC assisted health care facilities. Data is stored on a DHIS2 server at the ICRC in Geneva and integrated with IRIS for calculating replenishment orders as well as with Tableau for business analytics.

### 1.2 Structures and preconditions

The application is based on adherence to specific structures and processes which inform the system design and functionality.

* All assisted health care facilities are owned and managed by non-ICRC entities such as state authorities, Ministries of Health (MoH), National Red Cross/Red Crescent societies and communities.
* Almost all users at the health care facility are non-ICRC staff and neither have an ICRC ICT profile nor an ICRC email address.
* In every health care facility, all medical stocks provided by the ICRC are stored and managed in a single central pharmacy. In addition, other medical stocks donated by other actors may be managed separately inside the same health care facility.
* While the system and application is primarily designed for managing health care goods, any other types of goods such as food, cleaning materials, stationery etc. could also be managed.
* A single (central) pharmacy supplies all wards and services of the health care facility.
* The Imprest System is used in all wards/services and the pharmacy as the sole inventory control system.
* For the medical store managing ICRC supplied stocks, a stock item list is clearly defined, maintained and managed by the responsible ICRC programme manager.
* The system will replace and facilitate certain current processes, but health care facilities are of course free to continue any additional manual or electronic data recording and processing systems (such as using bin card, stock cards, delivery records, tally sheets etc.), especially if these are required under national guidelines and policies.
* All pharmacies have at least daily access to at least a 2G mobile phone network for transmitting and receiving data or (if this is not the case), once a month, the mobile device can be physically taken to an ICRC office with a driving distance of less than one hour for synchronizing data and returning the mobile device to the health care facility.
* Health care facilities using the "advanced" mode will require at least a daily network connection to a WLAN or a 3G mobile phone network at the site of the health care facility for synchronizing data.
* In case of any part of the system failing, pharmacies must be able to "switch" back to a manual (backup) system at any time without in any way impairing the supply of the pharmacy.
* State authorities, health authorities (national, provincial, district level), management of health care facilities as well as pharmacy staff agree to the use of mobile devices for recording, storing, managing and transmitting pharmacy stock data.
* For security reasons, no private mobile devices, either or ICRC or non-ICRC staff, must be used. Instead dedicated mobile devices will be provided by the ICRC and made available to non-ICRC staff at health care facilities permanently or temporarily at any time needed for the purposes of managing medical stocks in the facility.
* Staff at the health care facility are conversant with the use of mobile devices or can be trained (within reasonable time).

### 1.3 Overview of processes and use cases by user groups

The Pharmacy Stock Management (PSM) application has three specific functionalities which are used by different groups of users:

* Pharmacy stock management at assisted health care facilities in DHIS2.
* Pharmacy order management in IRIS at ICRC offices and (sub)-Delegations.
* Business Analytics in Tableau at health care facilities and ICRC offices and (sub)- Delegations. **1. 3. 1 Pharmacy stock management in the DHIS2 mobile device application**

The application is used by storekeepers of medical stores at ICRC assisted health care facilities. In the great majority of cases, these storekeepers are non-ICRC staff members.

"Ward" stands for any facility in any health care facility which holds and manages stocks of any kind which are regularly replenished such as patient wards, dispensaries (OPD), operating theatres, sterilization services, laboratory and blood transfusion services, diagnostic imaging or other services.

#### Processes

* Monthly physical stock count at the pharmacy.
* Receiving and put-away of stocks sent by an ICRC medical warehouse.
* Managing stocks.
* Receiving, recording and managing periodic orders from wards and services.
* Picking, packing and delivering ordered goods to wards and services.

#### Use cases

* "Basic mode": digital recording, storage and transmission of (at least monthly) stock data.
* "Advanced mode": digital recording and transmission of stock issues to wards in real-time.
* Basic business analytics in DHIS2 mobile device application.

#### 1.3.2 Pharmacy order management in IRIS

The responsibility for the monthly order lies with ICRC staff (Hospital Administrator, Hospital Project Manager, Programme Manager or other staff assigned by the Health Coordinator) according to the decision of the ICRC Health Coordinator.

#### Processes

* Determine, set, review, analyse (in Tableau) and revise Imprest Levels.
* Analyse stock data.
* In IRIS, review and revise proposed order calculations and place monthly orders ("Supply Request") to ICRC medical distribution centres.
* Consult dashboards and other (self-service) analysis in Tableau for management and monitoring the quality of stock and order management.

#### Use cases

* Preparing monthly pharmacy orders (revising Imprest Level, order calculation and processing)

**1.3.3 Business Analytics**

Business Analytics will be available to all staff at health care facilities and within the ICRC (field and regional level and the head office, Health as well as management staff) according to user access determined by the ICRC Health Coordinator.

Three distinct applications will be used for different user groups and using different applications:

* DHIS2 mobile device application: basic reporting and analysis for pharmacy staff.
* DHIS2 web portal: advanced reporting and analysis only of stock data for ICRC staff at the programme level
* Tableau BI Server: detailed analysis of stock data and ICRC logistics data for ICRC Health staff and logistics specialists at all levels

#### Use cases

* Consult basic analysis and dashboards at the health care facility level in DHIS2.
* Consult dashboards and other analysis in Tableau for management and monitoring

## 1.4 Business process flow mapping

The flow map below represents a high-level overview of business processes, actors and tools of the PSM application.

<figure><img src="../.gitbook/assets/image (216).png" alt=""><figcaption></figcaption></figure>

The flow map below represents "Basic mode" processes of the monthly physical stock count at the pharmacy with recording data in the DHIS2 Capture app.

<figure><img src="../.gitbook/assets/image (217).png" alt=""><figcaption></figcaption></figure>

In the "Advanced mode", only stock issues are recorded while the stock on hand is calculated in real time from the stock receipts and stock issues which eliminates the need for the monthly physical stock count.

<figure><img src="../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>

The review, and if needed revision of the Imprest Level, as well as preparation of the monthly stock replenishment order is the same for the "Basic mode" and the "Advanced mode".

<figure><img src="../.gitbook/assets/image (219).png" alt=""><figcaption></figcaption></figure>

## 1.5 User support

User support will be provided at different levels but should be available as close to the end- user in the field as possible to ensure knowledge of the language, context as well as the same time zone and working schedule.

User training and support on functional issues concerning processes, workflows and DHIS functionality:

* Peer to peer support by colleagues working in other Health programmes
* Health programme manager
* Technical specialists in the region and at the head office

#### DHIS2 metadata configuration and any technical issues related to the DHIS2 server instance:

* ICT Service Desk at the Belgrade Shared Service Centre (BSSC) For IRIS and Tableau BI Server the ICT Service Desk will provide services as for any other ICRC application.

Users at health care facilities (not all of which have an ICRC email account or access to the ICT ServiceDesk) are expected to first consult with the respective ICRC Programme Managers who in turn will contact the ICT Service Desk if needed.

## 2 DEVICE MANAGEMENT

This chapter details the use of desktop computers which will be used only by ICRC (resident and national) staff (who also have access to the mobile device application) and non-ICRC users who will only have access to the mobile device application.

### 2.1 ICRC desktop and notebook personal computers

ICRC staff, such as Hospital Administrators, Hospital Project Managers, other project managers (Primary Health Care, Health in Detention, First Aid and Prehospital Emergency Care) will primarily access the DHIS2 web portal through any ICRC device allocated to them. These devices are managed by the respective Delegations according to well established policies.

The use of the DHIS2 web portal does not require any specific configuration of personal computers or any particular device and IRIS and Tableau BI Server are already routinely used by all Health staff.

All ICRC staff members have access to the ICRC network and a multitude of applications, will simply bookmark the DHIS2 web portal URL and access it as needed with their authentication.

### 2.2 Selection of mobile devices

The Pharmacy Stock Management application can be run on any mobile device which supports the DHIS2 application which supports, as an absolute minimum, Android versions of 4.4 (KitKat, launched in October 2013) and higher but recommends the use of Android versions of at least 7.x (Nougat, launched in August 2016) or higher and recommends better using at least Android version 8.x (Oreo, launched in August 2017).

While in principle smart phones can be used for running DHIS2, the use of tablet PCs is strongly recommended in order to display the entire width of the user interface in landscape mode without the need for having to scroll left and right on the screen.

DHIS2 recommends the following, minimum specifications which is compared with the specifications of the tablet computer recommended by the ICRC ICT department.

| Specification                    | DHIS2                                                              | Samsung Galaxy Tab S6 Lite SM-P615                        |
| -------------------------------- | ------------------------------------------------------------------ | --------------------------------------------------------- |
| Construction                     | Lifespan of at least 2 years                                       | two years average battery life                            |
| Android operating system version | minimum 4.4, minimum recommended 7.X and recommended 8.X or higher | Android 9.0                                               |
| Processor                        | 4 cores, 1.2 GHz                                                   | 8 cores, 2.3 GHz                                          |
| RAM                              | minimum 1.5 Gb, recommended more than 3 Gb                         | 4 Gb                                                      |
| Storage                          | minimum 8 Gb, recommended 32 Gb                                    | 64 Gb                                                     |
| Screen size                      | minimum 7 inches                                                   | 10.4 inches                                               |
| Camera                           | minimum 5 megapixel, recommended at least 8 megapixel              | 8 megapixel                                               |
| Connectivity                     | 4G (LTE) / 3G and WLAN                                             | <p>Bluetooth, WLAN, 4G (LTE)</p><p>nano SIM-card slot</p> |

ITABTBLTGLXS6LT Tablet Samsung Galaxy Tab S6 Lite WiFi – price 247 CHF ITABTBLTGALTCS6 Tablet Back Cover Rugged GRIP Galaxy Tab S6 – price 27 CHF

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

It is an explicit requirement of the PSM project that access to the DHIS2 mobile device application is possible through any Android mobile device and does not require the use of an ICRC mobile device. Also, access of the DHIS2 server instance by mobile devices must be possible through any public Internet access (WLAN or mobile Internet) and not require access to any ICRC (internal) network.

In 2022, the standard device which complies with a range of specific technical requirements, and which should be ordered by default is the Galaxy Tab S6 Lite / SM-P615:

ITABTBLTGALTCS6 Tablet Back Cover Rugged GRIP Galaxy Tab S The rugged cover (which is not provided by default) should always be ordered to protect the device from damage and is in particular indispensable when using the “Advanced mode” as the loop for holding the tablet computer with one hand is essential for scanning barcodes.

Since Jan 2023, the standard tablet model for all the purchases has been changed by the ICRC ICT. Therefore, the model mentioned above has been no longer available for purchase for new deployments. The old sites have continued to use the old one as long as it is functional.

The specifications for the new model are as follows: Tablet: Samsung Galaxy Tab Active 4 Pro LTE Enterprise Edition 128 GB ( can fit a sim card) Ref: SM-T636BZKEEEE Street price: 760 CHF ICRC Item code: ITABTBLTTA4PR5G This item is a standard ICRC device which can be ordered through the usual IRIS SR.

### 2.3 Ownership of mobile devices

The use of private mobile devices whether owned by ICRC or non-ICRC staff is not allowed for data protection reasons and to avoid disputes over payment of mobile Internet charges as well as fees for their use.

#### The mobile devices can be managed in two ways:

* The mobile device is purchased by the ICRC and handed over to the management of the health care facility with a donation certificate indicating its dedicated use for pharmacy stock management. Device do not need to be registered or managed by the ICT department.
* The device remains property of the ICRC and is assigned to the project manager or field officer like any other ICRC device who then makes it available to the pharmacy staff when and as required.

Depending on circumstances, the ICRC mobile device may be permanently kept in the pharmacy (under lock and key or not) or kept at the ICRC office and provided to and retrieved from the pharmacy by the ICRC staff member when and as needed.

### 2.4 Management of mobile devices

Various mobile devices are already in use in the ICRC for some time for various projects and different purposes and mobile devices will inevitably become a basic requirement for most ICRC Health programmes in future:

* Almanach expert system for facilitating childhood disease diagnostic using mobile phones
* Tablet PCs for the mobile digital x-ray unit Dragon Fly X LW
* PEARL and HeMAP
* Telemedicine
* Various EcoSec projects The possibility of sharing a single (or several) device(s) among programmes for different purposes will have to be decided by the respective Health programme managers depending on the number of users and the frequency of use.

For health clinics, mobile devices could also be shared among nearby health care facilities. As increasingly mobile devices are used by different departments such as by EcoSec for Device Magic or Red Rose, the possibility of sharing between departments should also be considered.

The respective Health departments will have to budget, order and manage the devices as well as any mobile Internet subscriptions which may be needed.

Every health care facility should also have access to a backup device which can be used if the primary mobile device is not functional. Such backup devices may be shared among health care

facilities or even different programmes.

The ICRC ICT services are not responsible for maintaining, servicing or repairing mobile device which are donated to health care facilities and any services will have to be purchased from commercial suppliers.

### 2.5 Contingency plan in case of device failure

The "Basic mode" (monthly reporting) in any case requires maintaining manual (paper) records, at least stock cards, for recording daily transactions. The "Advanced mode" in principle does not require maintaining stock cards and if the digital system fails, all stock issues to wards or other services need to be recorded manually during the time of the failure. Alternatively (or additionally) a monthly physical stock count can be carried out at the end of the month which, together with the stock receipts recorded from IRIS/JDE allows calculating the total stock issues.

In case the mobile device fails or malfunctions for any reason (out of charge, damaged, not found, stolen, authentication forgotten) or the Internet access is not available, health care facilities have various options. In any case, the DHIS2 web portal will always be available (or with only short interruptions) at all ICRC sites as this application is managed by the ICRC ICT department with daily backups and technical support for resolving any technical, software or network issues.

#### In case of (temporary) Internet access problems

* Physically move the mobile device to an ICRC office, synchronize data and return the mobile device to the health care facility
* Use of WLAN hotspot of an ICRC vehicle furnished with BGAN 323 (or BGAN 325 without WLAN but the option of connecting a mobile device to the terminal with a USB cable). This system is under field testing since 2021 and will be globally implemented in the coming years.
* Use of a satellite Internet modem

#### In case of (temporary) mobile device failure

* Use the backup mobile device
* Exceptionally, use the DHIS2 web portal for updating stock data ("Basic mode" only)

**In case all systems fail (temporarily)** At any time, users can resort to the manual, paper- or spreadsheet-based method which was in use prior to implementing the Pharmacy Stock Management tool:

* Carry out the physical stock count
* Record the stock on hand and monthly consumption on a worksheet printout or

## 3 DISTRICT HEALTH INFORMATION SOFTWARE 2 (DHIS2) SOFTWARE

DHIS2 (District Health Information Software 2) is offered free of charge as a Global Public Good (free and open software), the world’s largest health information management system (HMIS) which was developed by the HISP Centre at the University of Oslo and has been implemented in more than 70 countries covering 30% of the world’s population.

### 3.1 System components

#### DHIS2 consists of three main components:

* DHIS2 mobile device application - DHIS2 Capture App
* DHIS2 web portal
* DHIS2 server instance

#### 3.1.1 DHIS2 mobile device application - DHIS2 Capture App

As the users at assisted health care facilities rely entirely on the mobile device application, its accessibility to non-ICRC users, user friendliness, adaptation to user needs and convenience are critical for the acceptance of the mobile device application.

The principle of "digital frugality" of keeping the mobile device application as simple, "light" and "lean" as possible was an explicit objective of the project. The mobile device application features only a login window for authentication, a window for selecting the appropriate data set and a third window for editing stock data.

Another principle is that the DHIS2 mobile device application must be kept as simple, intuitive and clear as possible as not all users in the field are necessarily conversant with using mobile devices and needs for user training as well as risks for incorrect use should be minimized.

The DRY ("Don't Repeat Yourself") software development principle is strictly applied ("Every piece of knowledge must have a single, unambiguous, authoritative representation within a system") and redundancies and duplications are avoided.

The mobile device application is primarily intended for collecting, temporarily storing and transmitting to the server in Geneva only essential data which could not be collected otherwise. Anybody requiring access to additional data or business analysis can either access the DHIS web portal or the Tableau BI Server.

Among other reasons, this approach minimizes the frequency, amount of data and size of data packages which need to be transmitted from the mobile device which reduces the time of data transmission, reduces costs and increases resilience of the data transmission to poor mobile Internet connections.

Around one-to-four-hundred-line items will and can be managed by this mobile device application. Although in principle there is no limitation by the system, usability decreases with an increasing number of line items.

The DHIS2 Capture app is only available on Android devices. Access to the Pharmacy Stock Management application does not require any ICRC profile or access to the ICRC network and is accessible to any non-ICRC staff members, provided they have been granted access by the respective Health programme managers.

The mobile device application can be accessed through any WLAN or public Internet connection and does not require any ICRC network but is of course also accessible through the ICRC network.

The DHIS2 Capture App was designed for off-line use and allows recording, storing and managing all data on a local database of the Android device which is synchronized whenever a network connectivity is available.

Any data values entered on the mobile device using the DHIS2 Capture is stored instantly upon entry and does not require "saving".

The mobile device application does not allow users to export or download data from the mobile device in any way nor is this required. Previously recorded data can be viewed in dashboards on the mobile device and all data is also available in the DHIS2 web portal and the Tableau BI Server.

#### 3.1.2 DHIS2 web portal

The DHIS2 web portal will only be accessible on the ICRC network and therefore require users to have an ICRC user profile as well as an authentication for DHIS2 and will be used mainly for managing the Imprest Level and basic business analytics.

The application will be accessible through standard ICRC web browser applications where Chrome is recommended by ICT services.

#### 3.1.3 DHIS2 server instance

The DHIS2 server (instance) is the physical device where the DHIS2 software is installed, permanently running and allows a large number of users to connect to the DHIS2 web portal as well as the DHIS2 mobile device application and its database at any time.

DHIS2 is hosted at the ICRC head office in Geneva as a standard ICRC application managed by the ICT department in Geneva. Systems are protected by the usual ICT security protocols and all data is regularly backed up to allow restoring data in case of damage to or failure of the server.

### 3.2 Processed data

The table below lists the data items, their category (also represented by colors), attributes, data type, origin of the data value and the owner of the data. For some data fields the names differ in different software applications. For example, "2nd Item Number" (JDE) is identical with "Item code" (DHIS2) or "Name (Ship To)" (JDE) is identical with "Recipient Place Master Name" (Locator).

<table data-full-width="true"><thead><tr><th width="157">Data category </th><th>Attribute </th><th>Data Type </th><th>Origin data base of data values</th><th width="123">Data owner </th><th>Comments </th><th>Personal data</th></tr></thead><tbody><tr><td>Recipient Place data </td><td>Recipient Place Master name </td><td>Text (name) </td><td>Locator </td><td>ICRC </td><td> </td><td>Personal data</td></tr><tr><td>Recipient Place data </td><td>Recipient Place Master name </td><td>Text (alphanumeric) </td><td>Locator </td><td>ICRC </td><td> </td><td>Personal data</td></tr><tr><td>Recipient Place data </td><td>Recipient Place Master name </td><td>Geographic coordinate </td><td>JDE </td><td>ICRC </td><td></td><td>Personal data</td></tr><tr><td>Recipient Place data </td><td>Recipient Place Master name </td><td>Geographic coordinate </td><td>JDE </td><td>ICRC </td><td> </td><td>Personal data</td></tr><tr><td>Item data </td><td>2nd Item Number </td><td>Text (alphanumeric) </td><td>JDE </td><td>ICRC </td><td> </td><td> </td></tr><tr><td>Item data </td><td>Description </td><td>Text (alphanumeric) </td><td>JDE </td><td>ICRC </td><td> </td><td> </td></tr><tr><td>Item data </td><td>Description - Line 2 </td><td>Text (alphanumeric) </td><td>JDE </td><td>ICRC </td><td> </td><td> </td></tr><tr><td>Facility data </td><td>Recipient Place Master name </td><td>Text (name) </td><td>PSMDIA application </td><td>ICRC </td><td>Copied from RADAR database </td><td>Personal data </td></tr><tr><td>Facility data </td><td>User Role </td><td>Text (name) </td><td>PSMDIA application </td><td>ICRC </td><td>Storekeeper, project manager </td><td> </td></tr><tr><td>Facility data </td><td>Username = RP master name + user role </td><td>Text (name) </td><td>PSMDIA application </td><td>ICRC </td><td> </td><td> </td></tr><tr><td>Facility data </td><td>Password </td><td>Text (alphanumeric) </td><td>PSMDIA application </td><td>ICRC </td><td> </td><td> </td></tr><tr><td>Stock data </td><td>Stock on Hand - field </td><td>0 or positive integer </td><td>PSMDIA web application </td><td>ICRC </td><td>Field name without value (quantity) </td><td> </td></tr><tr><td>Stock data </td><td>Imprest Level - field </td><td>Positive integer </td><td>PSMDIA web application </td><td>ICRC </td><td>Field name without value (quantity) </td><td> </td></tr><tr><td>Stock data </td><td>Batch number - field </td><td>Text (alphanumeric) </td><td>PSMDIA web application </td><td>ICRC </td><td>Field name without value (quantity) </td><td> </td></tr><tr><td>Stock data </td><td>Expiry date - field </td><td>Data (month / year) </td><td>PSMDIA web application </td><td>ICRC </td><td>Field name without value (quantity) </td><td> </td></tr><tr><td>Stock data </td><td>Stock on Hand - value </td><td>0 or positive integer </td><td>PSMDIA mobile application </td><td>Health care facility </td><td>Actual quantity </td><td> </td></tr><tr><td>Stock data </td><td>Imprest Level - value </td><td>Positive integer </td><td>PSMDIA web application </td><td>ICRC </td><td>Actual quantity </td><td> </td></tr><tr><td>Stock data </td><td>Batch number - value </td><td>Text (alphanumeric) </td><td>PSMDIA mobile application </td><td>Health care facility </td><td>Actual quantity </td><td> </td></tr><tr><td>Stock data </td><td>Expiry date - value </td><td>Data (month / year) </td><td>PSMDIA mobile application </td><td>Health care facility </td><td>Actual quantity </td><td> </td></tr><tr><td>Order data / past </td><td>2nd Item Number </td><td>Text (alphanumeric) </td><td>JDE </td><td>ICRC </td><td>= Item code </td><td> </td></tr><tr><td>Order data / past </td><td>Name (Ship To) </td><td>Text (name) </td><td>JDE </td><td>ICRC </td><td>= "Recipient Place Master name" </td><td> </td></tr><tr><td>Order data / past </td><td>Quantity Origin (outstanding quantity) </td><td>0 or positive integer </td><td>JDE </td><td>ICRC </td><td>Next status &#x3C; 999, Last status &#x3C;> 980 </td><td> </td></tr><tr><td>Order data / calculated </td><td>Name (Ship To) </td><td>Text (name) </td><td>PSMDIA mobile application </td><td>Health care facility </td><td>= "Recipient Place Master name" </td><td>Personal data </td></tr><tr><td>Order data / calculated </td><td>Item code </td><td>Text (alphanumeric) </td><td>PSMDIA mobile application </td><td>Health care facility </td><td>= "2nd Item Number" </td><td> </td></tr><tr><td>Order data / calculated </td><td>Stock on Hand - value (quantity) </td><td>0 or positive integer </td><td>PSMDIA mobile application </td><td>Health care facility </td><td> </td><td> </td></tr><tr><td>Order data / calculated </td><td>Imprest Level - value (quantity) </td><td>Positive integer </td><td>PSMDIA web application </td><td>ICRC </td><td> </td><td> </td></tr><tr><td>Order data / calculated </td><td>Order quantity rounded </td><td>Positive integer </td><td>IRIS </td><td>ICRC </td><td>This value is calculated in IRIS </td><td> </td></tr></tbody></table>

The chart below represents the flows of data items presented above. Note that "fields" in the DHIS2 mobile device application are initially empty (at least for certain dates) but required to define fields in the mobile application where the data "values" (quantities) are entered which are then returned to the DHIS2 server instance.

The data model below is a simplified representation of the "visible" data processed in the system while any (other) meta and system data (such as IP addresses, data and time stamps, encryptions etc.) are not depicted. The data model represents:

* The data items
* Grouping of data items (such as item data, stock data etc.), represented by colours
* The location where the data resides (ICRC or health care facility)
* The data base of origin of the data field (Locator, JDE or IRIS)
* The data base of the origin of the data value (mobile device application, JDE or IRIS)
* Whether the data item originates in the indicated location or just transmits a "copy"

In addition to the recorded data visible in the DHIS2 web portal, a complete audit table (log file) of every system access (user as well as date/time stamp) as well as a complete record of all transactions (changes to any data) carried out is indispensable for business analytics purposes. A complete record of all data values and the date/time they were made must be available (and not just daily "snapshots" of the data values).

<div data-full-width="true"><figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure></div>

As, once the rollout has been completed, addition of new health care facilities will be relatively rare and there is no default setting indicating which health care facilities use the Pharmacy Stock Management tool and which ones do not, this data is updated manually by BSSC by uploading a corresponding data file.

Likewise, adding additional items will be relatively rare and therefore also done "manually" rather than being automated.

### 3.3 System integration

In order for the Pharmacy Stock Management system to provide all required functionality, the DHIS2 server, IRIS/JDE server and Tableau BI server are integrated with each other according to the diagrams below.

In the "basic scenario" the following integrations are required:

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

In addition to the above, the integrations required for the "advanced scenario" requires synchronizing shipping data from the JDE server to the DHIS2 server (instance).

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

## 4 District Health Information Software 2 (DHIS2) system management

This chapter explains the complete configuration of DHIS2 as well as its management which will be the sole responsibility of the BSSC who will apply the same standards and policies as for HeMAP. Therefore, this chapter is not intended for everyday users but rather serves a documentation of the entire system and for enhancing the understanding of the system and its configuration by any interested user.

Field users will not have any access to most of the configuration options but may want to understand their implications for the user of the system.

### 4.1 Overview of DHIS2 apps

In DHIS2 “app” denotes a host of applications within the DHIS2 web portal with are represented by icons but are not mobile applications (“mobile apps”). Below an overview of the various DHIS2 apps, most of which are available only to system administrators, which are in use for the PSM project:

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

### 4.2 System Settings app

The System Settings app is used by system administrators for managing some general settings, appearance of the home page, languages, general user access and others. This chapter will

document the settings without explaining them in detail. Please refer to the online DHIS2 Documentation for details: [_https://docs.dhis2.org/en/use/use.html_](https://docs.dhis2.org/en/use/use.html)

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

#### **4.2.1 General**

The following settings are configured:

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

#### 4.2.2 Analytics

The following settings are configured:

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

#### 4.2.3 Server

The following settings are configured:

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

#### 4.2.4 Appearance

By default, the "Interface language" as well as the "Database language" are set to English. The following settings are configured:

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

#### 4.2.5 Email

Email notifications are not used in PSM but the following generic DHIS2 settings are maintained:

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

#### 4.2.6 Access

The following settings are configured:

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

#### 4.2.7 Calendar

The standard date format is set to day/month/year. The following settings are configured:

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

#### 4.2.8 Data Import

The following settings are configured:

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

#### 4.2.9 Synchronization

The following settings are configured:

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

#### 4.2.10 OAuth2Clients

The following settings are configured:

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

### 4.3 Users app

The Users app allows configuring User roles, creating user profiles for individual users and assigning them to defined User groups.

#### 4.3.1 User

BSSC will give access to all users. ICRC employees continue to use their SSO (Single Sign On) which allows them to access all DHIS2 applications to which they have been granted access with their usual ICRC credentials.

For all non-ICRC staff, the ICT Service Desk will create a user profile and a “dummy” ICRC profile with an ICRC email which can only be used for the Microsoft Authenticator but is not linked to any actual email account and does not allow using Outlook or any other ICRC applications. With this “dummy” profile, the respective non-ICRC staff can access all DHIS2 applications using SSO (Single Sign On) without any specific usernames or password like any other ICRC staff. However, they will require a Username and password for accessing the ICRC ICT environment and using the Microsoft Authenticator.

Any user, whether employed by the ICRC or not, can be granted access to the PSM application by the responsible project manager who needs to submit a request to the BSSC for configuring the required user settings.

The ICRC ICT security policy requires every user logging into any ICRC application to be clearly and uniquely identifiable with their real name and every user must also possess its own and unique email address.

For every user the default "Interface language" as well as the "Database language" is set to English, French, Spanish, Russian or Arabic by the BSSC when the use profile is created but which can be overridden by the user in their individual user profile settings.

According to their responsibilities, needs for accessing (viewing) data and authority to change (edit) data, every user is assigned one or several of the "User roles" and assigned to one specific (or exceptionally more than one) Organisation unit for which s/he has access for viewing and editing data.

#### 4.3.2 User role

Five distinct User roles are configured which each give access to specific DHIS2 apps and determine whether users can access certain metadata such as Data elements, Data sets or Organisation units. Separate user roles for the "Basic mode" and the "Advanced mode" allow configuring access to sites for either of the modes as any time only a single mode (either the "Basic mode" or the "Advanced mode") must be used by all users of any health care facility (Organisation unit).

**PSM advanced mode - data entry** This User role allows users to access the “Advanced mode” on mobile devices using the customized DHIS2 app for viewing, entering and editing stock data.

**PSM basic mode - data entry - Stock data (mobile only)** This User role allows users to access the DHIS2 Capture app (native app) on mobile devices for viewing, entering and editing stock data.

**PSM data entry - Imprest Level** This User role allows ICRC programme managers to access the DHIS2 web portal for viewing, entering and editing the Imprest level as well as correcting stock data should this exceptionally be necessary.

**PSM Reader** This User role allows users to view stock data in Data entry forms as well as in DHIS2 dashboards.

_**Superuser**_ This user role is reserved to the BSSC in Belgrade and allows configuring settings and managing the DHIS2 instance and system.

The table below provides and overview of the settings configured for each of the five User roles:

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

#### 4.3.3 User group

The main purpose of user groups is facilitating configuration of "Sharing" settings (which determine viewing and editing rights) by groups rather than having to manage them at the level of hundreds of individual users.

The relation between User groups and the assigned User role is displayed in the table below:

<figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

The individual metadata viewing and editing access settings are configured as shown in the table below:

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

### 4.4 Maintenance app

The DHIS2 Maintenance app allows BSSC to configure and modify DHIS2 metadata which are necessary for running DHIS2 and PSM. All geographical conventions must follow the conventions of the institutional ICRC "Location Manager Application". In order to ensure consistency across digital applications used by the ICRC Health Unit, this metadata must also be aligned with conventions and policies used for the HeMAP (Health Monitoring and Analysis Platform) project.

Fields marked with "(\*)" are mandatory fields in DHIS2 and must be filled.

* Organisation unit = health care facility (Recipient Master Place Name)
* Organisation unit group = grouping by level of care (clinic, hospital etc.)
* Organisation unit level = hierarchy levels (regions, countries, FAL, health care facility).
* Category option = logistics data fields (stock on hand, stock distributed, Imprest Level)
* Category = monthly stock report (combination of Category options)
* Category combination = monthly stock report (identical with the Category)
* Data elements = stock items (health care products)
* Data set = stock item list (distinct for every health care facility)
* Predictor = computation for "copying" the Imprest Level to the next month
* Predictor group = grouping of all Predictors for facilitating scheduler user
* Scheduler app = automated routine for the Predictor Metadata requires configuration only when setting up the DHIS2 instance and whenever changing the master data such as adding or "inactivating" Organisation units, adding or removing items from the item catalogue. These configurations and settings are not changed frequently but need to be carefully and meticulously managed to ensure that the DHIS2 is always kept up to date.

In DHIS2 all metadata is automatically assigned unique IDs ("keys") which are not visible to field users but indispensable for the functioning of databases.

#### 4.4.1 Organisation unit

The term Organisation unit is used to denote the geographical hierarchy of health care facilities and structure them hierarchically. This application allows creating new and editing existing geographical entities. As the hierarchy of regions, countries and First Administrative Level is defined by institutional policies and does not change, the main objective of this application is adding new health care facilities.

When new health care facilities are added to the PSM project, their metadata (if available) is imported from the HeMAP database. All newly created health care facilities need to placed in the correct geographical hierarchy and be placed under the correct region, country and First Administrative Level. Within, they are sorted alphabetically.

The "Name" must correspond to the ICRC Location Manager Application and the "Short name" is identical.

The "Code" is unique for every health care facility and also available from the ICRC Location Manager Application. This code corresponds to the ICRC "Master Recipient Place code" which is essential for "linking" DHIS2 with JDE as well as Tableau data.

The "Opening date" indicates the date when the health care facility is added to the DHIS2 database. However, DHIS2 will not allow entering any data before this date. Therefore, if historic data is available, the "Opening date" must be correspond to the beginning of the period for which data is uploaded.

The "Closed date" is entered when support to a health care facility is terminated and no more new data is entered. This allows "deactivating" Organisation units for users but maintaining a complete record of all transactions and data. Any Organisation units which have been created in DHIS2 are never actually deleted.

The "Latitude" and "Longitude" are useful for mapping the location of health care facilities in Tableau.

The "Master Recipient Place Code" field was added for technical reasons as JDE cannot be integrated on the "Code" field and must always be identical with the "Code" field.

The other settings are not used. Example of the configuration of an Organisation unit:

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

#### 4.4.2 Organisation unit group

The "Organisation unit groups" allow grouping health care facilities according to their level of care and functions and the "Country" group is created for technical reasons.

* Clinic
* Country
* Health centre
* Hospital&#x20;

For this configuration only the "Name" is used and all other settings are left blank. Example of the configuration of an Organisation unit group:

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

#### 4.4.3 Organisation unit level

The Organisation unit levels allow to represent the geographical structure of health care facilities according to their First Administrative Level, country and ICRC region.

* Global = represents the "root directory" which encompasses all entities
* Region = corresponds to the geographical ICRC regions (Africa, Near and Middle East etc.)
* Country = international states
* First Administration Level = ICRC system of separation of countries
* Health care facility

<figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

#### 4.4.4 Hierarchy operations

The Hierarchy operations application represents the complete geographical structure of the Organisation units and allows changing the position of Organisation units in the Organisation unit hierarchy if they were not created at the correct hierarchical levels. Once created, the place in the hierarchy should never change.

Example of a part of the Organisation unit hierarchy:

<figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

#### 4.4.5 Category option

In DHIS2 the three logistics data fields (Imprest Level, Stock distributed and Stock on hand) are configured one-off as "Category option". Apart from the Name and the "Short name" no further settings are required:

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

However, the “Sharing settings” are configured to restrict the editing of the “Imprest Level” only to the “PSM basic mode – Imprest Level editor” User role while the “Stock on hand” and “Stock distributed” can be viewed and edited by storekeepers, storekeepers can also view the “Imprest Level” while “PSM readers” can only view data.

#### 4.4.6 Category

The three categories options "Imprest Level", "Stock distributed" and "Stock on hand" are combined into the category "Health facility - monthly stock report". The "Data dimension type" must be set to "Disaggregation", otherwise no further settings are required.

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

#### 4.4.7 Category combination

The "Category combination" allows to combine several "Categories" but as the PSM uses a single "Category", the "Category combination", also named "Health facility - monthly stock report" just replicates the "Category" with the need for any further settings.

<figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

#### 4.4.8 Data element

Data elements represent the items (health care products) for which logistics data is recorded and managed.

The item codes and item descriptions of the data elements must exactly match the item codes and item descriptions in JDE. Since DHIS2 provides only a single field, the item code and description are concatenated and separated by a hyphen with a space before and after the hyphen. For example:

DORAPARA5T - PARACETAMOL (acetaminophen), 500 mg, tab.&#x20;

The "Short name" is note used in PSM but since it is a mandatory field in DHIS2, many item descriptions exceed the maximum of 50 allowed characters and truncated item descriptions leads to non-unique duplicates, this field also contains the item code.

The "Domain type" must be set to "Aggregate", the "Value type" to "Positive or Zero Integer" and the "Aggregation type" to "None". The field "Store zero data values" must be ticked in order to allow storing the value of zero and the "Category combination" must be set to "Health facility

* monthly stock report".

Data elements which have been created and used cannot be deleted from the database anymore as the historic data needs to be maintained. Data elements which are no longer needed, for example if they have been set to "Obsolete" by logistics have to first to be removed by the BSSC manually from any Data Set where they were included. Then the term "Obsolete" is added at the beginning of the name to prevent future inadvertent use.

#### 4.4.9 Data set

The Stock item list is set as a Data set separately for each health care facility and is used for recording stock data at health care facilities. Data sets, which are collections of Data elements are a precondition for data entry in DHIS2. Every Data set has to be assigned to the Organisation unit where it is in use. In principle, different health care facilities could use the same Data set but it is unlikely that two Stock item lists of different health care facilities would be identical except perhaps for specific programmes using a small number of items such as for a specific primary health care programme. Only Data sets which have been assigned to Organisation units will appear under the respective name of the Organisation unit and only those can be used for recording and managing data. The Name of the Data set first indicates the name of the health care facility followed by "Stock item list", for example:

Akobo Hospital - Stock item list

The "Short name" is identical with the "Name" or abridged if the name exceeds 50 characters.

"Expiry days" denotes the number of days after the end of the monthly reporting period until which data for that reporting period can still be entered. In order to allow completion of physical stock counts in the days following the end of the month in case the end of the month falls on a day off, the default setting is 15 (days).

"Open future periods for data entry" is set to 1 by default which allows to record data any time during the month of the current reporting period. For example, stock data for January can be entered and edited throughout the month from the first to the last day of January.

"Days after period to qualify for timely submission" is also set to 15 days for the sake of consistency meaning that reports completed within the first five days of the following month are considered having been submitted on-time.

The "Period type" is set to "Monthly" by default as all health care facilities are requested to submit reports every month.

The "Category combination" is a mandatory field and must be set to "None". Under "Data elements", upon request of the respective ICRC Health programme manager, the BSSC Belgrade will add or remove all "Data elements" which are included in the respective Stock item list of the health care facility.

Finally, every Data set must be assigned to one Organisation (and exceptionally to more than one is explained earlier).

All other settings are left blank.

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

#### 4.4.10 Predictor and Predictor group

The sole purpose of the predictor is carrying the Imprest Level from the previous month forward to the current month. During recording or editing stock data, storekeepers want to be able to view the Imprest Level in order to determine any inconsistency which they can then discuss with the ICRC Health programme manager. On the other hand, ICRC Health programme managers should not have to have to manually re-enter the Imprest Levels from the previous month into the current month every month.

As soon as the predictor is run (by the Scheduler app during the early morning of the first day of every month) it will "copy" the value from the previous month to the next month. This value can then be edited by the ICRC Health programme manager at any time. If the value is not changed, the same value is "copied" to the next monthly period and if the value is changed the changed value is "copied" to the next monthly period until it is (eventually) changed again.

A separate predictor with a distinct name is required for every Data element.

The predictor is "written" the "Imprest Level" field ("Output category option combo) of the Data element with the same name once a month and the "Period type" is therefore "Monthly".

By default, the "Imprest level" field is blank and a blank field will be copied forward until a first value is entered.

The "Generator" simply "averages" the value from one previous monthly reporting period ("Sequential sample count = 1) where the calculation uses the Data element ID rather than the actual name. For example:

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

It is critical that the "Organisation unit levels" is set to "Health care facility" to ensure that the "average" is created for each health care facility separately and not overaged over any other Hierarchical level.

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

The "Predictor group" allows applying a single, pre-set "Scheduler" once a month rather than having to either run each "Predictor" manually every month or to have to create a separate "Scheduler" for every "Predictor".

<figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

#### 4.4.11 Scheduler app

This application allows configuring and managing DHIS2 background jobs which are executed automatically according to pre-set schedule and configuration. The single scheduled job is running the calculation for each of the Predictors in at 0: 05 a.m. on the first day of every month.

The "Select frequency" is set to "Custom" and the "Cron expression" is set to "0 0 5 1 \*\*" (zero seconds, zero minutes, 00:05:00 a.m., first day of every month, any month and any year).

The "Relative start" is set to "-1" (the previous day), the "Relative end" to "1" (the next day) and the "Imprest Level - carried forward from previous month" is selected under "Predictor groups".

The time is intentionally set to 5:00 a.m. (time in Switzerland) and not 0:00 a.m. as this time applies to all PSM users regardless of what time zone they are working in. Except for those working in the Swiss time zone, there is a risk that entered Imprest Level values will be "overwritten" by the previous value (and therefore be ignored) or will not be rolled forward to the next month.

Time differences with Switzerland also depend on day light saving time changes but the two relevant "extreme" cases are -7 hours in Colombia and +6 hours in the Philippines.

The risk for time zones which are "behind" Geneva is that if an Imprest Level is edited within up to 7 hours before the end of the month, the Imprest Level will be changed in the current month but will not be rolled forward as the Predictor has already run in Geneva before the entry was made in Colombia.

The risk for time zones which are "ahead" of Geneva is that if an Imprest Level is edited within up to 6 hours of the current month, the value will be "overwritten" by the value of the previous month by the Scheduler app and therefore be "erased".

To avoid errors, ICRC programme managers should not edit any Imprest Levels 12 hours before and after the end of the month.

#### 4.4.12 Summary of metadata configuration

The table below summarizes the main metadata configurations and settings:

<figure><img src="../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

### 4.5 Android Settings app

The Android Settings app allows system administrators to control various settings of the DHIS2 Capture app (mobile device application).

<figure><img src="../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

### 4.6 Other DHIS2 user apps

In DHIS2, the various applications are called "apps" although they are used on the web portal and are not available as apps on mobile devices.

The following applications are (depending on the assigned user roles) available to all ICRC users on the web portal and are accessed by clicking on the nine-dot icon on the upper right of the screen:

* Data Entry app
* Dashboard app
* Browser Cache Cleaner app
* Menu management app

<figure><img src="../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

In practice, only the "Data Entry app" and the "Dashboard app" are needed regularly.

#### 4.6.1 Data Entry app

The "Data Entry" app allows selecting a health care facility, entering and editing logistics data (Imprest Level, Stock distributed and Stock on hand) in the Stock item lists for the selected reporting period.

#### 4.6.2 Dashboard app

The "Dashboard" app allows users to view preconfigured reports and analytics. As the institutional business analytics tool (Tableau) will be used for analysis, the dashboard will be limited to a simple month by month overview of data for storekeepers and other users in the field.

#### 4.6.3 Browser Cache Cleaner app

The "Browser Cache Cleaner" app allows clearing data stored on the computer locally. Usually this is only required if configuration changes are made which may not appear on the user interface until the computer cache is cleared.

In some cases, this app will not be effective (for example changing the language of the month names). In this case the cache cleaner of the browser in use must be used.

_**For Chrome browser the shortcut CTRL + SHIFT + DEL and selecting “Cached images and files” will allow a “deep cleaning” of the browser cache.**_

#### 4.6.4 Menu Management app

The "Menu Management" app allows uses to customize the layout of the apps drop-down menu and change the position and order of apps (except for the "Menu Management" app which is always displayed as the last app at the bottom). However, given the small number of apps in use for the PSM, this feature is not really required.

#### 4.6.5 Data Administration app

The "Data Administration" is not accessible to field users but used by the BSSC Belgrade for example for running the "Analytics tables management" in case dashboard calculations need to be updated and for various system maintenance.

#### 4.6.6 Data Visualizer app

The "Data Visualizer" app is needed for creating new and editing existing visualizations which are then accessible to field users in the dashboard app.

#### 4.6.7 Unavailable apps

In total DHIS2 offers 28 different apps which can be made available to users if needed. In order to keep the user interface as simple and "clean" as possible, apps which are not in use for the PSM project are "hidden" from field users.

### 4.7 User profile

The user account preferences are accessed by clicking the blue disc in the upper right corner indicating the user initials which opens the following drop-down menu:

<figure><img src="../.gitbook/assets/image (180).png" alt=""><figcaption></figcaption></figure>

Selecting "Edit profile", or any other of the options" takes the user to the "DHIS2 - User profile" page.

**Edit user profile**

This menu gives access to a number of user settings which are not in use and are only to be managed by the BSSC Belgrade.

**Edit user settings** "Edit user settings" allows users to change the default "Interface language" and "Database language" while the various other settings are not in use. The default language is English but the language used in the country of the respective user will be set as default for that user when the DHIS2 profile is established.

Users can change both the “Interface language” and “Database language” separately but those two languages should always be identical, whatever language is selected.

Interface language: this setting controls the language of all native DHIS2 “apps”, user interfaces, drop-down and pop-up windows etc. The translations are natively available in DHIS2, are part of the DHIS2 source code and cannot be corrected by the ICRC.

_**Note that while changes in principle take effect immediately, in practice often the “Browser Cache Cleaner” as well as a browser “refresh” are needed before the changed language settings are displayed.**_

Database language: this controls the language of all “metadata” which is specific to the ICRC PSM configuration such as the headers for “Imprest Level”, “Stock on hand” as well as translations of all item descriptions. These translations are managed and controlled by the ICRC system administrator and can in principle be changed.

**Edit account settings** These options are not in use as the authentication is controlled by the ICRC SSO (Single Sign On).

**View full profile** This application allows users to view their name, email, assigned user roles and the Organisation Units to which they have access.

**About DHIS2** This application provides technical information such as the version of DHIS2 or the server time.

### 4.8 General DHIS2 settings

The settings below list some DHIS2 behaviour which is native to the application and cannot be configured:

* In tables, all text fields are left aligned
* In tables, all value fields are right aligned
* All dates are displayed in the dd/mm/yyyy (day/month/year) format
* All times are displayed in the hh:mm (hour/minute) format using 24 hour format
* Except for analytics, no decimals are used for values (unnecessary, prone to errors, prone to confusion with thousand separators and decreases legibility)
* All numbers greater than 999 are displayed with a comma (",") as thousand separator (for example 1,200).
* All text fields (including the item code field) are alphanumeric (English alphabet A to Z and numbers 0-9, no other characters are needed).
* At all times, all items are sorted alphabetically by item names and this sorting cannot be changed. As the item codes and item descriptions are concatenated, in practice all items are sorted by item codes.

## 5 DISTRICT HEALTH INFORMATION SOFTWARE 2 (DHIS2) WEB PORTAL

This chapter details who ICRC staff can access the DHIS2 web portal, manage the Imprest Levels for each health care facility and view PSM data on an ICRC computer.

#### 5.1 DHIS2 web portal user access

The DHIS2 web portal can only be accessed on ICRC desktop computers or ICRC notebook computers connected to an ICRC network at an ICRC facility (or through remote access) and can only be accessed by ICRC staff and only when the computer is online.

After logging in to the ICRC computer with the usual authentication (same as for accessing the general ICRC ICT environment with Outlook, the ICRC Intranet site etc.), the ICRC DHIS2 server instance can be accessed with any web browser and does not require any installation on the computer itself.

Before accessing the DHIS2 web portal for the first time, new users need to request a dedicated DHIS2 user profile from the ICT Service Desk which will have to provide a specific username, password and provide access to the required country and health care facility (or facilities).

Microsoft Edge is the recommended browser and Chrome can be used as a backup as DHIS2 was tested in this environment. Other browsers (such as Internet Explorer or Firefox should not be used).

For authentication and login only the ICRC login is needed (users do not have a specific DHIS2 username and password).

<table><thead><tr><th width="73">No </th><th>Step / Results</th></tr></thead><tbody><tr><td>1 </td><td>User switches on the ICRC personal computers and authenticates with the usual personal ICRC username and password. </td></tr><tr><td>2 </td><td>The ICRC home screen appears. </td></tr><tr><td>3 </td><td>The user opens the Microsoft Edge web or Internet Explorer browser (recommended) and selects the DHIS2 URL from the bookmarks menu. For accessing DHIS2 for the first time the following URL can be used: https://dhis2psm.ext.icrc.org/dhis </td></tr><tr><td>4 </td><td><p>The DHIS2 login screen appears. </p><p><img src="../.gitbook/assets/image (45).png" alt=""></p></td></tr><tr><td>5 </td><td><p>The user selects “Login with ICRC account”. </p><p><img src="../.gitbook/assets/image (46).png" alt="" data-size="original"></p></td></tr><tr><td>6 </td><td>The DHIS2 home screen (Dashboard screen) opens. <br><img src="../.gitbook/assets/image (47).png" alt=""></td></tr><tr><td>7 </td><td><p>The user selects the nine-dot menu in the far upper right corner for opening the “apps” menu. </p><p><img src="../.gitbook/assets/image (48).png" alt="" data-size="original"></p></td></tr><tr><td>8 </td><td><p>The “app” menu opens. The available apps will differ according to the user profile assigned to the respective user. </p><p> <img src="../.gitbook/assets/image (220).png" alt=""></p></td></tr><tr><td>9 </td><td>The user selects the required “app” such as “Data Entry” for accessing the required application. After completing work, the user clicks on the “Profile” icon, the blue disc with the user initials. </td></tr><tr><td>10 </td><td>The user profile menu opens. <br><img src="../.gitbook/assets/image (50).png" alt=""></td></tr><tr><td>11 </td><td>The user Selects “Logout” from the menu. </td></tr><tr><td>12 </td><td><p>The DHIS2 login screen reverts. </p><p> <img src="../.gitbook/assets/image (51).png" alt=""></p></td></tr></tbody></table>

### 5.2 Imprest Level management

This application allows viewing the history of Data Sets with the Imprest level and the Stock on Hand as well as editing the Imprest Level of the current month.

For every health care facility, at least one user should have the authority to change the Imprest Levels and a second person should be available for replacement in case of her/his absence.

The Imprest Level for all items has to be entered whenever a new health care facility starts using the PSM tool for stock management. By definition, the Imprest Level cannot be zero as this would stop any replenishment orders. But if no regular stock replenishment is required, then the respective item should be immediately removed from the stock item list all together.

At the end of every month, the Imprest Level of that month will be “locked” for editing and all the most recent values from the end of the month will be automatically brought forward by the system (“copied”) to the current month in the early morning of the first day of the month. This system ensures that only the current Imprest Levels can be edited while the Imprest Levels of past months (which have already been used for previous replenishment calculations) are locked for editing and cannot be changed retrospectively (and there should also be no need for this).

During the current month, Health programme managers can edit and change the Imprest Level whenever and as often as needed. If the Imprest Level is not changed, then the value brought forward from the previous month is again copied to the next month. If the Imprest Level is changed any time during the current month, that value is maintained for the current month and also automatically brought forward to the next month.

Imprest Levels should be changed about every six months, but that system does not restrict how often they can be changed. Imprest Levels can also be changed for only one, several or all items as needed without any restrictions by the system.

In principle other stock data (stock on hand and stock issues) could be managed through the same web portal but this should only be necessary in exceptional cases.

_**It is critical to always enter an Imprest Level for all stock items and never leave any field blank as the IRIS application will only synchronize data from reporting periods with both Stock on hand and stock distributed and will not synchronize at all if, for example, no Imprest Level or imprest level entered is zero.**_

<table data-header-hidden><thead><tr><th width="80"></th><th></th></tr></thead><tbody><tr><td>No </td><td>Step / Results </td></tr><tr><td>1 </td><td>User logs into the DHIS2 web portal (see DHIS2 web portal user access guidance). </td></tr><tr><td>2 </td><td><p>The DHIS2 web portal home screen (dashboard) appears. </p><p> <img src="../.gitbook/assets/image (53).png" alt=""></p></td></tr><tr><td>3 </td><td><p>The user selects the nine-dot menu in the far upper right corner for opening the “apps”  </p><p>menu.<br> <img src="../.gitbook/assets/image (181).png" alt=""></p></td></tr><tr><td>4 </td><td><p>The “app” menu opens. The available apps will differ according to the user profile assigned to the respective user. </p><p> <img src="../.gitbook/assets/image (221).png" alt=""></p></td></tr><tr><td>5 </td><td>User selects the "Data Entry" app </td></tr><tr><td>6 </td><td><p>The "Data Entry" window opens. </p><p> <img src="../.gitbook/assets/image (56).png" alt=""></p></td></tr><tr><td>7 </td><td><p>On the left side window, user expands the “Organisation Unit” levels by clicking on the </p><p>“+” icons. </p></td></tr><tr><td>8 </td><td><p>The select “Organisation Unit” expands and the “+” icons change to “-“ icons. </p><p>Chapter 5.2 Imprest Level management <br><img src="../.gitbook/assets/image (182).png" alt=""></p></td></tr><tr><td>11 </td><td><p>User navigates down the “Organisation Unit” tree and clicks on the name of the health </p><p>care facility for which the Imprest Level is of interest. </p></td></tr><tr><td>12 </td><td>The text colour of the selected health care facility (“Organisation Unit”) changes to orange and bold and the same name is displayed in the “Organisation Unit” field on the right. <br><img src="../.gitbook/assets/image (183).png" alt=""></td></tr><tr><td>13 </td><td>From the “Data Set” drop-down menu, user selects the stock item list required and from the “Period” drop-down menu the period for which data needs to be edited. Note that it is not possible to enter or edit data from any previous month later than the fifth day of the current month. </td></tr><tr><td>14 </td><td><p>The complete “Data Entry” form of the selected health care facility and for the selected time period is displayed. Note that the “Imprest Level” is automatically brought forward from the previous month. </p><p> <img src="../.gitbook/assets/image (59).png" alt=""></p></td></tr><tr><td>15 </td><td>User edits the Imprest Levels as required. Note that all values are saved as soon as the cursor is moved to another field and there is no “save” button and no need for saving any entries. </td></tr><tr><td>16 </td><td><p>The respective changes appear in the respective data field. </p><p> <img src="../.gitbook/assets/image (60).png" alt=""></p></td></tr><tr><td>17 </td><td>After completing all editing, the user opens clicks on the profile icon with the user initials in the far upper right corner. </td></tr><tr><td>18 </td><td>A drop down menu opens. <br><img src="../.gitbook/assets/image (185).png" alt=""></td></tr><tr><td>19 </td><td>User selects “Log out”. </td></tr><tr><td>20 </td><td><p>The DHIS2 login screen reverts. </p><p> <img src="../.gitbook/assets/image (62).png" alt=""></p></td></tr></tbody></table>

The stock item list as displayed in this application also serves as the main (and only) reference for managing stock item lists for each of the health care facilities. Health program managers use this list as a reference for the daily work as well as for asking the ICT Service Desk for any changes by adding or removing items.

The automatic “rolling forward” of the Imprest Levels from the previous month to the next month is automatically scheduled on the DHIS2 server at 00:05 Geneva time (Switzerland) of the first day of every month. As all DHIS2 users use the same server instance in Geneva, the time zone of the users will differ from the time zone in Geneva in many cases.

All users must avoid editing any Imprest Levels during the 24 hours between 12:00 o’clock Geneva time on the last day of the month and 12:00 o’clock Geneva time of the first day of the month. In addition, users should always check that they are editing the latest value of the Imprest Level in the system. For example, when editing Imprest Levels on the last day of the month, to check whether the Imprest Level was already automatically carried forward to July.

**As an example, to explain the potential problem which is very unlikely but possible.**

Assume July 1st at 00:05 Geneva time all Imprest Levels from June are "copied" to July but in Bogota it is only 17:05. Later, for example at 19:00, the ICRC program manager updates the Imprest Level for June (after the previous value has already been "copied" to July), then that value would be updated for June, but the previous value would have already been “brought forward” to July and therefore the previous value is “copied” and the Imprest Level is not updated for future months. Such an error could easily be corrected throughout the month of July but the corrected Imprest Levels would have to be re-enter a second time.

The second risk is in "positive" time zones: if the scheduler runs at 00:05 Geneva time, and an ICRC program manager in the Philippines changes the Imprest Level on July first at 05:00 local time, then that value will be overwritten at 06:00 local by the (outdated value) from June.

Such an error could easily be corrected throughout the month of July, but the corrected Imprest Levels would have to be re-enter a second time.

### 5.3 Business analytics management

While Tableau (Business Analytics application) is the main and primary tool for all reporting, dashboards and analysis, it is only accessible to ICRC staff on ICRC computers and therefore not accessible to non-ICRC staff. Therefore, a single, very simple, standardized dashboard is configured in DHIS2 itself which is accessible to all users (including non-ICRC staff) and accessible on mobile devices through any web browser (not through the Capture app) with the same user access as for the Capture app but only when the mobile device is on-line.

However, Health program managers may occasionally want to adapt this standard dashboard, which automatically shows data on for the health care facility to which the respective user logging in has access to. For example, decreasing or increasing the number of months for which data is displayed. The easiest way to build or adapt an existing dashboard is by opening the default Pivot table and select “Save as” for saving it under another name.

In DHIS2 there are two steps for building and sharing reports and other visualizations. First building a table or a chart using the “Data Visualizer” (for any data from “aggregate” Data Entry forms) and then adding the table or chart to a dashboard in a second step.

<table data-header-hidden><thead><tr><th width="73"></th><th></th></tr></thead><tbody><tr><td>No </td><td>Step / Results </td></tr><tr><td>1 </td><td>User logs into the DHIS2 web portal (see DHIS2 web portal user access use case). </td></tr><tr><td>2 </td><td><p>The DHIS2 web portal home screen appears (the exact appearance depends on the dashboards which have already been created). </p><p> <img src="../.gitbook/assets/image (63).png" alt=""></p></td></tr><tr><td>3 </td><td>User selects the nine-dot app icon. </td></tr><tr><td>4 </td><td>A drop-down window with all apps available to the user appears. <br><img src="../.gitbook/assets/image (222).png" alt=""></td></tr><tr><td>5 </td><td>User selects the "Data Visualizer" app. </td></tr><tr><td>6 </td><td><p>The "Data Visualizer” window opens. Not that by default, no visualization is displayed. </p><p><img src="../.gitbook/assets/image (65).png" alt="" data-size="original"></p></td></tr><tr><td>7 </td><td>User selects "File" and “Open”. </td></tr><tr><td>8 </td><td>A pop-up window with available visualizations opens. <br><img src="../.gitbook/assets/image (187).png" alt=""></td></tr><tr><td>9 </td><td><p>User selects the default visualization (or any other visualization s/he may want to modify). </p><p> </p><p>Alternatively, the data can be selected per health facility to monitor the status across different time periods </p><p><img src="../.gitbook/assets/image (67).png" alt="" data-size="original"></p></td></tr><tr><td>10 </td><td>The selected visualization opens. <br><img src="../.gitbook/assets/image (68).png" alt=""></td></tr><tr><td>11 </td><td>Users selects "File”, “Save as” and saves the visualization under another name (to avoid the existing one from being modified). </td></tr><tr><td>12 </td><td><p>The name of the visualization is changed and the visualization is saved under its new name. </p><p><img src="../.gitbook/assets/image (69).png" alt=""></p></td></tr><tr><td>13 </td><td><p>The new name of the visualization now appears at the top of the visualization and the </p><p>user selects the parameter which she wants to modify, for example the “Period”. </p></td></tr><tr><td>14 </td><td><p>A pop-up window for the respective parameter opens. </p><p><img src="../.gitbook/assets/image (70).png" alt=""></p></td></tr><tr><td>15 </td><td>User modifies the parameter as required, for example changing the “Selected Periods” to “Last 6 months” and selects “Update”. </td></tr><tr><td>16 </td><td>The modified visualization is displayed. </td></tr><tr><td>17 </td><td>Users selects “File” and “Save” to confirm and complete the change. </td></tr><tr><td>18 </td><td><p>The changes are now saved. </p><p><img src="../.gitbook/assets/image (71).png" alt=""></p></td></tr><tr><td>19 </td><td>Users returns to the home screen (dashboard) by selecting “DHIS 2 – Dashboard” in the upper left corner or selecting the “Dashboard app” from the drop down menu. </td></tr><tr><td>20 </td><td>The dashboard window reverts. <br><img src="../.gitbook/assets/image (188).png" alt=""></td></tr><tr><td>21 </td><td>User selects the green “+” icon in the upper left corner of the window. </td></tr><tr><td>22 </td><td><p>A window for editing dashboards opens. </p><p><img src="../.gitbook/assets/image (73).png" alt=""></p></td></tr><tr><td>23 </td><td>User enters a name under “Dashboard title” and clicks in the “Search for times to add to this dashboard”. </td></tr><tr><td>24 </td><td><p>The dashboard name is changed and a pop-up window with available dashboard items appears. </p><p> </p><p><img src="../.gitbook/assets/image (74).png" alt=""></p></td></tr><tr><td>25 </td><td>User selects the required visualization from the pop-up window and “Save changes”. </td></tr><tr><td>26 </td><td><p>The visualization is added to the dashboard window and the dashboard is changed. </p><p><img src="../.gitbook/assets/image (75).png" alt=""></p></td></tr><tr><td>27 </td><td>User continues editing the dashboard, for example by changing the size of the table by dragging the handle in the lower left corner and “Save changes”. </td></tr><tr><td>28 </td><td>The dashboard is saved and the new dashboard is displayed on the home page which reverts. <br><img src="../.gitbook/assets/image (189).png" alt=""></td></tr><tr><td>29 </td><td>User selects the “Share” button. </td></tr><tr><td>30 </td><td><p>A pop-up window with “Sharing settings” opens. </p><p> <img src="../.gitbook/assets/image (77).png" alt=""></p></td></tr><tr><td>31 </td><td><p>User adds the user groups or individuals who should have read access by selecting them </p><p>from the “Add users and user groups” window. </p></td></tr><tr><td>32 </td><td>The user access is added to the dashboard. <br><img src="../.gitbook/assets/image (78).png" alt=""></td></tr><tr><td>33 </td><td>User selects “Close”. </td></tr><tr><td>34 </td><td><p>The home screen with the new dashboard reverts. </p><p> <img src="../.gitbook/assets/image (79).png" alt=""></p></td></tr><tr><td>35 </td><td>The user logs out of DHIS2. </td></tr><tr><td>36 </td><td>The DHIS2 login screen reverts. <br><img src="../.gitbook/assets/image (80).png" alt=""></td></tr></tbody></table>

## 6 DISTRICT HEALTH INFORMATION SOFTWARE 2 (DHIS2) CAPTURE APP

This chapter describes the installation of the DHIS2 mobile device application (“app”) which is called “Capture app”, user access as and the use of the “basic mode” as well as the “Advanced mode”.

### 6.1 DHIS2 mobile device application (APK) installation

Before using the application for the very first time, as well as in case of any error in the mobile device, the mobile device application must be (re)installed on every mobile device individually by the user. The same procedure applies to installing any future updates of the mobile device application. In case any other version of DHIS2 is already installed, please select the app(s) and uninstall them as it is not possible to run different versions of the DHIS2 app in parallel.

Depending on whether the “Basic mode” or the “Advanced mode” is used at a specific facility either the “Basic mode” or the “Advanced mode” apk-file need to be installed but both applications must never be installed on the same device (as stock must be reported in one or the other mode but never using both modes at the same time) and if more than one mobile device is used at the same health care facilities, all of them must use the same mobile application (either “Basic mode” or “Advanced mode”).

_**Any healthcare facility must either use only the “Basic mode” or only the “Advanced mode” on all mobile devices and by all staff of that healthcare facility.**_

The installation as well as accessing the application for the first time will require connection to the Internet throughout the process. However, if the mobile device cannot connect to the ICRC \[Health Wiki / ICT app store], the apk-file can be simply copied to a USB-key and then copied from the USB-key to the mobile device.

The installation requires several steps but is not difficult and as easy as downloading any exe- file and clicking for auto-installation.

Note that the DHIS2 Capture app is an open source application which is available for free on Google Play Store. However, this application cannot be used for the PSM project as the application has been modified for the ICRC, among others for including more stringent authentication requirements.

_**Do not download and install the native DHIS2 Capture App from Google Play Store as it will not work for connecting to the ICRC DHIS2 server instance!**_

Instead, only the mobile application distributed by the ICRC with an APK (Android application package) as an apk-file which contains the entire software package _**either (!) for the “Basic mode” or for the “Advanced mode”**_ needs to be installed. No other applications or tools need to be installed except for this one apk-file. If the mobile device cannot be connected to the ICRC ICT environment, the apk-file can be transformed from a personal computer (desktop or notebook computer) to the mobile device with a USB data cable or a USB-key.

_**At any time, only install either the apk-file for the “Basic mode” or for the “Advanced mode” and make sure to “uninstall” either before installing the other. The “Basic mode” and the “Advanced mode” cannot but installed or used on the same device at the same time and must never be used together.**_

<table data-header-hidden><thead><tr><th width="74"></th><th></th></tr></thead><tbody><tr><td>1 </td><td><p>Open the ICRC [Health Wiki / ICT app store], search for the PSM application and download either: </p><ul><li>“Basic mode”: dhis2-v2.4.3-dhis-debug_uat_v2.apk </li></ul><ul><li>“Advanced mode”: psm-uat-v1.0.1-debug.apk </li></ul><p>to the “Downloads” folder (or any other) folder of the ICRC personal computer. </p></td></tr><tr><td>2 </td><td><p>The apk-file now appears in the “Downloads” (or another) folder. </p><p><img src="../.gitbook/assets/image (81).png" alt="" data-size="original"></p></td></tr><tr><td>3 </td><td>Switches on the mobile device and ensure the battery is sufficiently charged. </td></tr><tr><td>4 </td><td><p>The home screen of the mobile device appears. Note that the exact contents and layout of the home screen depends on the mobile device in use and may differ from the screenshot below. </p><p><img src="../.gitbook/assets/image (82).png" alt="" data-size="original"></p></td></tr><tr><td>5 </td><td>Connect the mobile device to the ICRC computer with a USB-cable which allows data transfer (some USB-cables allow only charging). </td></tr><tr><td>6 </td><td>A pop-up menu appears requesting permission to access the data. <br><img src="../.gitbook/assets/image (83).png" alt=""></td></tr><tr><td>7 </td><td>Select the option “Allow”. </td></tr><tr><td>8 </td><td><p>The pop-up window closes on the mobile device and on the ICRC computer the folder </p><p>“Galaxy Tab S6 Lite” is displayed in the Windows Explorer. </p><p><img src="../.gitbook/assets/image (84).png" alt="" data-size="original"></p></td></tr><tr><td>9 </td><td>Open the sub-directory “Downloads” (or other sub-directory) on the ICRC computer where the apk-file was downloaded and copy/paste the apk-file to the “Download” folder of the mobile device. </td></tr><tr><td>10 </td><td><p>The apk-file now appears in the “Download” folder on the mobile device and is now </p><p>ready for installation <br><img src="../.gitbook/assets/image (85).png" alt=""></p></td></tr><tr><td>11 </td><td><p>On the mobile device single tap the “My Files” icon and navigate to the “Download” </p><p>folder of the mobile device. </p></td></tr><tr><td>12 </td><td><p>The “Downloads” directory in “My Files” opens and displays the copy/pasted apk-file. </p><p><img src="../.gitbook/assets/image (86).png" alt="" data-size="original"></p></td></tr><tr><td>13 </td><td>Double tap the icon or file description in the “Downloads” folder. </td></tr><tr><td>14 </td><td>A pop-up window appears requesting permission to install the app. <br><img src="../.gitbook/assets/image (87).png" alt=""></td></tr><tr><td>15 </td><td>Single-tap “Install”. </td></tr><tr><td>16 </td><td><p>The app will automatically start installing and display a notification when the installation is completed. </p><p><img src="../.gitbook/assets/image (88).png" alt=""><br><br><img src="../.gitbook/assets/image (89).png" alt=""></p></td></tr><tr><td>17 </td><td><p>Select “Done”, close the window and on the main window navigate to the screen with </p><p>all the installed apps by “pulling” the main window upwards. </p></td></tr><tr><td>18 </td><td><p>In addition to already installed apps the “DHIS2 Training” app now appears. </p><p><img src="../.gitbook/assets/image (90).png" alt="" data-size="original"></p></td></tr><tr><td>19 </td><td>“Drag and drop” the “Dhis2 Training” app to the home screen. </td></tr><tr><td>20 </td><td>The Dhis2 Training app is now installed and available for accessing on the home screen of the mobile device and ready to use. <br><img src="../.gitbook/assets/image (91).png" alt=""></td></tr></tbody></table>

### 6.2 Stock data entry and editing - Basic mode

The entry of stock data is done during the (monthly) physical stock count at the end of every month while corrections or updates (such as in case shortages or stockouts occur during the month) for individual items can be made at any time.

Any user will have access only to the health care facilities assigned to them by ICT support and not be able to view or edit data in other health care facilities. In nearly all cases this will be a single health care facility but in some rare cases, supervisors may have access to several health care facilities they are assisting.

During the monthly physical stock count, storekeepers enter the stock on hand and total monthly demand for all stock items while the Imprest Level column is only displayed for information but not editable by storekeepers.

In order to enter or edit any data, users need to first start the mobile device, open the PSM mobile app and authenticate themselves.

<table data-header-hidden><thead><tr><th width="88"></th><th></th></tr></thead><tbody><tr><td>No </td><td>Step / Results </td></tr><tr><td>1 </td><td>User opens the PSM app and authenticates her/himself. </td></tr><tr><td>2 </td><td><p>The home screen opens and a list of only those health care facilities to which the respective user has been granted access appears. </p><p><img src="../.gitbook/assets/image (92).png" alt=""></p></td></tr><tr><td>3 </td><td>User single-tapps the health care facility name (“Organisation Unit”) for which data should be entered or edited. Note that the selected health care facility name is displayed at the top of the screen on all screens. </td></tr><tr><td>4 </td><td><p>If no stock data has been recorded yet, an empty window will appear or otherwise a list of monthly records for which data is available will appear (provided the data has been synchronized with the mobile device). </p><p><img src="../.gitbook/assets/image (93).png" alt="" data-size="original"></p></td></tr><tr><td>5 </td><td>The storekeeper either selects one of the existing records by single-tapping on the respective entry or single-tapps the blue “+” icon for creating a new monthly record. </td></tr><tr><td>6 </td><td><p>An application window indicating the health care facility (Organisation Unit) opens. </p><p><img src="../.gitbook/assets/image (94).png" alt="" data-size="original"></p></td></tr><tr><td>7 </td><td>User single-tapps the “Report period” caption. </td></tr><tr><td>8 </td><td>A pop-up window with monthly reporting periods opens with the current month displayed at the top. <br><img src="../.gitbook/assets/image (95).png" alt=""></td></tr><tr><td>9 </td><td>User single-tapps the required monthly reporting period. But note that while any reporting period can be selected, entering data into previous reporting periods is restricted. Data can only be entered or edited in the current month or up to five days after the last day of the previous month but for no periods two months or longer back. In most cases, storekeepers will select the current month. </td></tr><tr><td>10 </td><td><p>The pop-up window closes, the selected month and year are displayed in the “Report period” which can still be corrected by single-tapping and changing the selection and the “NEXT” button appears at the bottom right of the screen. </p><p><img src="../.gitbook/assets/image (96).png" alt="" data-size="original"></p></td></tr><tr><td>11 </td><td>User confirms the selections by single-tapping the “NEXT” button. </td></tr><tr><td>12 </td><td>The monthly stock report record of the selected month opens. Note that the “Imprest Level” column is always greyed out for storekeepers which indicates that the data can be viewed but cannot be edited. Also note that all three columns are greyed out if the record from the previous month is opened after the 5th day of the month or any period of more than one month in the past is selected. <br><img src="../.gitbook/assets/image (97).png" alt=""></td></tr><tr><td>13 </td><td><p>User single-tapps in the first empty field (intersection of the first fow of items and the </p><p>column “Stock distributed”). </p></td></tr><tr><td>14 </td><td><p>A pop-up window with a number pad opens (whenever any field is tapped). Note that the background colour of the corresponding column and row change from dark grey to blue and the selected field is marked by a blue field around it. </p><p><img src="../.gitbook/assets/image (98).png" alt=""></p></td></tr><tr><td>15 </td><td>User types the total distribution quantity in the field. </td></tr><tr><td>16 </td><td>The entered quantity is displayed in the field while the number pad remains opened. <br><img src="../.gitbook/assets/image (99).png" alt=""></td></tr><tr><td>17 </td><td>User either single-tapps “Next” for moving the column on the right (or the left column in the next row if entering a value in the right column). Note that in DHIS2 there is no “Save” button and all entries are instantly saved on the mobile device. </td></tr><tr><td>18 </td><td><p>The adjacent field is highlighted with the cursor blinking in the next field and a pop-up window indicating “Saved” appears briefly indicating that the just entered value is now saved on the mobile device.23 </p><p><img src="../.gitbook/assets/image (100).png" alt="" data-size="original"></p></td></tr><tr><td>19 </td><td>User continues entering data into the remaining fields. Note that the user can scroll up and down the stock item list as needed and any of the fields can be selected for entering new data or editing previous entries until all data fields are filled. Once completed, the user selects the blue disc icon for closing the monthly reporting form. <br><img src="../.gitbook/assets/image (101).png" alt=""></td></tr><tr><td>20 </td><td><p>A pop-up window opens allowing the user to either select “NO” for reverting and continuing editing or “YES” for completing the data entry. </p><p><img src="../.gitbook/assets/image (102).png" alt="" data-size="original"></p></td></tr><tr><td>21 </td><td><p>User selects “YES” (or if required “NO”). Note that if the monthly reporting form is closed </p><p>it can be re-opened any time during the current month can remains fully editable. </p></td></tr><tr><td>22 </td><td>The list of monthly reporting period reverts. <br><img src="../.gitbook/assets/image (103).png" alt=""></td></tr><tr><td>23 </td><td>The user can either continue editing existing or creating a new monthly report or revert to the home screen by selecting the back arrow at the top of screen. </td></tr><tr><td>24 </td><td><p>The Home screen reverts. </p><p></p></td></tr><tr><td>25 </td><td>User selects the three line button on the far left top of the screen. </td></tr><tr><td>26 </td><td>The side bar opens. <br><img src="../.gitbook/assets/image (104).png" alt=""></td></tr><tr><td>27 </td><td>User single-tapps the “Log Out” button. </td></tr><tr><td>28 </td><td><p>The DHIS2 login screen reverts. Note that after logging out, only the “Server url” defaults </p><p>to (and caches the URL) while the “Username” and “Password” field remain blank. </p><p><img src="../.gitbook/assets/image (105).png" alt="" data-size="original"></p></td></tr></tbody></table>

### &#x20;6.3 Stock data entry and editing - Advanced mode

Instead of collecting data for monthly reports, the “Advanced mode” records all transactions at the central pharmacy as at when they are effected in real-time.

_**The “Basic mode” apk-file must be uninstalled before installing the “Advanced mode” apk- file as the “Basic mode” and “Advanced mode” must never be used in parallel.**_

Note that the Health Unit has decided on the following static list of wards and services for which stock transactions can be recorded and only these are available for selection. In case none of the available options matches the service supplied to, “Other” can be selected. This list is “static” (fixed in the coding) and cannot be changed:

**Diagnostic imaging (X-Ray)**

**Emergency room**

**High Dependency Unit (HDU)**

**Inpatient Medical Department**

**Inpatient Surgical Department**

**Inpatient Surgical Department 2**

**Inpatient Surgical Department 3**

**Laboratory Department**

**Mortuary**

**Obstetrics & Gynaecology services**

**Operating Theatre**

**(Other)**

**Out-Patient Department**

**Paediatric Department**

**Physiotherapy Department**

**Recovery Room**

**Sanitation / Housekeeping**

**Sterilization Department**

**Transfusion services**

**Patients transfer/Medevacs**

**Anesthesia department**

**MHPSS department**

**Biomed department**

In case, only one inpatient surgical department is supported, use ‘Inpatient Surgical Department’ only. In case more than one inpatient surgical department is supported in your hospital/there are more than one physical location, you can decide to allocate which number to be used in which inpatient surgical department. It is very important to remain coherent in the numbering for the reporting.

_The “Advanced mode” only manages, receives and displays items which are included in the stock item list of the respective health care facility, and which require regular, monthly stock replenishment._ Whenever the content of packing lists is uploaded from the JDE software to DHIS2, only the items which are currently included in the stock item list for the respective health care facility are considered. Any other items, such as health care equipment, will not be uploaded and will not appear in the list of stocks.

Note that the three processes “Distribution”, “Discard” and “Correction” are nearly identical and the description below applies to and covers all of them.

For the sake of saving space only the upper half of the mobile device screen is shown in the descriptions below.

There are three distinct but very similar workflows which each have their own and specific purpose:

**Distribution** workflow: for distributing healthcare goods from the central pharmacy to wards or services&#x20;

**Discard** workflow: for removing expired, damaged or otherwise unusable stock which is subsequently disposed of&#x20;

**Correct** workflow: for reconciling (positive or negative) discrepancies between the stock on hand (physical stock count) and the remaining stock on hand as calculated by DHIS2.

#### 6.3.1 “Settings” - Advanced mode

The “Settings” menu allows users to personalize the language settings, control the microphone setting, prompt synchronization of the local database and logout and applies equally to all three workflows. Note that the microphone and language settings are permanent, are not reset during logout and during any subsequent login will remain as during the prior logout.

<table data-header-hidden><thead><tr><th width="76"></th><th></th></tr></thead><tbody><tr><td>No. </td><td>Step / Results </td></tr><tr><td>1 </td><td>User accesses the DHIS2 mobile device application. </td></tr><tr><td>2 </td><td>The home screen opens, by default none of the “transactions” is selected and the button to the “Settings” menu (three-dot icon) is visible at all times and throughout all transactions. <br><img src="../.gitbook/assets/image (190).png" alt=""></td></tr><tr><td>3 </td><td>User taps on the three-dot menu in the upper right corner of the window. </td></tr><tr><td>4 </td><td>The “Settings” window opens and fills the entire screen. <br><img src="../.gitbook/assets/image (191).png" alt=""></td></tr><tr><td>5 </td><td>User toggles the button in the far upper corner for switchen the microphone on (right) or off (left). </td></tr><tr><td>6 </td><td>The microphone is activated (switched on) the the toggled button changes its colour from grey to green. <br><img src="../.gitbook/assets/image (192).png" alt=""></td></tr><tr><td>7 </td><td><p>User taps the “Language” button. As changing the language will automatically and inevitably prompt a “Restart” with complete closing of the mobile app, ensure completion of any ongoing transactions as well as a prompting a “manual” synchronization before changing any language settings. </p><p>Also note that when changing any language settings the mobile app will inevitably close, automatically restart but require to re-authenticate and log in to the application again which requires a network connection. </p></td></tr><tr><td>8 </td><td>The “Language” window opens and displays “Select your desired language”. <br><img src="../.gitbook/assets/image (193).png" alt=""></td></tr><tr><td>9 </td><td>User taps the “Select your desired language” button for change the language. Note that the user can only change the interface language but that the language of the item descriptions can only be changed by system administrator. </td></tr><tr><td>10 </td><td><p>A pop-up window opens and displays the five language which are available by default to all users. </p><p><img src="../.gitbook/assets/image (110).png" alt="" data-size="original"></p></td></tr><tr><td>11 </td><td>User toggles one of the available languages. Note that in case of a mistake (for example selecting “Arabic”) the language can be changed back by any user any time but all menus will appear in the selected language. In this (unlikely) case the user can follow this instruction and simply select the settings based on the relative position of options in the menus for “restoring” (or chosing) another language. </td></tr><tr><td>12 </td><td>A pop-up window with a warning that any unsaved changes will be lost. <br><img src="../.gitbook/assets/image (111).png" alt=""></td></tr><tr><td>13 </td><td>Before confirming the change, the user must ensure that any transactions are completed and that all data has been “manually” synchronized before changing the language setting. User either selects “RESTART LATER” which cancels any change of language settings or “OK”. </td></tr><tr><td>14 </td><td>The application closes, restarts, requires the user to re-authenticate and reopens the PSM home page with the changed language settings. <br><img src="../.gitbook/assets/image (112).png" alt=""></td></tr></tbody></table>

#### 6.3.2 “Distribution” workflow - Advanced mode

<table data-header-hidden><thead><tr><th width="80"></th><th></th></tr></thead><tbody><tr><td>No. </td><td>Step / Results </td></tr><tr><td>1 </td><td>User accesses the DHIS2 mobile device application. </td></tr><tr><td>2 </td><td>The home screen opens, by default none of the “transactions” is selected, the header bar “Pharmacy Stock Management” therefore appears in black, only the health care facility to which the user has been assigned is displayed under “Select Facility” and the “Date of Transaction” defaults to the current date. In the exceptional case that a user is assigned to more than a single health care facility, the user can tap on the drop down menu for selecting one of those facilities. <br><img src="../.gitbook/assets/image (194).png" alt=""></td></tr><tr><td>3 </td><td><p>User selects “Distribution” by taping on the icon. </p><p><em>For “Discard” and “Correction” work flows please refer to the next section.</em> </p></td></tr><tr><td>4 </td><td>The colour of the header bar “Pharmacy Stock Management” changes to green and the “Distributed to” drop-down menu appears on the screen. <br><br><img src="../.gitbook/assets/image (114).png" alt=""></td></tr><tr><td>5 </td><td>User opens the “Distributed to” drop-down window and selects the required, department or service to which the goods are delivered. Note that this drop-down window only applies to “Distribution” (but neither to “Discard” nor to “Correction”). </td></tr><tr><td>6 </td><td>The selected service appears in the “Distributed to” window: <br><img src="../.gitbook/assets/image (195).png" alt=""></td></tr><tr><td>7 </td><td>User selects the “Proceed” button at the bottom right of the screen. </td></tr><tr><td>8 </td><td>The “Distribution” window opens and displays the settings selected in the previous window at the top of the screen and a complete list of all stock items with their current stock on hand below: <br><img src="../.gitbook/assets/image (116).png" alt=""></td></tr><tr><td>9 </td><td><p>The user is now ready to start preparing the order received from the ward or service requiring goods which is usually a filled in form with items and quantities. The user has three possibilites for searching for items in the list (with the first two being self- explanatory and only the third option being explained in detail): </p><p>·         Manually scrolling down the list until the requested item is found </p><p>·         Enter a search term in the “Search item” window </p><p>·         Scan the barcode attached to the item on the shelf </p><p>User taps the ”SCAN BARCODE” button in the upper right corner of the window. </p></td></tr><tr><td>10 </td><td><p>The barcode viewfinder window opens which displays a white field with a horizontal red line displaying the view of the mobile device camera: </p><p><img src="../.gitbook/assets/image (117).png" alt="" data-size="original"></p></td></tr><tr><td>11 </td><td><p>User place the viewfinder window in front of the barcode which is attached to the label on the shelf and positions the red line across the centre of the barcode: </p><p><img src="../.gitbook/assets/image (118).png" alt="" data-size="original"></p></td></tr><tr><td>12 </td><td><p>The DHIS2 Capture app will audibly signal as soon the mobile device has captured the barcode, close the viewfinder window and display only the selected item in the window. The window will display the current “Stock on hand” (which should correspond to the actual remaining stock on the shelf) and a red microphone icon (“activated”, “switched on” in the “Quantity” window. </p><p><img src="../.gitbook/assets/image (119).png" alt="" data-size="original"></p></td></tr><tr><td>13 </td><td>User dictates the ordered quantity which is to be picked out load. </td></tr><tr><td>14 </td><td><p>The application will convert the speech into text, fill in the “Quantity” field and switch </p><p>off the microphone (greyed out, “inactivated”). </p><p></p></td></tr><tr><td>15 </td><td>This completes the recording of the first item which is picked and the user continues to pick the remaining items for the same ward or service and after recording the last item, selects the “REVIEW” button. </td></tr><tr><td>16 </td><td>At any time during the order picking the application displays the complete list of all stock items and quantities for those items which have been recorded so far. <br><img src="../.gitbook/assets/image (196).png" alt=""></td></tr><tr><td>17 </td><td><p>After the last required item has been picked, the user selects the “REVIEW” button at </p><p>the bottom right of the screen. </p></td></tr><tr><td>18 </td><td>The final application window showing only the selected items appears. The user can change (increase or decrease) any quantities and delete items by selecting the “x” button. Note that in this final steps items cannot be added to the list anymore and the “Search item” as well as the “SCAN BARCODE” can only be used for search items within the list (in case the list is long and the user is not sure that a certain item was correctly picked). In case items are actually missing the user can either discard all entries and start from scratch or simply complete the transaction and then start a second transaction for the same ward or service for the items which were missed. <br><img src="../.gitbook/assets/image (197).png" alt=""></td></tr><tr><td>19 </td><td>User selects the “CONFIRM” button. Note that this step is irreversible and cannot be reverted or be undone in any way. </td></tr><tr><td>20 </td><td>The home screen reverts, a pop-up window displaying “The transaction was successfully completed” appears at the bottom of the screen and the recently completed transaction is indicated at the the top of the “Recent Activity” list with the “Distributed to” location and a date and time stamp. Note that the details of the transactions are not available in the PSM app but available in the dashboards on the mobile device as soon as the data has been synchronized. <br><img src="../.gitbook/assets/image (198).png" alt=""></td></tr><tr><td>21 </td><td>User selects the three dot menu at the far right top of the window and “Settings”. </td></tr><tr><td>22 </td><td>The “Settings” window opens. </td></tr><tr><td>23 </td><td><p>User selects the ”Force data snchronization” button. In principle data can be stored on the local database with the mobile device off-line indefinitely but transactions will not be available on the central DHIS2 server, will not appear in the dashboard on the mobile device and if another user logs into the mobile device, any transactions which were not synchronized with the server, will be irreversibly lost. </p><p>Always synchronize data before leaving the application. </p></td></tr><tr><td>24 </td><td>A pop-up window at the top as well as the bottom of the screen (“Syncing data”) indicate that the data is being synchronized as well as after completion (“Syncing completed”). </td></tr><tr><td>25 </td><td>User select “Logout” from the same “Settings” window. <br><img src="../.gitbook/assets/image (199).png" alt=""></td></tr><tr><td>26 </td><td>The home screen of the mobile device appears. <br><img src="../.gitbook/assets/image (124).png" alt=""></td></tr></tbody></table>

#### 6.3.3 “Discard” workflow - Advanced mode

As the three workflows are almost identical, only the few differences with the “Distribution” workflow are presented below.

<table data-header-hidden><thead><tr><th width="65"></th><th></th></tr></thead><tbody><tr><td>1 </td><td>User accesses the DHIS2 mobile device application. </td></tr><tr><td>2 </td><td>The home screen opens, by default none of the “transactions” is selected, the header bar “Pharmacy Stock Management” therefore appears in black, only the health care facility to which the user has been assigned is displayed under “Select Facility” and the “Date of Transaction” defaults to the current date. In the exceptional case that a user is assigned to more than a single health care facility, the user can tap on the drop down menu for selecting one of those facilities. </td></tr><tr><td>3 </td><td>User selects “Discard” by taping on the icon. <br><img src="../.gitbook/assets/image (200).png" alt=""></td></tr><tr><td>4 </td><td>The color of the header bar “Pharmacy Stock Management” changes to green and the “Distributed to” drop-down menu disappears from the screen. Note that the “PROCEED” button now appears in red. <br><img src="../.gitbook/assets/image (201).png" alt=""></td></tr><tr><td>5 </td><td>User choses the healthcare facility (in the rare cases where assigned to more than one facility), changes the “Date of Transaction” (only if needed) and selects the “PROCEED” button. </td></tr><tr><td>6 </td><td>The “Discard” window opens and note that the background header bar changes to red to indicate that the user is in a “Discard” transaction. <br><img src="../.gitbook/assets/image (127).png" alt=""></td></tr><tr><td>7 </td><td>User proceeds with the transaction in the same way as for a “Distribution” transaction and completes the transaction by selecting the “PROCEED” button (for the details please refer to sub-chapter 6.3.2 “Distribution” workflow). </td></tr><tr><td>8 </td><td>After completing the transaction, the home screen reverts and the date as well as the time of the “Discard” transaction will be listed as the first entry in the “Recent Activity” list. <br><img src="../.gitbook/assets/image (202).png" alt=""></td></tr></tbody></table>

#### 6.3.4 “Correction” workflow - Advanced mode

As the three workflows are almost identical, only the few differences with the “Distribution” workflow are presented below.

<table data-header-hidden><thead><tr><th width="81"></th><th></th></tr></thead><tbody><tr><td>1</td><td>User accesses the DHIS2 mobile device application.</td></tr><tr><td>2</td><td>The home screen opens, by default none of the “transactions” is selected, the header bar “Pharmacy Stock Management” therefore appears in black, only the health care facility to which the user has been assigned is displayed under “Select Facility” and the “Date of Transaction” defaults to the current date. In the exceptional case that a user is assigned to more than a single health care facility, the user can tap on the drop down menu for selecting one of those facilities.</td></tr><tr><td>3</td><td>User selects “Correction” by taping on the icon.<br><img src="../.gitbook/assets/image (203).png" alt=""></td></tr><tr><td>4</td><td>The colour of the header bar “Pharmacy Stock Management” changes to grey and the “Distributed to” drop-down menu disappears from the screen. Note that the “PROCEED” button now appears in grey.<br><img src="../.gitbook/assets/image (204).png" alt=""></td></tr><tr><td>5</td><td>User choses the healthcare facility (in the rare cases where assigned to more than one facility), changes the “Date of Transaction” (only if needed) and selects the “PROCEED” button.</td></tr><tr><td>6</td><td><p>The “Correction” window opens and note that the background header bar changes to</p><p>grey to indicate that the user is in a “Correction” transaction.<br><img src="../.gitbook/assets/image (205).png" alt=""></p></td></tr><tr><td>7</td><td><p>Note that “Correction” is the only transaction which allows entering positive or negative values which apply in the following way:</p><p>Positive value = “missing quantity” (physical stock less than the calculated value) Negative value = “found in stock” (physical stock is more than the calculated value)</p><p>While this may not seem intuitive, note that all “reductions” of stocks (“Distribution” and “Discard”) are consistently recorded as positive values. Therefore a “Correction” with a positive value indicates that stock was issued (without having been recorded). Therefore conversly (and consistently) any negative value indicates a stock “receipt” without having been recorded.</p><p>In order to guide storekeepers, selecting the “I” (information) icon next to the “Quantity” header displays an explanation. This explanation is intentionally only displayed “on demand” to avoid taking too much space and the storekeeper can decide whether to display the notice and close it any time.</p></td></tr><tr><td>8</td><td>A pop-up window opens below the search bar and displays an explanation for the positive or negative sign of entered values.<br><img src="../.gitbook/assets/image (206).png" alt=""></td></tr><tr><td>9</td><td>User selects the “x” icon for closing the pop-up information window. The pop-up information window closes, the user proceeds with the transaction in the same way as for a “Distribution” transaction and completes the transaction by taping the “CONFIRM” buttton (for the details please refer to sub-chapter 6.3.2 “Distribution” workflow).</td></tr><tr><td>10</td><td>After completing the transaction, the home screen reverts and the date as well as the time of the “Correction” transaction will be listed as the first entry in the “Recent Activity” list.<br><img src="../.gitbook/assets/image (207).png" alt=""></td></tr></tbody></table>

#### 6.3.5 Stock list and real-time stock on hand calculations – Advanced mode

The stock item list needs to be defined by the ICRC Health programme manager in preparation of introducing the “Advanced mode” and share it with the BSSC Belgrade which will “enrol” all of the items.

This stock item list is “static”, and the configuration remains as long as the stock item list is not changed by adding or removing items.

The “Advanced mode” will always display the entire list regardless of whether the stock on hand of items is positive or zero (with negative stocks not allowed under any circumstances).

When users acknowledge receipt of stock with the dedicated IRIS application, any quantities of items which are part of the stock item list, are added to the current stock on hand balance as soon as the local database on the mobile device is synchronized with the central DHIS2 database. Any quantities of items which are not included in the stock item list are “ignored” by the PSM application and have no effect on the stock balance of any items.

The calculation is made according to the following algorithm for each health care facility and each item code separately:

Stock on hand (current) + SUM (Stock receipts) - SUM (Stock issues) = Stock on Hand (new balance).

The PSM application always displays the currently calculated Stock on hand for each item and immediately increments (stock receipts) or decrements (stock issues) the value but does not maintain a history of the stock on hand at previous times or dates. This information is only available in Tableau from the central DHIS2 database.

### 6.4 DHIS2 mobile device application analytics – Basic and Advanced mode

While Tableau (Business Analytics application) is the main and primary tool for all reporting, dashboards and analysis, it is only accessible to ICRC staff on ICRC computers and therefore not accessible to non-ICRC staff using mobile devices. Therefore, a single, very simple dashboard is configured in DHIS2 itself which is accessible to all users (including non-ICRC staff) and accessible on mobile devices through any web browser with the same user access as for the Capture app but not in the Capture app itself (as this functionality is not available in the DHIS2 which is used by the PSM).

The DHIS2 dashboard portal provides access to all dashboards for the “Basic mode” as well as for the “Advanced mode” and is accessed for both modes in the same way.

While all data is presented in a single dashboard for the “Basic mode” and the “Advanced mode” respectively, the dashboard itself consists of several tables because the number of rows which can be displayed in any one report are limited. Therefore, the list of items was split into two groups, one from item groups A through L and another from M through X.

In the DHIS2 version used for the Pharmacy Stock Management tool, the in-app dashboards are not available. However, “snapshots” of dashboards showing all data as at the time of downloading, can be saved in the web browser as download and opened any time on-line or off- line like any other downloaded file.

After accessing the DHIS2 dashboard for the first time, users should create a “bookmark” in their web browser and a shortcut to their home screen for quick access. The selected web browser, such as the Chrome web browser, must allow downloading websites.

In order to view dashboards, users need to first start the mobile device and have web browser installed on the mobile device. Note that when accessing DHIS2 dashboards through a web browser the same authentication as for accessing the mobile device application will be required and the username and password can be used.

<table data-header-hidden><thead><tr><th width="71"></th><th></th></tr></thead><tbody><tr><td>No</td><td>Step / Results</td></tr><tr><td>1</td><td>User accesses the mobile devices and opens the home screen.</td></tr><tr><td>2</td><td>The mobile device home screen appears.<br><img src="../.gitbook/assets/image (208).png" alt=""></td></tr><tr><td>3</td><td>User opens the web browser by tapping the icon.</td></tr><tr><td>4</td><td>The web browser home page appears.<br><img src="../.gitbook/assets/image (137).png" alt=""></td></tr><tr><td>5</td><td><p>Users enters the same URL as for accessing the mobile device application into the URL</p><p>window and selects “Enter”.</p></td></tr><tr><td>6</td><td>The URL appears in URL window.<br><img src="../.gitbook/assets/image (138).png" alt=""></td></tr><tr><td>7</td><td><p>The web browser home page opens and prompts the user for his authentication.</p><p><em>Note that the instruction below does not explain the authentication, please refer to the Camtasia video guide with the exact details of authentication which is identical for accessing the mobile device application and DHIS2 on a web browser.</em></p><p><img src="../.gitbook/assets/image (139).png" alt="" data-size="original"></p></td></tr><tr><td>8</td><td>The DHIS2 dashboard will automatically appear as the home screen in the web browser.<br><img src="../.gitbook/assets/image (140).png" alt=""></td></tr><tr><td>9</td><td>User bookmarks the web page by selecting the star icon (this may be differ if another web browser is used).<br><img src="../.gitbook/assets/image (209).png" alt=""></td></tr><tr><td>10</td><td><p>The star icon is highlighted and the web page is now saved under “Bookmarks” from</p><p>where it can be selected for quick navigation when accessing subsequently.<br><img src="../.gitbook/assets/image (210).png" alt=""></p></td></tr><tr><td>11</td><td>The user navigates among available dashboards as required. For saving any of the dashboards for offline viewing, users selects the download icon (downward arrow) in the right upper corner of the web browser.</td></tr><tr><td>12</td><td>The selected dashboard (browser window) is downloaded and a notification appears at the bottom of the screen when the download has been completed.<br><img src="../.gitbook/assets/image (211).png" alt=""></td></tr><tr><td>13</td><td>User accesses the off-line dashboard by selecting “Open”.</td></tr><tr><td>14</td><td>The off-line dashboard is displayed.<br><img src="../.gitbook/assets/image (212).png" alt=""></td></tr><tr><td>15</td><td>User can manage several downloads (of different dashboards or at different times) by selecting the three-dot menu in the upper right corner of the web browser.</td></tr><tr><td>16</td><td>The “Downloads” open appears.<br><img src="../.gitbook/assets/image (213).png" alt=""></td></tr><tr><td>17</td><td>The “Downloads” page appears which displays all downloads which are available for offline viewing on the mobile device. The user can open them by tapping on a download or delete them by selecting the three-dot menu next to each of the downloads.</td></tr><tr><td>18</td><td>A pop-up window with options appears next to each dashboard download.<br><img src="../.gitbook/assets/image (214).png" alt=""></td></tr><tr><td>19</td><td>User closes the web browser.</td></tr><tr><td>20</td><td>The home screen of the mobile device reverts.<br><img src="../.gitbook/assets/image (215).png" alt=""></td></tr></tbody></table>

### 6.5 DHIS2 mobile device application data synchronization – Basic mode

The details of the synchronization of the local DHIS2 database on the mobile device and the central DHIS2 server in Geneva are rather intricate and explained for users taking interest but in practice not of much importance for the day to day work.

This chapter explains the synchronization of the “Basic mode” while details for the “Advanced mode” (which is far simpler) are given in sub-chapter 6.3.1 “Settings” – _Advanced mode_.

<table data-header-hidden><thead><tr><th width="86"></th><th></th></tr></thead><tbody><tr><td>No</td><td>Step / Results</td></tr><tr><td>1</td><td>User accesses the DHIS2 mobile device application or reverts to the home screen from any other application window.</td></tr><tr><td>2</td><td>The home screen opens or reverts. If data has been stored (added or edited) on the mobile device since the last synchronization, a double circular arrow icon is displayed:<br><img src="../.gitbook/assets/image (151).png" alt=""></td></tr><tr><td>3</td><td>User selects the three-line menu on the upper far left.</td></tr><tr><td>4</td><td>The sidebar opens on the left side of the screen.<br><img src="../.gitbook/assets/image (152).png" alt=""></td></tr><tr><td>5</td><td>User selects the "Settings" button.</td></tr><tr><td>6</td><td>The "Settings" application window opens and the date and time of the last data as well as synchronization is displayed.<br><img src="../.gitbook/assets/image (153).png" alt=""></td></tr><tr><td>7</td><td>User selects the "Sync data" button.</td></tr><tr><td>8</td><td><p>The application menu expands displaying “Syncing period is not editable” (which only</p><p>refers to the pre-set automatic synchronization).<br><img src="../.gitbook/assets/image (154).png" alt=""></p></td></tr><tr><td>9</td><td>User selects the "SYNC DATA NOW" button.<br><img src="../.gitbook/assets/image (155).png" alt=""></td></tr><tr><td>10</td><td><p>A small pop-up window “Dhis2 PSM is Syncing your Configuration” will appear briefly and “Syncing your data” will be displayed briefly instead of the last synchronization data and time and the data and time of current synchronization is displayed.</p><p>Note that no error will appear in case the synchronization is not completed. Instead the user must confirm that the data and time have changed to the current date and time.<br><img src="../.gitbook/assets/image (156).png" alt=""></p></td></tr><tr><td>11</td><td><p>User selects the "Back" button on the mobile device or alternatively the three-line menu</p><p>and “Home”.</p></td></tr><tr><td>12</td><td>The Home screen of the mobile device application reverts. Note that if the double circular error was displayed before the synchronization, it will no longer be displayed after a successful synchronization.<br><img src="../.gitbook/assets/image (157).png" alt=""></td></tr><tr><td>13</td><td>The users logs out of the mobile device application.</td></tr><tr><td>14</td><td><p>The login screen of the mobile device application reverts.</p><p> <img src="../.gitbook/assets/image (158).png" alt=""></p></td></tr></tbody></table>

By default, all mobile devices are always “off-line” (even if there is a permanent network connection) and all data which is entered on a mobile device is stored in the local database on the mobile device. “Synchronization” means that any new or corrected data (for example stock data) or metadata (configuration changes) entered on the mobile since the last synchronization is “copied” from the local database on the mobile device to the central DHIS2 database and vice versa.

“Metadata” synchronization refers to changes of the configuration and settings such as adding or removing items from the stock item list or correcting translations of item descriptions while “Data” synchronization refers to changes of numeric values. For example, any changes of Imprest Levels are “copied” from the central DHIS2 server to the local database on the mobile device or stock data entered by the storekeeper is “copied” to the central DHIS2 database.

The synchronization rules are rather intricate and provided in detailed for those users who are particularly interested while the most important information is highlighted in red:

**Scheduled synchronization** The global system setting, which applies to all mobile devices, will prompt synchronization every 24 hours. This setting does not indicate a fixed time for the synchronization but rather means that, by default, the local DHIS2 database will automatically attempt synchronization 24 hours after the last synchronization regardless of whether this was in turn a scheduled synchronization or prompted by a user. In practice, therefore any two devices are (eventually) unlikely to synchronize at the same time and the “randomization” of synchronization times of different devices prevents the central DHIS2 server from becoming overloaded.

This daily synchronization applies, even if the mobile device is connected to the mobile network or a WLAN all day in order to use resources economically.

In addition, any changed “metadata” as well as all changed data values will automatically by synchronized during every login of every user.

_**Note that during the very first login of a new user, when the user has not logged into that specific device or if many changes were made (for example many changes of stock items or much data entered through another device) the synchronization can take several minutes even if an excellent network connection is available.**_

The synchronization process must not be interrupted as it has to be completed before the mobile device application can be used. The duration of the synchronization process can range from less than a second to many minutes depending on the number of Organisation Units to which the user is assigned, the number of changes to the metadata and the number of data values which have changed. By default, users should have access to a single healthcare facility and the synchronization should not take more than a few minutes

If the daily synchronization which is prompted 24 hours after the last synchronization fails due to a lack of network connection, the reconnecting attempts are controlled by the Android operating system of the mobile device and not by the DHIS2 application itself. But users who want to “manually” prompt the synchronization do no need to concern themselves with the load on the central DHIS2 server as it is designed for handling many concurrent users.

However, users can prompt a “manual” synchronization at any time and _**it is very highly recommended that storekeepers “manually” synchronize the mobile device whenever any data was entered**_ (or at least substantial amounts of data) to prevent any loss of data for example if the mobile device is lost. Malfunctions or another users logs into the same device. Any data which has been synchronized, will be permanently stored on the server and can be accessed from any mobile device at any time (including devices other than the one used for initially collecting the data).

A default security measure requires that any data which is not synchronized with the central DHIS2 server will irrevocably lost, if the user logs out. This measure is intended to prevent unauthorized access to data on the mobile device.

_**Before logging out of the mobile device application, ensure completion of synchronization of data as any data which has not been synchronized will be irrevocably lost and cannot be retrieved by any means.**_

**Prioritization of synchronization** When data is entered on the mobile device as well as on the central DHIS2 server from a desktop or notebook computer using the DHIS2 web portal, DHIS2 applies a simple rule:

* the data which is either synchronized to the central DHIS2 instance or edited on the DHIS2 instance (through the web portal), supersedes (“overwrites”) any data previously synchronized with or entered in the DHIS2 web portal.

In principle, storekeepers are entering and editing only stock data (stock on hand and stock issues) on mobile devices and Health program managers only enter and edit Imprest Levels through a desktop or notebook computer through the DHIS2 web portal. Therefore, in principle, there should never be any risk that data entered by storekeepers or ICRC Health programme mangers would be accidentally “erased” and overwritten. However, it is important to know that there is a possibility that the actual chronology of data entry is not maintained. This problem of course only applies in case two users edit the same cells, in the same month for the same health care facility. There are two possible cases, depending on which user enters data first (recall that data is always synchronized “both ways” from the mobile device to the DHIS2 server and vice versa):

**DHIS2 web portal is chronologically entered later**

* The storekeeper enters stock on hand data on the first day of the month on a mobile device (but does not synchronize this data for whatever reason).
* The ICRC Health program manager enters data on the last day of the same month through the DHIS2 web portal, for example for entering some corrections and therefore has _made the most recent edit_.
* The mobile device synchronizes its data with the DHIS2 central server after the ICRC Health programme manager has completed her/his editing.
* This synchronization will “overwrite” the data on DHIS2 central server and replace it with the data which is now “copied” from the mobile device to the DHIS2 server, although it was entered long before the data entered on the DHIS2 web portal.

_**The same data fields are edited on the mobile device and in the web portal at the same time**_

* The storekeeper and the ICRC Health programme manager (by chance) edit the same data field for the same month, the same health care facility at exactly the same time but with different values (for whatever reason).
* The mobile device synchronizes with the DHIS2 central server.
* The synchronization will “overwrite” the data entered in the DHIS2 web portal which will be “replaced” by the data from the mobile device.

_**Data from mobile devices always “overwrites” any data on the central DHIS2 server during synchronization.**_

The options “Delete local data” and “Reset app data & configuration” will lead to loss of all data which was not synchronized, must not be used by non-expert users and must only be used if explicitly instructed by the ICT Service Desk.

## 7 ICRC RESOURCES INTEGRATED SYSTEM (IRIS) IMPREST ORDER USER INTERFACE

The IRIS “Imprest Order” application integrates and presents data from DHIS2 collected at the health care facility on mobile devices together with real-time data from JDE in a single user interface and proposes a monthly replenishment order based on the “Imprest System”.

### 7.1 Preparing and submitting monthly pharmacy orders in IRIS

Health programme managers, or other staff members they delegate this task to, prepare one monthly order for each health care facility. In exceptional cases, urgent orders can be made at any time in addition to the monthly order and in some cases, orders may be made only every two or three months instead of monthly which requires increasing the Imprest Level accordingly.

_**Note that data from DHIS2 is synchronized with IRIS only every six hours**_ , at 0:00, 6:00, 12:00 and 18:00 Geneva time, Switzerland). Therefore, after the storekeeper has synchronized data from the mobile device with the DHIS2 server, it will take a maximum of six hours for all that data to be updated in IRIS.

In order to avoid duplication of functionality already available in other systems and to keep the whole project as simple as possible, the entire process involves the use of three existing software applications, namely the DHIS2 web portal, IRIS and Tableau BI Server rather than developing a single application which would be quite complicated.

After the storekeeper has completed the physical stock count and entered the stock on hand as well as monthly consumption data, the user accesses the dedicated IRIS interface where a proposed order is calculated using the Imprest System. After review, and if necessary, editing the proposed order quantities, the programme managers "pushes" the list of items and quantities to the usual SR template in IRIS for further processing like any other SR.

_**The entire process involves three steps in three different systems:**_

* Review of the Imprest Levels and recommendations for changes in **Tableau**
* Revising Imprest Levels in the **DHIS2** web portal as and when needed
* Preparing and issuing the monthly replenishment order in **IRIS**&#x20;

In principle, the Imprest Levels for each health care facility should only be reviewed two or three times per year but it is advised to check them every month for identifying items with a significant increase in demand for which the Imprest Levels need to be increased immediately in order to avoid stockouts. Otherwise the shortage or stockout is likely to persist until the next Imprest Level review takes place and the ordered goods are delivered.

<table data-header-hidden><thead><tr><th width="87"></th><th></th></tr></thead><tbody><tr><td>No</td><td>Step / Results</td></tr><tr><td>1</td><td>User opens Tableau BI Server which authenticates through SSO (Single sign-on), accesses the "Health – DHIS2 Pharmacy Stock Management analysis", selects the "Imprest level analysis" worksheets, selects the health care facility for which the monthly order is being prepared, reviews and, if necessary, revises the Imprest Levels.</td></tr><tr><td>2</td><td>The Tableau worksheet appears:<br><img src="../.gitbook/assets/image (159).png" alt=""></td></tr><tr><td>3</td><td>User opens the DHIS2 web portal, selects the health care facility for which the monthly order is being prepared and, if necessary, revises the Imprest Levels for any item where this is required.</td></tr><tr><td>4</td><td><p>The DHIS2 web portal appears:</p><p> <img src="../.gitbook/assets/image (160).png" alt=""></p><p><em>Please refer to details in chapter 5</em>.</p></td></tr><tr><td>17</td><td>The user logs into the IRIS web portal which authenticates through SSO (Single sign-on): <a href="https://iris.ext.icrc.org/ls/cp/imprest-order">https://iris.ext.icrc.org/ls/cp/imprest-order</a></td></tr><tr><td>18</td><td>The IRIS home screen appears.<br><img src="../.gitbook/assets/image (161).png" alt=""></td></tr><tr><td>19</td><td>The user navigates to the "IMPREST ORDER" icon (white square with a black cross) on the vertical sidebar on the left and double-clicks on it.</td></tr><tr><td>20</td><td><p>The "IMPREST ORDER" application window opens:</p><p> <img src="../.gitbook/assets/image (162).png" alt=""></p></td></tr><tr><td>21</td><td>The user selects the “Country”, the “Branch Plant”, the “Recipient Place Type” (optional) as well as the “Recipient Place” from the drop-down filter menus. By default the settings for “Country” and “Branch Plant” used most recently will appear by default.</td></tr><tr><td>22</td><td>The selections made by the user are displayed in the respective filter fields.<br><img src="../.gitbook/assets/image (163).png" alt=""></td></tr><tr><td>23</td><td>User selects the “APPLY FILTER” button.</td></tr><tr><td>24</td><td>The main screen with a header (displaying the selected health care facility details) as well as a table with the stock details for all stock items which appear in the DHIS2 “Data set” of the respective facility are displayed.<br><img src="../.gitbook/assets/image (164).png" alt=""></td></tr><tr><td>25</td><td><p>If there are open (unvalidated) SRs (JDE status &#x3C; 520) for the same health care facility, a pop-up window will appear at the top of the screen: “An open order was detected under this Recipient Place, please check before creating a new Imprest Order”. Note that any SRs whether medical or non-medical and regardless of whether they were made with the Imprest Order application or not will prompt an alert and the user must then check whether they are relevant.</p><p>The user should always select “please check” and review all open (unvalidated) SRs to</p><p>ensure that the monthly stock replenishment order is not being duplicated.</p></td></tr><tr><td>26</td><td>A pop-up window “Recipient Place Open Orders” opens and displays all unvalidated SRs (“Supply Requests”). Note that open SO (“Sales Orders”) are not included as those quantities are in any case considered in the “Stock on order” column.<br><img src="../.gitbook/assets/image (165).png" alt=""></td></tr><tr><td>27</td><td>The user can select any of the SR numbers for review.</td></tr><tr><td>28</td><td>IRIS opens a separate web browser tab with a user interface displaying the native IRIS “Order Status” application and the user can review the detailed contents of the SR. <em>Please refer to the IRIS documentation for details on the “Order Status” application</em>.<br><img src="../.gitbook/assets/image (166).png" alt=""></td></tr><tr><td>29</td><td>The user closes the pop-up window by selecting the “X” in the far upper right corner.</td></tr><tr><td>30</td><td>The pop-up window closes and the “Imprest Order” screen reverts.<br><img src="../.gitbook/assets/image (167).png" alt=""></td></tr><tr><td>31</td><td><p>“Basic mode”: the user reviews the date displayed under ”Last Stock Data Update” and ensures that a stock count has taken place end of the previous month. If this is not the case, the ICRC Health program managers needs to consult with the respective storekeeper and postpone the stock replenishment calculation until the stock data has been updated.</p><p><em>Note that the “Last Stock Data Update” displays the date of the last entry made in the Data Entry Form of the respective health care facility even if only a single item was updated</em>. Therefore a recent date is not a confirmation that a (complete) physical stock count has taken place nor that the physical stock count has been completed for all items. “Advanced mode”: there is no need to verify this date as in the “Advanced mode” the stock on hand is calculated in real time, (in principle) no physical stock counts are needed and stock corrections can be made at any time. However, the storekeeper must ensure (at least) daily synchronization of data from the mobile device with the DHIS2 central database.</p></td></tr><tr><td>32</td><td>The “Last Stock Data Update” is automatically displayed in the right upper right corner.<br><img src="../.gitbook/assets/image (168).png" alt=""></td></tr><tr><td>33</td><td>The user reviews the date of the “Last SO date” to avoid duplications of monthly replenishment orders. Note that this date displays the most recent SO (“Sales order”) date for that health care facility, regardless of whether this is a medical or non-medical order and whether the medical order was for the monthly stock replenishment or other medical items. In case of doubt, the user can consult the native IRIS “Order Status” application and review recent SOs.</td></tr><tr><td>34</td><td>The “Last Stock Data Update” is automatically displayed in the right upper right corner.<br><img src="../.gitbook/assets/image (169).png" alt=""></td></tr><tr><td>35</td><td><p><em>Optional</em>: the user selects the Branch/Plant of the medical distribution centre which</p><p>routinely supplies the health care facility from the “SELECT” drop-down menu.</p></td></tr><tr><td>36</td><td>The column displays the current stock levels for each item at that medical distribution centre. Note that (part of) those quantities may early have been allocated to other customers and these stock levels are therefore only indicative. On there other hand, in case the stock level is below the required quantity or the item is out of stock, then a delay in delivery is likely and the Health programme manager should consult with the logistician.<br><img src="../.gitbook/assets/image (170).png" alt=""></td></tr><tr><td>37</td><td><em>Optional</em>: the user toggles on the “Available Stock” button.</td></tr><tr><td>38</td><td>The button changes its color from grey to pink and screen icon appears on the far right of every line item.<br><img src="../.gitbook/assets/image (172).png" alt=""></td></tr><tr><td>39</td><td>The user selects the icon for any of the line items (this selection has to be done line item by line item as and when needed).</td></tr><tr><td>40</td><td>A pop-up window appears and after selecting any country to which the user has access, the stock levels in that country will be displayed separately for each medical distribution centre where stocks are available. Note that this application is purely for information purposes, users do not have the choice of deciding which medical distribution they are supplied from but can discuss options with the Customer Service Desks at the logistics department. The window can be closed by clicking on the small “x” in the upper right corner of the pop-up window.<br><img src="../.gitbook/assets/image (173).png" alt=""></td></tr><tr><td>41</td><td><p>The table displays the details of each item included in the DHIS2 stock item list: item code, item description, unit price, Sec. packaging quantity, Imprest Level, Stock on Hand and Stock on Order. The application automatically calculates the “CALCULATED ORDER QUANTITY” in the following way:</p><p>“IMPREST LEVEL” – “STOCK ON HAND” – “STOCK ON ORDER”.</p><p>Positive calculation results are displayed as positive integers and any negative values are replaced by zero (as stock levels are too high and no stock replenishment is needed). This quantity is then rounded up (but never rounded down) to the next multiple of the “PACK SIZE” (secondary packaging quantity) and displayed in the “ROUNDED ORDER QUANTITY” column which cannot be edited. The identical quantity is displayed in the “CONFIRMED ORDER QUANTITY” column by default but can be freely edited.</p></td></tr><tr><td>42</td><td>The user reviews the "Calculated order quantity" for each item one by one and, if necessary, modifies the "Confirmed order quantity" either by using the “-“ and “+” buttons or by typing the required quantity into the field. <em>It is not possible to “delete” line items, but they will automatically removed if the “CONFIRMED ORDER QUANTITY” is set to zero.</em><br><img src="../.gitbook/assets/image (174).png" alt=""></td></tr><tr><td>43</td><td>In case the “CONFIRMED ORDER QUANTITY” is edited and is not a multiple of the “PACK SIZE” a pop-up “should be multiple of [PACK SIZE]” appears as a warning.</td></tr><tr><td>44</td><td>The user then needs to increase (or decrease) the quantity until the warning disappears.<br><img src="../.gitbook/assets/image (175).png" alt=""></td></tr><tr><td>45</td><td><em>Optional</em>: at any time, the user selects the “EXPORT” button to generate a record of all values as currently appearing in the user interface. This can be useful to document all values at the time the order was made (note that all values are regularly updated, only current values can be displayed and it is not possible to retrieve values from any previous dates) or for keeping a record of the edited “CONFIRMED ORDER QUANTIES” in case the ordering procedure has to be interrupted. But note that if the order process is interrupted, any edited quantities will be lost and will have to be re-entered again.</td></tr><tr><td>46</td><td>A pop-up window at the bottom of the screen opens displaying the name of the generated CSV-file (comma separated file) which can be opened from the default download folder in Excel by double-clicking on it.<br><img src="../.gitbook/assets/image (176).png" alt=""></td></tr><tr><td>47</td><td>Once the entire stock item list and replenishment calculations have been reviewed, the user selects the “CREATE SR” button at the top right. <em>Note that after selecting the “CREATE SR” button the user is not able to revert back to this user interface and will no longer be able to edit the “CONFIRMED ORDER QUANTITY” fields.</em></td></tr><tr><td>48</td><td>IRIS refers the user to the native “Order Status” user interface but “transfer” all stock items with positive order quantities and their “CONFIRMED ORDER QUANTITY” to the “My Cart” section of the default SR screen. Any SRs which have been prepared with the IRIS Imprest Order application will automatically indicate IRIS-PSM in the “Order Title” and can always be distinguished from other orders.<br><img src="../.gitbook/assets/image (177).png" alt=""></td></tr><tr><td>49</td><td>The user fills in all mandatory fields (appearing in red) and the optional fields (appearing in grey) while the country and Recipient Place are prefilled from previous entries.</td></tr><tr><td>50</td><td>As soon as all mandatory information is completed, the “My Cart” section expands and displays all stock items which indicate a positive “CONFIRMED ORDER QUANTITY”. <em>Note that any item for which the “CONFIRMED ORDER QUANTITY” was zero on the previous application window, are no longer displayed in the list as an order quantity of zero is not meaningful.</em><br><img src="../.gitbook/assets/image (178).png" alt=""></td></tr><tr><td>51</td><td>The user can still freely edit any quantities, delete line items add items as for any other SR. Note that the warning in case the quantity is not a multiple of the “PACK SIZE” applies in the same way as it does for the previous screen. The total value is displayed at the bottom of the screen and instantly updated whenever any change is made.</td></tr><tr><td>52</td><td>After the final revision (if any) a complete SR (Supply Request) with details of the items and the order quantities are displayed.<br><img src="../.gitbook/assets/image (179).png" alt=""></td></tr><tr><td>53</td><td>The user reviews the “Financial Summary” and selects “CONFIRM ORDER” (or “SAVE AS DRAFT”) for processing the SR like any other order. Please refer to the IRIS user guide for further details.</td></tr></tbody></table>

## 8 TABLEAU BUSINESS ANALYTICS APPLICATION

Since the analytics in DHIS2 is limited and does not allow analysis across different data sources, such as DHIS2 and IRIS (JDE), Tableau is a key component of the PSM concept for analysis in general and managing the Imprest Levels in particular.

### 8.1 Introduction

Tableau is the ICRC institutional Business Analytics tool to which all ICRC staff members with an ICT profile have access to through the ICRC home page. Frequently used Tableau workbooks can be marked and managed in a list of favourites.

### 8.2 Pharmacy Stock Management analytics

This Tableau workbook is intended for the data analysis of individual health care facilities, particularly for providing guidance on the revision of Imprest Levels.

**The worksheets in this workbook cover three topics:**

* Analysis of the Imprest Level
* Analysis of Stock on hand
* Analysis of Stock distributed (“Consuption”)

#### **8.2.1 Imprest Level**

This group of worksheets allows analysis of various aspects of the current Imprest Level and its changes over time.

While the actual Imprest Levels used for calculating the monthly replenishment orders in IRIS are entered, changed and managed in the DHIS2 web portal, users are completely free in choosing the actual Imprest Levels they enter or edit. This worksheets provides an analysis of demand of the past months, calculates the ideal Imprest Level based on parameters selected by the user, compares the “target” (ideal) Imprest Level with the current Imprest Level and (where applicable) makes a recommendation for increasing or decreasing the Imprest Level.

#### **8.2.2 Imprest Level parameter settings**

This is the only Tableau workbook, where the user must first set the parameters which determine the Imprest Level separately for each health care facility. In order not to lose the settings, the user can select filter settings and then create a “Custom View” with a name which will store those settings for future uses of the worksheet.

The user needs to select the following parameters:

**Review period / months of demand** The review period is the period after which stock levels are reviewed and stock replenishment orders are calculated. For monthly replenishment orders, the review period is 1 month, for replenishment orders made every three months, the review period is 3 etc.

Users have a choice between 1, 2 or 3 months.

**Replenishment lead time / months of demand** The replenishment lead time is the delay (in months) from placing a validated order in IRIS until delivery of the ordered health care goods at the health care facility. Since a small number of items will always have a very long lead time, in practice the time period within which 95% of the ordered items should be chosen. The following two worksheets provide an objective analysis for selecting the replenishment lead time (see below).

Users have a choice between 1, 2 or 3 months.

**Buffer stocks / months of demand** This parameter selects the buffer stock levels which are needed to hedge against uncertainty (unexpected increase) of demand as well as uncertainty of supply (longer replenishment lead time than anticipated and set in the replenishment lead time parameter).

Users have a choice between 1, 2, 3, 4, 5 or 6 months.

**Demand period / months** This parameter allows users to select the number of historic demand which is used for calculating average demand. Tableau will always use the aggregated demand of complete months. For example, if the calculations are made on July first and the user selects “6” for the data period, Tableau will calculate the average demand from the first day of January until the last day of June.

Shorter periods, such as 3 months, are more reactive to changes but increase demand distortion while longer periods, such as 6 months, are less reactive to changes but will lead to more stable stock management.

Users have a choice between 1 and 12 months (in increments of one month).

**Imprest Level calculation**

Once the user has selected these four parameters, Tableau will make the following calculations.

#### **8.2.3 Imprest Level calculations**

The worksheet will be default display the stock item list (as configured in DHIS2) for the selected health care facility. Based on the four parameters selected by the user as well as the data from the selected health care facility “Recipient Place Name”, Tableau will instantly update the following calculations:

**GLOBAL-item** This column indicates “GLOBAL” items which are available to all ICRC health programmes and should be preferred while the “non-GLOBAL” items are only available in certain countries or for certain health programmes and should, as far as possible, be replaced by equivalent “GLOBAL- items”.

**Obsolete / Use up item** “Obsolete” items are no longer available and cannot be ordered or delivered while “Use up” items cannot be ordered by remaining stocks will be delivered until depleted.

Items with either of these two tags should be immediately replaced by equivalent “GLOBAL” items.

**Sec UM Desc. 2** This column indicates the secondary packaging quantity which is the minimal quantity which can be ordered from and delivered by logistics services.

**Stock distributed - Minimum** The minimum monthly quantity which was distributed from the pharmacy during the selected “Demand period / months”.

**Stock distributed - Average** The average monthly quantity which was distributed from the pharmacy during the selected “Demand period / months”.

**Stock distributed - Maximum** The maximum monthly quantity which was distributed from the pharmacy during the selected “Demand period / months”.

**Stock distributed - Total** The total monthly quantity which was distributed from the pharmacy during the selected “Demand period / months”.

**Stock distributed – Coefficient of Variation** The Coefficient of Variation (a measure for the variability of monthly demand) of monthly quantities which were distributed from the pharmacy during the selected “Demand period / months”.

**Max. Imprest Level - Current** The current Imprest Level as set in the DHIS2 database. Please note that the “Max.” is a purely technical artefact related to Tableau.

**Imprest Level - Calculated** The ideal Imprest Level is calculated by multiplying “Stock distributed – Average” (the average demand during the “Demand period / months” selected by the user) with the sum of the “Review period / months of demand” + “Replenishment lead time / months of demand” + “Buffer stocks / months of demand”.

Although the mathematical calculation is correct, changing the “Max. Imprest Level – Current” to the “Imprest Level – Calculated” is not ideal as big changes of the Imprest Level inevitably cause demand distortion and make accurate planning at medical distribution centres impossible.

**Imprest Level – Ideal** Based on the “Imprest Level – Calculated” Tableau uses the following calculations to obtain the “Imprest level – Ideal”:

If the “Max. Imprest Level – Current” is lower than the “Imprest Level – Calculated” then Tableau recommends to immediately increase the Imprest Level in DHIS2 to the “Imprest Level

* Ideal” (which is identical with the “Imprest Level – Calculated”). With other words, increases of the Imprest Level need to be effected immediately, ideally every month, as otherwise shortages and stockouts will be inevitable, even if this sudden increase causes an upstream demand shock.

If the “Max. Imprest Level – Current” is higher than the “Imprest Level – Calculated” then Tableau recommends reducing the Imprest level only if the difference is more than 20% of the Imprest Level and only by 20% of the difference. If the Imprest Level is still too high during the next review, then the Imprest Level should be again be decreased by (only) 20% of the difference. This system leads to gradual decrease which greatly decreases the upstream demand shocks in the supply chain.

```
This is the Imprest Level that should be ideally set in the DHIS2 web portal.
```

**Imprest Level – Relation current to ideal** This column indicates whether the “Max. Imprest Level – Current” is “LOWER” than the “Imprest Level – Ideal” which means the Imprest Level should be increased immediately, “<=20% DIFF.” which means that the Imprest Level should not be changed “>20% DIFF.” which means that should be decreased but only by 20% of the difference between the “Max. Imprest Level – Current” and the “Imprest Level – Calculated”.

**Imprest Level - Correction** The last column (on the right) categorizes the Imprest Level changes into three groups:

* **INCREASE**: the Imprest Level in the DHIS2 web portal should be increased to the “Imprest Level – Ideal” immediately
* **DECREASE**: the Imprest Level in the DHIS2 web portal should be decreased to the “Imprest Level – ideal” during the next Imprest Level review
* **NO CHANGE**: the Imprest Level in the DHIS2 web portal does not need to be changed (because it is exactly correct or because the difference between the “Imprest Level – Calculated” and the “Imprest Level – Ideal” is less than 20%.

#### **8.2.4 Other Imprest Level analysis**

The other Imprest Level analysis worksheet allow only historic analysis of the Imprest Level.

**Picking lead time** The order picking lead time is the delay between the validation of an order (“Sales Order”) and picking (and packing) of the item in the medical distribution centre and is measured in months. Since some items, particularly non-stock items, will always have (very) long lead times, the time for receiving 95% of the line items is usually a good benchmark.

**Delivery lead time** The delivery lead time is the delay between the validation of an order (“Sales Order”) and confirmation of delivery at the health care facility by the customer through the “Goods Confirmation” application in IRIS. Deliveries can be delayed by security problems and false long lead times may be caused by delayed goods confirmation in IRIS. Therefore, the delivery lead time should be compared with the order picking lead time.

**Imprest Level changes / chart** This worksheet presents a simple bar chart indicating the number of items for which the Imprest Level needs to be increased (immediately), be decreased or which require no change. Note that the parameter settings (review period, replenishment lead time etc.) are linked with the “Imprest Level analysis” worksheet.

**Imprest Level / MY** This worksheet simply provides a historical overview of the Imprest Levels as registered in the DHIS2 web portal for analysis of the frequency of changes and changes of the Imprest Levels as such.

**Imprest Level changes / ABS / MY** This worksheet shows only the difference between Imprest Levels compared to the previous month.

**Imprest Level changes / MY** This worksheet displays the items for which, compared to the previous month, the Imprest Level was increased, decreased or remaining unchanged.

#### **8.2.5 Stock on hand analysis**

The second group of worksheets allows various analysis of the stock on hand.

**Stock on hand / MY** This worksheet displays the Stock on hand as reported by the health care facility (usually aat the end of the month) for the selected months

**Stock on hand analysis** The worksheet displays the minimum, maximum and average demand as well as the coefficient of variation of Stock on hand as a measure of variability of Stock on hand.

**Stockouts** The worksheet displays the stock item list for the selected reporting period and indicates whether currently there is any stock (that is a quantity of at least 1 on hand) or the item is out of stock. The list can be filtered for “STOCKOUT” for further analysis.

**Stock availability / MY** This bar chart displays the percentage of items which were in stock and out of stock during the respective reporting period.

**Coverage time** The stock coverage time is the time period (measured in months) that the current stock on hand would last if demand does not changed and if no stock is resupplied. It is indicated for the Stock on hand of the current month but the number of months which are used for calculating the average demand can be selected by the user. The result is displayed as an absolute value (in months) as well as assigned to the respective month/year bin.

**Coverage time chart** The stock coverage time is displayed as the number of items which fall in each of the respective month / year bins. Ideally this chart should represent a normal distribution with a sharp peak at about 3 months and very few items with lower and very few items with higher stock coverage time.

**Stock value / MY** For each of the stock items and for each reporting period, the Stock on hand (quantity) is multiplied with the unit value in CHF to calculated the stock value of each item.

**Stock value / Pareto** For any of the selected reporting periods, the unit cost and value of the stock of the item is displayed. This list can be sorted by “Stock on hand value” for displaying items representing the highest stock value on top.

#### **8.2.6 Stock distributed analysis**

The third, and last, group allows analysis of the quantities which are distributed from the (central) pharmacy to all wards and services during every of the selected reporting periods.

**Stock distributed / MY** This worksheet displays the total monthly quantities distributed for the selected reporting periods in chronological order.

**Non-zero demand / MY** The worksheet displays whether the demand for the respective item was zero or non-zero (irrespective of the quantity) during the reporting period. This worksheet allows identifying items without any demand for prolonged periods of time and which should therefore no longer be stocked.

**Non-zero demand count** The worksheet counts the number of months for which demand was non-zero during the reporting period. Items with low counts should be reviewed for determining whether they still need to be stocked.

**Stock distributed analysis** The worksheet displays and compares the total distributed quantity, the minimum, average, maximum, standard deviation, coefficient of variation (as a measure for demand variability) as well as the number of months with zero demand.

**Stock distributed / CoV chart** This bar chart displays the number of items in each of the coefficient of variation bin in increments of 0.1. Any item with a coefficient of variation of more than 1 has erratic demand which should be investigated for reasons and possibilities for reducing the variability.

### 8.3 Health – DHIS2 Pharmacy Stock Management meta-analytics

This workbook is very similar to the “Health – DHIS2 Pharmacy Stock Management analytics” workbook but allows analysis across several health care facilities for example hospitals, clinics are all health care facilities in a country.

#### **8.3.1 Imprest Level analysis**

**Imprest Level assessment** This worksheet displays the number of items for which the Imprest Level needs to be increased, decreased or does not require any change assuming that all selected health care facilities apply the same parameters.

**Stock item list alignment** The worksheet allows comparing the items selected for each stock item list across health care facilities in order to align them. The more similar stock item lists in a country are, the larger the monthly quantities ordered are and the easier the quantities are to forecast and provide on item while items used by a single health care facility will display very high demand variability and be difficult to supply reliably.

#### **8.3.2 Stock on hand analysis**

**Stock on hand** The comparison of Stock on hand across health care facilities allows identifying shortages, overstocks as well as options for redistributing excess stocks to facilities with shortages or stockouts.

**Stockouts** This worksheet is similar to the previous one but indicates stockouts with red squares and items which are in stock in green.

**Stock availability / MY chart** The worksheet displays the percentage of items in stock and the percentage of stockouts for the selected reporting periods over time.

**Stock availability / MY line chart** For the selected health care facilities the number and percentage of items in stock and with stockouts are displayed as a line chart which allows identifying trends.

**Coverage time chart** The worksheet displays the number of items in each stock coverage time bin as bar chart across the selected health care facilities.

**Stock value** For each item the unit cost and the total stock value is displayed across health care facilities.

#### **8.3.3 Stock distributed analysis**

The third, and last, group provides analysis of the monthly distributed quantities across the selected health care facilities.

**Stock distributed** The worksheet displays the total quantities distributed at each health care facility for selected reporting period(s)

**Non-zero demand / RPsx** For the selected reporting period, the worksheet indicates whether the respective item had any demand or not. Any items which have no demand across a large number of health care facilities in a country for a few months should be reviewed whether they are still required.

**Stock distributed / CoV chart** The variability of monthly distributed stocks is displayed as number of items in each coefficient of variation bin and allows comparison across the selected health care facilities. Any items with a coefficient of variation of more than 1 must be considered as erratic and should be studied for decreasing its variability.

#### **8.3.4 Monthly report**

The “DHIS2 monthly report” worksheet displays all data for the current month for all selected health care facilities which may be useful for regular reporting to authorities and other stakeholders. The reporting period is set to the previous calendar month so that reports always include a complete record of all transactions for the respective month.

Tableau allows any use to configure a “subscription” which will email automatically generated reports at pre-set intervals (weekly, monthly etc.) to any number of indicated emails (but only to ICRC staff members).

### 8.4 Health – DHIS2 Real-Time Stock Management

The analysis of the Real-Time Stock management system (“Advanced mode”) requires a separate Tableau workbook because the DHIS2 mobile application uses a “Tracker Program” and the data is stored in a separate Tableau data source with a different data model and data structure.

#### 8.4.1 Imprest Level analysis

**Imprest Level analysis time** The Imprest Level analysis worksheet is in principle identical with the worksheet for the “Basic mode”. However, because of constraints on the data model, only the average demand, current Imprest Level and ideal Imprest Level can be displayed.

Increases should be effected immediately while the user should only gradually reduce Imprest Levels which are too high.

**Picking lead time** The worksheet is identical with the worksheet for the “Basic mode”.

**Delivery lead time** The worksheet is identical with the worksheet for the “Basic mode”.

#### 8.4.2 Transaction analysis

This group allows analysis of the various aspects of the individual stock transactions.

**E-stock card / item** The electronic stock card contains all the information traditionally recorded on a paper stock card. Stock items are listed in alphabetical order and filters can be set for selecting individual stock cards. For each item all transactions are listed in chronological order with the transaction quantity indicated in the respective “Stock received”, “Stock distributed” column etc. and finally the resulting stock balance.

**Distributions / MY** The worksheet indicates the total quantities of each item distributed for the selected reporting periods (months).

**Distributions / Day** The worksheet displays the distributions for every day and separately by “Deliver to” destination.

**Distributions / Day / Deliver to** The worksheets display the distributions in a table with a separate column for each “Deliver to” destination.

**Distributions / Chronology / Deliver to** The worksheet displays all the distributions in chronological order with their exact transactions dates and with a separate column for each “Deliver to” destination.

**Distributions / MY / Deliver to** The worksheet displays the total quantity distributed to each “Deliver to” destination in a separate column for the selected reporting period (month).

**Discarded / Chronology** The worksheet displays a complete record of all “Discarded” transactions in chronological order.

**Correction / Chronology** The worksheet displays a complete record of all “Correction” transactions in chronological order.

**Stock receipts / Chronology** The worksheet displays the total quantities received by day for each item.

**Stock receipts / MY** The worksheet displays the total quantity received for each item by month for the selected reporting periods (months)

**Transactions / Chart** This bar chart displays the number of the different transaction types indicated with different colours in chronological order.

#### 8.4.3 Stock on hand analysis

**Stock on hand / Chronology** This worksheet displays the changes of stock on hand for each item in chronological oder.

**Stock on hand / MY** The worksheet displays the last stock on hand quantity of each month for each item. For technical reasons, cells are blank if no transaction of that item took place during the respective month. In these cases the stock on hand is identical with the stock on hand of the previous month.

#### **8.3.4 Monthly report**

This worksheet lists all transactions for all health care facilities and all items in chronological orders with separate columns for the “Deliver to” destination and is intended for reporting to authorities or other stakeholders. The reporting period is set to the previous calendar month so that reports always include a complete record of all transactions for the respective month.

This dashboard allows storekeepers at any health care facility supplied by an ICRC medical distribution centre to view a complete list of all batches and expiry dates which they currently have in stock without having to carry out any physical stock checks.

This claim seems counterintuitive if not absurd but imagine the following situation: you are standing at the entrance door of a room and record the names of people and the order in which they enter that room. Let’s assume that the people leave the room in the same order through another exit which you cannot observe. Now if somebody tells you exactly how many people are still in the room you can just check your list find the name of the last person that entered, the person who entered before etc. until you reach the number of people you were given and can reproduce a list of names of people who are in the room at any time with absolute certainty without ever looking inside the room or observing the people leaving the room.

The batch analysis is based on the same idea but is only correct under the following conditions which are usually easy to meet:

* All stocks were delivered from an ICRC medical distribution centre and are recorded in JDE
* Any batch delivered by the medical distribution centre has a longer remaining shelf life than all other batches ever delivered (remaining shelf life of all batches calculated relative to the same date)
* All storekeepers strictly adhere to the FEFO principle for all items at all times and without exceptions and no mistakes are made
* All data on items, batch numbers, expiry dates and quantities in JDE and the stock on hand record in DHIS2 are correct

If FEFO is mistakenly (and exceptionally) not applied for one distribution, then the mistake will “autocorrect” as soon as the expiry date of the batch which was distributed “prematurely” becomes the batch with the shortest remaining shelf life. In the worst case that by mistake the batch with the longest remaining shelf life was distributed, the automatic calculations in Tableau will only “autocorrect” once the entire stock which was on the shelf when the mistake was made is distributed but remain correct from there on.

If exceptionally the ICRC medical distribution does occasionally deliver a batch with a remaining shelf life shorter than previously delivered batches, the mistake will also autocorrect once that batch has physically been distributed.

In case two different batches of the same item happen to have the same expiry date, Tableau will not be able to identify which of the batches has been distributed first but the calculations on the remaining shelf, which are the critical issue, will still be correct.

As this calculation, although not complicated, is a mind teaser an example of the Tableau calculation is given:

Three different batches of hydralazine with three different expiry dates were delivered. Tableau orders these by expiry date with the earliest (shortest remaining shelf life) on the top and the latest (longest remaining shelf life) at the bottom. The “Quantity Received” indicates the quantity for which delivery was confirmed with the “Goods confirmation” in IRIS. The column

“Quantity Received – count by item” adds up the total quantity received, in this case 245 ampoules.

The batch P02110 has the longest remaining shelf life and must only be distributed once the other two batches have been completely distributed. Since the stock on hand reported in October 2022 was 90 ampoules, which is greater than 10, the entirety of the delivered quantity must still be on the shelf which is indicated in the last column “Batch N – Remaining SoH by batch”. The quantity of the second batch, namely 20, plus the quantity of the first batch of 10 (30 in total) is still less than the Stock on hand of 90 and therefore the entirety of the second batch must still be on hand and at least part of the third batch must still be available. The ICRC medical distribution centre originally delivered 215 ampoules of the third batch but since the reported Stock on hand is only 90, part of that stock must have already been distributed. Since the stock must be composed of 30 ampoules from the first two batches, this leaves only 60 ampoules for the third batch (P00783) which must be on hand.

The batches which must have already been distributed in their entirety are “hidden” from the view by a filter which ensures that only non-zero “Batch N – Remaining SoH by batch” quantities are displayed. Therefore, by definition, the entire quantities of all but the last batch (with the shortest remaining shelf life) will always be on hand with the same quantity as initially delivered and only the last batch will have a quantity less (or equal) to the delivered quantity.

The last column simple calculates the remaining shelf life in increments of three-month periods with a colour legend. Note that it is not possible to filter the list only for a certain period as the calculations are iterative and must remain visibly on the screen for the Tableau calculations to be correct.

## 9 PHARMACY STOCK MANAGEMENT WITH PSM APPLICATION

This chapter is not intended to define or detail best practices for pharmacy stock management at ICRC hospitals in general or policies established by the ICRC Health Unit but merely to explain the workflows and context in which the tool is intended to be used. The guidelines focus on the technical and practical aspects rather than on the project management of obtaining approval and required resources as well as regulatory issues.

While the “Basic mode” will easily apply to the great majority of pharmacies, implementing the “Advanced mode” will require some particular preparations and procedures.

### 9.1 Preparations for implementing the PSM mobile application

Most pharmacies will rely on paper records such as stock cards, batch cards and various register books for managing stocks and stock data. Any health care facility and anybody wanting to implement the use of the PSM system is well advised to consult with and obtain advice from colleagues who have implemented and are successfully using the system already.

* Plan the implementation with the country Health team
* Obtain approval from the Health Coordinator
* Obtain approval from the responsible Health authorities in the country and management of the health care facility
* Establish and sign MoU (Memorandum of Understanding) as well as data protection agreement with the health authorities and management of the health care facility
* Ensure approval for recording and transmitting facility stock data to ICRC managed databases and servers (in Geneva, Switzerland)
* Secure funding for mobile devices (which have to be paid by the Health programmes in the country)
* Inform ICT services of the future use of mobile devices in the respective sites
* Confirm availability of a wireless network or a reliable mobile Internet connection at the health care facility where the PSM system should be implemented
* Confirm availability, sustainability and subscription management for SIM-cards
* Identify qualified users
* Prepare briefings and trainings for users
* Ensure availability of a USB data cable, dual USB/mini-USB-key or confirm that apk-files can be transferred from the ICRC network to the mobile device wirelessly or in other ways
* Confirm availability of a backup system in case of (temporary) technical failure of the PSM

#### **9.1.1 Providing and setting up mobile devices**

Every health care facility should have at least one tablet PCs available which is dedicated for use by storekeepers or other digital applications in the same facility and, ideally, a second backup device which may be shared among several facilities.

Private devices should not be used as this poses data security risks and leads to arguments about payment for the Internet connection. Details on the specifications for recommended devices are given in chapter 2.2.

#### **9.1.2 Obtaining user access**

At every health care facility, at least the (main) pharmacist or storekeeper and another person replacing her/him in case of absence should have full access to the mobile device and the application. Other staff supervising pharmacists or storekeepers should also have access in order to be able to provide advice and training as well as understand any problems which may occur. Staff members can but do not have to be ICRC employees.

The ICRC staff member responsible for providing assistance to the health care facility should provide details of the implementation to the ICRC ServiceDesk by email:

* List of exact names and functions
* User role of each user
* Email address and mobile phone number of each user

Depending on the authentication method an email address and/or mobile phone number are needed for the Microsoft Authenticator which is mandatory for accessing the Pharmacy Stock Management mobile application.

#### **9.1.3 Adding health care facility to DHIS2**

Only health care facilities which use the PSM mobile application are configured in the DHIS2 and therefore any additional health care facility which intends to implement the system must be configured by the ICT ServiceDesk. The ICRC staff member responsible for providing assistance to the health care facility should provide the following details to the ICT ServiceDesk:

* Country of implementation
* Exact “Recipient Place Name”
* Exact and unique “RP code” which can both be found in the “Location Manager” database:

[https://gis.ext.icrc.org/geoportal/apps/locationmanager/](https://gis.ext.icrc.org/geoportal/apps/locationmanager/)

Since some health care facilities may have several similar but different names, it is important to adhere to the exact “Location Manager” conventions as the DHIS2 data is integrated with IRIS/JDE and the “RP Code” is used as the unique attribute which “links” both systems correctly. Otherwise, data from JDE on backorders and DHIS2 data cannot be correctly displayed in the “Imprest Order” application in IRIS and the SRs/SOs will not be correctly linked to the correct health care facility in the logistics management information system (JDE).

#### **9.1.4 Setting up stock item list in DHIS2 ICRC Health Unit 6 Pharmacy Stock Management application**

For the PSM system and stock replenishment orders to work correctly, every health care facility must manage a single, central stock for the entire health care facility.

In most cases, a stock item list which details all the items which are permanently maintained in the pharmacy and are regularly replenished will already be available but in case assistance to a new health care facility is just being established, a stock item list needs to be established.

It is critical to only include item codes and item descriptions which are listed in the IRIS catalogue

[https://iris.ext.icrc.org/ls/cp/item-search ](https://iris.ext.icrc.org/ls/cp/item-search)

since otherwise the integration between the DHIS2 database and the Imprest Order application in IRIS will not work correctly.

The ICRC staff member responsible for providing assistance to the health care facility should provide a complete list of item codes and their item descriptions to the ICT ServiceDesk with the request to configure the stock item list in DHIS2. In case of doubt or questions, the Medical Planners should be asked for advice on available items and suitable substitutes. Note that the ICT ServiceDesk is only in charge of adding correct and available items to the DHIS2 database but will not verify the suitability of items or correctness of their details.

Ideally, the ICT ServiceDesk should also be provided at least six months of historical monthly demand data for uploading into DHIS2 which can be used for reviewing and analysing Imprest Levels in Tableau.

#### **9.1.5 Setting up and managing Imprest Levels in DHIS2**

The Imprest Levels need to be entered into DHIS2 through the web portal both for the “Basic mode” and the “Advanced mode” and be managed by the users in the field.

As soon as the user who is responsible for setting up and managing the PSM system has access to the DHIS2 database, s/he can (and has to) access the Data Entry form in DHIS2 and enter the Imprest Levels for each item one by one. This entry is needed only one-off when the system is being set up and all Imprest Level values are automatically carried forward to the next month on the last day of the previous month.

Ideally, if at least six months of historical demand data were shared with and uploaded by the ICT ServiceDesk, the user can compare the entered Imprest Levels with the ideal Imprest Levels calculated by Tableau and, if necessary, revise them.

The Imprest Levels of all items should be reviewed every month after the monthly demand has been updated. Any Imprest Levels which are indicated as “INCREASE” in Tableau, should be increased immediately as otherwise shortages and stockouts are inevitable.

A complete review and revision of the Imprest Levels which require (gradual) decrease can be carried out every three months or every six months. In practice, significant risks of expiry of stock will only occur if items are overstocked and stock levels exceed the Imprest Level which will anyway not prompt any replenishment order. Limiting the review and revision of all Imprest Levels to only every three to six months will significantly reduce upstream demand distortion which makes forecasting and demand planning more difficult.

#### **9.1.6 Uploading initial stock - Advanced mode real time stock management**

While for the “Basic mode” (monthly reporting) storekeepers will enter the stock on hand (and monthly demand) on the mobile device during the monthly physical stock count, for the “Advanced mode” (real-time stock management) the initial stock can only be configured by the ICT ServiceDesk. Technically, the database starts with a Stock on hand of zero for all items and the initial stock is recorded in DHIS2 as a stock receipt to raise the Stock on hand to the current stock levels.

### 9.2 Basic mode

The PSM “Basic mode” maintains the monthly reporting of stock data, usually at the end of the month, but replaces paper records with digital records.

#### **9.2.1 Pharmacy setup**

In principle no specific preparations are needed as using the PSM mobile application only changes the means of recording, storing and sharing stock data.

However, all medical stocks should be physically ordered on shelves and floor pallets according to their item groups (such as drugs, dressing material etc.) and within in alphabetical order according to their item codes. Ideally, within item groups, items would be arranged alphabetically by their names but DHIS2 will only allow sorting by item codes.

In order to prepare for and facilitate the transition to the “Advanced mode”, standardized storage bins can already be set up, at least for the first batch according to FEFO/FIFO. This allows to anticipate the main change for implementing the “Advanced mode” which then only requires attaching labels with barcodes and item details.

In principle, the implementation of the digital stock reporting will replace stock cards but not the batch cards which still have to be maintained.

#### **9.2.2 Monthly stock reporting**

At the end of the month, the storekeeper will physically count the quantity of every item on the shelf and record the current stock balance in the PSM application.

The quantity of stock which was distributed during the month has to be tallied up from the bin card before being able to record it in the second column of the PSM application.

As soon as the physical stock count and data recording is completed, the local database on the mobile device should be synchronized with the central DHIS2 server in Geneva as quickly as possible.

Ideally, the monthly physical stock count should be carried out after all wards and services have received their last deliveries for that month. This ensures that the pharmacy stock replenishment is done when the stock levels are at their lowest point during the month and therefore (at a given Imprest Level) maximize the stock replenishment quantities.

As for the ICRC (logistics) in general all quantities of all health care goods must be exclusively counted, recorded and reported in units of measure (UoM) of "EA" (Each) and never in any packaging quantities. "EACH" refers to the smallest usable unit of a health care product such as one tablet, one syringe, one disposable glove or one pair (!) of sterile gloves (as these must always be used in pairs). In exceptional cases where the packaging quantity (such as "kit of 100 tests") is indicated in the item description, "EACH" refers to one kit (and not one test) as such products do not contain separate diagnostic tests but are an actual kit with bottles of liquids and other components sufficient for the indicated number of tests but cannot be “split”.

If pharmacies dispense to patients or pre-pack drug products in medicine bags, a maximum of a single secondary packaging should be kept at the dispensing workplace. Any stock should be reported in PSM as “distributed” as soon as containers are taken off the shelf and moved to the dispensing area. Therefore, opened packaging in the dispensing area is not considered in the PSM stock anymore and does not need to be counted at the end of the month.

### 9.3 Advanced mode

In the “Advanced mode” (real-time stock management system), storekeepers record each stock transaction (distributions, discard and correction) by first scanning a barcode and then entering the transaction quantity. Stock receipts are automatically added to the current stock

when the “Goods Confirmation” is effected in IRIS. For all of these transactions, the PSM mobile app will instantly update the current Stock on hand balance.

Using the “Advanced mode” requires a high level of discipline since the DHIS2 PSM application automatically recalculates the remaining stock balance after every transaction and any mistakes become evident immediately.

#### **9.3.1 Pharmacy setup**

As for the “Basic mode” all stocks should be arranged in alphabetical order of their item groups and by item codes. The first batch of each item should be placed in a bin (“active bin”) according to FEFO/FIFO. Any other batches which are not received in the tertiary supplier packaging should also be placed in separate bins while any health care goods delivered in tertiary supplier packaging should not be opened but placed on the shelf in the order of expiry dates. When the “active bin” is emptied, stock from the next batch can be placed in that bin for the next distribution.

In order to avoid having to scroll down a long list for finding an item, all “active” bins (first bin of each item only) should be fitted with barcodes which are clipped to the bin with a strong paperclip. The labels must not be pasted on the bins as otherwise a large number of bins without stock will accumulate which require a lot of storage space and it is much easier to just swap the barcode labels. The labels must also not be pasted on the shelves as the storage volumes fluctuate and it is much easier to change the location of bins with their labels.

#### **9.3.2 Generating barcode labels for stock**

Barcode labels can be very simply printed from Excel on any computer provided that the “LibreBarcode39” font is installed:

* close all Microsoft Excel files
* copy the LibreBarcode39-Regular.ttf file to your computer
* in the Windows Explorer right-click on the file: a pop-up window opens
* select “install”: a pop-up window opens
* select: “Yes”: the font installs on the computer
* Open the Excel file for printing barcode labels: any copied Excel file with the font set to barcodes will now display barcodes
* Highlight any (additional) fields which should display barcodes
* Click in the drop-down window with the fonts
* Scroll down to the list of available fonts to the letter L which will appear as a barcode and display “Libre Barcode 39” when mousing over
* Select “Libre Barcode 39”: the drop-down window closes and the text appears as barcodes

The “PSM barcode label template” Excel file contains three worksheets “A Item catalogue”: this worksheet contains a list of all the stock items used in the respective pharmacy. The user tags the items for which a label is required by typing “X” next to the item in column B.

“B Label selection”: this worksheet uses a lookup function to display only the items selected from the worksheet.

“C Label print”: this worksheet correctly formats the item code, barcode and item description on four labels per page if printed in landscape which can be printed on any printer.

#### **9.3.3 Stock receipts**

The person responsible for acknowledging receipt of consignments received from ICRC medical distribution centres will continue to effect the “Goods Confirmation” in the IRIS application and an automatic routine running in the background will add the quantities of all items indicated in the packing list to the stock on hand in the PSM mobile application.

If the mobile device is working in off-line mode, the user must synchronize the local database with the central DHIS2 server for the stock on hand to be updated.

In case of any discrepancies between the “Goods Confirmation” record (and the packing list) and the physically received consignments, the Medical Planner should be contacted for either arranging delivery of the shortshipped items and quantities or correcting the record in JDE. Either way, the corrected stock receipt quantities (all items and quantities in status 999) will update in the DHIS2 database. If excess stock was delivered, the logistics services can simply issue a packing list for the missing quantities which are again acknowledged with the IRIS “Goods Confirmation” application and will correct the record.

#### **9.3.4 Recording distributions**

Storekeepers will usually receive a list of items required for each ward or service once a day, weekly or according to another established schedule.

The storekeeper will locate the first item on the list in the pharmacy, scan the barcode for selecting the correct item from the stock item list and type or dictate the picked quantity and then move on to pick the next item. This method is the fastest option and since a single row is displayed as a result of the search, the storekeeper cannot accidentally enter the value into the wrong row (for the wrong item).

Alternatively, the storekeeper can scroll down the list until s/he finds the item or enter the required item in the search window. Once all items in the required quantity have been picked, the storekeeper will confirm the transaction and deliver the goods to the requester before starting treatment of the next request.

Negative balances are deliberately blocked by the DHIS2 PSM mobile application to force storekeepers to effect corrections immediately since if delaying them would be allowed, stock discrepancies occurring by “postponed” corrections would inevitably accumulate. Therefore, if the remaining quantity on the shelf is greater than indicated as Stock on hand on the mobile device, the storekeeper can only pick the available quantity. After completing the transaction, a stock correction needs to be made and then in a second transaction the now available quantities can be picked. Creating two separate transactions for the same ward or service will not make any difference for overall stock management and calculations. Alternatively, the storekeeper can interrupt the transaction but will lose all recorded data, then make the stock transaction and start the initially intended transaction from scratch.

In case during the order picking mistakes were made, they cannot be corrected after confirming the transaction. If the recorded quantity is less than the actually picked quantity, the mistake can be simply corrected by effecting another transaction. If the recorded quantity is larger than picked (and needed) then either the “excess” quantity is delivered to the ward or service, kept aside to be included in the next distribution (without recording) or by creating a “Correction” transaction. The “excess” quantity can also be given to another ward or service without recording. While the total stock on hand is thereby corrected, the statistics on distributions to each ward or service would no longer be correct (and cannot be corrected).

#### **9.3.5 Recording discarded stocks**

Stock which is expired, damaged or unusable for other reasons must be removed from the stock and be displayed in a locked cupboard or room which is dedicated only to stock waiting for disposable. In order to account for reduction of the stock on hand without allocating stocks to any specific ward or service, the storekeeper carries out a “Discard” transaction in the same way as for the “Distribution” transaction.

#### **9.3.6 Recording stock corrections**

Discrepancies between the physically available stock on hand on the shelf and the stock on hand balance calculated in the DHIS2 PSM mobile application may occur for different reasons.

* the quantities physically delivered to the health care facility are greater or less than in the electronic record (and not noted at the time of receipts)
* during order picking either greater or smaller quantities than indicated in the transaction are picked and delivered to wards and services (and not noted)
* stock is mislaid, misplaced in a wrong location, lost or stolen

In all of these cases, storekeepers must effect a “Correction” transaction in the PSM mobile application which will correct the calculated stock on hand. The amount of correction transactions and the quantities are a very good indicator for the overall quality of stock management.

In case “loans” are given to or received from other organizations or health care facilities options are not to create any transaction (as eventually the loan will be “repaid”) or by effecting two stock corrections.

#### **9.3.7 Residual balance counting for stock on hand**

As the stock on hand as well as the transaction quantities are instantly updated in the DHIS2 PSM mobile application, a complete and update record of the current stock on hand is available in the system at any time and in principle no (monthly) physical stock counts are necessary. However, if stocks are never counted, discrepancies will only become apparent if and once negative stocks would occur during a transaction.

There are simple and fast ways for counting and checking the remaining stock on hand in certain situations which will allow detecting any discrepancies. This “residual batch counting” has the big advantage that the items with largest number of stock transactions are counted more often and that discrepancies can, in principle, be detected immediately rather than only at the end of the month

* counting the remaining stock whenever a batch is depleted, and the next batch of an item is placed in the “active bin” (tertiary packaging is often provided in “round” quantities such as multiple of thousands with the quantities indicated on the tertiary packaging)
* just before opening any tertiary packaging, checking whether the remaining stock on hand is a “round” quantity (even without actually counting the entire remaining stock.
* Physically counting the remaining stock on hand for small quantities of items which can be effected quickly

### 9.4 Changing from the “Basic mode” to the “Advanced mode”

but requires some planning, preparation, precision and diligence. The “Imprest Levels” as entered and updated for the “Basic mode” will also apply to the “Advanced mode” and in principle no changes are required.

_**The “Basic mode” and “Advanced mode” must never be used at the same health care facility at the same time.**_ At any given time, all users must either use only the “Basic mode” or all users must use only the “Advanced mode” since otherwise the DHIS2 integration with IRIS will not be correct.

Once the pharmacy set-up is completed with the bins and barcode labels and staff have been trained the ideal time for a “switch over” is the end of the month.

* Contact the ICT ServiceDesk inform them of the planned transition and agree on a precise date
* Confirm to the ICT ServiceDesk that the stock item list from the “Basic mode” can also be used for the “Advanced mode” (as the list will have to be set up in a “Tracker Program”
* Confirm the names and user roles of all users to the ICT ServiceDesk (as these have to be changed from the “Basic mode” to the “Advanced mode”).
* Carry out a complete physical stock count at the end of the month in record the stock balances in the “Basic mode” as usual
* Share the results of the final stock count with the ICT ServiceDesk (which will have to “load” these stocks one-off as stock receipts to prime the system)
* Install the PSM “Advanced mode” mobile application
* Wait until the reported stock on hand has been “loaded” into the “Advanced mode” application by the ICT ServiceDesk
* Start using the “Advanced mode” for all transactions
* Use the “Advanced mode” Tableau dashboards for managing Imprest Levels and analytics.

### 9.5 Backup plan in case of system failure

Any digital systems can fail at any level: the mobile device at the health care facility, the Internet connection can fail for prolonged periods and central servers and databases can fail.

In order to ensure continuity of services while at the same time keeping a record of any transactions which could not be reported in DHIS2, a backup system needs to be in place from the beginning.

The simplest way is to continue or resume the use of stock cards for any transactions which cannot be reported in DHIS2.

For the “Basic mode” the stock on hand at the end of the monthly and the monthly demand can be entered retrospectively at any time although this will require the ICT ServiceDesk to temporarily increase the five-day deadline for entering stock data for the previous month.

For the “Advanced mode”, the quantities distributed to each ward or service and be tallied up and entered with a single transaction for each ward or service once the system is restored. This will falsify the transaction dates but still maintain an accurate record of the total quantities distributed to each ward or service. In case of prolonged system failure, temporarily switching back to the “Basic mode” which requires less documentation and reporting can be considered.
