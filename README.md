# 🛍️ Customer Segmentation for Clothing Store
This project applies clustering to segment customers based on their shopping behavior, preferences, and demographics.  
The analysis uses multiple dimensions such as gender, product categories, sizes, seasonality, subscription/promo usage, payment/shipping preferences, and color preferences.

In today’s fast-paced e-commerce landscape, understanding customers isn’t just a strategy—it’s a necessity. Our task is to design a customer clustering framework to unlock valuable insights into customer behavior. This approach will allow us to segment customers based on their purchasing patterns, preferences, and demographics.

Why does this matter? Because not all customers are the same. A one-size-fits-all promotion strategy no longer works in a market flooded with choices. By clustering customers into meaningful groups, we can pinpoint what types of product promotions resonate most with each segment.

This isn’t just about boosting sales—it’s about creating personalized experiences that make customers feel understood and valued. It’s about fostering loyalty in an environment where customer retention is more critical than ever.

By leveraging clustering, we’re not just analyzing data; we’re shaping strategies that align with customer needs, driving business growth and long-term success.

---

## 📊 Clustering Performance
- **Algorithm Used:** K-Means (k=5)  
- **Silhouette Score:** ~0.5 → indicates **moderate but meaningful clusters**, which is acceptable in retail datasets where customer behaviors naturally overlap.  

---

## 👥 Customer Personas

### Cluster 0 → Casual Bargain Seekers
- Gender mix: Balanced, slight male lean  
- Category preference: Mix of Clothing & Accessories  
- Size preference: Spread across L and XL  
- Seasonality: Strong spike in Summer purchases  
- Promo behavior: Mixed, often uses promos  
- Payment & shipping: Likes cash/bank transfer and standard shipping  
- Color style: Cool tones (blue, grey, black)  

✅ Persona: Budget-conscious casual shoppers, often buying in summer sales, prefer practical payment methods, and go for classic colors.  
📢 Marketing angle: Target with summer promotions, bundle deals, and discount vouchers.  

---

### Cluster 1 → Steady Minimalists
- Gender mix: More female representation  
- Category preference: Balanced across categories (Clothing & Accessories)  
- Size preference: Mix of S, L, and some XL  
- Seasonality: Spread evenly, not strongly seasonal  
- Promo behavior: Low promo usage, not very discount-driven  
- Payment & shipping: Prefers debit/bank transfer, slower shipping acceptable  
- Color style: Neutral and pastel tones  

✅ Persona: Loyal and steady shoppers, less promo-sensitive, shop consistently year-round.  
📢 Marketing angle: Engage via loyalty/subscription programs and highlight quality over discounts.  

---

### Cluster 2 → Fashion-Forward Deal Hunters
- Gender mix: Mostly male  
- Category preference: Heavy on Clothing + some Accessories  
- Size preference: Dominated by M  
- Seasonality: Consistent across all seasons  
- Promo behavior: Promo code lovers, heavy users of discounts  
- Payment & shipping: Prefer credit card & fast shipping (next-day/express)  
- Color style: Warm & neutral tones  

✅ Persona: Trendy male shoppers, prefer fast delivery, and chase promo codes for clothing.  
📢 Marketing angle: Use flash sales, promo-driven campaigns, and seasonal product launches.  

---

### Cluster 3 → Accessory Enthusiasts
- Gender mix: More female  
- Category preference: Lean toward Accessories (bags, jewelry)  
- Size preference: Mostly M, less variety  
- Seasonality: Balanced but not heavy in Winter  
- Promo behavior: Less frequent promo use  
- Payment & shipping: More standard shipping, mix of payment methods  
- Color style: Cool tones with some neutral  

✅ Persona: Fashion-conscious accessory buyers, not highly discount-driven, steady seasonal shoppers.  
📢 Marketing angle: Promote new accessory collections, upsell clothing with accessories, bundle cross-category offers.  

---

### Cluster 4 → Seasonal Stylists
- Gender mix: Male-dominated  
- Category preference: Strong in Clothing  
- Size preference: Split between L and S  
- Seasonality: Heavy Winter buyers, also strong in Fall  
- Promo behavior: Uses promos but not as aggressively as Cluster 2  
- Payment & shipping: Mix of credit card & faster shipping  
- Color style: Warm & pastel colors  

✅ Persona: Seasonal shoppers who stock up during colder months, stylish and selective.  
📢 Marketing angle: Push winter/fall collections, highlight seasonal colors, and promote premium shipping options.  


---

## 📌 Summary Table

| Cluster | Persona Name              | Key Traits                                | Marketing Angle                               |
|---------|---------------------------|-------------------------------------------|-----------------------------------------------|
| 0       | Casual Bargain Seekers    | Summer buyers, cool tones, promo users    | Discounts, summer bundles, voucher campaigns |
| 1       | Steady Minimalists        | Year-round buyers, neutral tones, loyal   | Loyalty programs, quality-first messaging     |
| 2       | Fashion-Forward Hunters   | Male, medium size, promo-driven, fast ship| Flash sales, seasonal launches, promo deals  |
| 3       | Accessory Enthusiasts     | Female skew, loves accessories, cool tones| Accessory launches, bundle with clothing      |
| 4       | Seasonal Stylists         | Winter/Fall buyers, warm/pastel colors    | Seasonal campaigns, premium shipping options |

---

## 🛠️ Tech Stack
- **Language:** Python 
- **Libraries:** pandas, matplotlib, seaborn, scikit-learn  
- **Visualization:** Cluster-wise barplots & distribution charts  

---

✨ This segmentation provides actionable insights to **tailor marketing, promotions, and inventory strategies** for different customer groups.
