# Introduction

## Overview

The PSM project provides a web and mobile app-based tool (with off-line capability), real-time digital solution for stock and order management as well as detailed business analytics at and for assisted health care facilities. It is fully integrated with the ICRC ICT environment (IRIS and Tableau Business Analytics) and provides global, real-time stock and data visibility to all pharmacy staff as well as ICRC Health programme managers, logistics services and general management with access from any computer or mobile device connected to the ICRC network anywhere in the world.&#x20;

Staff at ICRC assisted health care facilities replaces data collection on paper or with spreadsheet applications by recording data directly on mobile devices on-line (with off-line capability) using a dedicated mobile device application specifically adapted to the Imprest System. And Health staff will no longer have to re-enter data provided by pharmacies into Excel files (or any other application) for calculating monthly replenishment orders.&#x20;

The current, paper- (or spreadsheet) based, workflow for replenishing pharmacies at assisted health care facilities is replaced by a fully digital, integrated and systematic workflow which is standardized across all assisted health care facilities in the ICRC using the Imprest System. Health program managers can manage and control Imprest Levels at the item level for each facility without any other users having access and being able to modify replenishment calculations.&#x20;

A dedicated IRIS Imprest Order management application will access pharmacy data as well as data from JDE (stock on order) for correctly calculating monthly orders based on the Imprest System and placing orders directly in IRIS (JDE front-end, user interface for the ICRC Logistics Information System) like any other order.&#x20;

Health and management staff at all levels will have access to all data from assisted health care facilities through the ICRC Business Analytics application (Tableau) and be able to visualize and analyse data of individual or across several health care facilities.&#x20;

For health care facilities using the “Advanced mode”, Health managers, logistics planners and management staff will have access to global, real-time stock and stock management data across all assisted health care facilities as well as a complete history of all data at the level of supplied wards and services within health care facilities.&#x20;

The PSM serves as a mobile data collection tool for recording (entering/changing/managing) logistics data (Imprest Level, Stock on Hand and Stock distributed) at ICRC assisted health care facilities. Data is stored on a DHIS2 server at the ICRC in Geneva and integrated with IRIS for calculating replenishment orders as well as with Tableau for business analytics..

## Purpose of the guide



## Target audience

The application is based on adherence to specific structures and processes which inform the system design and functionality.&#x20;

* All assisted health care facilities are owned and managed by non-ICRC entities such as state authorities, Ministries of Health (MoH), National Red Cross/Red Crescent societies and communities. 1 Overview of the Pharmacy Stock Management application ICRC Health Unit - 9 - Pharmacy Stock Management application&#x20;
* Almost all users at the health care facility are non-ICRC staff and neither have an ICRC ICT profile nor an ICRC email address.&#x20;
* In every health care facility, all medical stocks provided by the ICRC are stored and managed in a single central pharmacy. In addition, other medical stocks donated by other actors may be managed separately inside the same health care facility.&#x20;
* While the system and application is primarily designed for managing health care goods, any other types of goods such as food, cleaning materials, stationery etc. could also be managed.&#x20;
* A single (central) pharmacy supplies all wards and services of the health care facility.&#x20;
* The Imprest System is used in all wards/services and the pharmacy as the sole inventory control system.&#x20;
* For the medical store managing ICRC supplied stocks, a stock item list is clearly defined, maintained and managed by the responsible ICRC programme manager.&#x20;
* The system will replace and facilitate certain current processes, but health care facilities are of course free to continue any additional manual or electronic data recording and processing systems (such as using bin card, stock cards, delivery records, tally sheets etc.), especially if these are required under national guidelines and policies.&#x20;
* All pharmacies have at least daily access to at least a 2G mobile phone network for transmitting and receiving data or (if this is not the case), once a month, the mobile device can be physically taken to an ICRC office with a driving distance of less than one hour for synchronizing data and returning the mobile device to the health care facility.&#x20;
* Health care facilities using the "advanced" mode will require at least a daily network connection to a WLAN or a 3G mobile phone network at the site of the health care facility for synchronizing data.&#x20;
* In case of any part of the system failing, pharmacies must be able to "switch" back to a manual (backup) system at any time without in any way impairing the supply of the pharmacy.&#x20;
* State authorities, health authorities (national, provincial, district level), management of health care facilities as well as pharmacy staff agree to the use of mobile devices for recording, storing, managing and transmitting pharmacy stock data.&#x20;
* For security reasons, no private mobile devices, either or ICRC or non-ICRC staff, must be used. Instead dedicated mobile devices will be provided by the ICRC and made available to non-ICRC staff at health care facilities permanently or temporarily at any time needed for the purposes of managing medical stocks in the facility.&#x20;
* Staff at the health care facility are conversant with the use of mobile devices or can be trained (within reasonable time).

## Key Features

The application is based on adherence to specific structures and processes which inform the system design and functionality.&#x20;

* All assisted health care facilities are owned and managed by non-ICRC entities such as state authorities, Ministries of Health (MoH), National Red Cross/Red Crescent societies and communities. 1 Overview of the Pharmacy Stock Management application ICRC Health Unit - 9 - Pharmacy Stock Management application&#x20;
* Almost all users at the health care facility are non-ICRC staff and neither have an ICRC ICT profile nor an ICRC email address.&#x20;
* In every health care facility, all medical stocks provided by the ICRC are stored and managed in a single central pharmacy. In addition, other medical stocks donated by other actors may be managed separately inside the same health care facility.&#x20;
* While the system and application is primarily designed for managing health care goods, any other types of goods such as food, cleaning materials, stationery etc. could also be managed.&#x20;
* A single (central) pharmacy supplies all wards and services of the health care facility.&#x20;
* The Imprest System is used in all wards/services and the pharmacy as the sole inventory control system.&#x20;
* For the medical store managing ICRC supplied stocks, a stock item list is clearly defined, maintained and managed by the responsible ICRC programme manager.&#x20;
* The system will replace and facilitate certain current processes, but health care facilities are of course free to continue any additional manual or electronic data recording and processing systems (such as using bin card, stock cards, delivery records, tally sheets etc.), especially if these are required under national guidelines and policies.&#x20;
* All pharmacies have at least daily access to at least a 2G mobile phone network for transmitting and receiving data or (if this is not the case), once a month, the mobile device can be physically taken to an ICRC office with a driving distance of less than one hour for synchronizing data and returning the mobile device to the health care facility.&#x20;
* Health care facilities using the "advanced" mode will require at least a daily network connection to a WLAN or a 3G mobile phone network at the site of the health care facility for synchronizing data.&#x20;
* In case of any part of the system failing, pharmacies must be able to "switch" back to a manual (backup) system at any time without in any way impairing the supply of the pharmacy.&#x20;
* State authorities, health authorities (national, provincial, district level), management of health care facilities as well as pharmacy staff agree to the use of mobile devices for recording, storing, managing and transmitting pharmacy stock data.&#x20;
* For security reasons, no private mobile devices, either or ICRC or non-ICRC staff, must be used. Instead dedicated mobile devices will be provided by the ICRC and made available to non-ICRC staff at health care facilities permanently or temporarily at any time needed for the purposes of managing medical stocks in the facility.&#x20;
* Staff at the health care facility are conversant with the use of mobile devices or can be trained (within reasonable time). 1.3 Overview of processes and use cases by user groups The Pharmacy Stock Management (PSM) application has three specific functionalities which are used by different groups of users:&#x20;
* Pharmacy stock management at assisted health care facilities in DHIS2. 1 Overview of the Pharmacy Stock Management application ICRC Health Unit - 10 - Pharmacy Stock Management application&#x20;
* Pharmacy order management in IRIS at ICRC offices and (sub)-Delegations.&#x20;
* Business Analytics in Tableau at health care facilities and ICRC offices and (sub)-Delegations. 1.3.1 Pharmacy stock management in the DHIS2 mobile device application The application is used by storekeepers of medical stores at ICRC assisted health care facilities. In the great majority of cases, these storekeepers are non-ICRC staff members. "Ward" stands for any facility in any health care facility which holds and manages stocks of any kind which are regularly replenished such as patient wards, dispensaries (OPD), operating theatres, sterilization services, laboratory and blood transfusion services, diagnostic imaging or other services. Processes&#x20;
* Monthly physical stock count at the pharmacy.&#x20;
* Receiving and put-away of stocks sent by an ICRC medical warehouse.&#x20;
* Managing stocks.&#x20;
* Receiving, recording and managing periodic orders from wards and services.&#x20;
* Picking, packing and delivering ordered goods to wards and services. Use cases&#x20;
* "Basic mode": digital recording, storage and transmission of (at least monthly) stock data.&#x20;
* "Advanced mode": digital recording and transmission of stock issues to wards in real-time.&#x20;
* Basic business analytics in DHIS2 mobile device application. 1.3.2 Pharmacy order management in IRIS The responsibility for the monthly order lies with ICRC staff (Hospital Administrator, Hospital Project Manager, Programme Manager or other staff assigned by the Health Coordinator) according to the decision of the ICRC Health Coordinator. Processes&#x20;
* Determine, set, review, analyse (in Tableau) and revise Imprest Levels.&#x20;
* Analyse stock data.&#x20;
* In IRIS, review and revise proposed order calculations and place monthly orders ("Supply Request") to ICRC medical distribution centres.&#x20;
* Consult dashboards and other (self-service) analysis in Tableau for management and monitoring the quality of stock and order management. Use cases&#x20;
* Preparing monthly pharmacy orders (revising Imprest Level, order calculation and processing).
