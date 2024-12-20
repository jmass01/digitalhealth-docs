---
description: Pharmacy stock management with PSM APPLICATION
---

# Pharmacy stock management

This chapter is not intended to define or detail best practices for pharmacy stock management at ICRC hospitals in general or policies established by the ICRC Health Unit but merely to explain the workflows and context in which the tool is intended to be used. The guidelines focus on the technical and practical aspects rather than on the project management of obtaining approval and required resources as well as regulatory issues.

While the “Basic mode” will easily apply to the great majority of pharmacies, implementing the “Advanced mode” will require some particular preparations and procedures.

## 1 Preparations for implementing the PSM mobile application

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

### **1.1 Providing and setting up mobile devices**

Every health care facility should have at least one tablet PCs available which is dedicated for use by storekeepers or other digital applications in the same facility and, ideally, a second backup device which may be shared among several facilities.

Private devices should not be used as this poses data security risks and leads to arguments about payment for the Internet connection. Details on the specifications for recommended devices are given in chapter 2.2.

#### **1.1.2 Obtaining user access**

At every health care facility, at least the (main) pharmacist or storekeeper and another person replacing her/him in case of absence should have full access to the mobile device and the application. Other staff supervising pharmacists or storekeepers should also have access in order to be able to provide advice and training as well as understand any problems which may occur. Staff members can but do not have to be ICRC employees.

The ICRC staff member responsible for providing assistance to the health care facility should provide details of the implementation to the ICRC ServiceDesk by email:

* List of exact names and functions
* User role of each user
* Email address and mobile phone number of each user

Depending on the authentication method an email address and/or mobile phone number are needed for the Microsoft Authenticator which is mandatory for accessing the Pharmacy Stock Management mobile application.

#### **1.1.3 Adding health care facility to DHIS2**

Only health care facilities which use the PSM mobile application are configured in the DHIS2 and therefore any additional health care facility which intends to implement the system must be configured by the ICT ServiceDesk. The ICRC staff member responsible for providing assistance to the health care facility should provide the following details to the ICT ServiceDesk:

* Country of implementation
* Exact “Recipient Place Name”
* Exact and unique “RP code” which can both be found in the “Location Manager” database:

[https://gis.ext.icrc.org/geoportal/apps/locationmanager/](https://gis.ext.icrc.org/geoportal/apps/locationmanager/)

Since some health care facilities may have several similar but different names, it is important to adhere to the exact “Location Manager” conventions as the DHIS2 data is integrated with IRIS/JDE and the “RP Code” is used as the unique attribute which “links” both systems correctly. Otherwise, data from JDE on backorders and DHIS2 data cannot be correctly displayed in the “Imprest Order” application in IRIS and the SRs/SOs will not be correctly linked to the correct health care facility in the logistics management information system (JDE).

#### **1.1.4 Setting up stock item list in DHIS2 ICRC Health Unit 6 Pharmacy Stock Management application**

For the PSM system and stock replenishment orders to work correctly, every health care facility must manage a single, central stock for the entire health care facility.

In most cases, a stock item list which details all the items which are permanently maintained in the pharmacy and are regularly replenished will already be available but in case assistance to a new health care facility is just being established, a stock item list needs to be established.

It is critical to only include item codes and item descriptions which are listed in the IRIS catalogue

[https://iris.ext.icrc.org/ls/cp/item-search ](https://iris.ext.icrc.org/ls/cp/item-search)

since otherwise the integration between the DHIS2 database and the Imprest Order application in IRIS will not work correctly.

The ICRC staff member responsible for providing assistance to the health care facility should provide a complete list of item codes and their item descriptions to the ICT ServiceDesk with the request to configure the stock item list in DHIS2. In case of doubt or questions, the Medical Planners should be asked for advice on available items and suitable substitutes. Note that the ICT ServiceDesk is only in charge of adding correct and available items to the DHIS2 database but will not verify the suitability of items or correctness of their details.

Ideally, the ICT ServiceDesk should also be provided at least six months of historical monthly demand data for uploading into DHIS2 which can be used for reviewing and analysing Imprest Levels in Tableau.

#### **1.1.5 Setting up and managing Imprest Levels in DHIS2**

The Imprest Levels need to be entered into DHIS2 through the web portal both for the “Basic mode” and the “Advanced mode” and be managed by the users in the field.

As soon as the user who is responsible for setting up and managing the PSM system has access to the DHIS2 database, s/he can (and has to) access the Data Entry form in DHIS2 and enter the Imprest Levels for each item one by one. This entry is needed only one-off when the system is being set up and all Imprest Level values are automatically carried forward to the next month on the last day of the previous month.

Ideally, if at least six months of historical demand data were shared with and uploaded by the ICT ServiceDesk, the user can compare the entered Imprest Levels with the ideal Imprest Levels calculated by Tableau and, if necessary, revise them.

The Imprest Levels of all items should be reviewed every month after the monthly demand has been updated. Any Imprest Levels which are indicated as “INCREASE” in Tableau, should be increased immediately as otherwise shortages and stockouts are inevitable.

A complete review and revision of the Imprest Levels which require (gradual) decrease can be carried out every three months or every six months. In practice, significant risks of expiry of stock will only occur if items are overstocked and stock levels exceed the Imprest Level which will anyway not prompt any replenishment order. Limiting the review and revision of all Imprest Levels to only every three to six months will significantly reduce upstream demand distortion which makes forecasting and demand planning more difficult.

#### **1.1.6 Uploading initial stock - Advanced mode real time stock management**

While for the “Basic mode” (monthly reporting) storekeepers will enter the stock on hand (and monthly demand) on the mobile device during the monthly physical stock count, for the “Advanced mode” (real-time stock management) the initial stock can only be configured by the ICT ServiceDesk. Technically, the database starts with a Stock on hand of zero for all items and the initial stock is recorded in DHIS2 as a stock receipt to raise the Stock on hand to the current stock levels.

## 2 Basic mode

The PSM “Basic mode” maintains the monthly reporting of stock data, usually at the end of the month, but replaces paper records with digital records.

### **2.1 Pharmacy setup**

In principle no specific preparations are needed as using the PSM mobile application only changes the means of recording, storing and sharing stock data.

However, all medical stocks should be physically ordered on shelves and floor pallets according to their item groups (such as drugs, dressing material etc.) and within in alphabetical order according to their item codes. Ideally, within item groups, items would be arranged alphabetically by their names but DHIS2 will only allow sorting by item codes.

In order to prepare for and facilitate the transition to the “Advanced mode”, standardized storage bins can already be set up, at least for the first batch according to FEFO/FIFO. This allows to anticipate the main change for implementing the “Advanced mode” which then only requires attaching labels with barcodes and item details.

In principle, the implementation of the digital stock reporting will replace stock cards but not the batch cards which still have to be maintained.

### **2.2 Monthly stock reporting**

At the end of the month, the storekeeper will physically count the quantity of every item on the shelf and record the current stock balance in the PSM application.

The quantity of stock which was distributed during the month has to be tallied up from the bin card before being able to record it in the second column of the PSM application.

As soon as the physical stock count and data recording is completed, the local database on the mobile device should be synchronized with the central DHIS2 server in Geneva as quickly as possible.

Ideally, the monthly physical stock count should be carried out after all wards and services have received their last deliveries for that month. This ensures that the pharmacy stock replenishment is done when the stock levels are at their lowest point during the month and therefore (at a given Imprest Level) maximize the stock replenishment quantities.

As for the ICRC (logistics) in general all quantities of all health care goods must be exclusively counted, recorded and reported in units of measure (UoM) of "EA" (Each) and never in any packaging quantities. "EACH" refers to the smallest usable unit of a health care product such as one tablet, one syringe, one disposable glove or one pair (!) of sterile gloves (as these must always be used in pairs). In exceptional cases where the packaging quantity (such as "kit of 100 tests") is indicated in the item description, "EACH" refers to one kit (and not one test) as such products do not contain separate diagnostic tests but are an actual kit with bottles of liquids and other components sufficient for the indicated number of tests but cannot be “split”.

If pharmacies dispense to patients or pre-pack drug products in medicine bags, a maximum of a single secondary packaging should be kept at the dispensing workplace. Any stock should be reported in PSM as “distributed” as soon as containers are taken off the shelf and moved to the dispensing area. Therefore, opened packaging in the dispensing area is not considered in the PSM stock anymore and does not need to be counted at the end of the month.

## 3 Advanced mode

In the “Advanced mode” (real-time stock management system), storekeepers record each stock transaction (distributions, discard and correction) by first scanning a barcode and then entering the transaction quantity. Stock receipts are automatically added to the current stock

when the “Goods Confirmation” is effected in IRIS. For all of these transactions, the PSM mobile app will instantly update the current Stock on hand balance.

Using the “Advanced mode” requires a high level of discipline since the DHIS2 PSM application automatically recalculates the remaining stock balance after every transaction and any mistakes become evident immediately.

### **3.1 Pharmacy setup**

As for the “Basic mode” all stocks should be arranged in alphabetical order of their item groups and by item codes. The first batch of each item should be placed in a bin (“active bin”) according to FEFO/FIFO. Any other batches which are not received in the tertiary supplier packaging should also be placed in separate bins while any health care goods delivered in tertiary supplier packaging should not be opened but placed on the shelf in the order of expiry dates. When the “active bin” is emptied, stock from the next batch can be placed in that bin for the next distribution.

In order to avoid having to scroll down a long list for finding an item, all “active” bins (first bin of each item only) should be fitted with barcodes which are clipped to the bin with a strong paperclip. The labels must not be pasted on the bins as otherwise a large number of bins without stock will accumulate which require a lot of storage space and it is much easier to just swap the barcode labels. The labels must also not be pasted on the shelves as the storage volumes fluctuate and it is much easier to change the location of bins with their labels.

### **3.2 Generating barcode labels for stock**

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

### **3.3 Stock receipts**

The person responsible for acknowledging receipt of consignments received from ICRC medical distribution centres will continue to effect the “Goods Confirmation” in the IRIS application and an automatic routine running in the background will add the quantities of all items indicated in the packing list to the stock on hand in the PSM mobile application.

If the mobile device is working in off-line mode, the user must synchronize the local database with the central DHIS2 server for the stock on hand to be updated.

In case of any discrepancies between the “Goods Confirmation” record (and the packing list) and the physically received consignments, the Medical Planner should be contacted for either arranging delivery of the shortshipped items and quantities or correcting the record in JDE. Either way, the corrected stock receipt quantities (all items and quantities in status 999) will update in the DHIS2 database. If excess stock was delivered, the logistics services can simply issue a packing list for the missing quantities which are again acknowledged with the IRIS “Goods Confirmation” application and will correct the record.

### **3.4 Recording distributions**

Storekeepers will usually receive a list of items required for each ward or service once a day, weekly or according to another established schedule.

The storekeeper will locate the first item on the list in the pharmacy, scan the barcode for selecting the correct item from the stock item list and type or dictate the picked quantity and then move on to pick the next item. This method is the fastest option and since a single row is displayed as a result of the search, the storekeeper cannot accidentally enter the value into the wrong row (for the wrong item).

Alternatively, the storekeeper can scroll down the list until s/he finds the item or enter the required item in the search window. Once all items in the required quantity have been picked, the storekeeper will confirm the transaction and deliver the goods to the requester before starting treatment of the next request.

Negative balances are deliberately blocked by the DHIS2 PSM mobile application to force storekeepers to effect corrections immediately since if delaying them would be allowed, stock discrepancies occurring by “postponed” corrections would inevitably accumulate. Therefore, if the remaining quantity on the shelf is greater than indicated as Stock on hand on the mobile device, the storekeeper can only pick the available quantity. After completing the transaction, a stock correction needs to be made and then in a second transaction the now available quantities can be picked. Creating two separate transactions for the same ward or service will not make any difference for overall stock management and calculations. Alternatively, the storekeeper can interrupt the transaction but will lose all recorded data, then make the stock transaction and start the initially intended transaction from scratch.

In case during the order picking mistakes were made, they cannot be corrected after confirming the transaction. If the recorded quantity is less than the actually picked quantity, the mistake can be simply corrected by effecting another transaction. If the recorded quantity is larger than picked (and needed) then either the “excess” quantity is delivered to the ward or service, kept aside to be included in the next distribution (without recording) or by creating a “Correction” transaction. The “excess” quantity can also be given to another ward or service without recording. While the total stock on hand is thereby corrected, the statistics on distributions to each ward or service would no longer be correct (and cannot be corrected).

### **3.5 Recording discarded stocks**

Stock which is expired, damaged or unusable for other reasons must be removed from the stock and be displayed in a locked cupboard or room which is dedicated only to stock waiting for disposable. In order to account for reduction of the stock on hand without allocating stocks to any specific ward or service, the storekeeper carries out a “Discard” transaction in the same way as for the “Distribution” transaction.

### **3.6 Recording stock corrections**

Discrepancies between the physically available stock on hand on the shelf and the stock on hand balance calculated in the DHIS2 PSM mobile application may occur for different reasons.

* the quantities physically delivered to the health care facility are greater or less than in the electronic record (and not noted at the time of receipts)
* during order picking either greater or smaller quantities than indicated in the transaction are picked and delivered to wards and services (and not noted)
* stock is mislaid, misplaced in a wrong location, lost or stolen

In all of these cases, storekeepers must effect a “Correction” transaction in the PSM mobile application which will correct the calculated stock on hand. The amount of correction transactions and the quantities are a very good indicator for the overall quality of stock management.

In case “loans” are given to or received from other organizations or health care facilities options are not to create any transaction (as eventually the loan will be “repaid”) or by effecting two stock corrections.

### **3.7 Residual balance counting for stock on hand**

As the stock on hand as well as the transaction quantities are instantly updated in the DHIS2 PSM mobile application, a complete and update record of the current stock on hand is available in the system at any time and in principle no (monthly) physical stock counts are necessary. However, if stocks are never counted, discrepancies will only become apparent if and once negative stocks would occur during a transaction.

There are simple and fast ways for counting and checking the remaining stock on hand in certain situations which will allow detecting any discrepancies. This “residual batch counting” has the big advantage that the items with largest number of stock transactions are counted more often and that discrepancies can, in principle, be detected immediately rather than only at the end of the month

* counting the remaining stock whenever a batch is depleted, and the next batch of an item is placed in the “active bin” (tertiary packaging is often provided in “round” quantities such as multiple of thousands with the quantities indicated on the tertiary packaging)
* just before opening any tertiary packaging, checking whether the remaining stock on hand is a “round” quantity (even without actually counting the entire remaining stock.
* Physically counting the remaining stock on hand for small quantities of items which can be effected quickly

## 4 Changing from the “Basic mode” to the “Advanced mode”

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

## 5 Backup plan in case of system failure

Any digital systems can fail at any level: the mobile device at the health care facility, the Internet connection can fail for prolonged periods and central servers and databases can fail.

In order to ensure continuity of services while at the same time keeping a record of any transactions which could not be reported in DHIS2, a backup system needs to be in place from the beginning.

The simplest way is to continue or resume the use of stock cards for any transactions which cannot be reported in DHIS2.

For the “Basic mode” the stock on hand at the end of the monthly and the monthly demand can be entered retrospectively at any time although this will require the ICT ServiceDesk to temporarily increase the five-day deadline for entering stock data for the previous month.

For the “Advanced mode”, the quantities distributed to each ward or service and be tallied up and entered with a single transaction for each ward or service once the system is restored. This will falsify the transaction dates but still maintain an accurate record of the total quantities distributed to each ward or service. In case of prolonged system failure, temporarily switching back to the “Basic mode” which requires less documentation and reporting can be considered.
