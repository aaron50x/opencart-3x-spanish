# Idioma español para OpenCart 3.x

- Decarga el paquede de idioma y extraiga el contenido en alguna carpeta.
- Usando Filezilla o algun gestor FTP cargue las carpetas 'admin' y 'catalog' del archivo del paquete de idioma extraído a la carpeta principal de OpenCart en su cuenta de alojamiento.
- Inicie sesión en el panel de administración de OpenCart con sus credenciales de administrador, vaya a Sistema -> Localizations -> Languages y haga clic en el botón "Add new". 
- Rellene los campos necesarios, en "Code" seleccione es-ES y guarde los cambios.

Luego de hacer eso se puede configurar el idioma para que se use en la tienda desde  System->Setings>Store

**Nota:** este fork está creado para incluir llaves de idioma no disponibles para el plugin multivendor

## Llaves Pendientes


->>> /home/aaron/neo/opencart-3x-spanish/seller/catalog/language/es-ES/seller/category.php

### Catalog

```
$ ./get_missing_language_keys.py html/catalog/language/en-gb/ spanish/catalog/language/es-ES/
<- html/catalog/language/en-gb/  &  spanish/catalog/language/es-ES/ ->
Missing files:
> account/review.php
> extension/module/seller.php
> extension/module/sellercategory.php
> mail/morder.php
> product/seller.php
> seller/contact.php
Missing keys per file:
> account/account.php: btn_add_seller
> account/account.php: btn_switch_seller
> account/account.php: text_apply_selling
> account/account.php: text_not_seller
> account/account.php: text_seller_account
> account/order.php: text_products
> account/order.php: text_rate
> account/order.php: text_review
> account/order.php: text_seller
> account/order.php: text_status
> checkout/cart.php: text_seller
> checkout/checkout.php: text_seller
> common/cart.php: text_seller
> common/header.php: text_buyeraccount
> common/header.php: text_selleraccount
> common/header.php: text_viewselleraccount
> product/product.php: column_seller
> product/product.php: contact_seller
> product/product.php: text_action
> product/product.php: text_choices
> product/product.php: text_more
> product/product.php: text_price
> product/product.php: text_seller
> product/product.php: text_seller_rating
> product/product.php: text_sellers
```

### Admin

```
$ ./get_missing_language_keys.py html/admin/language/en-gb/ spanish/admin/language/es-ES/
<- html/admin/language/en-gb/  &  spanish/admin/language/es-ES/ ->
Missing files:
> catalog/commission.php
> catalog/occategorythumbnail.php
> catalog/octestimonial.php
> catalog/sellerreview.php
> extension/module/seller.php
> mail/seller.php
> ocadminmenu/ocadminmenu.php
> report/seller_transactions.php
> sale/seller.php
Missing keys per file:
> catalog/attribute.php: approve_disabled
> catalog/attribute.php: approve_enabled
> catalog/attribute.php: approve_success
> catalog/attribute.php: column_approve
> catalog/attribute.php: column_approved
> catalog/attribute.php: column_seller
> catalog/attribute.php: entry_approve
> catalog/category.php: approve_disabled
> catalog/category.php: approve_enabled
> catalog/category.php: approve_success
> catalog/category.php: column_approve
> catalog/category.php: column_approved
> catalog/category.php: column_seller
> catalog/category.php: entry_approve
> catalog/category.php: text_approved
> catalog/option.php: approve_disabled
> catalog/option.php: approve_enabled
> catalog/option.php: approve_success
> catalog/option.php: column_approve
> catalog/option.php: column_approved
> catalog/option.php: column_seller
> catalog/option.php: entry_approve
> catalog/product.php: approve_disabled
> catalog/product.php: approve_enabled
> catalog/product.php: approve_success
> catalog/product.php: button_seller
> catalog/product.php: column_approve
> catalog/product.php: column_seller
> catalog/product.php: entry_approve
> catalog/product.php: entry_commission
> catalog/product.php: entry_retail_price
> catalog/product.php: entry_seller_name
> catalog/product.php: entry_wholesale_price
> catalog/product.php: fixed_commission
> catalog/product.php: percent_commission
> catalog/product.php: tab_seller_links
> common/column_left.php: text_commission
> common/column_left.php: text_seller
> common/column_left.php: text_seller_transactions
> common/column_left.php: text_sellerreview
> setting/setting.php: entry_default_category
> setting/setting.php: entry_default_commission
> setting/setting.php: entry_default_seller
> setting/setting.php: entry_eligible_payment
> setting/setting.php: entry_product_autoapprove
> setting/setting.php: entry_saccount_terms
> setting/setting.php: entry_seller_autoapprove
> setting/setting.php: tab_seller
> setting/setting.php: text_orderstatus
> setting/setting.php: text_select_all
> setting/setting.php: text_unselect_all
```

### Seller

```
$ ./get_missing_language_keys.py html/seller/catalog/language/english/ empty/
<- html/seller/catalog/language/english/  &  empty/ ->
Missing files:
> account/account.php
> account/address.php
> account/download.php
> account/edit.php
> account/forgotten.php
> account/login.php
> account/logout.php
> account/newsletter.php
> account/order.php
> account/password.php
> account/recurring.php
> account/register.php
> account/return.php
> account/reward.php
> account/success.php
> account/transaction.php
> account/voucher.php
> account/wishlist.php
> api/cart.php
> api/coupon.php
> api/currency.php
> api/customer.php
> api/login.php
> api/order.php
> api/payment.php
> api/reward.php
> api/shipping.php
> api/voucher.php
> captcha/basic_captcha.php
> captcha/google_captcha.php
> checkout/cart.php
> checkout/checkout.php
> checkout/failure.php
> checkout/success.php
> common/cart.php
> common/column_left.php
> common/currency.php
> common/filemanager.php
> common/footer.php
> common/header.php
> common/language.php
> common/maintenance.php
> common/search.php
> error/not_found.php
> information/contact.php
> information/information.php
> information/sitemap.php
> mail/affiliate.php
> mail/customer.php
> mail/forgotten.php
> mail/order.php
> mail/review.php
> mail/seller.php
> mail/voucher.php
> openbay/amazon_order.php
> openbay/amazonus_order.php
> openbay/ebay_order.php
> openbay/etsy_order.php
> product/category.php
> product/compare.php
> product/manufacturer.php
> product/product.php
> product/search.php
> product/special.php
> seller/account.php
> seller/address.php
> seller/attribute.php
> seller/category.php
> seller/contact.php
> seller/download.php
> seller/edit.php
> seller/filemanager.php
> seller/folderimage.php
> seller/forgotten.php
> seller/invoiceorder.php
> seller/login.php
> seller/logout.php
> seller/messages.php
> seller/newsletter.php
> seller/offer.php
> seller/option.php
> seller/order.php
> seller/password.php
> seller/pay_address.php
> seller/plan.php
> seller/product.php
> seller/register.php
> seller/return.php
> seller/reward.php
> seller/success.php
> seller/transaction.php
> seller/voucher.php
> seller/wishlist.php
> shipping/auspost.php
> shipping/citylink.php
> shipping/fedex.php
> shipping/flat.php
> shipping/free.php
> shipping/item.php
> shipping/parcelforce_48.php
> shipping/pickup.php
> shipping/royal_mail.php
> shipping/ups.php
> shipping/usps.php
> shipping/weight.php
> tool/upload.php
> total/coupon.php
> total/credit.php
> total/handling.php
> total/klarna_fee.php
> total/low_order_fee.php
> total/reward.php
> total/shipping.php
> total/sub_total.php
> total/total.php
> total/voucher.php
Missing keys per file:
> empty.php: button_address_add
> empty.php: button_back
> empty.php: button_cancel
> empty.php: button_cart
> empty.php: button_change_address
> empty.php: button_checkout
> empty.php: button_compare
> empty.php: button_confirm
> empty.php: button_continue
> empty.php: button_coupon
> empty.php: button_delete
> empty.php: button_download
> empty.php: button_edit
> empty.php: button_filter
> empty.php: button_grid
> empty.php: button_guest
> empty.php: button_list
> empty.php: button_login
> empty.php: button_map
> empty.php: button_new_address
> empty.php: button_quote
> empty.php: button_remove
> empty.php: button_reorder
> empty.php: button_return
> empty.php: button_reviews
> empty.php: button_reward
> empty.php: button_search
> empty.php: button_shipping
> empty.php: button_shopping
> empty.php: button_submit
> empty.php: button_update
> empty.php: button_upload
> empty.php: button_view
> empty.php: button_voucher
> empty.php: button_wishlist
> empty.php: button_write
> empty.php: code
> empty.php: date_format_long
> empty.php: date_format_short
> empty.php: datetime_format
> empty.php: decimal_point
> empty.php: direction
> empty.php: error_exception
> empty.php: error_upload_1
> empty.php: error_upload_2
> empty.php: error_upload_3
> empty.php: error_upload_4
> empty.php: error_upload_6
> empty.php: error_upload_7
> empty.php: error_upload_8
> empty.php: error_upload_999
> empty.php: text_all_zones
> empty.php: text_home
> empty.php: text_loading
> empty.php: text_no
> empty.php: text_none
> empty.php: text_pagination
> empty.php: text_select
> empty.php: text_yes
> empty.php: thousand_point
> empty.php: time_format
```