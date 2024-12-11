# Repair process

## Repair process

Get the product to repair (TRM)

To begun the process, you need first to receive the product to repaired.

To do that you have 2 choice :

Go to a SU, click on the button “Receive items to repair”, if you already created a manufacturing order for this client then by default the system will select the last one.

Then you need to validate this receipt.

Second choice is to go to “Repair” >” Receive for repair”

<figure><img src="../../../.gitbook/assets/image (192).png" alt=""><figcaption></figcaption></figure>

It will create a receipt order, you will ned to select the correct partner and on the operation tab the correct product. When validating the system will propose the correct lot number.

Otherwise you can select the correct one.

You can now “Auto fill”/”Validate” the movement.

Now we can proceed to the next step : the repair order.

### Create the Repair order : (TRM)

Same here multiple choice :

Go to a SU, click on the button “New repair order”

If you select a SU without manufactured product a pop up will appear to warn and stop you that there is no items belonging to this SU

<figure><img src="../../../.gitbook/assets/image (193).png" alt=""><figcaption></figcaption></figure>

Go to the “Repair” module and go to “Repair Order” and click create.

You will have a possibility to select the partner, the system will automatically find the product received to repair.

**Component tab :**

This is all the product that will be removed/added to a specific prothesis

When adding a line, you have the choice to Add or Remove a product.

If we select to add a product, The product choosed will be deduced from the stock.

First there is a transfer that will be created to be done,

<figure><img src="../../../.gitbook/assets/image (194).png" alt=""><figcaption></figcaption></figure>

If the user select “Supress” then we have multiple choice, We can change the destination location to either add again the product in stock or to add to the scrap location (Not in stock).

When this is done we can click on “Confirmer la reparation”

**Operation :**

The Operation tab is all the “Service product”, that will be done during the repair.

This Tab is mostly used to invoice specific service like Human resource.

### Repair process: (TRM)

We can start now the repair. To do that click on “Start Repair”.

<figure><img src="../../../.gitbook/assets/image (186).png" alt=""><figcaption></figcaption></figure>

If you have an error pop-up go \[here]

If all the configuration is ok, all the component on the list should be “Waiting Another Move”.This means that there is an ongoing Transfer to “Replenish the repair stock”

Next step if for the Storekeeper, to go to “Resupply repair” on the Inventory module to validate the Transfer when the User will pick the component.

<figure><img src="../../../.gitbook/assets/image (187).png" alt=""><figcaption></figcaption></figure>

Here is the same step as any other “Stock move”, You can check all step \[here]

Then this move is validated. We can return to the Repair Order.

We can see now on the list of all component that the move state is “Available” and the “Reserved quantity”

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

When the repair is done, we just need to click on “End Repair”.

The repaired is now done and the stock was updated.

### Invoice the Repair (WIP)

Qc control

When the repair had been ended if the QC (quality control) is enabled. It will create a quality check to this reparation. By default the step that need to be check is hardcoded to be&#x20;

{% hint style="info" %}
Alignment is correct in all three planes (frontal, sagittal and transversal)
{% endhint %}

* All screws and fixtures are secure
* Device has no sharp edges and is comfortable to wear
* Materials and components have fulfilled expected functions
* Cosmesis and Workmanship (including cleaning of marking) Each step to be checked have 3 potential value : “Yes(passed)”, “No(failed)”,”Not relevant (passed)”

<figure><img src="../../../.gitbook/assets/image (189).png" alt=""><figcaption></figcaption></figure>

Then then head of PT/PO will be able to approve this QC

<figure><img src="../../../.gitbook/assets/image (190).png" alt=""><figcaption></figcaption></figure>

If one of the inspection line is not succeed then the All QC after confirmation will be failed if not it will be successful and the Repair need to be Ended by clicking on the “End repair button”.

DOUBT : Why does the PT/PO can only approve or cancel and not Approve and Refute?

### Deliver the repaired. Item (TRM)

Then we need to deliver the item. On the repair form Click on the “Deliver item” button to create the Deliver order.

<figure><img src="../../../.gitbook/assets/image (191).png" alt=""><figcaption></figcaption></figure>

It has created a Delivery Repaired order. Next step will be to approve this Stock move Order. It’s the same process as all Stock move.

You can access it from the SU or from the inventory module “Deliver REPAIRED”.

You can check stock move step \[here]

When this move is done, it’s meant the Patient received his repaired product.

