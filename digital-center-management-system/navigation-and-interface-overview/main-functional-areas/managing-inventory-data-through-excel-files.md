# Managing Inventory data through excel files

### Managing inventory data through excel files

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

The XLSX Manage menu item give access to various valuable excel documents.

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

Through theses files you will be able to update any data among your warehouse except the quantities which need to be done through an inventory adjustement as it will create new entries (the stock moves).

For instance to update product template data on the product view

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

As the excel file is perfectly set you can import it back without any issue

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

Be aware that once your data are updated there will not be any record of the previous data in Odoo so use this feature carefully.

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

Reordering rules can be update and create like this as well.

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

The min quantity is the trigger to create a draft order, the max is the one which will order and the

multiple means what it means 😊.

Let s take the example of the first line&#x20;

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

It means if the quantity of this product will reach 20 or under, let’s say 19 a reordering rule will be triggered and then 12 unit will be ordered as 19 + (2x6) = 31 < 35 but 19 + (3x6) = 37 > 35 and 35 is our maximum quantity.
