# Managing MRP Order

### Create the MRP Order

Once you have finalized the components to be consumed and defined the operations in the BoM configuration, you can proceed to create a Manufacturing Order by clicking the "Create MRP Order" button located on the top ribbon.

<figure><img src="../../../.gitbook/assets/image (159).png" alt=""><figcaption></figcaption></figure>

This action initiates the creation of a Work Order that includes all the necessary components for consumption. The Work Order starts in a draft status.

It's important to note that depending on your security role, you may not have the authorization to confirm the MRP order. Typically, only physiotherapist, orthotist or authorized personnel can confirm this MRP order, ensuring that the manufacturing process proceeds accurately and according to plan.

### How to confirm an MRP order

If the user does not have the role (group\_mrp\_manager), they will not see the "Confirm" button and will be unable to proceed with any actions related to confirming the Manufacturing Resource Planning (MRP). Only users with this specific role will have the "Confirm" button enabled. Before proceeding to confirm the MRP, these authorized users must ensure that all products intended for consumption are thoroughly checked for accuracy. This includes verifying quantities and addressing any issues such as missing products.

If adjustments are needed, the user can edit existing lines or create new ones following the same process outlined here.

Once all product details are correct, the user can proceed to confirm the MRP by clicking the "Confirm" button. Upon confirmation, the system will reserve the necessary stock for this order. Typically, products are available in the main stock but may need to be transferred to the workshop.

By default, the system generates a transfer order from the main stock to the workshop, which can be accessed directly from the MRP order or through the Inventory module.

Additionally, if the Purchase module is properly configured, confirming the Purchase Order (PO) will trigger the creation of purchase orders to vendors. For more details on this process, refer to the specific guidelines provided.

<figure><img src="../../../.gitbook/assets/image (160).png" alt=""><figcaption></figcaption></figure>

### How to manage a Stock Move

_Stock move explanation_

Warning : The name of the step can vary based on the configuration of the center.

<figure><img src="../../../.gitbook/assets/image (161).png" alt=""><figcaption></figcaption></figure>

First, go to the correct stock move. TO UPDATE

In this form, you can see the source location and the destination location on the top left. The scheduled date, the deadline, and the source document are displayed on the top right. If it's an internal transfer, you will see a checkbox "Is recasting" that indicates whether the picking component is used for recasting. This checkbox is purely informational and does not perform any actions.

<figure><img src="../../../.gitbook/assets/image (162).png" alt=""><figcaption></figcaption></figure>

There are two main tabs in this form: "Detailed Operations" and "Operations". The "Detailed Operations" tab shows the specific operations required for the stock move, including any reserved quantities and lot numbers if necessary. The "Operations" tab shows the amount of product requested for the move. If the move is in draft status, only the "Operations" tab with the amount of product requested will be visible.

### _Process of any stock move_

Click on the “Check availability” button to reserve the product, which will change the stock move status to "Ready".

<figure><img src="../../../.gitbook/assets/image (163).png" alt=""><figcaption></figcaption></figure>

The user can print a PDF file to see which products need to be moved by clicking on the print button and selecting “Picking operations”. If the button is not visible, save the record, and the button will appear.

<figure><img src="../../../.gitbook/assets/image (164).png" alt=""><figcaption></figcaption></figure>

There are multiple ways to progress this order:

1. **Clicking on "AutoFill", then click on “Validate”.** It will AutoFill all the quantities available in the tabs “Detailed operations”
2. Directly clicking on "Validate" ̈ If no “Done quantities” are recorded, a pop-up will ask if you want to process all the reserved quantities before validating. If you apply it will AutoFill all the quantities available.

<figure><img src="../../../.gitbook/assets/image (165).png" alt=""><figcaption></figcaption></figure>

3. Updating the quantity line by line. Sometimes the reserved quantity is hidden. To show it, click on the three dots and select "Reserved quantity". This will display the quantity to be retrieved and the correct value to populate in the done column.

<figure><img src="../../../.gitbook/assets/image (166).png" alt=""><figcaption></figcaption></figure>

```
Once the quantities are correctly populated, click on "Validate". After
validation, the system will ask if you want to create a backorder for any
remaining products not yet delivered. If you want to deliver or pick up these
components later, create a backorder. If you do not want to deliver the
remaining products, select “No backorder”.
```

This step is mostly the same for Every stock move, only the Stock location / Destination change.

### Request new component for recasting

To request new components for a recast, you have two options:

1. Duplicate the last Picking Component (PC): o Return to the Manufacturing order and open the transfer from the previous step. o Click on Action > Duplicate at the top.

<figure><img src="../../../.gitbook/assets/image (167).png" alt=""><figcaption></figcaption></figure>

o This creates a new transfer with the correct products. Then, check the “Is Recasting” field.

2. Create a new request:&#x20;

o Go to the Inventory Module, click on the three dots of the Pick Component tag, and select Planned Transfer.

<figure><img src="../../../.gitbook/assets/image (168).png" alt=""><figcaption></figcaption></figure>

o Populate all required products and check the “Is Recasting” field.

In both cases, validate the request as outlined previously.

### Work order line :

In this tab you will found, all the step that need to be done by the workshop.

The user will need to progress through all the Work order Line.

<figure><img src="../../../.gitbook/assets/image (169).png" alt=""><figcaption></figcaption></figure>

Each line Have a “Start”/”Block” button,

When starting the workorder. The timer will begin until you “Pause” or “Done” this line. This will help to track the time for each step.

Currently only 1 person can start the step even if there is multiple person working on it.

<figure><img src="../../../.gitbook/assets/image (170).png" alt=""><figcaption></figcaption></figure>

If the Tier Validation module is installed and the workorder stage is Greenlight or any other validation step, then only specific user can validate this line.

This is configured on the Module Tier Validation to check the configuration you can look here.

<figure><img src="../../../.gitbook/assets/image (171).png" alt=""><figcaption></figcaption></figure>

Example :

Only a person with the role “Head Of clinician” can approve this tier validation.

<figure><img src="../../../.gitbook/assets/image (172).png" alt=""><figcaption></figcaption></figure>

Only When all this Work order is Done you can validate the MO.

## Validating the Manufacturing Order

To validate a Manufacturing Order (MO), click on the “Mark Done” button. Several checks are performed during validation:

1. If any work order is still open, a pop-up will inform you to complete all work orders first.

<figure><img src="../../../.gitbook/assets/image (173).png" alt=""><figcaption></figcaption></figure>

2. If the consumed quantity differs, a pop-up will warn you. After reviewing, you can either “Confirm” or “Review the consumption” in more detail.

<figure><img src="../../../.gitbook/assets/image (174).png" alt=""><figcaption></figcaption></figure>

3. If no serial number was assigned, a pop-up will prompt you to provide a Lot/serial number.

<figure><img src="../../../.gitbook/assets/image (175).png" alt=""><figcaption></figcaption></figure>

```
To assign a Lot/serial number, return to the MO, create a new Lot manually or
click the + button to add the serial number, and re-validate the record.
```

<figure><img src="../../../.gitbook/assets/image (176).png" alt=""><figcaption></figcaption></figure>

After resolving any issues, the MO status will change to “Done” and become read- only. The next step is to deliver the product to the SU.

### Send the product to the SU.

To send the product to the client, you have two options:

1. Go to the SU Form and Click on the Tab "Stock Items": Navigate to the Service User (SU) form and access the "Stock Items" tab. Here, you can initiate the process to send the product to the client directly from the SU record.

<figure><img src="../../../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>

2. Go to the Inventory Module and Select the Box "Delivery Orders": Alternatively, you can access the Inventory module and select the "Delivery Orders" option.

<figure><img src="../../../.gitbook/assets/image (178).png" alt=""><figcaption></figcaption></figure>

In both cases, the process follows the step as for any other stock move.

<figure><img src="../../../.gitbook/assets/image (179).png" alt=""><figcaption></figcaption></figure>

When validating the order, it signifies that the product has been received by the client and will no longer be available in stock. This action updates the inventory accordingly, reflecting the outgoing shipment and ensuring accurate stock management.

