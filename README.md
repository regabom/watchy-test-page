# Watchy test page

A fake public product page used to test Watchy change detection end to end. Nothing here is for sale.

Edit `index.html` to simulate changes:
- **Relevant change:** edit the `Sale price` line (`id="price"`). Watchy should alert.
- **Irrelevant change:** edit the banner, the reviews count or the "Customers also bought" prices. Watchy should stay quiet.
