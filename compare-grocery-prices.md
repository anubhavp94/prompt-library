# Compare Grocery Prices from Blinkit Cart

## Step 1: Extract Cart Items from Blinkit
- Navigate to your Blinkit cart
- Extract each item's details:
  - Product name
  - Brand name  
  - Size/quantity
  - Current price in Blinkit

## Step 2: Clear Existing Carts on Other Platforms
Before adding new items, clear any existing cart items:
1. **Zepto** - zepto.com
   - Navigate to cart
   - Remove all existing items (click remove/delete for each item)
   - Verify cart is empty
2. **Swiggy Instamart** - swiggy.com/instamart
   - Navigate to cart
   - Remove all existing items (click remove/delete for each item)
   - Verify cart is empty

## Step 3: Search and Add to Cart on Other Platforms
Navigate to each platform and search for cart items:

## Search Strategy (Use in Order)

### Step 1: Exact Search
- Use the exact product name from Blinkit cart
- Example: "Amul Gold Milk 1L"

### Step 2: Brand + Generic Search (If Step 1 fails)
- Search: "[Brand] [Generic Item Type]"
- Example: "Amul milk" or "Britannia biscuits"

### Step 3: Generic Search (If Step 2 fails)  
- Search only: "[Generic Item Type]"
- Example: "milk" or "biscuits"
- Filter for closest match to original brand/size

## Add to Cart Process
For each item found:
1. **Select the item** that best matches the Blinkit product
2. **Choose quantity** to match Blinkit cart quantity
3. **Click "Add to Cart"** or equivalent button
4. **Verify item added** - check cart icon or confirmation message
5. **Continue to next item**

## Data Collection
For each item found and added, record:
- Platform name
- Product name (as shown)
- Price
- Size/quantity
- Quantity added to cart
- Price per unit (if available)
- Delivery time
- Stock status
- Any offers/discounts
- Cart add status (Added/Failed)

## Step 4: Final Cart Summary
Navigate to cart on each platform to verify:
1. **Zepto Cart** - Review total price and delivery charges
2. **Swiggy Instamart Cart** - Review total price and delivery charges
3. **Compare with Blinkit** original cart total

## Step 5: Price Comparison Table
Create table with columns:
| Blinkit Item | Quantity | Blinkit Price | Zepto Price | Instamart Price | Cart Status | Best Deal |

## Instructions
- If exact search fails, try brand + generic, then generic only
- Match quantities exactly when adding to cart
- Check delivery area availability before adding items
- If "Add to Cart" fails, try refreshing page and retry
- Mark cart status as "Added", "Failed", or "Not Available"
- Note any minimum order requirements
- Include delivery charges in final comparison
- Highlight platform with lowest total cost (items + delivery)