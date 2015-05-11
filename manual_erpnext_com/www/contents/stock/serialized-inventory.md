As we discussed in the **Item** section, if an **Item** is _serialized_, a
**Serial Number** (Serial No) record is maintained for each quantity of that
**Item**. This information is helpful in tracking the location of the Serial
No, its warranty and end-of-life (expiry) information.

**Serial Nos** are also useful to maintain fixed assets. **Maintenance Schedules** can also be created against serial numbers for planning and scheduling maintenance activity for these assets (if they require maintenance).

You can also track from which **Supplier** you purchased the **Serial No** and
to which **Customer** you have sold it. The **Serial No** status will tell you
its current inventory status.

If your Item is _serialized_ you will have to enter the Serial Nos in the
related column with each Serial No in a new line.

### Serial Nos and Inventory

Inventory of an Item can only be affected if the Serial No is transacted via a
Stock transaction (Stock Entry, Purchase Receipt, Delivery Note, Sales
Invoice). When a new Serial No is created directly, its warehouse cannot be
set.

### Using Serial Nos

To add a Serial No to a stock transaction, you can set the Serial No in the
serial no field:

![Serial No Entry](/assets/manual_erpnext_com/old_images/erpnext/serial-no-entry.png)

### Creation

Serial Nos can automatically be created from a Stock Entry or Purchase
Receipt. If you mention Serial No in the Serial Nos column, it will
automatically create those serial Nos.

### Automatic Series

If in the Item Master, the Serial No Series is mentioned, you can leave the
Serial No column blank in a Stock Entry / Purchase Receipt and Serial Nos will
automatically be set from that series.

#### Step 1: Mention the Series in the Item

![Automatic Series](/assets/manual_erpnext_com/old_images/erpnext/item-serial-no-series.png)

#### Step 2: Keep Serial No field blank in your entry

#### Step 3: Save / Submit your transaction (Serial Nos Automatically Updated)

![Serial No Created Message](/assets/manual_erpnext_com/old_images/erpnext/serial-no-auto-1.png)

![Serial No Updated in Transaction](/assets/manual_erpnext_com/old_images/erpnext/serial-no-auto-2.png)

### Using Serial Numbers for Multiple Purposes  

Serial Nos are a useful tool for tracking different kinds of Items, by using
it along with Custom Fields. For example, in our internal system at Frappe,
each ERP account is a Serial No, with type of user “Plan” as the Item, its
expiry date, whether it is Trial or Paid and other details as Custom Fields.

We have known customers who use Serial Nos to track fixed assets, real-estate
properties or advertisement slots, even library books!

Since Serial Nos are deeply linked with all the core modules, Selling, Buying,
Inventory and Accounting, you may find many uses for them.

{next}
