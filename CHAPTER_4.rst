CHAPTER 4
=========

.. _purchases-1:

PURCHASES
~~~~~~~~~

Use the **Purchases** subsystem to identify and satisfy internal and
external demands for goods and services. To access the subsystem, in the
sections panel, click **Purchases**.

Products and services groups
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Products and services are classified by groups depending on the company
needs. It is better to classify them before adding information about
products and services items to the catalog. With the classification, you
can speed up operations and quickly find the required item in the
catalog. Besides, with products and services groups, you can aggregate
target indicators.

The list of products and services groups is an hierarchical list with no
nesting level limit.

To access the catalog, in the navigation panel of the **Company**
section, click **Catalogs**.

Products and services group can consist of an unlimited number of
products and services, but one item can be included only in one products
and services group.

Products and services
~~~~~~~~~~~~~~~~~~~~~

You can store information on all inventory, services and works included
in the company documents in the **Products and services** catalog. To
access the catalog, click the corresponding link in the navigation panel
in the **Sales**, **Purchases**, **Service**, and **Manufacturing**
sections.

|image1521153996160768|

All items in the **Products and services** catalog are classified by
groups. You can find the list of groups in the **Products and services
groups** catalog.

|image1521153999271902|

Entering information on products and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can edit and enter information on a catalog item (a products and
services item) on a separate form (product card).

|image1521153996135234|

Specify a short and full name (for print document forms) of the product,
and its type. The following types of products and services are available
in the application:

-  **Inventory** includes material inventories subject to warehouse
accounting.

-  **Service** includes various services, for example, tourism services,
hairdressing services, legal services or third party services
attributed to company expenses, for example, rental of rooms or
equipment.

-  **Work** includes manufacturing contracted works, for example,
building a construction, tailoring.

-  **Operation** includes technological operations performed during work
performance, service rendering, or product manufacturing.

-  **Activity kind** includes work (job) kinds performed by employees
for which you can set rates.

The card has the **Main parameters** tab and may contain several
additional tabs. Attributes on the **Main parameters** tab depend on the
selected products and services type. After saving the item, you cannot
change the products and services type and the tab kind.

The catalog also contains attributes that can be applied to all forms at
the same time, regardless of the products and services type, for
example, **SKU**. You can find most common attributes on the **General
information** tab.

For more information on different products and services types, see
chapters below.

Inventory
~~~~~~~~~

Use a card with the **Inventory** products and services type to enter
information about goods, materials and products which can be shown to
customers in the trade floor or sample room.

-  On the **Main parameters** tab, specify a products and services
group, a price group, customer order fulfillment deadline for these
products and services in days. You can also set VAT rate, inventory
self-cost estimation method when it is written off from the warehouse
(the **Write-off method** attribute), business area to which these
products and services are linked.

-  On the **Storage and purchasing** **parameters** tab, the following
attribute groups are available: **Storage**, **Production and
purchase**, **Use**:

In the **Storage** group, specify inventory storage location
(warehouse and bin). In the **Production and purchase** group,
specify a method and term of this inventory replenishment. You can
replenish inventory from production, purchasing of new inventory from
supplier or ordering inventory from processor. Replenishment period
is set in days. These days are counted from the date of purchase
order registration until receipt of the ordered products and services
to the company warehouse. In the group, you can also specify a
supplier (for inventory replenished by purchase) and/or a bill of
materials (if inventory is replenished by production). You can also
specify a country where the inventory is produced.

In the **Use** group, you can enable additional accounting sections
such as batches and characteristics by selecting check boxes. You can
use characteristics for products and services types **Inventory**,
**Service**, **Work** and **Consumption**. Use batches only for the
**Inventory** type.

In the products and services card of the **Inventory** type on the
**General information** tab, you can insert an image of products and
services. You can add a new file from the existing file on the disk.

To add a file from the disk, after saving the item, click Catalog
navigation panel **files**, then open the corresponding form and click
**Create**. When you select a file, a form appears. In the form, you can
change a name and an author of the attached file. Click **Save** or
**Save and close** to see an image in the products and services card.

|image1521153997779131|

Click **More...** in the navigation panel of the form to specify
additional information:

-  In the **GL account** attribute group:

-  Inventory GL accounts for accounting of own and transferred or
received for processing goods of the **Inventory** type

-  GL account of products and services as costs in unfinished production

-  Click **Inventory management** to set maximum or minimum inventory
level for the selected goods.

|image1521153995306393|

.. _service-1:

Service
~~~~~~~

Use a card with the **Service** products and service type to enter data
on services that the company renders to counterparties. The attributes
of the card are similar to Inventory, but some attribute groups are
missing as they cannot be used for services.

|image1521153997192403|

You can fill in attributes on the **Main parameters** tab in the same
way as for Inventory, only the **Write-off method** attribute is
missing.

Work
~~~~

Use a card with the **Work** products and services type to enter data on
works performed by the company. Cards of the **Service** and **Work**
types have almost identical attributes.

|image1521153995219167|

To determine how work cost is calculated in job orders – by hourly cost
according to the price list or by standard hour cost specified for this
work kind, use the **Work cost calculation method** radio button on the
**Main parameters** tab.

The **Bill of materials** additional attribute is available on the
**Storage and purchasing parameters** tab in a card of the **Work**
type. You can specify a corresponding document related to this work
performance in this attribute.

Operation
~~~~~~~~~

Use a card with the **Operation** products and services type to enter
data on technological operations of product manufacturing and work
performance.

|image1521153995865740|

VAT rate, deadline, and business area are not specified for
technological operations, but GL account of costs is specified. The
**Standard time** attribute is available on the **Storage and purchasing
parameters** tab. You can enter standard time to execute an operation to
this attribute.

Activity kind
~~~~~~~~~~~~~

Use a card of the **Activity kind** products and services type to enter
data on activity kinds performed by company employees. Unlike for
operations, you do not need to specify a GL account of costs, or storage
and purchasing parameters for the activity kind.

|image1521153991779407|

UOM classifier
~~~~~~~~~~~~~~

To access the catalog, in the navigation panel of the **Company**
section, click **Catalogs**. Enter a list of units of measure (pieces,
containers, boxes, etc.) used by the company into the catalog. The
catalog has one-level structure. You can edit and enter new items
directly in the catalog list form. You can use All-Russian Classifier of
Measurement Units (OKEI) for filling in.

|image1521153999296681|

The catalog contains two predefined values of unit of measure: **Piece**
and **Hour**.

Warehouse bins
~~~~~~~~~~~~~~

You can keep records of inventory by storage place structure (racks,
areas, etc) united by the same name of a **warehouse bin**. To enable
warehouse accounting by bins, in the **Settings** section, on the
**Purchases** accounting parameters form, select the **Inventory
accounting by bins** check box. Any number of bins is allowed in the
application. Do not specify bins for the business unit which is a
two-phase warehouse in financial documents.

To keep a bin list, use the **Warehouse bins** catalog. To access it, on
a **Business units** catalog item form, in the navigation panel, click
**Warehouse bins**. Before starting operation, enter data on bins into
the catalog.

Each catalog item contains data on a warehouse bin.

|image1521153999320901|

If accounting by companies is set in the accounting policy settings,
warehouse inventory of a small or middle company is managed in terms of
warehouse physical location and its products and services range, not
considering product formal ownership to a company, that is, warehouses
are common for the whole company. Otherwise, remaining products in
warehouses are considered to be the property of different companies.

You can use the **Warehouse bins** catalog items almost in all documents
which register inventory movement. The items determine the place in the
warehouse where inventory movement is actually made. Batch accounting is
available in the application. The list of batches is stored in the
**Products and services batches** catalog subordinate to the **Products
and services** catalog. A batch is intended to select certain product
groups which have some common properties. You can receive the products
of the same batch from the supplier by several goods receipts.

Purchase order
~~~~~~~~~~~~~~

Use the **Purchase order** document to record prearrangements of
products and services item purchase. The order can be a basis document
for payment and product receipt.

|image1521153996079112|

In the order list, you can see information about order fulfillment,
state, and order payment percent.

Order fulfillment details are shown as the order lines.

**Black** line shows that the order is an advance request. **Blue**
shows that the order is in progress, **Green** shows completed orders.
**Strikeout** line shows that the order is closed.

Level of shipment and payment are shown using pie charts.

|image1521153996050015|

When you register the **Purchase order** document, specify the order
fulfillment date, a counterparty – the product supplier, and a contract
with the supplier. In the **Customer order** field, you can specify an
order for which you will use products purchased from the supplier (i.e.
place the customer order to the purchase order). Enter data on the
ordered products and services in the table field.

When you create a purchase order, specify an operation type – a
purchasing order or a processing order.

To schedule payment for orders with states **In progress** or
**Completed**, select the **Schedule payment** check box. The **Payment
calendar** tab appears on the document form where you can specify
planned dates, a payment method, and a percent that must be paid not
later than the specified date. Payment (percent) amount and VAT will be
auto calculated.

|image1521153991401826|

Payment data can be represented as a list so that you can schedule
payment in a few steps. To view and edit it, click **As a** **list**.

|image1521153991473933|

Supplier invoice
~~~~~~~~~~~~~~~~

In the application, you can register proforma invoices received from
suppliers. It can be entered based on the purchase order. To access a
list of proforma invoices received from suppliers, in the **Purchases**
navigation panel, click **Supplier invoices for payment**.

In the document, you can see information about purchased products and
services, their quantity and price.

|image1521153997365381|

As in the order, to plan payment in the supplier invoice, select the
corresponding check box and populate the **Payment calendar** tab. In
the payment calendar, you can select a **payment method** – cash or
non-cash. If you do not know the payment method, select **Undefined**.

Receiving goods
~~~~~~~~~~~~~~~

To record goods receipts from suppliers, use the **Goods receipt**
document. You can register the document based on the **Purchase order**
document. You can register supplier prices using the goods receipt.

|image1521153994152388|

In the goods receipt, specify the **Receipt from supplier** operation
type, enter information about the supplier and contract, a goods receipt
warehouse, and a certain storage bin if necessary.

On the **Services** tab, record receipt of third party services, for
example, lease or goods delivery. If the **Include services in the
inventory cost** check box is selected, before posting the document,
allocate expenses to the purchased goods cost. To allocate the expenses,
on the **Goods** tab, click **Allocate services**. When you click the
button, a menu to select one of allocation options (by quantity or by
cost) appears.

On the **Additionally** tab, you can specify a number and a date of the
incoming document, a performer department, and an employee responsible
for entering the document.

|image1521153991891976|

With the document list, you can record receipt of goods and services
(expenses) from suppliers including against open purchase orders.

|image1521153994174842|

You can register documents both against one and several selected
purchase orders.

You can analyze payment state of the selected purchase orders and mutual
settlements.

Returning products to supplier
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can return received products to the supplier counterparty. To
register return, use the **Goods issue** document generated based on the
goods receipt. In the document, specify the **Return to supplier**
operation type.

|image1521153994080099|

Attributes of the goods issue for return to supplier are the same as
goods receipt attributes. In the document, you can see information about
the returned products. You cannot return the third party services.

Received invoice
~~~~~~~~~~~~~~~~

You can create the **Received invoice** document based on the goods
receipt.

|image1521153996830180|

Use the document to register invoices received from suppliers and keep
records of numbers of customs cargo declarations.

Goods movements
~~~~~~~~~~~~~~~

Goods can be moved among warehouses, departments and its bins. You can
register such movement using documents **Inventory movement** and
**Movement among bins**. If a two-phase warehouse is used, additionally
register documents **Debit slip** and **Credit slip** on goods shipment
and receipt.

Movement among bins
~~~~~~~~~~~~~~~~~~~

Use the **Movement among bins** document to register transfer of
products and services items among different bins of the same business
unit. It is available only if the **Inventory accounting by bins** check
box is selected in accounting parameters.

To access the document list, in the **Purchases** section, in the
**Warehouse** subsection, click **Movement among bins**.

|image1521153995774855|

In the document, specify a starting and final destination for the goods
being moved with precision to a warehouse bin. You can use the following
operation kinds of movement among bins:

-  Movement from one bin to several

-  Movement from several bins to one

Specify standard information about moved goods (name, characteristic,
quantity, and other) in the table field of the form.

Inventory movement
~~~~~~~~~~~~~~~~~~

Use the **Inventory movement** document to register movement of products
and services items between different storage locations, as well as to
write off inventory for internal consumption.

You can access a list of documents by clicking **Inventory movements**
in the **Warehouse** subsection in the **Purchases** section.

|image1521153994425361|

As a shipping warehouse, specify a warehouse from which goods are
shipped and if required its bin (attributes **Sender** and **Storage
bin** accordingly). As a receiving warehouse (the **Recipient**
attribute), specify a department to which goods are received.

Depending on the selected operation kind (**Movement**, **Write off as
expenses**, **Commissioning** or **Return from operation**), use the
document to display:

-  Inventory movement between warehouses

-  Inventory movement between production departments

-  Inventory movement from warehouse to production

-  Inventory movement (return) from production to warehouse

-  Inventory write-off for internal consumption

-  Inventory transfer to operation

-  Inventory return from operation

Option selection is also determined by the type of source business unit
and recipient.

Registering product movement based on release document
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Use the **Manufacturing** document to register product release. Enter
this document based on the **Production order** document. The entered
document is a basis for the **Inventory movement** document using which
you can register movement of manufactured products to a new storage
location.

Registering movement of goods reserved against customer order
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To register movement of the goods reserved against a customer order, in
the **Inventory movement** document, specify a warehouse to move the
goods to as a receiving warehouse. Specify a warehouse where the goods
were reserved as a shipping warehouse. Fill in table field of the
document form with all items reserved against customer order in the
shipping warehouse taking into account the real product balance in
warehouse. For each item, you can specify quantity of reserved goods
intended for movement in the **Reserve** column.

You can create a single movement document for several orders. In this
case, specify information about each order in the **Customer order**
column of the table field of the document form.

Example

Goods were reserved against customer order in the **Main warehouse**. It
is more convenient for customer to take a part of the goods from another
warehouse (e.g. **temporary storage warehouse**). In the **Inventory
movement** document, specify the corresponding order in the **Customer
order** column. In the **Reserve** column, specify the quantity of
product units the customer wants to take from the shop. Specified
quantity of the goods reserved against order will be shipped from
temporary storage warehouse. On posting the **Goods issue** document,
the reserve shipped against customer order is removed automatically.

Additional expenses
~~~~~~~~~~~~~~~~~~~

You can use the **Additional expenses** document to record in accounting
additional expenses that increase the cost of inventory received from
counterparties. To access the document, in the **Purchases** section, in
the navigation panel, click **Additional expenses**.

|image1521153991865782|

In the document table field, specify goods receipts for registering
goods receipt with additional expenses and goods to which cost these
expenses will be allocated. To allocate cost, click **Allocate
expenses**, and then click **By quantity** or **By amount**. Based on
the document, a separate invoice with additional expense list is
generated.

Power of attorney
~~~~~~~~~~~~~~~~~

You can use the **Power of attorney** document to register powers of
attorney for receipt of goods. To access the document, in the **See
also** group, in the navigation panel, click **Powers of attorney**.

|image1521153999343250|

In the document, specify a goods supplier and an individual to whom
their receipt is trusted. You can specify a document for receiving goods
in the **Basis** field, i.e. **Purchase order**. Specify a goods list in
the table field.

Surplus and shortage
~~~~~~~~~~~~~~~~~~~~

You can access a journal of warehouse acts of physical inventory,
inventory capitalization and write-off by clicking **Warehouse acts** in
the navigation panel in the **Surplus and shortage** subsection of the
**Purchases** section.

|image1521153999366967|

Physical inventory
~~~~~~~~~~~~~~~~~~

You can use the **Physical inventory** document to carry out physical
inventory in a production department or a warehouse. The document does
not generate movements.

You can access the document by clicking **Physical inventory** in the
navigation panel in the **Surplus and shortage** group of the
**Purchases** section.

|image1521153996211389|

In the document, it is required to specify a warehouse or a production
department in which physical inventory is carried out. You can
additionally specify a storage bin which belongs to this storage
location if accounting by bins is kept in the application.

In the table field of the document form, enter information about the
product. Specify a product name, its characteristic, unit of measure,
quantity and amount (accounting and actual), and price. If batch
accounting is kept, specify a batch.

To automatically fill in a product list with remaining goods in the
warehouse, click **Fill in**, and then click the corresponding command
in the menu. To specify only accounting data in the table field without
filling in columns for actual product quantity, click **Fill in only
accounting data**.

Based on the **Physical inventory** document, you can generate documents
**Inventory capitalization** for surplus, **Inventory write-off** for
shortage write-off and **Entry of opening balance**. Table fields of
these documents depend on the carried out physical inventory. Enter
surplus of products and services items detected during physical
inventory into the **Inventory capitalization** document. Enter the
detected shortage into the **Inventory write-off** document.

You can enter opening balance for the **Inventory** section based on the
physical inventory document.

After posting these documents, quantity of products and services items
in the warehouse will be equal to the actual quantity.

Inventory capitalization
~~~~~~~~~~~~~~~~~~~~~~~~

To register capitalization of tangible assets to the warehouse or
production department, you can use the **Inventory capitalization**
document.

The document can be registered based on the carried out physical
inventory or an unlinked document in case of arbitrary goods
capitalization.

You can access the capitalization document journal by clicking
**Inventory capitalization** in the navigation panel (the **Surplus and
shortage** group) of the **Purchases** section.

If there is no **Inventory capitalization** link in the navigation
panel, add it. Click **Navigation settings** in the upper right corner
of the navigation panel. The **Navigation panel setup** form opens. Move
the **Inventory capitalization** link from the left side (objects which
you can add to the navigation panel) to the right side (objects which
you see in the navigation panel) by clicking **Add**.

|image1521153995277895|

In the document, fill in the **Correspondence** attribute to specify an
offsetting GL account, as well as main attributes (information about
company on whose behalf the document is registered, business unit and
storage bin to which goods are capitalized). In the **Basis** field,
specify the physical inventory document based on which capitalization is
carried out.

In the table field of the document form, specify information about
goods. This information is fully consistent with the information of the
**Physical inventory** document. If capitalization is carried out based
on this document, the table field will contain information about goods
surplus detected during physical inventory, including prices.

Specify information about goods with different characteristics as
separate lines of the capitalization document.

Inventory write-off
~~~~~~~~~~~~~~~~~~~

Use the **Inventory write-off** document to register write-off of
tangible assets from a warehouse or a production department from its
storage bin. The document can be registered based on carried out
physical inventory or an unlinked document in case of arbitrary product
write-off.

You can access the write-off document journal by clicking **Inventory
write-off** in the navigation panel (the **Surplus and shortage** group)
in the **Purchases** section.

If there is no **Inventory write-off** link in the navigation panel, add
it. Click **Navigation settings** in the upper right corner of the
navigation panel. The **Navigation panel setup** form opens. Move the
**Inventory write-off** link from the left side (objects which you can
add to the navigation panel) to the right side (objects which you can
see in the navigation panel) by clicking **Add**.

|image1521153995368688|

Fill in the document form in the same manner as for the **Inventory
capitalization** document. The only difference is that the product is
written off but not capitalized.

If you register the document based on the **Physical inventory**
document, a table field of the form is filled in automatically according
to shortage information detected during the physical inventory.

Inventory acceptance for commission
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

With «1C:SimpleERP», you can take advantage of automated recording of
business transactions of acceptance and transfer of goods for
commission.

.. _goods-acceptance-for-commission-1:

Goods acceptance for commission
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To record goods receipt for commission in accounting, use the **Goods
receipt** document with the **Acceptance for commission** operation
kind.

|image1521153991724322|

In the table field, you can specify an order document under which
acceptance is carried out for each product. You can return goods
accepted for commission to the principal in the same manner as you
return goods received from the supplier. To register commission goods
return, use the **Goods issue** document with the **Return to
principal** operation kind.

To distinguish between own inventory on the company's balance sheet and
received inventory which is not on the company's balance sheet, specify
a delivery batch on acceptance and keeping records of goods for
commission, processing, or safe custody. For each type of inventory
there can be one batch with the corresponding status or several batches.
For example, for each delivery there is its own batch.

.. _sales-report-to-principal-1:

Sales report to principal
~~~~~~~~~~~~~~~~~~~~~~~~~

Use the **Report to principal** document to report to principal on sold
goods and calculate the commission.

|image1521153996855649|

In the table field of the **Inventory** tab, you can see all information
from the table field of the goods receipt using which you can register
goods acceptance for commission. In the table field, you can also see
information about prices and amounts of receipts and sales. In the
**Order** column, specify a sales order against which the goods received
for commission were sold. In the **Commission amount** column, specify
our company commission amount calculated using the information specified
on the **Additionally** tab.

Accepting for processing and safe custody
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

With the application, you can receive goods for processing and safe
custody (it is sale of customer goods processing and storage). These
receipt kinds are carried out using goods receipts for which the
**Receipt for processing** (**Receipt for safe custody**) operation kind
is set. To access the **Goods receipt** document form, in the
**Purchases** group, in the navigation panel, click **Goods receipts**.
The documents are registered in the same manner as commission trade
documents.

Transferring for processing and safe custody
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

With the application, you can transfer goods for processing and safe
custody (in fact, it is the purchase of services of processing and
storage of company goods). To enable this option, in the **Settings**
section, in the **Purchases** accounting settings, select the
**Inventory receipt for safe custody** and **Inventory transfer for safe
custody** check boxes. These transfer kinds are executed using the goods
issues for which the **Transfer to processing** (**Transfer for safe
custody**) operation kind is specified. To access the **Goods issue**
document form, in the **Sales** section navigation panel, click **Goods
issues**. The documents are registered in the same manner as commission
trade documents.

Use the **Processor report** document to enter processing of raw
materials and materials transferred to the processor in accounting. To
access the document, in the **Purchases** section, in the **Processing**
group, click **Processor reports**. The document form looks like:

|image1521153996470975|

The document contains information about the processor and concluded
contact. Enter data about products received due to processing into the
**Products** attribute group: finished product name according to the
**Products and services** catalog, quantity, unit of measure,
characteristic, production bill of materials. The list of goods
transferred to processing and consumed for manufacturing is specified on
the **Materials** tab.

The **Waste** tab contains the list of side products, i.e., products and
services manufactured due to processing. Waste is capitalized at zero
cost.

|image1521153997831582|

Information about processor services is specified on the **Services**
tab: service name, its cost and VAT amount.

|image1521153997166775|

Selling goods from two-phase warehouse
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To enable separation of inventory accounting to warehouse and financial
accounting, select the **Use two-phase warehouse** check box in the
**Purchases** accounting settings of the **Settings** section.

Register the **Goods issue** document when selling goods from a
warehouse.

To access the document list, in the **Sales** section, in the **Sales**
subsection, click **Goods issues**.

Mutual settlements and remaining goods in warehouses change after
posting the document. If goods are shipped from a two-phase warehouse,
register the **Issue slip** document for shipment.

Another option of write-off from a warehouse is to return goods which
were received to the warehouse and create financial receipt documents.
In this case, the scheme will be similar to sale of goods.

You can enter the document based on a customer order, a proforma invoice
or a goods receipt.

|image1521153996957699|

In the document table field, specify information about products and
services for sale, including previously entered **Customer order** if
the sale is carried out against the order.

Prepayment setoff
~~~~~~~~~~~~~~~~~

On the **Prepayment** tab, you can see a tabular section to fill in with
information on setoff of advances from customer or setoff of advances to
supplier if a return operation is recorded with the document. Click
**Select** to open a dialog box for editing the **Prepayment setoff**
tabular section.

|image1521153996394318|

In the dialog box, you can enter information about setoff of advances
received earlier from a customer.

|image1521153996369693|

The field in the upper side of the dialog box (the **Advances** group)
is automatically filled in with a list of this customer advances that
are not set off. In the lower side of the dialog box, specify which
payments of this customer recorded with documents **Credit slip** and
**Cash receipt to account** are to be set off as an advance.

Issue slip
~~~~~~~~~~

You can enter the document based on the goods issue. Use the document to
register shipment from a two-phase warehouse. To access the document
list, in the **Purchases** section, in the **Warehouse** subsection,
click **Issue slips**.

If there is no **Issue slips** link in the navigation panel, add it. To
add it, click **Navigation settings** in the **Purchases** panel. The
**Navigation panel setup** form opens. Move the **Issue slips** link
from the left side (items which you can add to the navigation panel) to
the right side (items which you can see in the navigation panel) by
clicking **Add**.

|image1521153999395768|

In the form table field, enter a list of products and services items
shipped from a two-phase warehouse. For each item, specify a name, a
characteristic, a unit of measure and quantity.

Receiving goods to a two-phase warehouse
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Use the **Goods receipt** document to record receipt of goods to a
warehouse.

To access the document list, in the **Purchases** section, click **Goods
receipts**. When you post this document, remaining goods in the
accounting system and mutual settlements state change. If goods are
received to a two-phase warehouse, create the **Receipt slip** document.

You can enter the goods receipt based on the **Purchase order**
document. Inventories earlier written off from a warehouse can also be
returned to the warehouse. In this case, financial sale documents are
registered. Document flow scheme will be similar to receipt.

|image1521153994152388|

In the document on the **Goods** tab, specify standard information about
received inventory – a name, a characteristic, quantity, a price, and an
amount. In the **Order** column, you can see a link to the **Purchase
order** basis document.

Receipt slip
~~~~~~~~~~~~

Use the document to register receipt of tangible assets to a two-phase
warehouse. You can create a goods receipt document based on this
document.

To access the document list, in the **Purchases** section, in the
**Warehouse** subsection, click **Receipt slips**.

If there is no **Receipt slips** link in the navigation panel of the
**Purchases** section, add it. To add it, click **Navigation settings**
in the **Purchases** section. The **Navigation panel setup** form opens.
Move the **Receipt slips** link from the left side (items which you can
add to the navigation panel) to the right side (items which you can see
in the navigation panel) by clicking **Add**.

|image1521153999424586|

In the document table field, enter a list of products and services items
received to a two-phase warehouse. For each item, specify a name, a
characteristic, a unit of measure and quantity.

If you register inventory movement to a two-phase warehouse, enter
**Receipt slip** as the inventory movement document does not generate
receipt movements by a two-phase warehouse.

Calculating inventory demand
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The application includes a specific data processor calculating company
inventory demand (shortage). To open the data processor, in the
**Purchases** section, click **Demand calculation**.

|image1521153994376777|

The data processor form contains a tree of products and services items
and information about them.

In table field columns of the data processor, you can specify products
and services, characteristics and overdue demand (in products and
services units) on the current date, and demand forecast by dates.

If you select an item in the tree and expand it, you can receive
information on the calculation basis: forecasted inventory balance,
expected receipt and consumption, minimum and maximum inventory levels
(the latter is specified in the **Inventory management** information
register. You can access it from a products and services card). Basis
can be detailed up to orders, which are sources of inventory receipt and
consumption.

On the **Recommendations** tab, you can see a list of products and
services items with shortage and inventory replenishment methods.
Replenishment method main for products and services is represented as
"…(main)".

|image1521153994318091|

For each products and services item, in the **Characteristic/Source**
column, specify products and services characteristic with suppliers. The
main supplier is defined on the basis of the products and services card
data and information on suppliers using which prices for these products
and services were registered. Besides, in the table field, you can
specify a receipt date, i.e. inventory demand date with possible receipt
dates. The latest date from inventory demand date and the current date
including replenishment deadline is specified.

Select a check box for the products and services item to be included in
the order. By default, check boxes are selected for the items whose
demand dates are greater than or equal to the date of expected receipt.

Besides, for every products and services item, specify shortage amount,
a price registered on products and services receipt from a counterparty
(according to the counterparty price list), cost, a currency and a price
kind from the counterparty price list.

On the **Orders** tab, click **Generate orders**. Orders including
products and services items with selected check boxes will be generated
automatically.

|image1521153994345522|

Orders are generated according to the following rules:

-  Order type is defined by replenishment method of products and
services item (for purchase, the **Purchase order** document with the
**Purchasing order** operation kind is generated. For production, the
**Production order** document is generated. For processing, the
**Purchase order** document with the **Processing order** operation
kind is generated).

-  If a supplier is known, the default counterparty contract is
automatically inserted into the order.

-  Products and services items with the same indicators, for example, a
replenishment method, a counterparty, a currency, a receipt date (if
the **Specify planned receipt date in the tabular section** radio
button is set in the accounting parameter settings) are grouped into
a single order.

Use buttons of the command bar |image1521153999451719|
to post the order selected in the list or cancel the order posting. You
can mark for deletion orders generated by mistake.

Counterparty price lists
~~~~~~~~~~~~~~~~~~~~~~~~

With the application, you can generate and print a counterparty price
list using the **Counterparty price lists** data processor.

|image1521153992636490|

Prices are registered in the application by posting the **Goods
receipt** document with the counterparty price kind and the selected
**Register supplier prices** check box. This data is displayed in the
**Counterparty price lists** data processor. You can change the data
using the **Counterparty products and services price** dialog box.

|image1521153999482254|

The application saves information about all users who changed the price
of products and services or counterparty products and services.

Counterparty price kinds
~~~~~~~~~~~~~~~~~~~~~~~~

In the application, you can store prices of suppliers and company
competitors, as well as print a price list of the selected counterparty.
You can automatically insert counterparty prices into goods receipts and
purchase orders and register them by goods receipts.

You can change company own prices (to percent or amount), calculate them
according to the basic price kind, products and services prices or
counterparty prices, round off products and services prices, or delete
price values. Specify price calculation methods in the **Price kinds**
catalog. Prices are recalculated dynamically in the document (dynamic
prices) or in a special data processor (calculated prices).

Data on price kinds, discounts, counterparty prices under the contract,
price kind format used when displaying prices in the price list is
stored in the infobase. When you select a contract, default values are
automatically inserted into the document and company own prices are
recalculated.

Purchasing reports
~~~~~~~~~~~~~~~~~~

You can access **Purchasing** reports by clicking **Inventory and
purchasing reports** in the panel.

|image1521153999508105|

Inventory demand
~~~~~~~~~~~~~~~~

With the **Inventory demand** report, you can identify demands for raw
materials and materials required for production (both from own and
supplier's raw materials) and for transferring for processing.

|image1521153999537960|

The report shows demand for products and services and how to satisfy the
demand by displaying unsatisfied demand.

You can satisfy demand for products and services using the following
methods:

-  Reservation in storage location

-  Placement in a purchase order

-  Placement in a production order

The selected option is registered by documents generated on the basis of
the **Customer order** document.

Inventory movement schedule
~~~~~~~~~~~~~~~~~~~~~~~~~~~

In the **Inventory movement schedule** report, you can see planned
receipts and shipments of products and services in quantitative terms
over the selected time period.

|image1521153994401706|

You can display the schedule with details by dates.

Order placement
~~~~~~~~~~~~~~~

To access the **Order placement** report, in the **More** menu, click
**All reports**, and then click **Order placement**. The **Order
placement** report contains data on orders that are fulfilled due to
receipts under other orders. The report is generated with details up to
products and services. It can be generated in the following modes:
**Statement** and **Balance**.

|image1521153995918406|

Inventory turnover
~~~~~~~~~~~~~~~~~~

Use the report to analyze the **Turnover** and **Average inventory
storage time (days)** indicators.

The **Turnover** indicator is calculated as ratio between inventory
consumption over the period and average remaining inventory over the
period. The **Average inventory storage time (days)** indicator is
calculated as ratio between a number of period days and inventory
turnover.

|image1521153995336788|

You can manage the indicator calculation precision by setting the
calculation frequency. It is not recommended to generate the report if
the period end and start are not set.

Payable by periods
~~~~~~~~~~~~~~~~~~

To access the **Order placement** report, in the **More** menu, click
**All reports**, and then click **Order placement**. In the **Payable by
periods** report, you can see an amount of company debt to
counterparties with debt periods – less than a week, 1-2 weeks, 2 weeks
– a month, 1-2 months, over two months.

The report also shows information about total debt, overdue receivable
amount and number of overdue days.

The report is generated for a specific date or the current one if the
date is not set.

Purchase orders
~~~~~~~~~~~~~~~

Use the report to analyze company purchase orders. You can access the
report by clicking **All reports...**. There are the following modes of
the report generation: **Statement** and **Balance**.

In the **Statement** mode, you can see information about purchase orders
registered over the specified period. Orders are grouped by suppliers
(counterparties). For each order, specify products and services listed
in it and products and services turnover: **Opening balance** and
**Closing balance**, **Ordered** and **Received**.

|image1521153995999190|

In the **Balance** mode, the report contains information about
allocation of order balance for purchase on the specified date. Data is
grouped by suppliers.

|image1521153999568736|

Order payment
~~~~~~~~~~~~~

With the report, you can analyze purchase order payment. To access the
report, in the **Mutual settlements** report group, click **Order
payment**.

|image1521153999619982|

The report data is grouped by suppliers, companies and contracts.

.. _invoice-payment-1:

Invoice payment
~~~~~~~~~~~~~~~

In the report, you can see data on supplier invoice payment. To access
the report, in the **Mutual settlements** report group, click **Invoice
payment**.

|image1521153999650401|

The report data is grouped by suppliers and contracts.

.. _purchases-2:

Purchases
~~~~~~~~~

With the **Purchases** report, you can analyze products and services
purchased by the company over the specified period. You can access the
report by clicking **Purchases** in the **All reports** group. In the
report, you can see information about quantity and amount of purchase.
Data is grouped by orders and products and services.

|image1521153996700052|

Settlements with suppliers
~~~~~~~~~~~~~~~~~~~~~~~~~~

Use the **Settlements with suppliers** report to see dynamics of
settlements with counterparties over the specified period. You can
access the report by clicking the corresponding link in the **All
reports** group. You can generate the report in the following modes:
**Statement** and **Balance**.

In the **Statement** mode, you can see information about settlements
with suppliers, including orders and contracts under which there were
transactions between the company and counterparties.

|image1521153997240449|

The report is generated over the specified period. The report data is
grouped by counterparties, contracts and orders.

In the **Balance** mode, you can see information about balance of
settlements with suppliers, including orders and contracts under which
there were transactions between the company and counterparties.

In the **Balance** mode, there are the same data groups as in the
**Statement** mode.

.. _mutual-settlements-1:

Mutual settlements
~~~~~~~~~~~~~~~~~~

With the **Mutual settlements** report, you can see state and dynamics
of mutual settlements with counterparties (customers, suppliers, etc.)
over the specified period.

.. _inventory-1:

Inventory
~~~~~~~~~

With the **Inventory** report, you can receive full information about
receipt, shipment and current quantity of inventory in unrestricted
stock and reserve under customer orders. To access the report, in the
**See also** report group, click Inventory. Data is additionally grouped
by warehouses.

Below, you can see an example of the report with a filter set by company
and products and services. The report contains information about opening
and closing balance in the company and counterparty warehouses. The
report data is presented in quantitative and value terms.

|image1521153999687314|

You can generate the report in the following modes: **Statement** and
**Balance**. In the **Balance** mode, the report does not display
information on receipt and consumption and shows only closing balance.

|image1521153991521726|

Inventory by CCD
~~~~~~~~~~~~~~~~

You can analyze inventories imported from foreign countries using the
**Inventory by CCD** report. You can access the report from the **See
also** report group. In the **Statement** mode, the report allows you to
receive full information about receipt, shipment and current quantity of
any imported product having the CCD number, in the selected storage
location. The report data is presented in quantitative terms.

|image1521153995247214|

In the **Balance** mode, the report does not display information on
receipt and consumption. It shows only closing balance.

|image1521153991548254|

Received inventory
~~~~~~~~~~~~~~~~~~

The report allows you to receive full information about inventory
received for commission, processing or safe custody. You can access the
report from the **See also** report group.

|image1521153996802677|

The report contains information about opening and closing balance of
counterparty inventory in the company warehouses. The report data is
presented in quantitative and value terms.

You can generate the report in the following modes: **Statement** and
**Balance**. In the **Balance** mode, the report does not display
information on receipt and consumption and shows only closing balance.

|image1521153990642854| 

Transferred inventory
~~~~~~~~~~~~~~~~~~~~~

The report allows you to receive full information about inventory
transferred for commission, processing or safe custody by a third party
counterparty. You can access the report from the **See also** report
group.

|image1521153997624896|

The report contains information about opening and closing balance of
counterparty inventory. The report data is presented in quantitative and
value terms.

You can generate the report in the following modes: **Statement** and
**Balance**. In the **Balance** mode, the report does not display
information on receipt and consumption. It shows only closing balance.

Remaining quantity in warehouse
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To access the report, in the **Purchases** section, click **More**, and
then click **All reports**.

The report does not display information about receipt and consumption.
It shows only closing balance in storage locations.

|image1521153999721803|

Receipt and payment under orders
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Use the report to analyze state of purchase order payments and receipt.
To access the report, in the **Purchases** section, in the **More**
menu, click **All reports**.

|image1521153990711559|

The data is grouped by products and services and purchase orders.

The report presents the following information about payment for goods
under order: order amount, paid amount and amount for repayment to fully
pay for the order.

The report presents information about goods receipt displaying the
following goods quantity in base units: specified in the order,
received, and quantity to receive. You can also see goods quantity under
the customer order placed in this purchase order.

Goods movement among warehouses
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Use the report to get information about receipt, shipment and current
quantity of goods in the selected storage location. Data is grouped by
warehouses.

Below, you can see an example of the report with a filter set by company
and products and services. In the report, you can see information about
opening and closing balance in warehouses and counterparty-processors.
The report data is presented in quantitative and value terms.

|image1521153999746388|

If a two-phase scheme is used for corresponding warehouses, you can see
information about inventory quantity to be written off with issue slips
and inventory quantity to be capitalized with goods receipts.

Serial numbers and guarantee periods
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In «1C:SimpleERP» you can use serial numbers and guarantee periods.

Who will benefit from this solution? First of all, electronic stores and
other trading companies which keep accounting of goods using serial
numbers.

It can also be useful for manufacturing companies which assign serial
numbers to finished products or use components with serial numbers.

By specifying a serial number on sale, you record the sale of a specific
product unit and print a guarantee card.

Guarantee period and sale date are registered in products and services
card, and based on this data the application helps to control the
guarantee period.

A user can quickly determine a sale date on return by generating a
report by the serial number.

To make serial numbers and guarantee period available, in the
**Settings** section, click **Purchases**, and then select the **Use
serial numbers** check box.

|image1521153992248347|

You can specify serial numbers for reference and also control balance
considering these numbers.

If you use serial numbers for reference, they are optional. Serial
numbers are entered in the sale documents when a product is transferred
to a customer to register a guarantee period start.

**Important!** Serial numbers are unique for each products and services
item.

You can determine whether accounting by serial numbers is kept for this
specific products and services item for each products and services item.

If serial numbers are required for the product, select the **Use serial
numbers** check box in the products and services card.

|image1521153998736716|

If you need to control product guarantee period, fill in the following
parameters on the **Production and procurement** tab of the products and
services card:

|image1521153998763782|

Select the **Write out guarantee card** check box to print a guarantee
card on sale.

Accounting of goods with serial numbers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you enable serial numbers, the **Serial numbers** column will appear
in the **Products** tabular section of all receipt documents (supplier
invoice, entry of opening balance, receipt slip, production).

If balance control by numbers is used, the column is required. Users can
use a selection form to facilitate serial number input:

|image1521153998789657|

In this form, you can:

|image1521153990761449|
– Read a serial number with a barcode scanner.

When registering serial numbers using a scanner, a number and a barcode
of this serial number will be recorded in the application.

|image1521153998814440| – Select a serial number from those created earlier.

|image1521153998843359| – Enter manually using a keyboard. If number template is
specified, unchanged part will be inserted automatically.

|image1521153998868936| – Create a serial number.

|image1521153998898333| – Create a required quantity of serial numbers. Available
actions are **Generate numbers in order** and **Fill with numbers from
the range**.

Serial number shall include not more than 25 characters. The number can
be created from template or in free format.

|image1521153998920003|

If balance control is enabled, serial numbers are required in all goods
movement documents.

Serial numbers in shipment and movement documents are selected according
to the current availability status.

|image1521153998947179|

While scanning a barcode, all data about the scanned product as well as
a serial number are filled out in documents.

Barcode can be generated both for products and services item and for a
separate serial number of a product. Barcodes in 1C shall be unique.

Reports
~~~~~~~

Use the following reports to control balance and turnovers with serial
numbers:

-  Serial number movements

-  Serial number balances

-  Record serial number by warehouses

These reports can be found in the report list using the Serial numbers
tag.

|image1521153998973849| 

.. |image1521153996160768| image:: media/image116.png
   :width: 4.63542in
   :height: 2.20833in
.. |image1521153999271902| image:: media/image117.png
   :width: 3.97917in
   :height: 2.42708in
.. |image1521153996135234| image:: media/image118.png
   :width: 4.67708in
   :height: 3.10417in
.. |image1521153997779131| image:: media/image119.png
   :width: 4.63542in
   :height: 3.92708in
.. |image1521153995306393| image:: media/image120.png
   :width: 2.72917in
   :height: 2in
.. |image1521153997192403| image:: media/image121.png
   :width: 4.63542in
   :height: 3.67708in
.. |image1521153995219167| image:: media/image122.png
   :width: 4.63542in
   :height: 3.66667in
.. |image1521153995865740| image:: media/image123.png
   :width: 4.63542in
   :height: 2.5625in
.. |image1521153991779407| image:: media/image124.png
   :width: 4.63542in
   :height: 2.77083in
.. |image1521153999296681| image:: media/image125.png
   :width: 3.9375in
   :height: 1.875in
.. |image1521153999320901| image:: media/image126.png
   :width: 3.9375in
   :height: 1.25in
.. |image1521153996079112| image:: media/image127.png
   :width: 4.63542in
   :height: 3.42708in
.. |image1521153996050015| image:: media/image128.png
   :width: 4.63542in
   :height: 4.125in
.. |image1521153991401826| image:: media/image129.png
   :width: 4.55208in
   :height: 2.4375in
.. |image1521153991473933| image:: media/image130.png
   :width: 4.55208in
   :height: 2.39583in
.. |image1521153997365381| image:: media/image131.png
   :width: 4.63542in
   :height: 4.54167in
.. |image1521153994152388| image:: media/image91.png
   :width: 4.63542in
   :height: 3.79167in
.. |image1521153991891976| image:: media/image132.png
   :width: 4.67708in
   :height: 2.3125in
.. |image1521153994174842| image:: media/image133.png
   :width: 4.67708in
   :height: 3.76042in
.. |image1521153994080099| image:: media/image134.png
   :width: 4.65625in
   :height: 3.71875in
.. |image1521153996830180| image:: media/image135.png
   :width: 4.63542in
   :height: 3.82292in
.. |image1521153995774855| image:: media/image136.png
   :width: 4.63542in
   :height: 3.85417in
.. |image1521153994425361| image:: media/image90.png
   :width: 4.625in
   :height: 3.21875in
.. |image1521153991865782| image:: media/image137.png
   :width: 4.63542in
   :height: 3.78125in
.. |image1521153999343250| image:: media/image138.png
   :width: 3.9375in
   :height: 2.84375in
.. |image1521153999366967| image:: media/image139.png
   :width: 4.63542in
   :height: 2.34375in
.. |image1521153996211389| image:: media/image140.png
   :width: 4.63542in
   :height: 3.78125in
.. |image1521153995277895| image:: media/image141.png
   :width: 4.625in
   :height: 3.15625in
.. |image1521153995368688| image:: media/image142.png
   :width: 4.63542in
   :height: 3.16667in
.. |image1521153991724322| image:: media/image87.png
   :width: 4.63542in
   :height: 3.41667in
.. |image1521153996855649| image:: media/image88.png
   :width: 4.625in
   :height: 2.92708in
.. |image1521153996470975| image:: media/image143.png
   :width: 4.63542in
   :height: 3.59375in
.. |image1521153997831582| image:: media/image144.png
   :width: 4.63542in
   :height: 2.16667in
.. |image1521153997166775| image:: media/image145.png
   :width: 4.63542in
   :height: 2.16667in
.. |image1521153996957699| image:: media/image146.png
   :width: 4.66667in
   :height: 3.77083in
.. |image1521153996394318| image:: media/image147.png
   :width: 4.625in
   :height: 1.52083in
.. |image1521153996369693| image:: media/image148.png
   :width: 4.63542in
   :height: 3.34375in
.. |image1521153999395768| image:: media/image149.png
   :width: 3.9375in
   :height: 1.96875in
.. |image1521153994152388| image:: media/image91.png
   :width: 4.63542in
   :height: 3.79167in
.. |image1521153999424586| image:: media/image150.png
   :width: 3.9375in
   :height: 2.02083in
.. |image1521153994376777| image:: media/image151.png
   :width: 4.63542in
   :height: 2.15625in
.. |image1521153994318091| image:: media/image152.png
   :width: 4.63542in
   :height: 2.15625in
.. |image1521153994345522| image:: media/image153.png
   :width: 4.63542in
   :height: 2.16667in
.. |image1521153999451719| image:: media/image154.png
   :width: 0.27083in
   :height: 0.125in
.. |image1521153992636490| image:: media/image55.png
   :width: 4.625in
   :height: 3.22917in
.. |image1521153999482254| image:: media/image155.png
   :width: 2.39583in
   :height: 2.39583in
.. |image1521153999508105| image:: media/image156.png
   :width: 4.58333in
   :height: 5.52083in
.. |image1521153999537960| image:: media/image157.png
   :width: 3.9375in
   :height: 2.84375in
.. |image1521153994401706| image:: media/image158.png
   :width: 4.63542in
   :height: 2.71875in
.. |image1521153995918406| image:: media/image159.png
   :width: 4.63542in
   :height: 2.5in
.. |image1521153995336788| image:: media/image160.png
   :width: 4.63542in
   :height: 3.3125in
.. |image1521153995999190| image:: media/image161.png
   :width: 4.63542in
   :height: 3.26042in
.. |image1521153999568736| image:: media/image162.png
   :width: 3.9375in
   :height: 2.13542in
.. |image1521153999619982| image:: media/image163.png
   :width: 3.9375in
   :height: 2.13542in
.. |image1521153999650401| image:: media/image164.png
   :width: 3.9375in
   :height: 1.97917in
.. |image1521153996700052| image:: media/image165.png
   :width: 4.63542in
   :height: 3.29167in
.. |image1521153997240449| image:: media/image166.png
   :width: 4.63542in
   :height: 2.41667in
.. |image1521153999687314| image:: media/image167.png
   :width: 4.40625in
   :height: 2.86458in
.. |image1521153991521726| image:: media/image168.png
   :width: 4.4375in
   :height: 3.08333in
.. |image1521153995247214| image:: media/image169.png
   :width: 4.625in
   :height: 2.36458in
.. |image1521153991548254| image:: media/image170.png
   :width: 4.53125in
   :height: 1.92708in
.. |image1521153996802677| image:: media/image171.png
   :width: 4.63542in
   :height: 2.0625in
.. |image1521153990642854| image:: media/image172.png
   :width: 4.46875in
   :height: 2.90625in
.. |image1521153997624896| image:: media/image173.png
   :width: 4.63542in
   :height: 2.375in
.. |image1521153999721803| image:: media/image174.png
   :width: 4.21875in
   :height: 2.39583in
.. |image1521153990711559| image:: media/image175.png
   :width: 4.39583in
   :height: 2.76042in
.. |image1521153999746388| image:: media/image176.png
   :width: 4.25in
   :height: 2.16667in
.. |image1521153992248347| image:: media/image177.png
   :width: 4.60417in
   :height: 2.66667in
.. |image1521153998736716| image:: media/image178.png
   :width: 4.65625in
   :height: 2.67708in
.. |image1521153998763782| image:: media/image179.png
   :width: 4.65625in
   :height: 0.89583in
.. |image1521153998789657| image:: media/image180.png
   :width: 4.73958in
   :height: 1.89583in
.. |image1521153990761449| image:: media/image181.png
   :width: 0.41667in
   :height: 0.33333in
.. |image1521153998814440| image:: media/image182.png
   :width: 0.875in
   :height: 0.30208in
.. |image1521153998843359| image:: media/image183.png
   :width: 0.96875in
   :height: 0.29167in
.. |image1521153998868936| image:: media/image184.png
   :width: 1.28125in
   :height: 0.28125in
.. |image1521153998898333| image:: media/image185.png
   :width: 1.05208in
   :height: 0.28125in
.. |image1521153998920003| image:: media/image186.png
   :width: 4.53125in
   :height: 2.88542in
.. |image1521153998947179| image:: media/image187.png
   :width: 4.41667in
   :height: 1.65625in
.. |image1521153998973849| image:: media/image188.png
   :width: 4.38542in
   :height: 2.27083in
