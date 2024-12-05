# BoM Configuration

### BoM Configuration

### Creating the BoM Configuration

To configure a BoM configuration, start by selecting a Service User (SU) and opening the corresponding form. Within the form, locate and click on the "Mrp Configuration" button. This action will display all existing configurations already created for this patient. Click on "Create" to initiate a new configuration. Begin by selecting the BoM template appropriate for this configuration process. As mentioned previously, only the approved templates will be shown. In this example, we will use a Trans-Tibial PTB.

<figure><img src="../../../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

Next, select the attributes of the prosthesis. When populating the Side and Human Size, the product variant should update accordingly.

Once this is done, click on Confirm Configuration and then Create BoM.

If there is a pop-up message, it may indicate one of the following issues:

* One of the products is not configured correctly.
* One component doesn’t exist or is archived.
* One of the products doesn't have a specific attribute, which can often happen with attributes like colour or size.

<figure><img src="../../../.gitbook/assets/image (155).png" alt=""><figcaption></figcaption></figure>

To solve this problem, first close the message and click on "ReConfigure". In a scenario where, for instance, the Foot Sach 2.0 in "Beige" is not available

<figure><img src="../../../.gitbook/assets/image (156).png" alt=""><figcaption></figcaption></figure>

You have two options: either change the BoM's color selection to an available option or update the product variant to include the "Beige" color if it's applicable.

In the "BoM Components" tab, you can view all the products that will be utilized during the manufacturing process. These values are editable to accurately reflect the materials used in production. For instance, you can adjust items such as replacing EVA FOAM in Terra Brown with olive color or substituting Foot Sach with a different color variant as needed. This flexibility ensures the BoM accurately represents the materials employed in manufacturing.



### How to replace a product:

To replace a product in the BoM Components tab, begin by editing the BoM record where the change is needed. Within the record, locate the specific line corresponding to the product you wish to update or remove. This step ensures you are targeting the correct item within the Bill of Materials.

You have two primary methods to effect the replacement:

You can click on the trash can icon positioned at the end of the line representing the product.

Alternatively, if you intend to temporarily eliminate the product from the Bill of Materials, you can adjust its quantity to zero. This step allows for flexibility in managing changes in material requirements.

Once you have removed the outdated or incorrect product, proceed by navigating to the end of the table and selecting the option labeled "Add a line".

<figure><img src="../../../.gitbook/assets/image (157).png" alt=""><figcaption></figcaption></figure>

This action opens up a new line where you can specify the replacement product and its required quantity. Additionally, you have the option to specify the stage in the manufacturing process where this new product will be consumed, although this step is not mandatory.

<figure><img src="../../../.gitbook/assets/image (158).png" alt=""><figcaption></figcaption></figure>

After entering the details for the replacement product, ensure to save your changes. This final step updates the Bill of Materials with the revised product configuration, ensuring accuracy in the materials utilized throughout the manufacturing process.

Cancel a BoM Configuration (WIP)

It’s possible to cancel it?
