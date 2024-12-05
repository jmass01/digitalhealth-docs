# Stock Management

## Stock Management.

### Warehouse

Various stock locations

In many centers, there are typically three primary stock locations:

1. Daily Usage / Shop This location serves as the primary stock area where all products are stored for regular use and immediate access. It is the central hub where items are readily available for sale or distribution to customers and staff daily.
2. Workshop location The workshop location is dedicated specifically to manufacturing operations. It houses materials and components needed for production orders. While some centers may not have a physical distinction between the main stock and the workshop, in the system, it is crucial to maintain a separate inventory to accurately track materials used exclusively for manufacturing purposes.
3. Repair location This stock location is exclusively designated for repair components and products that require servicing. It serves as a specialized area where returned items are assessed, repaired, and prepared for reintegration into inventory or return to customers in optimal condition.

The names of these locations can vary based on the language used and the specific practices of each center. Additionally, some centers may include additional locations such as dormitories or food storage areas, each serving specific operational needs within the facility.

### Products

Lot number

<figure><img src="../../../.gitbook/assets/image (180).png" alt=""><figcaption></figcaption></figure>

```
Product categories
Product categories play a crucial role in organizing and
managing inventory effectively.
Product categories help determine how inventory is valued.
Each category can be assigned a specific valuation method
such as Standard Price or FIFO (First In, First Out),
```

impacting how the cost of goods sold (COGS) and inventory valuation are calculated.

Product categories facilitate efficient logistics and organization. They allow products to be grouped based on similar characteristics, such as type, function, or usage. This grouping simplifies inventory searches, reporting, and ensures products are stored and managed logically.

Overall, product categories in Odoo are fundamental for structuring inventory management, optimizing logistics, facilitating accurate valuation, enabling detailed reporting, and automating workflows.

### Stock on hand / Forecasted

In Odoo, "Stock on Hand" represents the actual quantity of a product available in inventory at any given moment. It is determined by the physical count of products in stock, updated through transactions such as receipts from suppliers, internal transfers between locations, sales to customers, and adjustments for damages or discrepancies.

On the other hand, "Forecasted Stock" in Odoo is a projection of future inventory levels based on planned transactions and anticipated demand. It takes into account pending purchase orders, manufacturing orders, sales orders, and forecasted demand to estimate how much stock will be available in the upcoming periods. Forecasted Stock helps businesses anticipate inventory requirements, plan production schedules, and make informed decisions regarding procurement and inventory management

The key difference between Stock on Hand and Forecasted Stock lies in their temporal perspective and calculation basis. Stock on Hand reflects current inventory levels based on actual transactions and physical counts, while Forecasted Stock looks ahead by predicting future inventory positions based on planned transactions and expected demand.

### Les different flow de stock (WIP)

Daily Distribution without requests (WIP)

Some cem

### Inventory adjustments

To manage inventory in Odoo, you can create an inventory adjustment. Start by navigating to "Inventory" > "Operations" > "Inventory Adjustments". From there, create a new record and select the location you want to update. Typically, this will be either "WH/Stock" (main stock) or the "WH/Workshop" (workshop location).

If you want to include all products, even those with zero stock, make sure to check the "Include exhausted products" field. Next, click on "Start Inventory". This will allow you to update each product line with the actual stock value. If a product is not listed, you can click on the "Create" button to add a new line.

As you update the quantities, any lines with discrepancies between the counted stock and the stock on hand will be highlighted in red. Once all quantities are accurate, you can proceed by clicking on "Validate Inventory". This action will lock the inventory and update the stock based on the inventory adjustment.

Replenish stock / Receipt (WIP)

1. Creer un purchase manuellement
2. Automatiser les flux a. Flux tendu b. Regle de réassortiment
3. Create a “receipt” manually.

Transfer interne / Immediate transfer vs planned transfer(WIP)

Reordering rules (NU)

W.I.P This Reordering Rules is not used.

Repair (WIP)

Delivery order(WIP)

Stock reporting (WIP)

Inventory report (WIP)

Stock en fin de mois (WIP)

Mouvement par mois (WIP)

Ask for stock.

Configure the product to replenish on Order (WIP)

<figure><img src="../../../.gitbook/assets/image (181).png" alt=""><figcaption></figcaption></figure>

### Inventory Valuation

Cost method by categories of product

In Odoo, the cost method for inventory valuation is managed at the Product category level. Each Product category can be assigned one of the following cost methods:

1. FIFO (First In, First Out): o FIFO assumes that the first units purchased or manufactured are the first ones to be sold or used. This method ensures that the cost of goods sold (COGS) reflects the cost of the oldest inventory items, thus maintaining better accuracy in cost calculation over time.
2. LIFO (Last In, First Out): o LIFO assumes that the last units purchased or manufactured are the first ones to be sold or used. This method may result in different COGS calculations compared to FIFO, particularly in times of inflation, as newer (more expensive) inventory items are considered sold first.
3. Standard Price: o Standard Price uses a fixed cost per unit for a product, regardless of the actual cost of purchasing or manufacturing it. This method simplifies accounting and cost calculation, as it assumes a constant cost per unit for all transactions until the standard cost is updated.
4. Average Cost (AVCO - Average Cost or Weighted Average Cost):

```
o AVCO calculates the cost of goods sold and the value of ending inventory by
averaging the costs of all units available for sale or use during the period. This
method smooths out cost fluctuations and is suitable for businesses that want a
stable and predictable cost base.
```

<figure><img src="../../../.gitbook/assets/image (182).png" alt=""><figcaption></figcaption></figure>

Check the Inventory Valuation (WIP)

###





The repaired is now done and the stock was updated.

### Invoice the Repair (WIP)

Qc control

When the repair had been ended if the QC (quality control) is enabled. It will create a quality check to this reparation. By default the step that need to be check is hardcoded to be :

```
Alignment is correct in all three planes (frontal, sagittal and transversal)
```

* All screws and fixtures are secure
* Device has no sharp edges and is comfortable to wear
* Materials and components have fulfilled expected functions
* Cosmesis and Workmanship (including cleaning of marking) Each step to be checked have 3 potential value : “Yes(passed)”, “No(failed)”,”Not relevant (passed)”

Then then head of PT/PO will be able to approve this QC



