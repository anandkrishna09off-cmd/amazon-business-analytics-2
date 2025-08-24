
# Results — Business Impact (Questions 4, 5, 6)

## Q4. Repeat Buyers by Price Buckets
**Method:** Users with >1 rows in dataset treated as repeat buyers. Primary price bucket = user's most frequent bucket.
**Key Results:**
price_bucket  users  repeat_rate_pct
       0-500    447             15.4
   1000-5000    383              8.6
      10000+     68             33.8
    500-1000    221              6.3
  5000-10000     75              6.7

**Insights:**
- Buckets with higher repeat rates are more suitable for loyalty perks and premium support.
- Buckets with low repeat rates but many users (e.g., 0–500) are ideal for upsell & cross-sell.

**Actions:**
- Create **VIP retention** flows for the bucket(s) with highest repeat_rate.
- For low-price buckets, trigger **post-purchase bundles** and **win-back coupons** in 7–14 days.

## Q5. Potential Churn Signals (Proxy)
**Definition:** Single-purchase users with discounted purchase and average price ≤ ₹500.
**Flagged potential churn users:** **355**
- Exported file: `potential_churn_users.csv` for CRM targeting.

**Actions:**
- Send **personalized win-back** emails (₹50–₹100 coupon, free shipping).
- Recommend **complementary low-cost accessories** matching last category purchased.

## Q6. Seasonality
No date column found — seasonality analysis not possible.

**If you want seasonality:** Add a column like `order_date` or `review_date` (YYYY-MM-DD). Then re-run the notebook section 6.
