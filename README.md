# Prestashop 1.7 Smarty Global Variables

<strong>Note: This only works with Prestashop 1.7.x.x versions.</strong>

## General info about your online store

`{$shop.name}` Store name

`{$shop.email}` Store Email
`{$shop.logo}` Store logo

`{$shop.favicon}` Store icon (map, title of the browser window, etc.)

`{$shop.address.address1}` Store address 1

`{$shop.address.address2}` Store address 2

`{$shop.address.postcode}` Store Zip Code

`{$shop.address.city}` Store City

`{$shop.address.state}` Store State (Province)

`{$shop.address.country}` Store Country

`{$shop.phone}` Store Telephone

`{$shop.fax}` Store Fax

## Language

`$language.name}` Name of the language in use (example: English) 

`{$language.iso_code}` ISO code of the language in use (it for Italian, fr for French, etc.)

`{$language.language_code}` Code of the language in use (it for Italian, en-us for American English, etc.)

`{$language.is_rtl}` (1 when language is written from right to left; 0 if from left to right)  

`{$language.id}` ID value of the language in use

## Currency

`{$currency.name}` Name of the currency in use (Euro, American Dollar, etc.)

`{$currency.iso_code}` Currency ISO code of the currency in use (Eur, USD, etc.)

`{$currency.sign}` Symbol of the currency in use (€, $, etc.) 

`{$currency.iso_code_num}` ISO code number of the currency in use (978 for Euro, 840 for American Dollar, etc.)

## Pages and elements of the e-commerce site

`{$urls.base_url}` Store web address (example: https://www.claudioalcantara.com)

`{$urls.current_url}` Current web address (url), the page we are viewing

`{$urls.shop_domain_url}` Store domain

`{$urls.img_ps_url}` Image root directory url

`{$urls.img_cat_url}` Url of the categories images directory

`{$urls.img_lang_url}` Url of the languages images directory

`{$urls.img_prod_url}` Url of the products images directory

`{$urls.img_manu_url}` Url of manufacturers images directory

`{$urls.img_sup_url}` Url of providers images directory

`{$urls.img_ship_url}` Url of carriers images directory

`{$urls.img_store_url}` Url of physical store images directory

`{$urls.img_url}` Url of theme images directory

`{$urls.css_url}` Url of css files directory used by the theme

`{$urls.js_url}` Url of javascript files directory used by the theme

`{$urls.pic_url}` Url of file uploaded directory

`{$page.page_name}` Page Name (file template)

`{$page.meta.title}` Page Title (SEO)

`{$page.meta.description}` Tag description content (SEO)

`{$page.meta.keywords}` Tag keywords content (SEO)

`{$page.meta.robots}` Rule for search engines: blocks or not the page indexing  (SEO)

`{$page.canonical}` Indicates the canonical (main) URL to avoid duplication of contents (SEO)

`{$urls.pages.address}` Url of the "My Address" section (registered user)

`{$urls.pages.addresses}` Url of the "My addresses" section (registered user)

`{$urls.pages.authentication}` Url of the authentication page

`{$urls.pages.cart}` Url of cart page (order summary)

`{$urls.pages.category}` Url of the category

`{$urls.pages.cms}` Url of the page (type CMS)

`{$urls.pages.contact}` Url of the contact page

`{$urls.pages.discount}` Url of the discount voucher page

`{$urls.pages.guest_tracking}` Tracking url for unregistered clients

`{$urls.pages.history}` Url of the "Order History" page (registered user)

`{$urls.pages.identity}` Url of the "Personal data" page (registered user)

`{$urls.pages.index}` Home page url

`{$urls.pages.my_account}` Url of "My Account" page (registered user)

`{$urls.pages.order_confirmation}` Url of the "Order Confirmation" page

`{$urls.pages.order_follow}` Url in the "Order Tracking" (registered user)

`{$urls.pages.order}` Url of the "Order" page

`{$urls.pages.order_return}` Url of the "Order Return" page

`{$urls.pages.order_slip}` Url of the "Order Slip" page

`{$urls.pages.pagenotfound}` Url of the "404 - Page not found"

`{$urls.pages.password}` Url of "Recover Password" page

`{$urls.pages.pdf_invoice}` Url of Pdf invoice

`{$urls.pages.pdf_order_return}` Url of Pdf order return

`{$urls.pages.pdf_order_slip}` Url of Pdf order slip

`{$urls.pages.prices_drop}` Url of "Our Offers" page 

`{$urls.pages.product}` Url of the "Product" page

`{$urls.pages.search}` Url of the "Search" page

`{$urls.pages.sitemap}` Url of thr "Site Map" page

`{$urls.pages.stores}` Url of the "Shops/Our stores" page

`{$urls.pages.supplier}` Url of the "Suppliers" page

`{$urls.pages.register}` Url of the "Register" page 

`{$urls.pages.order_login}` Url of the "Login" page

`{$urls.theme_assets}` Url of the "assets" directory of the theme

`{$urls.actions.logout}` Url to disconnect from the site (registered user)

## Cart

`{$cart.totals.total.amount}` The total amount of the cart without currency (ex: 45,00)

`{$cart.totals.total.value}` The total amount of the cart with currency (ex: 45,00 €)

`{$cart.totals.total_including_tax.amount}` The total amount of the cart, including taxes, without currency (ex: 45,00)

`{$cart.totals.total_including_tax.value}` The total amount of the cart, including taxes, with currency (ex: 45,00 €)

`{$cart.totals.total_excluding_tax.amount}` The total amount of the cart, excluding taxes, without currency (esempio: 35,70)

`{$cart.totals.total_excluding_tax.value}` The total amount of the cart, excluding taxes, with currency (esempio: 35,70 €)

`{$cart.products_count}` Number of products in the cart

`{$cart.subtotals.products.amount}` The amount of products in the cart without currency

`{$cart.subtotals.products.value}` The amount of products in the cart withcurrency

`{$cart.subtotals.shipping.amount}` The amount of shipping in the cart without currency

`{$cart.subtotals.shipping.value}` The amount of shipping in the cart with currency

## Customers

`{$customer.lastname}` Customer Last Name

`{$customer.firstname}` Customer First Name

`{$customer.email}` Customer Email (provided during the registration)

`{$customer.birthday}` Customer Birthday

`{$customer.newsletter}` Subscribed to the newsletter (1 if subscribed, 0 if unsubscribed)

`{$customer.newsletter_date_add}` Newsletter subscription date

`{$customer.ip_registration_newsletter}` IP of Customers at the newsletter registration

`{$customer.optin}` Subscribed to offers from partners (1 if subscribed, 0 if unsubscribed)

`{$customer.date_add}` Customer registration

`{$customer.date_upd}` Last updated (customer registration)

`{$customer.id}` Customer ID

`{$customer.id_default_group}` ID group to which the client is associated

`{$customer.is_logged}` Check if the client is "logged in" (1 yes, 0 no)

`{$customer.gender.name[$customer.gender.id]}` Client Gender (example: Ms, Mr, etc.)

`{$customer.addresses[AddressID].city}` Client City of address with an ID (AddressID, example 8, where 8 is the ID of the customer's address), because a client could have multiple addresses)

`{$customer.addresses[AddressID].alias}` Address alias

`{$customer.addresses[AddressID].firstname}` Address Holder first name

`{$customer.addresses[AddressID].lastname}` Address Holder last name

`{$customer.addresses[AddressID].company}` Address Holder company

`{$customer.addresses[AddressID].address1}` Address Holder address 1

`{$customer.addresses[AddressID].address2}` Address Holder address 2

`{$customer.addresses[AddressID].postcode}` Address Holder ZIP code

`{$customer.addresses[AddressID].id_state}` Address Holder ID state

`{$customer.addresses[AddressID].state}` Address Holder state name

`{$customer.addresses[AddressID].state_iso}` Address Holder state ISO code

`{$customer.addresses[AddressID].id_country}` Address Holder ID country

`{$customer.addresses[AddressID].country}` Address Holder country name

`{$customer.addresses[AddressID].country_iso}` Address Holder ISO country

`{$customer.addresses[AddressID].phone}` Address Holder telephone

`{$customer.addresses[AddressID].phone_mobile}` Address Holder mobile phone

`{$customer.addresses[AddressID].dni}` Address Holder DNI

`{$customer.addresses[AddressID].vat_number}` Address Holder VAT number

`{$customer.addresses[AddressID].formatted}` Address Holder formatted address
