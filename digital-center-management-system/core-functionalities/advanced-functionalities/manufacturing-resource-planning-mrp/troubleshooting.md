# Troubleshooting

Configuration level

### BoM Configuration

* The product is archived, so the system doesn’t recognized it. You can either delete the product from the BoM Template by clicking the trash bin at the end of the line.

<figure><img src="../../../.gitbook/assets/image (214).png" alt=""><figcaption></figcaption></figure>

```
Or unarchived it.
Go to the product list, Add a filter with the archived one
```

<figure><img src="../../../.gitbook/assets/image (215).png" alt=""><figcaption></figcaption></figure>

```
Open the product form, then on Action click “Unarchive”.
```

<figure><img src="../../../.gitbook/assets/image (216).png" alt=""><figcaption></figcaption></figure>

```
The product is now Active, and you can return to your BoM Template to
reconfigurate it.
```

* The colour that you selected is not available for some specific product. You can either delete the product from the BoM Template by clicking the trash bin at the end of the line and adding a new line with the right product if nesscesary.

<figure><img src="../../../.gitbook/assets/image (217).png" alt=""><figcaption></figcaption></figure>

```
Or select an other colour on the BoM Configuration.
Or Go to the product to add the colour if it’s existing. Example for Foot stach 2.0
Foot
```

<figure><img src="../../../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>

```
Add the Variant on the product (on the product itself, not the product Variant)
```

### Odoo chat blocking the view.

You can go to the profile to update the chatbox view to normal. This will not block the view for small screen. This will show the chatbox at the end of the form and not in the left.

### No access to user form

When doing backup of database, attachement is being deleted or modified.

To resolve this issue you need to go to “Config” > Attachement. Then select all and delete it.

It will solve the error, you can regenerate assets bundle if you want but it’s not necessary.

### Issues with stock picking :

The product are in the right stock but can’t be reserved :

A product is missing in the move

The wrong lot number as been selected :

System will prevent to have negative value.

### No routes configuration for a product :

<figure><img src="../../../.gitbook/assets/image (219).png" alt=""><figcaption></figcaption></figure>

Check on the product if there is the “Replenish On Order(MTO)”

<figure><img src="../../../.gitbook/assets/image (220).png" alt=""><figcaption></figcaption></figure>

### Product already expensed when validating the MO

Already expensed error is raised because we implemented control, that disables creating expense line for same product twice ( mostly to prevent accidental cases of two left prothesis

or something)... To solve the problem it depend of the situation :

1. You will not invoice the client : Delete the line from the expense.
2. Create 2 invoices a. Create an invoicing b. Confirm the MO c. Create a new invoicing
3. Create 1 invoices. a. Delete the line from the expense. b. Confirm the MO c. Edit the expense line with quantity of 2.

### Cancelling the Manufacturing order

When cancelling the Manufacturing order it will cancel the stock move that create the product.

So even if the Manufacturing order is reset to draft the user will have an error at the end.

That the quantity product can’t be negative.

To solve it, edit the form to show the field “move\_finished\_ids”:

Refresh the page and add a new line with the product to produce.

You can then validate the MO and re-edit the form to hide the field “move\_finished\_ids”.

Other stuff to know about

### Strange number after name of expense line

If there is strange number at the end that means that there is ref in the User that was populated but since the base in anonymized the ref became a strange number
