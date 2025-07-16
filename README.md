# 🛍️ Ecommerce Product API (Mock)

This is a simple **public JSON API** containing mock product data for clothing and accessories — ideal for developers working on frontend projects, prototyping e-commerce apps, or building portfolios.

Hosted using **GitHub** + **jsDelivr CDN** for fast and reliable access.

---

## 📦 API Endpoint

You can fetch all products using the following URL:

https://cdn.jsdelivr.net/gh/Vinodkumar9429/ecommerce-db@main/db.json


---

## ✅ Sample Usage (React / JavaScript)

### 🔹 Fetch all products:

```js
fetch("https://cdn.jsdelivr.net/gh/Vinodkumar9429/ecommerce-db@main/db.json")
  .then(res => res.json())
  .then(data => console.log(data.products));
```



## 🧾 JSON Structure : 


```
{
  "products": [
    {
      "id": 1,
      "name": "Oversized Half Sleeves",
      "price": 1075,
      "category": "men",
      "sizes": ["L", "XL"],
      "description": "Crafted for modern style and everyday ease, this Oversized Half Sleeves blends comfort with a touch of class.",
      "image": "https://images.unsplash.com/photo-1620461818402-d991ac8a03a2?w=600&auto=format&fit=crop&q=60"
    },
    ...
  ]
}
