# How to confirm an MRP order

It's important to note that depending on your security role, you may not have the authorization to confirm the MRP order. Typically, only physiotherapist, orthotist or authorized personnel can confirm this MRP order, ensuring that the manufacturing process proceeds accurately and according to plan.

_Technically: If the user does not have the role (group\_mrp\_manager), they will not see the "Confirm" button and will be unable to proceed with any actions related to confirming the Manufacturing Resource Planning (MRP). Only users with this specific role will have the "Confirm" button enabled._

Before proceeding to confirm the MRP, these authorized users must ensure that all products intended for consumption are thoroughly checked for accuracy. This includes verifying quantities and addressing any issues such as missing products.

&#x20;If adjustments are needed, the user can edit existing lines or create new ones following the same process for the BoM configuration outlined here.

Once all product details are correct, the user can proceed to confirm the MRP by clicking the "Confirm" button.

<figure><img src="../../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

Upon confirmation, the system will reserve the necessary stock for this order. Typically, products are available in the main stock but may need to be transferred to the workshop.

<figure><img src="../../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

By default, the system generates a transfer order from the main stock to the workshop, which can be accessed directly from the MRP order or through the Inventory module.

<figure><img src="../../../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

Additionally, if the Purchase module is properly configured, confirming the Purchase Order (PO) will trigger the creation of purchase orders to vendors. For more details on this process, refer to the specific guidelines provided.
