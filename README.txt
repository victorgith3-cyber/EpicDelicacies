EPIC DELICACIES - landing page
==============================

OPEN IT
  Double-click index.html. Keep the "images" folder and the icon files
  next to it, otherwise pictures will not show.

PUT IT ONLINE (free, no backend)
  - Netlify: go to app.netlify.com/drop and drag the whole folder in.
  - Or Cloudflare Pages / GitHub Pages.
  After it is live, open index.html and change the og:image line near the
  top to the full address, e.g. https://yourdomain.com/images/og-share.jpg
  so WhatsApp/Facebook link previews show the logo.

EDIT THE CONTENT  (open index.html in any text editor)
  Search for "CLIENT CONFIG". There you can change:
    BUSINESS  - WhatsApp number, display number, social links
    PRODUCTS  - names, descriptions, categories, photos, optional price
    BOOKINGS  - the four booking buttons and their WhatsApp messages
  Colours: the ":root" block at the top of the CSS.

CART
  Each product has "Add to cart". A green "View cart" button appears at the
  bottom-left. The cart lets customers change quantities, enter name,
  delivery/pickup, location, time and notes, then sends the whole list to
  your WhatsApp in one message. The cart is remembered on their device.
  Add price:150 (a number) to products to show prices and a cart total.
  The total appears only when every item in the cart has a price.

ADD A PRODUCT
  1. Save a photo in the images folder (about 800px wide, JPG).
  2. Copy one line in PRODUCTS and change name, image, description.
  Add price:150 to a line to show a price (currency is set in BUSINESS).

REUSE FOR ANOTHER CLIENT
  Copy this folder, then change: the CONFIG block, the colours, the fonts
  (Google Fonts link), the logo/favicon files and the photos. Also change
  the layout of the hero so each client's site looks different.

FAVICON FILES
  favicon.ico, favicon-16/32/48.png, apple-touch-icon.png, icon-192.png,
  icon-512.png, icon-maskable-512.png, site.webmanifest
  To change the logo, replace these with new versions of the same names.

NOTE ON PHOTOS
  images/popsicles.jpg has a stock-photo watermark. Replace it with your
  own photo (same file name) before you advertise.
