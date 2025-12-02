# Images Directory - The 27th Plate

## Image Integration Status ✅

All images have been successfully integrated and linked throughout the website.

---

## 📸 Product Images (6 files)

These images appear on the Menu page and Product detail pages:

```
images/
├── WatermelonJuice.jpg ................. Water Melon Chill Splash (Product)
├── PassionFruitJuice.jpg .............. Passion Bliss (Product)
├── CreamyWoodApple.jpg ................ Creamy Wood Apple (Product)
├── CoffeeCloud.jpg .................... Coffee Cloud (Product)
├── YellowRice.jpg ..................... Grandma's Chicken Yellow Rice (Product)
└── RiceandCurry.jpg ................... Homemade Chicken Rice & Curry (Product)
```

**Used In:**
- menu.html (Menu page product cards)
- Product detail pages (Header image)

---

## 🌍 Origin Story Images (6 files)

These images appear in the "Origin Story" section of each product detail page:

```
images/
├── Origins-watermelon.jpg ............. Water Melon Origin Story
├── Origins-passion.jpg ................ Passion Fruit Origin Story
├── Origin-woodapple.jpg ............... Wood Apple Origin Story
├── Origin-coffeecloud.jpg ............ Coffee Origin Story
├── Origins-yellowrice.jpg ............ Yellow Rice Origin Story
└── Origins-riceandcurry.jpg ......... Rice & Curry Origin Story
```

**Used In:**
- Product detail pages (Origin Story section)

---

## 📖 Product Story Images (6 files)

These images appear in the "Our Story" section of each product detail page:

```
images/
├── Story-watermelon.jpg ............... Water Melon Story
├── Story-passion.jpg .................. Passion Bliss Story
├── MyStory-woodapple.jpg .............. Wood Apple Story
├── Story-coffeecloud.jpg .............. Coffee Cloud Story
├── MyStory-yelowrice.jpg .............. Yellow Rice Story
└── MyStory-riceandcurry.jpg .......... Rice & Curry Story
```

**Used In:**
- Product detail pages (Product Story section)

---

## 🏠 Other Images

```
Images/
└── Official logo.png .................. Logo (used in navbar on all pages)
```

---

## ✅ Image Link Verification

All images are linked using relative paths from their respective pages:

### From menu.html (root level):
```html
<img src="images/WatermelonJuice.jpg" alt="Water Melon Chill Splash">
```

### From product pages (/products/ folder):
```html
<img src="../images/WatermelonJuice.jpg" alt="Water Melon Chill Splash">
```

---

## 📊 Total Images

- Product Images: 6
- Origin Story Images: 6
- Product Story Images: 6
- Logo: 1
- **Total: 19 images**

---

## 🔄 How Images Are Used

### Menu Page
Each product has a product image displayed in a card format:
- Watermelon Juice product image
- Passion Fruit product image
- Wood Apple product image
- Coffee Cloud product image
- Yellow Rice product image
- Rice & Curry product image

### Product Detail Pages
Each product page includes:
1. **Product Image** (header) - Shows the finished product
2. **Origin Story Image** - Shows where/how the ingredients come from
3. **Product Story Image** - Shows the story behind the product creation

### Navigation
Logo appears in the navbar on all 12 pages.

---

## 🎯 Best Practices for Images

### Image Optimization
- Images should be optimized for web (compress before uploading)
- Recommended file size: 100-300KB per image
- Formats: JPG for photos, PNG for graphics

### Image Placement
- Ensure images are in the correct folder
- Use relative paths (not absolute paths)
- Keep file names consistent with links

### Image Updates
- To replace an image, keep the same filename
- No need to update HTML files
- Just replace the file in the images/ folder

---

## 🖼️ Viewing Images

All images can be viewed:
- On the Menu page (product cards)
- On each Product detail page (3 images per product)
- In the Images/ folder (logo)

---

## 📁 Folder Structure

```
27th plate/
└── images/
    ├── WatermelonJuice.jpg ................. Product
    ├── PassionFruitJuice.jpg .............. Product
    ├── CreamyWoodApple.jpg ................ Product
    ├── CoffeeCloud.jpg .................... Product
    ├── YellowRice.jpg ..................... Product
    ├── RiceandCurry.jpg ................... Product
    ├── Origins-watermelon.jpg ............. Origin
    ├── Origins-passion.jpg ................ Origin
    ├── Origin-woodapple.jpg ............... Origin
    ├── Origin-coffeecloud.jpg ............. Origin
    ├── Origins-yellowrice.jpg ............. Origin
    ├── Origins-riceandcurry.jpg .......... Origin
    ├── Story-watermelon.jpg ............... Story
    ├── Story-passion.jpg .................. Story
    ├── MyStory-woodapple.jpg .............. Story
    ├── Story-coffeecloud.jpg .............. Story
    ├── MyStory-yelowrice.jpg .............. Story
    ├── MyStory-riceandcurry.jpg .......... Story
    ├── origin/ ............................ (Empty - for future use)
    └── story/ ............................. (Empty - for future use)

Images/
└── Official logo.png ..................... Logo
```

---

## ✨ Image Quality

All linked images are:
- ✅ Optimized for web
- ✅ High resolution
- ✅ Properly formatted
- ✅ Correctly linked in HTML
- ✅ Displaying on all pages

---

## 📝 Adding New Images

To add new images:

1. **Create the image** and save it to the `images/` folder
2. **Update the HTML** with the new image link
3. **Test the link** to ensure it displays correctly

Example:
```html
<img src="images/new-product.jpg" alt="New Product">
```

---

## 🐛 Troubleshooting

### Images Not Showing?

1. **Check file path**
   - Ensure path is relative: `images/filename.jpg` or `../images/filename.jpg`
   - Not absolute: `C:\Users\...` ❌

2. **Check file exists**
   - Verify image file is in the correct folder
   - Check spelling matches exactly

3. **Clear cache**
   - Hard refresh (Ctrl+Shift+R)
   - Open in incognito window
   - Clear browser cache

4. **Check file format**
   - Ensure file extension is correct (.jpg, .png, etc.)
   - Verify file is actually an image

---

## ✅ Verification Checklist

- [x] All 6 product images linked and displaying
- [x] All 6 origin story images linked and displaying
- [x] All 6 product story images linked and displaying
- [x] Logo displaying in navbar on all pages
- [x] All image paths are relative
- [x] All images optimized for web
- [x] No broken image links
- [x] Images responsive on all devices

---

## 📞 Contact

For image-related issues, refer to the main website documentation:
- README.md
- QUICK_START.md
- IMPLEMENTATION_SUMMARY.md

---

**Status:** ✅ All Images Successfully Integrated

Created: December 2, 2025  
Project: The 27th Plate - Homemade Cloud Kitchen Website
