# Jumia E-Commerce Sales Performance Dashboard

## 📊 Project Overview
This Power BI dashboard provides a strategic, executive-level analysis of sales performance, operational health, and revenue leakage for a Jumia storefront. By pairing financial metrics against operational volume, the report isolates exactly where revenue is being successfully captured versus where cash is leaking due to fulfillment failures.

## 🎨 Design System
* **Theme:** High-end modern application interface featuring a custom floating tile design.
* **Palette:** Vibrant Pink accents paired with Electric Blue data points over an ambient deep purple canvas.
* **Layout:** Structured alignment with 30% layer transparency, soft depth shadows, and 15px rounded borders for an interactive app feel.

## 📸 Dashboard Preview
![Jumia Dashboard Screenshot](dashboard_screenshot.png)

## 💡 Key Business Insights
* **The Cash-on-Delivery (COD) Risk:** Cash on Delivery remains the dominant driver of customer conversion, bringing in 65K KSh in delivered revenue. However, this channel introduces significant transit volatility compared to upfront mobile prepayments (46K KSh).
* **Delivery Failure Bottleneck:** While the storefront maintains a 62.5% success rate (10 orders), operational friction stems from Failed Deliveries (18.75% / 3 orders), which outpaces standard customer cancellations.
* **High-Value Product Leakage:** Premium lines like the *Luxury Velvet Blanket* and *6x6 Heavy Soft Woolen Duvet* generate the highest revenue gross volumes but also experience the highest concentration of lost cash due to delivery failures.

## 🛠️ Technical Skills Demonstrated
* **Advanced DAX Modeling:** Authored custom isolated measures (`Delivered_Revenue`, `Total_Lost_Revenue`) to accurately track specific financial states independently of global page filters.
* **UI/UX Customization:** Configured advanced visual properties, conditional formatting, and card styles to break out of rigid default templates into a modern app design.
* **Data Storytelling:** Linked cross-filtering elements between monthly trends, payment mode distributions, and product matrix drill-downs.
