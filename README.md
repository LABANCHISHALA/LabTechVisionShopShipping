# LabTechVision Shop

Storefront for lab and test equipment delivering across Africa: 15 country options, local currencies, and each country's usual mobile money and bank payment methods. Orders go to your WhatsApp.

## Put it on GitHub Pages
1. Create a new public repository on github.com.
2. Upload everything in this folder (index.html, images, .nojekyll).
3. Settings > Pages > Deploy from a branch > main, folder /root > Save.
4. Your shop appears at https://YOUR-USERNAME.github.io/REPO-NAME/ after a minute or two.

## Change contacts, payment details and adverts
- Open your shop and click "Owner settings" in the footer (or add #owner to the address).
- Edit phone, WhatsApp number, email, payment details per method, and the top advert banner. Save.
- That saves in YOUR browser only. To change them for everyone, copy the code shown at the bottom of the panel and paste it over the `var CFG0=` line in index.html, then upload the file again.

## Sending adverts
In Owner settings, pick a product, edit the message, then send it on WhatsApp (you choose contacts or groups) or by email to buyers who ticked the offers box. Visitors also see the optional banner at the top of the shop.

## Buyer accounts
Buyers register (name, age, country, city, phone, email, password) and sign in or out from the top bar. In this static version accounts are stored in the buyer's own browser only, so you cannot see them from your side. A shared customer list and password reset need the live WooCommerce store ("Go live" section) or a backend.

## Account required to order
Everyone can browse the shop freely. Adding to the cart or placing an order asks the visitor to create an account or sign in first, then continues what they were doing.

## Payments and approval
Checkout offers each country's mobile money and bank methods plus Visa/Mastercard and PayPal. In Owner settings enter your PayPal.me name and a card payment link (from your card provider) and the shop opens them with the order amount. Every order waits as "Awaiting approval" in the Orders list until you press "Approve payment"; only approved orders move on to the supplier steps.

## eBay and AliExpress
Supplier sync has Connect AliExpress and Connect eBay buttons. They are a preview in this static page; a live link needs eBay Developer keys and supplier sign-in through a sync app or plugin. In Owner settings you can add products bought from AliExpress or eBay and remove them. Products show "Bought" once an order has been sent to the supplier, and buyers see a green "Bought" badge on items they ordered.

## Real photos
Save photos as images/products/1.jpg ... 12.jpg and change `PHOTO_EXT=".svg"` to `PHOTO_EXT=".jpg"` in index.html. Use only photos you own or have permission to use.

## Limits
GitHub Pages hosts static files only. You confirm payments by hand, then ship. Confirm each country's payment methods, fees and import rules with your provider.
