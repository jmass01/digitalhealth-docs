# MRP Process

## MRP Process

MRP Template

### Pre-Configured Template (WIP)

By default, there is 31 Configuration templates.

Each template needs to be modified and approved by the user to be selectable on a BoM request.

### Pre-Configured product (WIP)

By default, there is 179 pre-configured product.

### How to create a new BoM Configuration Template

To configure a Bill of Materials (BoM) in the Odoo Manufacturing module, start by navigating to "Settings" > "BoM Config Template". Click on "Create" to begin the process.

<figure><img src="../../../.gitbook/assets/image (151).png" alt=""><figcaption></figcaption></figure>

Select the product that will be manufactured or create a new product if necessary. Ensure that the product has the "Manufactured" checkbox selected to make it available for selection here. If you need guidance on configuring a new product, you can find instructions \[here].

When you select a product, the Reference and Name fields will automatically update based on the selected product. However, you can still modify the name and reference if needed. If your Odoo instance supports multiple languages, you can update the translation for the product in any other installed languages.

Next, click on "Configure Attributes". Select the attributes you want for your product. By default, the attributes will match those of the product, but you can select different attributes if needed. These will be displayed with the "main product" column

unchecked. You can use the three-dot menu to show more columns, such as "Allowed Value". Here, you can add or remove values as required.

<figure><img src="../../../.gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

Finally, click on "Start BoM Configuration". Two tabs will appear: "Components" and "Operations". These tabs allow you to define the components and operations necessary for manufacturing the product.

Let’s first begin by creating a new work order line in the Operations tab, When selecting the operation, if you want to create a new one, you can write the name of the new operation and click on "Create and Edit". This will open the form for further details.

Here is an explanation of the fields and options available:

<figure><img src="../../../.gitbook/assets/image (153).png" alt=""><figcaption></figcaption></figure>

1. Name: This is the name of the operation that will be displayed.
2. Work Center: Select the work center where this operation will take place. The work center refers to a specific location or set of equipment where manufacturing activities are performed.
3. SU Needed: Indicate if the service user presence is required for this operation.
4. Green Light: Check this box if the operation requires approval before proceeding.
5. Default Duration: Set the default duration for this step, indicating how long the operation is expected to take.
6. Description: Provide a detailed description to guide users on what needs to be done during this operation.

Next, navigate to the Components tab. When adding a line, you must first select the product category. This selection will filter the available products, showing only those associated with the chosen category.

NEED TO TAKE A DEEP LOOK AT CONFIG STATUS

Once you are satisfied with the configuration template, click on “Approve”. The BoM Template will now appear under the BoM section, ready for use in the manufacturing process.
