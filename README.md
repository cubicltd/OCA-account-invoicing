[![Runbot Status](https://runbot.odoo-community.org/runbot/badge/flat/95/10.0.svg)](https://runbot.odoo-community.org/runbot/repo/github-com-oca-account-invoicing-95)
[![Build Status](https://travis-ci.org/OCA/account-invoicing.svg?branch=10.0)](https://travis-ci.org/OCA/account-invoicing)
[![Coverage Status](https://coveralls.io/repos/OCA/account-invoicing/badge.svg?branch=10.0)](https://coveralls.io/r/OCA/account-invoicing?branch=10.0)

OCA account invoicing modules for Odoo
======================================

This project aim to deal with modules related to manage invoicing in a generic way. You'll find modules that:

 - Add a validation step on invoicing process
 - Add check on invoice
 - Unit rounded invoice
 - Utils and ease of use for invoicing with OpenERP
 - ...

[//]: # (addons)

Available addons
----------------
addon | version | maintainers | summary
--- | --- | --- | ---
[account_group_invoice_line](account_group_invoice_line/) | 10.0.1.1.0 |  | Add option to group invoice lines per account
[account_invoice_analytic_search](account_invoice_analytic_search/) | 10.0.1.0.0 |  | Search invoices by analytic account or by project manager
[account_invoice_blocking](account_invoice_blocking/) | 10.0.1.0.1 |  | This module allows the user to set a blocking (No Follow-up) flag on invoices.
[account_invoice_change_currency](account_invoice_change_currency/) | 10.0.1.0.0 |  | Allows to change currency of Invoice by wizard
[account_invoice_check_total](account_invoice_check_total/) | 10.0.1.0.0 |  | Check if the verification total is equal to the bill's total
[account_invoice_date_required](account_invoice_date_required/) | 10.0.1.1.0 | [![rousseldenis](https://github.com/rousseldenis.png?size=30px)](https://github.com/rousseldenis) | Requires invoice date before validation to avoid Odoo setting 'today' as default if not filled in.
[account_invoice_fiscal_position_update](account_invoice_fiscal_position_update/) | 10.0.1.0.1 |  | Changing the fiscal position of an invoice will auto-update invoice lines
[account_invoice_fixed_discount](account_invoice_fixed_discount/) | 10.0.1.0.0 |  | Allows to apply fixed amount discounts in invoices.
[account_invoice_force_number](account_invoice_force_number/) | 10.0.1.0.0 |  | Allows to force invoice numbering on specific invoices
[account_invoice_kanban](account_invoice_kanban/) | 10.0.1.1.0 |  | Add Kanban view in Invoice to follow administrative tasks
[account_invoice_line_description](account_invoice_line_description/) | 10.0.1.0.1 |  | Account invoice line description
[account_invoice_line_sequence](account_invoice_line_sequence/) | 10.0.1.0.0 |  | Adds sequence field on invoice lines to manage its order.
[account_invoice_merge](account_invoice_merge/) | 10.0.1.0.1 |  | Merge invoices in draft
[account_invoice_merge_attachment](account_invoice_merge_attachment/) | 10.0.1.0.0 |  | Consider attachment during invoice merge process
[account_invoice_merge_payment](account_invoice_merge_payment/) | 10.0.1.0.0 |  | Use invoice merge regarding fields on Account Payment Partner
[account_invoice_merge_purchase](account_invoice_merge_purchase/) | 10.0.1.0.0 |  | Compatibility between purchase and account invoice merge
[account_invoice_partner](account_invoice_partner/) | 10.0.1.0.0 |  | Replace the partner by an invoice contact if found
[account_invoice_pricelist](account_invoice_pricelist/) | 10.0.1.0.0 |  | Add partner pricelist on invoices
[account_invoice_pricelist_sale](account_invoice_pricelist_sale/) | 10.0.1.0.0 |  | Module to fill pricelist from sales order in invoice.
[account_invoice_pro_forma_sequence](account_invoice_pro_forma_sequence/) | 10.0.1.0.0 |  | Bind a sequence to pro-forma invoices
[account_invoice_refund_link](account_invoice_refund_link/) | 10.0.1.0.3 |  | Link refund invoice with its original invoice
[account_invoice_rounding](account_invoice_rounding/) | 10.0.1.0.2 |  | Unit rounded invoice
[account_invoice_search_by_reference](account_invoice_search_by_reference/) | 10.0.1.0.0 |  | Account invoice search by reference
[account_invoice_supplier_ref_unique](account_invoice_supplier_ref_unique/) | 10.0.1.0.0 |  | Checks that supplier invoices are not entered twice
[account_invoice_supplierinfo_update](account_invoice_supplierinfo_update/) | 10.0.1.0.2 |  | In the supplier invoice, automatically updates all products whose unit price on the line is different from the supplier price
[account_invoice_transmit_method](account_invoice_transmit_method/) | 10.0.1.0.1 |  | Configure invoice transmit method (email, post, portal, ...)
[account_invoice_triple_discount](account_invoice_triple_discount/) | 10.0.1.0.2 |  | Manage triple discount on invoice lines
[account_invoice_view_payment](account_invoice_view_payment/) | 10.0.1.0.0 |  | Access to the payment from an invoice
[account_payment_term_extension](account_payment_term_extension/) | 10.0.1.1.1 |  | Adds rounding, months, weeks and multiple payment days properties on payment term lines
[product_supplierinfo_for_customer_invoice](product_supplierinfo_for_customer_invoice/) | 10.0.1.0.1 |  | Based on product_customer_code, this module loads in every account invoice the customer code defined in the product,
[purchase_stock_picking_return_invoicing](purchase_stock_picking_return_invoicing/) | 10.0.1.0.1 |  | Add an option to refund returned pickings
[sale_timesheet_invoice_description](sale_timesheet_invoice_description/) | 10.0.1.0.0 |  | Add timesheet details in invoice line
[stock_picking_invoicing](stock_picking_invoicing/) | 10.0.1.0.0 |  | Stock Picking Invoicing


Unported addons
---------------
addon | version | maintainers | summary
--- | --- | --- | ---
[account_invoice_customer_ref_unique](account_invoice_customer_ref_unique/) | 1.0 (unported) |  | Unique Customer Reference in Invoice
[account_invoice_line_sort](account_invoice_line_sort/) | 8.0.0.1.0 (unported) |  | Manage sort of customer invoice lines by customers
[account_invoice_period_usability](account_invoice_period_usability/) | 8.0.1.0.0 (unported) |  | Display in the supplier invoice form the fiscal period next to the invoice date
[account_invoice_template](account_invoice_template/) | 0.1 (unported) |  | Account Invoice Template
[account_invoice_uom](account_invoice_uom/) | 8.0.1.0.0 (unported) |  | Unit of measure for invoices
[account_invoice_validation_workflow](account_invoice_validation_workflow/) | 8.0.1.0.1 (unported) |  | Add "To Send" and "To Validate" states in Invoices
[account_invoice_zero_autopay](account_invoice_zero_autopay/) | 8.0.1.0.0 (unported) |  | Account Invoice Zero Autopay
[sale_order_partial_invoice](sale_order_partial_invoice/) | 1.1 (unported) |  | Sale Partial Invoice
[stock_invoice_picking_incoterm](stock_invoice_picking_incoterm/) | 0.1 (unported) |  | Stock Invoice Picking Incoterm

[//]: # (end addons)

Translation Status
------------------
[![Transifex Status](https://www.transifex.com/projects/p/OCA-account-invoicing-10-0/chart/image_png)](https://www.transifex.com/projects/p/OCA-account-invoicing-10-0)

----

OCA, or the Odoo Community Association, is a nonprofit organization whose 
mission is to support the collaborative development of Odoo features and 
promote its widespread use.

http://odoo-community.org/
