CHAPTER 3
=========

.. _sales-1:

SALES
~~~~~

In «1C:SimpleERP», business transactions related to trading activities
of the company are recorded automatically. To start operating with the
**Sales** subsystem, go to the **Sales** section.

COUNTERPARTIES
~~~~~~~~~~~~~~

**Counterparties** involve suppliers and customers, companies and
individuals. The catalog has hierarchical structure. All counterparties
can be divided into catalog classifier groups, for example,
**Suppliers**, **Customers**, **Agents**.

To access the **Counterparties** catalog, in the **Sales** section, in
the navigation panel, click **Counterparties**. Enter counterparty data
on the counterparty card form.

|image1521153994269502|

Specify a company type (legal entity or individual) for each
counterparty using the **Counterparty kind** radio button. Depending on
the selected option, you will see different fields in the card: there is
an additional field **Individual** for an individual. Values of this
attribute are selected from the **Individuals** catalog.

Specify default values of a contract with the counterparty and a bank
account in the **Used as primary** group of the counterparty's card.

In the **Mutual settlements accounting** group, select one (simple mode)
or several (advanced mode) dimensions of keeping mutual settlements with
a counterparty. Depending on your selection, there is different number
of dimensions in documents to be filled in to generate a report on
mutual settlements with counterparties by corresponding sections.

|image1521153994246824|

To quickly enter addresses, use the address classifier. Enter addresses
and phones using a special dialog box.

|image1521153998320793|

|image1521153998343897|

Counterparty contact persons
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can register interactions between a counterparty and a company as
events (for example, phone calls, emails received from counterparty
representatives or vice versa addressed to them) in the infobase. A list
of such representatives is stored in the infobase, in the **Counterparty
contact persons** catalog subordinate to the **Counterparties** catalog.

|image1521153998373116|

Specify a full name and a role for each counterparty. You can edit
information on contact persons of a counterparty in a separate window.
You can open it from the list form of the **Contact persons** catalog.

In the **Individual** attribute, specify an individual that corresponds
to a contact person by selecting the required value from the
corresponding catalog. Thus, you can store complete information about
each contact person including passport data.

In the **Responsible person** field, specify a person responsible for
entering information. Select them from the **Employees** catalog.

In the lower side of the form, specify dates of registration and end of
interaction with the contact person.

On the **Roles** tab, specify a role of each contact person. Role values
are selected from the corresponding catalog.

|image1521153998404609|

On the contact person form, the **Additionally** (for entering an
arbitrary employee comment) and **Addresses** (for specifying contact
information of a counterparty: an email, a phone number) tabs are
available.

In the application, you can print contact information of counterparties.

|image1521153993175676|

To print contact information, in a counterparty list, perform the
following steps:

-  Select required counterparties. You can select either a single
counterparty or an entire group.

-  Expand the **Additional information** group.

-  Click **Print contact information**.

Depending on the specified option (**List** or **Card**), contact
information can be displayed as a line for each counterparty or as a
separate area.

Events such as a phone call, sending email to a contact person of a
counterparty or personal meeting with them are registered and planned
with the **Event** document. |image1521153993102397|

Each event has one of the following states: **Planned**, **Completed**,
**Canceled**. Specify start and end dates (planned and actual) for an
event. You can also specify values of additional attributes whose
content is specified by user. On the basis of an event, you can generate
the following documents:

-  **Work order**

-  **Customer order**

-  **Job order**

-  **Purchase order**

-  **Supplier invoice**

-  **Proforma invoice**

-  **Event**

A user can view history of interaction with the selected counterparty
any time from their card. To display history, click **Events**.

|image1521153993582692|

From a counterparty card you can display a list of all documents related
to a specific counterparty. In the navigation panel, click
**Counterparty documents**.

|image1521153993434994|

Sending emails
~~~~~~~~~~~~~~

To send an email to a counterparty, in the counterparty card, click
**More**, and then click **Send email**.

|image1521153997063387|

To email a generated print document to a counterparty from the document
form, click **Send**.

|image1521153998432516|

The sent email is recorded automatically by the application by
generating the **Event** document.

|image1521153997088535|

You can receive information on sent emails:

-  If you operate with a document, in the navigation menu of the
document, click **Event**.

-  In the event list, filter by the **Email** value.

Employee calendar
~~~~~~~~~~~~~~~~~

To manage events on interaction with counterparties, you can use
**Employee calendar**. To access it, in the **See also** group, click
**Employee calendar**. Use **Employee calendar** to analyze events and
job orders planned for the current period (day, week, month), and
schedule the new ones. On the **My agenda** tab, you can analyze planned
events and jobs.

|image1521153998458675|

To plan events and jobs (both for you and other employees), use
**Employee schedule**.

|image1521153993458581|

To plan a new event, on the **Day** schedule form, double-click or
right-click the schedule scale to open document form **Event** or **Job
order**.

You can also view events in the **Month** presentation. To view it,
click **Month**.

|image1521153998482105|

PRICING
~~~~~~~

Company price list
~~~~~~~~~~~~~~~~~~

With the application, you can sell goods at different prices depending
on conditions. You can generate a price list for every price.

To generate, view, and configure a price list, in the **Prices** group,
click **Counterparty price lists**.

|image1521153992636490|

The price list structure depends on price kinds and price groups. Price
kinds form columns of the price list. Price groups divide the price list
into hierarchical groups.

Using the attributes above the command bar, you can generate the price
list with data filter by prices, price groups, and specific products.

|image1521153992603037|

Besides, you can use advanced filters. To set advanced filters, click
**Setting** and specify the required conditions.

|image1521153990863844|

You can also add, delete, and set products and services prices using the
price list.

Price kinds
~~~~~~~~~~~

To specify price kinds for products and services, use the **Price
kinds** catalog. You can access the catalog by clicking **Price kinds**
in the **Prices** group. There are the following predefined items in the
catalog: **Wholesale price** and **Accounting price**. Users can edit
them and add other price kinds to the catalog.

|image1521153998506419|

In the document, specify the following for every price kind: a name, a
currency, and set whether this price kind will be rounded off.

On the **Main data** tab, specify a price calculation method:

-  Manually

-  Calculated

-  Calculated dynamically

When selecting a value, a help text appears and the form attributes
change.

If you select the **Calculated** or **Calculated dynamically** price
calculation method, required attribute **Basic price kind** appears on
the form. To calculate the price, you can specify a markup percent.

|image1521153998533209|

On the **Price format** tab, specify a format for the selected price
kind using a special dialog box available by clicking **Change**.

|image1521153994708720|

The format is used to display a price in the price list.

Price groups
~~~~~~~~~~~~

Company's products and services can be allocated by price groups. You
can specify a price group value in the products and services card of any
type on the **Main parameters** tab. You can access a price group list
in the **Price groups** catalog by clicking **Price groups** on the
price list form.

|image1521153998559080|

Discounts and markups
~~~~~~~~~~~~~~~~~~~~~

When registering sales, you can set discounts and markups. Their amounts
and terms are stored in the **Markup and discount kinds** catalog. You
can access the catalog by clicking the corresponding link of the
**Prices** group.

|image1521153998583846|

Specify a discount name and its percent (specify a markup percent with
minus sign) for every item of the catalog. You can add an arbitrary
comment.

Using price kinds, discounts and markups
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Company provides customers with discounts which are set, for example,
while registering a sale using the **Goods issue** document based on the
information specified in the table field of the document form. To access
a list of goods issues, in the **Sales** group in the navigation panel,
click **Goods issues**.

|image1521153994058378|

To set a discount for the specified product, on the document form, click
the corresponding hyperlink shown in the picture. Select a price kind.
Select a discount kind from the **Discounts and markups** catalog, then
select the **Refill prices** check box and click **OK**.

|image1521153998605820|

.. _pricing-1:

Pricing
~~~~~~~

Using the **Pricing** data processor sales representatives set prices on
the current date considering new information about prices. You can
access the data processor from the command bar of a price list. The data
processor can set values only for price kinds of products and services
with calculation method **Manually** or **Calculated**.

In attribute group **Step 3. Edit prices**, click **Execute**. Table
field of the data processor is filled in with new price values of the
specified goods. The group attributes depend on the method of changing
prices in the **Fill in price** field:

-  **By prices**

-  **By counterparty prices**

-  **By goods receipt**

-  **Calculate**

-  **Change by %**

-  **Change to the amount**

-  **Round off**

-  **Delete**

-  **Clear relevance**

In this example, you set relevant wholesale prices for the selected
products and services using the **Pricing** data processor. The prices
are changed according to the selected document, a goods receipt.

|image1521153996418013|

Click **Set** in **Step 4** attribute group to set prices for the goods
specified in the table field of the data processor and selected with
check boxes. You can clear some check boxes before setting prices.
Prices specified in the cleared rows will not be set.

CUSTOMER SERVICE
~~~~~~~~~~~~~~~~

Customer service can be simply described as product sale or service
rendering to a customer. Product sale is registered with the **Goods
issue** document, work performance or service rendering – with the
**Acceptance certificate** document.

Main business process of customer service includes the following steps:

-  Registration of customers and their demands – new customers are
registered in the **Counterparties** catalog

-  Registration of customer orders:

-  New item is entered into the **Counterparty** **contracts** catalog

-  **Customer order** document is generated

-  Order fulfillment

Customer order
~~~~~~~~~~~~~~

You can use the **Customer order** document to register customer
intention to purchase goods, works or services. You can find a customer
order list in the order book. To access the order book, in the **Sales**
navigation panel, click **Customer orders**.

|image1521153992576630|

In the order list, you can see information about order fulfillment,
state, and order payment percent.

Order fulfillment details are shown as the order lines.

Order states are determined by font color of the line:

-  Black shows that the order has a request status.

-  Blue shows that the order is in progress.

-  Green shows that the order is fulfilled.

-  Strikeout line shows that the order is closed.

Level of shipment and payment are shown using pie charts.

The **Customer order** document includes information on the order
content and its cost. On the **Main** tab, specify a counterparty
contract under which the document is registered. If the contract itself
does not exist, enter a fictitious contract, for example, **Main
contract**.

Specify a project for which the order is planned in the **Project**
field (only if you enable accounting by projects in accounting parameter
settings).

|image1521153990787434|

To assign a discount for the selected product, on the document form,
click the link highlighted in the picture.

|image1521153994733975|

An additional form appears. On this form, specify a price kind, select a
discount kind from the **Markup and discount kinds** catalog, select the
**Refill prices** check box, and then click **OK**.

You can select one of the following operation types for the order: sales
order and processing order. When registering a processing order, you can
specify a list of raw materials and materials that the customer will
provide to the company for manufacturing products.

You can select a value of the **State** attribute on the order form.
Possible values depend on the **Customer order states** catalog. To
access the catalog, in the **Settings** section, in the **Sales**
accounting settings, click **Customer order states** catalog.

|image1521153998633033|

Users can create any required state values. Assign a status for every
state: **Open**, **In progress**, or **Completed**. The document
behavior depends on the status assigned for the selected order state. If
you specify a state with the **Open** status, for example, **Request**,
the order will become a customer request or a preliminary cost estimate
without movements by registers.

Specify a state value with the **In progress** status for an order being
fulfilled. In this case, the order data is recorded in the payment
calendar and taken into account when calculating inventory demand. When
the order is fulfilled, set the **Completed** value for the **State**
attribute.

To cancel an order having the **Request** or **In progress** state,
select the **Closed** check box.

Users can specify a font color of order states for displaying in the
order list.

For orders having the **In progress** or **Completed** state, you can
schedule payment on the **Payment calendar** tab. You can specify
planned dates, payment method, and percent to be paid not later than the
specified date. Payment (percent) amount and VAT will be auto
calculated.

|image1521153991220792|

Payment data can be represented as a list so that you can schedule
payment in a few steps. To view and edit it, click **As a list**.

|image1521153991356267|

You can configure the customer order. To do it, click the button of the
command bar on the **Setup** form. A dialog box appears. Here you can
specify location of a shipping date of the customer order: in the header
(the order is for the same date) or in the tabular section, for every
row of the document.

|image1521153993409422|

If you want the application to remember these settings for the current
user, click **Remember my choice**. After that, the settings will be
used for insertion into new documents. If it is a one-time operation,
there is no need to remember the settings.

Contract with customer
~~~~~~~~~~~~~~~~~~~~~~

If the **By contracts** check box is not selected in the counterparty
card in the **Mutual settlements accounting** group on the **For
documents** tab, there is no counterparty document dimension by
contracts, and the **Contract** field in the customer order will be
missing. If you select a counterparty document dimension by contracts,
specify a contract when entering the **Customer order** document. You
can store data on contracts in the **Counterparty contracts** catalog
subordinate to the **Counterparties** catalog.

|image1521153998658620|

You can enter a new contract both from counterparty card and when
populating the **Customer order** document.

|image1521153998685652|

Specify a counterparty, a contract number, a date, and a settlements
currency in the catalog item form. The **Name** field is auto populated
based on the contract number and date.

On the **Pricing** tab, you can specify:

-  Allowable number of payable deferral days under the contract with a
customer and a supplier accordingly

-  Values of kinds of prices, discounts, markups, and counterparty
prices. If you select a contract, this data will be inserted into
documents by default.

On the **Contract text** tab, you can select a contract form based on
which a print form will be generated and record values of the list
fields to populate in the selected form.

When editing contract forms, you can insert the following into the form:

-  Branch ID and correspondent bank account of counterparty or own
company

-  Passport data of a counterparty, an individual

-  Company facsimile and logo

-  Document attributes based on which the contract (number, date) is
created

-  Page break

If you create additional attributes for the document based on which the
contract is printed, you can also add these attributes to the contract
form.

You can attach files to the contract (for example, scanned copy of the
printed contract). Files are attached after saving the contract. To
attach files, in the navigation panel of the contract card, click
**Files**. The **Attached files** form will open. In this form, click
**Create** and select a file.

|image1521153992351230|

Before saving the file, you can rename it, add a note, and specify the
author.

If you use digital signature, commands to operate with it become
available on the tab with the same name.

Proforma invoices
~~~~~~~~~~~~~~~~~

After generating an order, a proforma invoice is issued to the customer
to pay for the ordered goods. You can find a list of proforma invoices
in a journal. To access the journal, in the **Sales** navigation panel,
click **Proforma invoices**.

|image1521153998711361|

You can register the document based on an order, a goods issue, or an
acceptance certificate. In the proforma invoice, you can see information
on ordered goods and services, their quantity, and prices.

|image1521153995944377|

In the **Proforma invoice** document, you can schedule payment. To
schedule payment, on the document form, select the **Schedule payment**
check box. The **Payment calendar** tab appears on the document form
where you can specify planned dates, a payment method, and a percent
that must be paid not later than the specified date. Payment (percent)
amount and VAT will be auto calculated. To record expected funds receipt
in the payment calendar, set the **Payment method** radio button to the
required value to specify whether the invoice will be paid in cash or
via bank transfer. If you do not know the payment method, select
**Undefined**.

If you use both a customer order and a proforma invoice to register a
transaction, schedule payment either in the customer order or in the
proforma invoice. Or you can schedule payment partially in the customer
order and partially in the proforma invoice to avoid duplication of
scheduled receipts of funds in the payment calendar.

Inventory reservation
~~~~~~~~~~~~~~~~~~~~~

You can reserve a customer-ordered product with the **Inventory** type
in a warehouse, place in an opened purchase order or a production order
by creating the **Inventory reservation** document based on the order.

You can access the document only if you select the **Use inventory
reservation** check box in the **Purchases** accounting settings of the
**Settings** section.

|image1521153995394295|

In columns **Original location** and **New location**, specify business
units to which the reserved product is placed before and after
reservation, or documents **Customer order**, **Purchase order**, or
**Production order**. For example, if you need to reserve a
customer-ordered product available in a warehouse or ordered from a
supplier, do not specify anything as an original location. Specify a
warehouse, a purchase order or a production order as a new location. If
you need to cancel reservation of a customer-ordered product, specify
the current reservation location (a warehouse or an order) as an
original location, and leave the new location column empty.

You can reserve inventory immediately from the customer order. To
reserve it, specify a reserve warehouse in the document header, and
quantity of reserved inventories in the **Reserve** column of the
tabular section.

Goods issue
~~~~~~~~~~~

To record sales of goods to an external counterparty in accounting, you
can use the **Goods issue** document.

|image1521153994058378|

You can create the document based on the **Customer order** document.
The documents are mainly identical in content. In contrast to the order,
the **Project** field and the **Shipping date** column are missing in
the goods issue. But there you can find the **Basis** attribute to
specify an invoice or a goods receipt based on which the goods issue was
created. If you set the **Customer order position in shipment
documents** radio button to **In header (for the whole document)**, the
**Order** attribute appears on the form to specify a customer order. To
access the document setting form, click **More**, and then click the
required command.

On the **Additionally** tab, you can specify a contractor department and
an employee responsible for entering the document. 

You can create the following documents based on the **Goods issue**
document:

-  **Goods receipt** to register return (the **Return from customer**
value will be set automatically in the **Operation kind** field)

-  **Invoice**

-  **Invoice** (**Fill in CCD numbers**)

-  **Proforma invoice**

-  **Event**

-  **Issue slip** (if a two-phase warehouse is used)

-  **Funds receipt (plan)** (if a payment calendar is used)

-  **Credit slip** (if a customer pays for goods in cash)

-  **Receipt to account** (if a payment was made via bank transfer)

The document list allows you to record whether goods are shipped and
services are rendered, including customer orders which are in progress.

|image1521153994105817|

You can register documents based on one or several selected customer
orders.

Using the list, you can analyze state of the selected customer orders,
inventory demand, and mutual settlements state.

Invoice
~~~~~~~

You can register the **Invoice** document based on one of the following
documents: a job order or a goods issue when selling goods, or
**Acceptance certificate** when selling works and services, and
receiving an advance (prepayment) from a customer.

|image1521153995419410|

Information from the corresponding goods issue is transferred to the
document. When saving the document, its number and date are assigned
automatically.

For imported goods, specify a country of origin and a CCD number in the
table field of the document form. If there is CCD balance, the
corresponding columns can be filled in automatically by clicking **CCD
numbers**.

Goods return
~~~~~~~~~~~~

Use the **Goods receipt** document with the **Return from customer**
kind to register return of products and services items that were shipped
to the customer earlier.

|image1521153994198685|

You can enter the document based on the goods issue. In this case, the
table field will be filled in with the basis document data.
Additionally, you can specify cost of the returned goods in the table
field.

Acceptance certificate
~~~~~~~~~~~~~~~~~~~~~~

Use the **Acceptance certificate** document to record sales of services
(works) in accounting.

|image1521153991675061|

The document is mostly similar to a goods issue. However, in the table
field, you can specify products and services with either **Work** or
**Service** type only.

The document list allows you to record services rendered to customers,
including for the customer orders in progress.

|image1521153991698297|

You can create the documents using either one or several selected
customer orders.

Using the list, you can analyze state of the selected customer orders,
inventory demand, and mutual settlements state.

COMMISSION SALES
~~~~~~~~~~~~~~~~

With «1C:SimpleERP», you can take advantage of automated recording of
business transactions of acceptance and transfer of goods for
commission. You can access functionality of commission sales in the
**Sales** section.

Goods transfer for commission
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To register our company's (principal's) goods transfer for commission to
a counterparty (agent), in accounting policy settings of the **Sales**
section, select the **Use goods transfer for commission** check box.

Goods transfer for commission is registered using the **Goods issue**
document with the **Transfer for commission** operation kind.

|image1521153994128972|

When posting the document, our goods transfer to the counterparty is
registered. In the table field, specify a list of transferred goods and
the order document under which the goods are transferred.

Agent report
~~~~~~~~~~~~

Use the **Agent report** document to register goods sold by the agent.
To access the document, in the **Sales** group, in the navigation panel,
click **Agent reports**.

|image1521153991599692|

The **Agent report** document contains two tabular sections.

On the **Inventory** tab, specify customers of the principal's
inventory, cost of the inventory sold to customers, and information
about the issued invoice.

The second **Inventory** tabular section is subordinate to the
**Customers** tabular section. Several rows of the **Inventory** tabular
section can correspond to one row of the **Customers** tabular section.

Information on prices and amounts of transfer and sale is specified in
columns **Transfer price**, **Movement amount**, **Price**, **Amount**,
and **Total**. Specify VAT amount, amount of sale, transfer, and
commission in the corresponding columns.

In the **Order** column, specify a sales order against which goods
received for commission are sold. In the **Commission amount** column,
specify an amount that the agent keeps, it is calculated on the
**Additionally** tab.

|image1521153991943311|

On the **Additionally** tab, specify a commission calculation method:

-  If the commission amount is specified individually, select the **Not
calculated** calculation method.

-  If the commission is calculated as a sales percent, select the **Sale
percent** calculation method and specify a value in the **Commission
percent** field.

-  If the commission is calculated as a percent of difference between
receipt amount and sales amount, select the **Percent of difference
between receipt amount and sale amount** method and specify a value
in the **Commission percent** field.

You can set off prepayment on the **Prepayment** tab. Click **Select**
to open the **Prepayment setoff** form. On this form, fill in a tabular
section with the information on advance offset received from the agent
earlier.

Goods acceptance for commission
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To record goods accepted for commission in accounting, use the **Goods
receipt** document with the **Acceptance for commission** operation
kind. You can access the document in the **Purchases** section.

|image1521153991724322|

In the table field, you can specify an order document under which
acceptance is carried out for each product. You can return goods
accepted for commission to the principal in the same manner as you
return goods received from the supplier. To register commission goods
return, use the **Goods issue** document with the **Return to
principal** operation kind

To distinguish between own inventory on the company's balance sheet and
received inventory which is not on the company's balance sheet, specify
a delivery batch on acceptance and keeping records of goods for
commission, processing, or safe custody. For each type of inventory
there can be one batch with the corresponding status or several batches.
For example, for each delivery there is its own batch.

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

.. _goods-return-1:

Goods return
~~~~~~~~~~~~

Sold goods, goods transferred to commission, for processing, or safe
custody can be returned. You can register goods return using goods issue
and goods receipt with the **Return from customer** (from processor,
from agent, from safe custody) operation kind.

.. _retail-sales-1:

Retail sales
~~~~~~~~~~~~

You can access the **Retail sales** subsystem in the corresponding
subsection of the **Sales** section. To activate the subsystem, select
the **Retail sales accounting** check box in accounting settings. The
**Retail sales** group appears in the navigation panel.

If cash equipment is used in the sales outlet, in the **Settings**
section, on the **Peripherals** form, select the **Use peripherals**
check box. The **Peripherals** link gets active. You can use it to
configure peripherals and work places. For more information about
peripherals settings, see chapter.

To add a sales outlet with quantitative and value accounting to the
application, create a new item in the **Company business units**
catalog. Select **Retail** in the **Type** attribute. Specify a retail
price kind by selecting from the **Price kinds** catalog. To access the
catalog, in reference information of the **Company** section, click
**Warehouses**.

|image1521153991377197|

Inventory movement to retail outlet
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Inventory used for further movement to a retail outlet is received to
the main company warehouse. You can register this procedure with the
**Goods receipt** document.

|image1521153994425361|

To move the received inventory from the main warehouse to a retail
outlet, use the **Inventory movement** document. If a retail price is
not set for the product, the document will not be posted. You will
receive an error message and a tooltip. 

To post the document, set retail prices for the inventory to move. To
set retail prices, use the **Company price list** or **Pricing** data
processor.

Once you set retail prices, the inventory will be successfully moved to
the required retail outlet.

Receiving goods to retail
~~~~~~~~~~~~~~~~~~~~~~~~~

Goods can be received to a sales outlet directly from a supplier. In
this case, register receipt using goods receipt with a sales outlet
specified as a receiving warehouse.

|image1521153994152388|

If you do not set retail prices for the received goods, the document
will not be posted.

Sales outlets which use quantitative-value accounting
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In quantitative-value accounting, you keep accounting of products in a
warehouse and in accounting system of retail companies both by quantity
in physical terms and by cost in monetary terms.

You can use quantitative-value accounting of products in retail sale
only when using necessary automation technology. With that, product
accounting by purchasing prices causes no problems. Manufacturers mark
packaging with the sales ticket or mark the product with barcode. A
barcode contains information about manufacturing or seller country,
manufacturing company, and product characteristics (name, size, etc). On
products receipt to a store, you can write information about their name,
features, quantity, and purchasing prices to the infobase using scanning
device. If there is no manufacturer barcode on the product, write this
information manually to the infobase, and the product receives an
internal code.

On product sale, write the information about it to the infobase the same
way. A customer gives a cashier bought product with a barcode. The
product information is read using a scanner. On cash registering
receipt, you can see the name, quantity, price, and cost of the sold
product in retail prices. Such a receipt is an analog of a packing slip.

Data on sold products cost in purchasing prices is generated based on
data on names and quantity of sold products.

Sales outlet with fiscal data recorder connected to accounting system
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Before you start, enter the information about fiscal data recorder
installed in the sales outlet into the **Cash registers** catalog. To
access it, in the **Settings** section in accounting parameter setting,
click **Cash registers**. To add a cash fund with the **Fiscal data
recorder** type, click **Create**.

|image1521153999000250|

Also specify business unit, company department, and GL account for the
cash register. If the **Without connection** check box is not selected,
in the list of configured peripherals, select a value of the
**Peripherals** attribute. By default, the cash fund name is assigned by
the [Cash fund type] ([Company business unit]) template, but you can
change it.

Use the **Inventory movement** and **Goods receipt** documents to
register product receipt to sales outlet area (for example, from head
office warehouses or directly from the supplier). To access the logs of
movement documents and goods receipts, in the **Purchases** section, in
the navigation panel, click the corresponding links.

To open the shift:

-  Open the **Cash receipts** log: in the **Sales** section, click
**Cash receipts**.

-  In the log navigation panel, select the cash register.

-  Click the **Open shift** button.

|image1521153991247757|

Then it registers the **Cash receipt** documents in the accounting
system during the shift.

|image1521153999024342|

The products are sold from the sales outlet area (the products are on
shelves) at retail prices with quantity discounts if appropriate.
Payments are accepted in cash or with payment card.

After creating a new receipt, a cashier clicks **Reserve**. Then payment
fields become available in accordance with the value specified in the
**Payment method** field. A customer can pay in cash, with payment card,
or partly in cash, partly with payment card.

Note

Payment card is accepted if a POS terminal is connected to the user work
place. Before you start, enter the POS terminal information into the
**POS terminal** catalog.

|image1521153999048725|

In the table field of the terminal form, specify the list of payment
cards accepted by the device.

You can see the data on payment with payment card in cash receipts and
on the **Payment with payment cards** tab in the **Retail sales report**
document.

Specify the data on payment with payment card in the corresponding tab
of the **Cash register** document form.

To finish payment input, a cashier clicks **Issue receipt**.

To register a return on the same day basis, register refund receipt
using the **Refund receipt** document. To create the receipt, in the
command bar of the **Cash receipts** document log, click **Return**.

|image1521153991274908|

To register product return on another day basis, use the **Goods
receipt** document with the **Return from customer** operation kind.

A customer must be registered in the **Counterparties** and
**Individuals** catalogs of the accounting system.

To receive a Z report which registers shift closing, in the command bar,
click **Close shift.**

|image1521153996934493|

Then a cashier passes revenue to the operating cash, and a cashier of
the operating cash receives it and makes entries in the cashier log. To
register revenue pass and receipt, use the **Credit slip** document with
the **Retail revenue** operation kind.

To deposit cash to the cash register, in the command bar, click **Cash
deposit**. Specify the amount of deposited cash in the dialog box.

To withdraw cash from the cash register, click **Cash withdrawal**. Both
buttons can only be used to manage fiscal data recorder.

Sales outlet with an offline cash register
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Procedure of starting operation with Offline cash registers is similar
to the previous case. The only difference is that when you enter data
into the **Cash registers** catalog, the **Offline cash register** value
is specified in the **Cash register type** attribute.

During the shift, a cashier operates with an offline cash register
without creating any records in the accounting system. At the shift end,
they generate the Z report from the cash register, make entries to the
cashier log, and fill in a retail report manually (using entries in a
copybook or physical inventory results).

In the **Retail sales report** document, on the **Payment with payment
cards** tab, information on payment for goods with a payment card is
shown.

To view and edit retail sales reports, use the corresponding log. To
access it, in the navigation panel, click the corresponding link. In the
log, you can filter data by shift status. Also you can archive cash
receipts by clicking **Archive cash receipts**.

Accounting in a "copybook"
~~~~~~~~~~~~~~~~~~~~~~~~~~

During the shift, a cashier registers sales in a "copybook". To register
revenue in the accounting system, use the **Credit slip** document.

|image1521153993225753|

To register sales based on entries in the "copybook", use the **Retail
sales report** document.

Accounting with periodic physical inventory
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

As previously, to register revenue in the accounting system, use the
**Credit slip** document. To register sales, use the **Retail sales
report** document based on data of physical inventory made in the sales
outlet (product number decrease due to the sales).

|image1521153999071666|

Sales outlets with value accounting
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

When you use value accounting, you keep accounting of product receipt
and outflow only in monetary terms. When using product value accounting
in retail sale, sales prices are usually used as accounting prices.

You can keep accounting of the goods flow in a sales outlet with value
accounting in the following way:

-  On product receipt to a store warehouse, register the number of
received products in the product card or register. To release
products to departments, use picking lists. With that, product
outflow from the warehouse is registered in cards or registers. Thus,
you organize quantitative accounting on the warehouse level.

-  In the accounting system, you can record product receipt in cost
terms (in sales prices) as entries on GL accounts of products.

-  Write off products in the accounting system on the basis of cash
receipts where daily revenue, which is the cost of sold products in
sales (retail) prices, is registered.

The cost is calculated in direct ratio to sales revenue (by average) and
at the same time as posting the **Credit slip** document with the
**Retail revenue (value accounting)** operation kind.

To add a sales outlet with value accounting to the system, in the
**Business units** catalog, create a new item. In the **Type** field,
select the **Retail (value accounting)** value and retail price kind
from the **Price kinds** catalog. On the **GL accounts** tab, specify
the retail GL account and markup GL account.

|image1521153991497810|

As the operation starts, move products from wholesale warehouse to the
sales outlet with value accounting. To do that, register the **Inventory
movement** document in the accounting system.

|image1521153994425361|

As a result, products are written off from the wholesale warehouse, and
balance of the sales outlet increases in sales (retail) and cost prices.

You can also use the **Inventory movement** document to return products
from sales outlet to warehouse.

To change sales (retail) prices in sales outlet, use the **Inventory
revaluation in retail (value accounting)** document. With that, in the
**Inventory** table field, register actual product quantity in the sales
outlet, new and old retail prices.

|image1521153996908472|

In this case, use the **Physical inventory** document only to prepare a
form with prices (goods are recounted in the store, their cost is
calculated and compared with the accounting cost).

There are the following cases for setting new prices:

-  On new batch receipt (in this case the difference in prices of
remaining products of the previous batch is profit/loss of the
seller)

-  On revaluation of actual quantity of remaining products in sales
outlet (in this case, it is possible to understate/overstate actual
product quantity on purpose to get profit).

To write off remaining products at the sales outlet in sales prices and
receive cash to the company cash fund, use the **Credit slip** document.

Peripherals dashboards
~~~~~~~~~~~~~~~~~~~~~~

In the application, convenient dashboards for some peripheral kinds are
available, for example, POS terminal and fiscal data recorder. To open
dashboards, use the command bar of cash receipt register.

On the **POS terminal management** dashboard, there are the following
button groups: **Main operations** and **Additional operations**.

|image1521153999097424|

Using the buttons, a cashier can perform different operations related to
payment for products with payment card. In the right part of the
dashboard, you can see the result (printed receipt) as the operation is
over.

On the fiscal data recorder dashboard, there are only two buttons. They
are intended to print fiscal data recorder reports with or without
clearance.

|image1521153999120124|

Sales reports
~~~~~~~~~~~~~

With the application reports, you can analyze efficiency of trading
activity. Click **Sales reports** to access all reports of the **Sales**
section. Use the section report panel to open the section report
variants divided by subsystems.

|image1521153990992417|

To open a form of selection and report panel settings, click **All
reports**. In the left side of the form, you can see a tree of sections
and command interface groups. As you navigate through the tree nodes, a
report list in the **Description** column is automatically filtered by
the selected section.

If a list of report variants is quite big, you can quickly find the
required report variant using search tools. To search for a required
report variant, type the required value in the **Search** field, and
then click **Find**. Search is carried out in the selected section
(group).

You can search for reports using a word (part of the word) or several
words. The search is carried out in:

-  Report names

-  Report variant descriptions

-  Presentations of report variant fields

-  Presentations of report variant parameters and filters

-  Names of user settings of the report variant

-  Names of sections and groups of the application and report panel

In the **Author** field, you can select a report variant author from the
list.

|image1521153996884743|

In the setting form, you can generate any report from the tree and
determine which reports will be available for quick selection, i.e.
placed directly to the report panel.

Customer order fulfillment
~~~~~~~~~~~~~~~~~~~~~~~~~~

Use the **Customer order** **fulfillment** report to analyze content and
progress of customer orders.

|image1521153999144093|

The report is grouped by orders. Missing (not provided with sources)
quantity of products and services items is calculated for each order.
Using the report you can identify demand for purchase or production of
products and services item required for order fulfillment.

You can satisfy the demand for products and services using the following
methods:

-  Reservation in warehouse

-  Placement in a purchase order

-  Placement in a production order

Reservation and placement are registered by documents generated based on
the **Customer order** document. In the report, you can also see
quantity of items reserved in the warehouse.

Unrestricted stock
~~~~~~~~~~~~~~~~~~

Use the **Unrestricted stock** report to receive information about
unrestricted stock of products by warehouses. In the report, you can
also see summary data on balance, reserves, and unrestricted stock for
the company as a whole.

|image1521153999171179|

Customer order payment
~~~~~~~~~~~~~~~~~~~~~~

Using the report, you can analyze customer order payment.

|image1521153999195658|

The report data is grouped by counterparties, companies, and contracts.

Invoice payment
~~~~~~~~~~~~~~~

In the report, you can see information on invoices paid by
counterparties.

|image1521153999219773|

The report data is grouped by customers and contracts.

Receivable by periods
~~~~~~~~~~~~~~~~~~~~~

With the **Receivable by periods** report, you can see amounts of
counterparty debts to the company with periods – less than a week, 1-2
weeks, 2 weeks – a month, 1-2 months, over two months.

The report also shows information about total debt, overdue receivable
amount and number of overdue days. Overdue receivable and number of
overdue days are calculated considering a customer payment due date
specified in the counterparty contract or parameter settings if the
payment due date is not set in the contract.

|image1521153991304568|

The report is generated for a specific date or the current one if the
date is not set.

Shipment and payment against customer orders
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Use the report to analyze states of customer orders in terms of payment
and shipment.

You can see planned payment amount (order amount), amount paid against
the order, and amount that should be paid off to pay for the order in
full.

As for shipment against the order, you can see quantity of goods for
shipment, shipped and reserved goods, and remaining goods to be shipped
against the order.

|image1521153991327653|

Mutual settlements
~~~~~~~~~~~~~~~~~~

With the **Mutual settlements** report, you can see state and dynamics
of mutual settlements with counterparties (customers, suppliers, etc.)
over the specified period.

|image1521153995797996|

Data is displayed with grouping by counterparties, contracts and orders.
There are the following available modes in this report: **Mutual
settlements list**, **Mutual settlements list in foreign currency
(briefly)** and **Mutual settlements balance**. In the **Mutual
settlements balance** mode, you can see only information about mutual
settlements balance on the specified date.

|image1521153999247570|

Cash in cash registers
~~~~~~~~~~~~~~~~~~~~~~

In the report, you can see information on cash in cash registers:
inflow, outflow, and balance.

|image1521153992716220|

You can generate the report in the following modes: **Statement**,
**Statement in currency**, **Balance**, **Balance in currency**. The
**Statement** mode is the most complete. In this report, all information
on cash in cash registers – inflow, outflow, and balance both in
currency and management accounting currency is displayed.

Value accounting in retail outlet
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In the report, you can see information about retail funds in currency
and management accounting currency, and data on product cost in a retail
outlet. The report displays data on opening and closing balance,
receipt, and expense.

|image1521153997650336|

You can generate the report in the following modes: **Statement**,
**Statement in currency**, **Balance**, **Balance in currency**.

.. |image1521153994269502| image:: media/image39.png
   :width: 4.625in
   :height: 4.98958in
.. |image1521153994246824| image:: media/image40.png
   :width: 4.63542in
   :height: 5.07292in
.. |image1521153998320793| image:: media/image41.png
   :width: 3.13542in
   :height: 2.4375in
.. |image1521153998343897| image:: media/image42.png
   :width: 3.10417in
   :height: 1.26042in
.. |image1521153998373116| image:: media/image43.png
   :width: 3.9375in
   :height: 1.47917in
.. |image1521153998404609| image:: media/image44.png
   :width: 3.69792in
   :height: 2.82292in
.. |image1521153993175676| image:: media/image45.png
   :width: 4.63542in
   :height: 2.15625in
.. |image1521153993102397| image:: media/image46.png
   :width: 4.63542in
   :height: 3.16667in
.. |image1521153993582692| image:: media/image47.png
   :width: 4.63542in
   :height: 1.5in
.. |image1521153993434994| image:: media/image48.png
   :width: 4.61458in
   :height: 1.92708in
.. |image1521153997063387| image:: media/image49.png
   :width: 4.65625in
   :height: 4.39583in
.. |image1521153998432516| image:: media/image50.png
   :width: 3.9375in
   :height: 2.26042in
.. |image1521153997088535| image:: media/image51.png
   :width: 4.625in
   :height: 2.5625in
.. |image1521153998458675| image:: media/image52.png
   :width: 4.46875in
   :height: 2.90625in
.. |image1521153993458581| image:: media/image53.png
   :width: 4.63542in
   :height: 2.01042in
.. |image1521153998482105| image:: media/image54.png
   :width: 3.9375in
   :height: 3.3125in
.. |image1521153992636490| image:: media/image55.png
   :width: 4.625in
   :height: 3.22917in
.. |image1521153992603037| image:: media/image56.png
   :width: 4.625in
   :height: 3.21875in
.. |image1521153990863844| image:: media/image57.png
   :width: 4.11458in
   :height: 3.02083in
.. |image1521153998506419| image:: media/image58.png
   :width: 4.20833in
   :height: 3.27083in
.. |image1521153998533209| image:: media/image59.png
   :width: 3.9375in
   :height: 2.09375in
.. |image1521153994708720| image:: media/image60.png
   :width: 3.82292in
   :height: 4.04167in
.. |image1521153998559080| image:: media/image61.png
   :width: 3.9375in
   :height: 2.89583in
.. |image1521153998583846| image:: media/image62.png
   :width: 3.9375in
   :height: 2.52083in
.. |image1521153994058378| image:: media/image63.png
   :width: 4.625in
   :height: 3.6875in
.. |image1521153998605820| image:: media/image64.png
   :width: 2.3125in
   :height: 2.22917in
.. |image1521153996418013| image:: media/image65.png
   :width: 4.67708in
   :height: 4.38542in
.. |image1521153992576630| image:: media/image66.png
   :width: 4.61458in
   :height: 3.02083in
.. |image1521153990787434| image:: media/image67.png
   :width: 4.63542in
   :height: 3.17708in
.. |image1521153994733975| image:: media/image68.png
   :width: 3.77083in
   :height: 3.375in
.. |image1521153998633033| image:: media/image69.png
   :width: 3.9375in
   :height: 1.3125in
.. |image1521153991220792| image:: media/image70.png
   :width: 4.41667in
   :height: 3.33333in
.. |image1521153991356267| image:: media/image71.png
   :width: 4.35417in
   :height: 3.05208in
.. |image1521153993409422| image:: media/image72.png
   :width: 3.77083in
   :height: 1.55208in
.. |image1521153998658620| image:: media/image73.png
   :width: 3.9375in
   :height: 1.33333in
.. |image1521153998685652| image:: media/image74.png
   :width: 3.9375in
   :height: 1.70833in
.. |image1521153992351230| image:: media/image75.png
   :width: 4.63542in
   :height: 2.15625in
.. |image1521153998711361| image:: media/image76.png
   :width: 3.9375in
   :height: 2.375in
.. |image1521153995944377| image:: media/image77.png
   :width: 4.625in
   :height: 3.3125in
.. |image1521153995394295| image:: media/image78.png
   :width: 4.625in
   :height: 2.59375in
.. |image1521153994058378| image:: media/image63.png
   :width: 4.625in
   :height: 3.6875in
.. |image1521153994105817| image:: media/image79.png
   :width: 4.63542in
   :height: 3.01042in
.. |image1521153995419410| image:: media/image80.png
   :width: 4.63542in
   :height: 3.28125in
.. |image1521153994198685| image:: media/image81.png
   :width: 4.625in
   :height: 3.17708in
.. |image1521153991675061| image:: media/image82.png
   :width: 4.63542in
   :height: 3.28125in
.. |image1521153991698297| image:: media/image83.png
   :width: 4.63542in
   :height: 1.8125in
.. |image1521153994128972| image:: media/image84.png
   :width: 4.63542in
   :height: 4.6875in
.. |image1521153991599692| image:: media/image85.png
   :width: 4.63542in
   :height: 4.14583in
.. |image1521153991943311| image:: media/image86.png
   :width: 4.63542in
   :height: 3.84375in
.. |image1521153991724322| image:: media/image87.png
   :width: 4.63542in
   :height: 3.41667in
.. |image1521153996855649| image:: media/image88.png
   :width: 4.625in
   :height: 2.92708in
.. |image1521153991377197| image:: media/image89.png
   :width: 4.51042in
   :height: 2.85417in
.. |image1521153994425361| image:: media/image90.png
   :width: 4.625in
   :height: 3.21875in
.. |image1521153994152388| image:: media/image91.png
   :width: 4.63542in
   :height: 3.79167in
.. |image1521153999000250| image:: media/image92.png
   :width: 3.90625in
   :height: 1.94792in
.. |image1521153991247757| image:: media/image93.png
   :width: 4.53125in
   :height: 2.45833in
.. |image1521153999024342| image:: media/image94.png
   :width: 3.9375in
   :height: 2.60417in
.. |image1521153999048725| image:: media/image95.png
   :width: 4.61458in
   :height: 2.59375in
.. |image1521153991274908| image:: media/image96.png
   :width: 4.30208in
   :height: 3.125in
.. |image1521153996934493| image:: media/image97.png
   :width: 4.63542in
   :height: 3.02083in
.. |image1521153993225753| image:: media/image98.png
   :width: 4.63542in
   :height: 3.16667in
.. |image1521153999071666| image:: media/image99.png
   :width: 3.9375in
   :height: 2.53125in
.. |image1521153991497810| image:: media/image100.png
   :width: 4.47917in
   :height: 3.30208in
.. |image1521153994425361| image:: media/image90.png
   :width: 4.625in
   :height: 3.21875in
.. |image1521153996908472| image:: media/image101.png
   :width: 4.63542in
   :height: 3.29167in
.. |image1521153999097424| image:: media/image102.png
   :width: 3.59375in
   :height: 1.75in
.. |image1521153999120124| image:: media/image103.png
   :width: 3.59375in
   :height: 0.95833in
.. |image1521153990992417| image:: media/image104.png
   :width: 4.63542in
   :height: 4.36458in
.. |image1521153996884743| image:: media/image105.png
   :width: 4.63542in
   :height: 4.52083in
.. |image1521153999144093| image:: media/image106.png
   :width: 3.90625in
   :height: 2.83333in
.. |image1521153999171179| image:: media/image107.png
   :width: 4.25in
   :height: 2.52083in
.. |image1521153999195658| image:: media/image108.png
   :width: 3.9375in
   :height: 2.86458in
.. |image1521153999219773| image:: media/image109.png
   :width: 3.9375in
   :height: 2.23958in
.. |image1521153991304568| image:: media/image110.png
   :width: 4.5in
   :height: 2.44792in
.. |image1521153991327653| image:: media/image111.png
   :width: 4.5in
   :height: 3.08333in
.. |image1521153995797996| image:: media/image112.png
   :width: 4.625in
   :height: 2.73958in
.. |image1521153999247570| image:: media/image113.png
   :width: 3.9375in
   :height: 3.375in
.. |image1521153992716220| image:: media/image114.png
   :width: 4.63542in
   :height: 2.40625in
.. |image1521153997650336| image:: media/image115.png
   :width: 4.63542in
   :height: 2.41667in
