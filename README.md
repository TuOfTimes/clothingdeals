# clothingdeals
clothing deals

## Approach

### Abercrombie
- on a given page, all products information is displayed in a ul of class "product-grid__products"
- promo announcement on "responsive-nav-wrap"
- each product has class "product-card"
- "product-card__image": image link stored in src
- "product-card__name": name in plaintext
- product-card__price": price in plaintext, and other promos

### Adidas
- all products (not all on one page though): https://www.adidas.com/us/men?grid=true
- products are contained in a div in id="product_grid"/id="hc-container"
- <div class="product-title"> for each product
- inside this div you can find:
-- class="product-info-inner-content": contains product name in field "data-productname"
-- class="price": contains price in "data-context"
-- class="image": contains link at <img ... src> 
-- also class="color-count>: contains available colors

by John Na and Edward Tu