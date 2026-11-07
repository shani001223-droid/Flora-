# Flora By M/S & CO. — Online Store

A mobile-first, single-page, static storefront for Flora herbal hair care, beauty and wellness products.

## What works
- Browsable product catalog, category filters and live search
- Cart with quantities, local browser persistence and subtotal
- WhatsApp retail checkout (order request, not automatic order/payment capture)
- Individual product price inquiries for products without confirmed prices
- Reseller inquiry (minimum 5 hair-care sets; advance bank transfer by manual confirmation)
- Responsive, keyboard-accessible navigation and cart

## Catalog
- Herbal Shampoo + Hair Oil Set (500 ml + 250 ml): **PKR 2,520** (previously PKR 3,000)
- Herbal Shampoo (500 ml): price on request
- Herbal Hair Oil (250 ml): price on request
- 24K Golden Facial Kit (6 pieces): **PKR 3,500**
- Herbal Phakki, Wellness Powder (500 g), Protein Powder: pricing and details on request

No unsupported product/medical claims, fictitious reviews, fictional bank account, or automatic payment processing. Product illustrations are placeholders, not the approved product photographs. The merchant must verify prices, ingredients, policy wording, delivery fees, availability and product imagery before promotional launch.

## Order flow
The **Send order on WhatsApp** button creates a prefilled message to the contact team. It does not store customer contact information on a backend, charge a card or mark the order paid.

Main WhatsApp orders, reseller inquiries and customer support: **+92 337 3764975** (WhatsApp: https://wa.me/923373764975).

## Publishing on GitHub Pages
1. In this repository, open **Settings → Pages**.
2. Choose **Deploy from a branch**, select **main** and **/(root)**, then Save.
3. The published URL is typically: \`https://shani001223-droid.github.io/Flora-/\`.
4. Check the site and test WhatsApp checkout on mobile.

The site needs no build step, framework, paid service or API key.

## Maintenance
Edit the product records inside the \`products\` array in \`index.html\`. Change a \`price:null\` to an approved integer PKR price when ready to sell it through the cart. Replace illustrative visuals with exact owner-approved photos once available. Do not put private account credentials or payment details into public GitHub files.

© Flora By M/S & CO.