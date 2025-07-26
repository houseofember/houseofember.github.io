# 🕯️ House of Ember - Dynamic Products Guide

## How to Add New Products

Your website now automatically loads products from `products.json` - no more code changes needed!

### ✅ Simple Process:

1. **Add your image** to the appropriate collection folder:
   - `images/premium_collections/`
   - `images/jar_candles/`
   - `images/traditional_collection/`
   - `images/hampers/`

2. **Add the product name** to `products.json`:
   ```json
   {
     "premium_collections": [
       "existing_product_1",
       "existing_product_2",
       "your_new_product"  ← Add this line
     ]
   }
   ```

3. **Done!** Refresh your website and the new product appears automatically.

### 📋 Example:

**Step 1:** Save image as `images/premium_collections/vanilla_dreams.png`

**Step 2:** Edit `products.json`:
```json
{
  "premium_collections": [
    "blueberry_martini_candle",
    "cactus_boat",
    "vanilla_dreams"  ← New product added
  ],
  "jar_candles": [
    "jar_candle",
    "gel_wax_candle_jar"
  ]
}
```

**Step 3:** Refresh website → "Vanilla Dreams" appears automatically!

### 🎯 Naming Rules:

- **File naming:** Use underscores: `vanilla_dreams.png`
- **Display title:** Automatically converts to: "Vanilla Dreams"
- **File formats:** `.png`, `.jpg`, `.jpeg` supported

### 🔧 Features:

- ✅ **Automatic CSS generation** for background images
- ✅ **Automatic HTML generation** for product cards
- ✅ **Title conversion** (underscore → proper case)
- ✅ **Zero code changes** needed
- ✅ **Instant updates** - just refresh the browser

### 🚨 Troubleshooting:

**Product not showing?**
1. Check file name matches exactly in JSON
2. Verify image is in correct folder
3. Check browser console for errors
4. Ensure JSON syntax is valid

**Need help?** The system logs helpful messages in browser console (F12 → Console).

---
*Now adding products is as easy as dropping files and editing one line in JSON!* ✨ 