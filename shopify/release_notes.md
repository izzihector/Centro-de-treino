1.0:

- Initial Release

1.1:

- Added error log while import product from Shopify and in Odoo product variant is in different product template.

1.2:

- Improve stock update process.
- Webhook bug fix.
- Fetch orders based on update date.
- Update fulfillment status and financial status if order found.

1.3:

- Fixed issue of invoice sometime not fully reconciled.

1.4:

- Fixed error while creating invoice/delivery contact
- Now import variants if some products is not found in Odoo.

1.5:

- Fixed issue of Order import from Webhook.

1.6:

- Added field to identify Order's Source(like Online store, POS or others).

1.7:

- Added configuration in instance for customer to create company customer or not.
- Added configuration in instance to import fraud analysis or not.
- Bug fix regarding Shopify Order Source import.

1.8:

- Bug fix while import order.
- Not create Customers if order's workflow is not found.

1.9

- Added Order warehouse that will set accoring to Shopify Location
- Added default POS Customer, will be used while customer is not found in POS order.
- Update Shopify SKD from 7.0(2019-10) to 8.4.1(2021-04)
- Skipped while Importing Stock from Shopify to Odoo only import products with Tracking field set to No Tracking in
  Odoo.
- Increase readability of Shopify Location in Sale order.
- Improved code for currency convert.
- Bug fix while search Shopify location in import stock operation.
- Bug fix of product's price set to zero while update single variant product with only update product operation.

1.9.1

- Update barcode in listing Item.

1.9.2

- Fixed issue while import order from import screen fetch order based on create date instead of write date. 

1.9.3

- Fixed issue while do refund. 
- Fixed issue for Kit type BOM product's fulfillment update.
- Fixed create/update customer Webhook issue.

