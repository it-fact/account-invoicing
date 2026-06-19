To allow customization of the name of the section, user should be part of group
`Allow customization of invoice section name from sale order`.

A naming scheme can be defined per company on the configuration page in the
`Customer Invoices` section, or per partner in the accounting page, using
python expression.

<<<<<<< HEAD
For a fixed text, use quotes, for example `'Group'`. You can also use the sale
order through `object`, for example `object.client_order_ref or object.name`.

=======
>>>>>>> 85ac3f848d94830d4532ec7b356e030d1eebd402
The object used for the grouping can be customized by installing extra module
(e.g. `account_invoice_section_picking`).
