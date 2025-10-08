# LynqHub E-Commerce Analysis

# Company Background

<img width="1000" height="250" alt="image" src="https://github.com/user-attachments/assets/888ce549-cc7f-47fc-b4f6-d08ca132b3e7" />


&nbsp;  

Founded in 2018, LynqHub has quickly established itself as a global e-commerce leader in consumer electronics. Originally launched as an online retail platform, the company has expanded at a rapid pace, attracting a diverse customer base across international markets. Its portfolio features high-demand products from leading brands such as Apple, Samsung, and Lenovo, positioning LynqHub as a trusted destination for technology enthusiasts worldwide.

To fuel its growth, LynqHub leverages a multi-channel marketing strategy that includes email campaigns, search engine optimization (SEO), and affiliate partnerships, enabling the company to effectively engage and expand its global audience.

<details>
<summary> 🟢 Project Goals</summary>
&nbsp;  

LynqHub has accumulated extensive data across orders, customers, products, and geographic activity. However, much of this data remains unrefined and underutilized. The project’s goal is to clean, structure, and analyze this data to extract meaningful insights that can support finance, sales, product, and marketing teams. By transforming raw data into actionable intelligence, the project aims to:

- Improve operational efficiency
- Enable data-driven decision-making
- Optimize business processes
- Enhance customer experience on a global scale </details>

<details>

<summary> 🟢 Stakeholder Questions </summary>
&nbsp;  

1. What were the overall sales trends from 2019 to 2022?
2. What were the company's yearly and monthly growth rates?
3. How has the new loyalty program performed? Should we keep using it?
4. What was the company's refund rate and average order value (AOV)?

Key Metrics :

- Analyze sales, average order value (AOV), and order count to assess overall growth trends.

- Evaluate loyalty program performance, with particular emphasis on average order value (AOV) as a key indicator of customer value.

- Examine refund patterns in relation to AOV, with a specific focus on Apple products, incorporating both refund count and refund rate as critical metrics for comparison.

</details>

<details>

<summary> 🟢 Analysis Roadmap </summary>

- [Executive Summary](#executive-summary)
- [Insights Deep Dive](#insights-deep-dive)
  - [Growth Trends](#growth-trends)
  - [Seasonal Trends](#seasonal-trends)
  - [Product Trends](#product-trends)
  - [Geographical Trends](#geographical-trends)
  - [Loyalty Program](#loyalty-program)
  - [Refund Rates](#refund-rates)
- [Interactive Dashboard](#interactive-dashboard)
- [Appendix](#appendix)


</details>

# Executive Summary

<img width="1263" height="709" alt="image" src="https://github.com/user-attachments/assets/8fdcb7d5-5683-4e7b-9ac9-dbbe050e80c6" />


<p><b>LynqHub Performance (2018–2022)</b></p>

<p>
LynqHub recorded a strong upward trajectory from <b>2018 through early 2020</b>, achieving <b>total sales of approximately $26 million</b> and processing over <b>102,000 orders</b> across the five-year period. 
The company’s <b>average order value (AOV)</b> over this timeframe stood at roughly <b>$255 per order</b>, underscoring consistent purchasing behavior and healthy transaction sizes.
</p>


<ul>
  <li><b>Pandemic-Driven Peak (2019–2020)</b>
    <ul style="list-style-type: circle;">
      <li>Between 2018 and early 2020, order volume <b>nearly doubled (+95%)</b>, indicating rapid expansion and sustained demand growth.</li>
      <li>This surge in orders <b>propelled sales growth of over 50% year-over-year</b>, marking one of the company’s strongest upward trends to date.</li>
      <li>In <b>2020</b>, LynqHub reached its <b>highest performance point</b>, with <b>sales exceeding $9 million</b>, driven by surging demand and an expanding online customer base.</li>
      <li>The <b>average order value (AOV)</b> peaked at approximately <b>$275</b>, reflecting a shift toward higher-value products and stronger digital conversions during the pandemic period.</li>
    </ul>
  </li>
</ul>

<ul>
  <li><b>Post-2020 Decline and Market Stabilization</b>
    <ul style="list-style-type: circle;">
      <li>Following the <b>2020 peak</b>, LynqHub’s <b>sales momentum weakened</b>, signaling the start of a downward trend after a period of exceptional growth.</li>
      <li><b>Total revenue declined by about 15% in 2021</b> and fell even more sharply—<b>by approximately 45–50% in 2022</b>—bringing yearly sales down to nearly <b>$4.5 million</b>.</li>
      <li><b>Order count mirrored this decline</b>, dropping by <b>more than half (−55%)</b> compared to its 2020 high, underscoring a broad contraction in customer demand.</li>
      <li>The <b>average order value (AOV)</b> decreased moderately, stabilizing around <b>$240–$250 per order</b>, suggesting that the downturn was primarily <b>volume-driven rather than pricing-related</b>.</li>
    </ul>
  </li>
</ul>


<ul>
  <li><b>Key Insights & Opportunities</b>
    <ul style="list-style-type: circle;">
      <li><b>Sustained Customer Engagement:</b> The sharp decline after 2020 suggests a <b>pandemic demand bubble</b>. Building <b>retention programs</b> and <b>reactivating the 2020 cohort</b> could recover up to <b>30–35% of lost orders</b>.</li>
      <li><b>Product Mix Optimization:</b> With <b>AOV holding steady</b>, there’s potential to emphasize <b>higher-margin products</b> without reducing order frequency.</li>
      <li><b>Seasonal Campaign Leverage:</b> <b>Quarter 4 spikes</b> in both <b>2020 and 2021</b> highlight a recurring <b>end-of-year demand opportunity</b> that can be strategically amplified.</li>
    </ul>
  </li>
</ul>

# Insights Deep Dive
## Growth Trends
<p align="center">
  <img src="https://github.com/user-attachments/assets/47ef0da6-57fe-4ca1-ba99-4f377a8c0e12" alt="Total Sales" width="33%" height="260">
  <img src="https://github.com/user-attachments/assets/ef2fd168-4f48-4123-8a87-caccd9bb6e64" alt="AOV" width="33%" height="260">
  <img src="https://github.com/user-attachments/assets/47030e77-a99a-4320-8df9-0037f394a3d2" alt="Order Count" width="33%" height="260">
</p>

<p><b>Total Sales – Growth Insights</b></p>
<ul style="list-style-type: circle;">
  <li><b>Volatility & Peaks:</b> The Total Sales trend shows significant month-to-month volatility, especially between late <b>2019</b> and mid-<b>2020</b>, where growth peaked around <b>+50%</b>. These surges coincide with high-order months and likely reflect short-term demand spikes such as pandemic-related buying behavior.</li>
  <li><b>Sharp Declines:</b> Following each surge, sharp contractions of <b>−30% to −50%</b> indicate that sales are highly reactive to external demand triggers rather than driven by steady organic growth.</li>
  <li><b>Post-2021 Flattening:</b> After <b>2021</b>, growth rates stabilized below <b>+10%</b>, suggesting LynqHub entered a <b>plateau phase</b> with limited new customer acquisition or expansion opportunities.</li>
</ul>

<p><b>Recommendations:</b></p>
<ul style="list-style-type: circle;">
  <li><b>Implement Predictive Demand Planning:</b> Use historical MoM data to forecast demand surges and optimize marketing and inventory cycles to reduce volatility.</li>
  <li><b>Diversify Product Portfolio:</b> Introduce new categories or complementary products to smooth out revenue fluctuations across months.</li>
  <li><b>Maintain Marketing Continuity:</b> Develop ongoing loyalty or subscription programs to promote consistent engagement and prevent post-peak drop-offs.</li>
</ul>

<br>

<p><b>Average Order Value (AOV) – Growth Insights</b></p>
<ul style="list-style-type: circle;">
  <li><b>Moderate Fluctuations:</b> AOV shows smaller, more controlled swings ranging from <b>+18%</b> to <b>−16%</b>, reflecting relatively stable transaction values compared to total sales or order count.</li>
  <li><b>Seasonal Spikes:</b> Noticeable AOV increases of <b>10–18%</b> are likely tied to promotional or festive months, suggesting effective short-term upselling or premium product interest.</li>
  <li><b>Recent Downtrend:</b> The recent pattern shows more declines than gains, indicating a <b>gradual reduction in average spend per order</b>—possibly due to discount dependency or lower-priced product preferences.</li>
</ul>

<p><b>Recommendations:</b></p>
<ul style="list-style-type: circle;">
  <li><b>Encourage Upselling & Bundling:</b> Create bundled offerings and value-based upgrades to lift average transaction values during regular months.</li>
  <li><b>Limit Excessive Discounting:</b> Replace heavy discounts with loyalty rewards or free-shipping thresholds to maintain AOV stability without margin erosion.</li>
  <li><b>Customer Segmentation:</b> Identify high-value customer segments and personalize campaigns to target premium buyers more effectively.</li>
</ul>

<br>
<p><b>Order Count – Growth Insights</b></p>
<ul style="list-style-type: circle;">
  <li><b>Sharp Cyclical Movements:</b> The Order Count chart reveals frequent, steep MoM shifts with highs of <b>+40–45%</b> and lows reaching <b>−47%</b>, reflecting strong seasonal dependency or reliance on marketing campaigns.</li>
  <li><b>Pandemic Boom & Correction:</b> Early <b>2020</b> shows clear pandemic-driven growth, followed by consistent declines from <b>2021</b> onward—signaling a reversion to pre-pandemic purchasing levels.</li>
  <li><b>Recent Stabilization:</b> By <b>2022</b>, order count growth stabilized near zero, pointing to challenges in retaining customers and sustaining repeat purchases.</li>
</ul>

<p><b>Recommendations:</b></p>
<ul style="list-style-type: circle;">
  <li><b>Strengthen Customer Retention:</b> Launch reactivation campaigns, loyalty points, and referral incentives to increase repeat purchases and mitigate churn.</li>
  <li><b>Boost Off-Season Engagement:</b> Use micro-campaigns and limited-time offers during slower months to maintain consistent order flow.</li>
  <li><b>Optimize Conversion Funnel:</b> Evaluate checkout and cart abandonment data to streamline the purchasing process and lift completion rates.</li>
</ul>

## Seasonal Trends
<p align="left">
  <img src="https://github.com/user-attachments/assets/576b563d-65c1-4f23-8936-ea0a06c1f582" 
       alt="Seasonal Trends" 
       width="800" 
       height="260">
</p>

<ul style="list-style-type: circle;">
  <li><b>Strong Year-End and Fall Performance:</b> 
  <b>September</b> and <b>December</b> were the top-performing months, with sales surging <b>+13–23%</b> and order growth above <b>+10%</b>. These peaks align with back-to-school demand and the holiday shopping season, confirming clear <b>Q4 seasonality</b>.</li>

  <li><b>Mid-Year Slowdowns:</b> 
  <b>February</b> and <b>June</b> saw the weakest performance, with sales dropping <b>−9% to −25%</b> and orders down <b>−8% to −27%</b>. These troughs reflect post-holiday and mid-year lulls in consumer activity.</li>

  <li><b>High-Value Orders in Late Q3–Q4:</b> 
  Average Order Value (AOV) peaked between <b>August–October</b> ($263–$272), suggesting stronger product mix or premium purchases during late-year campaigns, even when order counts dipped.</li>

  <li><b>Sharp Declines in October:</b> 
  Despite the highest AOV ($272), <b>October</b> saw total sales and orders fall by nearly <b>−28% to −29%</b>, highlighting over-reliance on fewer high-value transactions and missed pre-holiday conversion opportunities.</li>
</ul>

<p><b>Recommendations:</b></p>
<ul style="list-style-type: circle;">
  <li><b>Leverage Q3–Q4 Peaks:</b> Begin marketing push from <b>August</b> onward to maximize back-to-school and holiday season growth.</li>
  <li><b>Address Low Months:</b> Run targeted promotions or loyalty rewards in <b>February</b> and <b>June</b> to stabilize post-holiday and mid-year dips.</li>
  <li><b>Boost October Retention:</b> Convert high AOV traffic into higher order counts via bundle discounts or limited-time campaigns.</li>
  <li><b>Maintain AOV Strength:</b> Continue emphasizing premium upsells and value-based bundles to sustain per-order profitability year-round.</li>
</ul>

## Product Trends

<p align="left">
  <img src="https://github.com/user-attachments/assets/0ca7eba8-420c-495d-b951-35e30e3bafbb" 
       alt="Product Trends" 
       width="1000" 
       height="500">
</p>
<ul>
  <li><b>Revenue Concentration Risk:</b> The top three products contribute the majority of total revenue, signaling a potential dependency on a limited product mix. Diversifying beyond high-performing categories could mitigate risk from market saturation or inventory shifts.</li>

  <li><b>Accessory-Driven Volume Growth:</b> Lower-priced accessories like <b>Samsung Cable Packs</b> and <b>Webcams</b> consistently deliver strong order counts, reinforcing their role as high-frequency, entry-level purchases that help sustain customer engagement and repeat transactions.</li>

  <li><b>Yearly Demand Cycles by Category:</b> Premium devices such as <b>MacBook Air</b> and <b>4K Monitors</b> show sharp year-over-year swings tied to upgrade or replacement cycles, while accessories maintain steadier sales. This contrast suggests opportunities for staggered promotion strategies to balance cyclical revenue dips.</li>

  <li><b>Brand Dominance and Ecosystem Synergy:</b> <b>Apple products</b> collectively command a large share of both high-value and high-volume segments, reflecting strong brand pull. Aligning marketing and bundling strategies around Apple’s ecosystem (e.g., <b>AirPods + MacBook</b> packages) could amplify overall conversion rates.</li>
</ul>

## Geographical Trends

<p align="left">
  <img src="https://github.com/user-attachments/assets/b3c8f367-7fb5-43bd-a2a1-3914da34c409" 
       alt="Product Trends" 
       width="1000" 
       height="600">
</p>

<ul>
  <li><b>Best Performing Market:</b> <b>North America (US & CA)</b> – Accounts for <b>66% of total sales</b>, led by the <b>US (61%)</b> with an <b>AOV of $262</b>. This region represents LyncHub’s strongest customer base and the highest transaction volumes, driving the majority of company revenue.</li>

  <li><b> High-Value Market:</b> <b>Asia-Pacific (APAC)</b> – Though smaller in total sales volume, this region delivers the <b>highest AOV globally ($393 in Japan)</b>. It reflects premium purchasing behavior and potential for expansion through targeted marketing strategies.</li>

  <li><b> Strong Growth Market:</b> <b>Europe (EMEA)</b> – Contributes <b>22% of total revenue</b>, with the <b>UK (10%)</b> as the top European market. <b>The Netherlands ($289)</b> and <b>Germany ($270)</b> lead in regional AOV, indicating high-value customers and strong demand for quality products.</li>

  <li><b>Underperforming Market:</b> <b>Latin America (LATAM)</b> – Currently underdeveloped, contributing minimal revenue despite a <b>mid-range AOV of $251</b>. Represents untapped growth potential through regional partnerships, localized promotions, and improved brand visibility.</li>
</ul>


## Loyalty Program

<p align="left">
  <img src="https://github.com/user-attachments/assets/e049236a-aa13-4297-93be-a10cb8cb8522" 
       alt="Product Trends" 
       width="1000" 
       height="600">
</p>

<ul style="list-style-type: circle;">
  <li><b>Sales Mix Shift:</b> loyalty sales have overtaken non-loyalty, indicating successful migration from one-time purchases to member transactions and a healthier repeat base.</li>

  <li><b>Order Volume Momentum:</b> Member order count shows steadier month-to-month growth than guests, suggesting improved retention and higher purchase frequency among enrolled customers.</li>

  <li><b>AOV Convergence:</b> The gap in average order value between cohorts has narrowed; member AOV now matches or slightly exceeds guest AOV, implying that benefits (points, free shipping thresholds, bundles) are lifting basket size without excessive discounting.</li>

  <li><b>Stability vs. Spikes:</b> guest activity is more promotion-driven and volatile, while member spend is smoother—pointing to a more predictable revenue stream from the program.</li>
</ul>

<p><b>Recommendations</b></p>
<ul style="list-style-type: circle;">
  <li><b>Double-Down on Enrollment:</b> Surface sign-up CTAs on PDP/checkout and offer first-purchase points to convert high-intent guests into members.</li>
  <li><b>Tiered Value & Bundles:</b> Introduce tier perks (early access, higher point multipliers) and member-only bundles to maintain AOV parity and lift order frequency.</li>
  <li><b>Reactivation Journeys:</b> Use points-expiry nudges and “complete your status” emails to bring lapsed members back during off-season months.</li>
  <li><b>Measure Incrementality:</b> Track cohort KPIs (90-day repeat rate, orders/member/month, AOV by tier) to quantify program lift and reduce broad discounting for guests.</li>
</ul>

## Refund Rates

<p align="left">
  <img src="https://github.com/user-attachments/assets/b9c496f4-1ae1-4458-8881-9469e1425095" 
       alt="Product Trends" 
       width="1000" 
       height="800">
</p>
<p>Brand-level analysis reveals that <b>Apple (58%)</b> and <b>Gaming Monitor Brands (27%)</b> together account for the majority of refunds, totaling over <b>3,700 returns</b>. 
Samsung and Lenovo follow with smaller shares of <b>9%</b> and <b>6%</b> respectively.</p>

<p>Year-over-year trends show a <b>sharp spike in refund rates in 2020 (50%)</b>, likely tied to the pandemic’s surge in online purchases and supply-chain challenges, 
followed by a <b>gradual recovery to 20% in 2021</b>. 
Post-2021, refund volumes stabilized, suggesting <b>improvements in product reliability and after-sales service.</b></p>

<ul>
  <li><b>Key Insights:</b>
    <ul style="list-style-type: circle;">
      <li><b>Apple</b> products show the highest refund volume, indicating both high sales and elevated quality concerns or post-purchase dissatisfaction.</li>
      <li><b>Gaming Monitors</b> represent 27% of all returns — primarily due to performance variability and product compatibility issues.</li>
      <li><b>2020</b> marked an exceptional spike in returns, accounting for over half of total refunds, reflecting global buying disruptions and shipping constraints.</li>
      <li>Refund rates <b>declined post-2021</b>, signaling better product quality control and more consistent customer experiences.</li>
    </ul>
  </li>

  <li><b> Recommendations:</b>
    <ul style="list-style-type: circle;">
      <li><b>Improve Apple & Gaming Monitor Quality Review Cycles:</b> Focus on pre-shipment testing and early defect detection to reduce return rates.</li>
      <li><b>Implement Refund Prediction Analytics:</b> Use historical refund data to flag at-risk SKUs and proactively address quality or support gaps.</li>
      <li><b>Enhance Product Descriptions & Demos:</b> Reduce returns from unmet expectations by improving accuracy and visual clarity in online listings.</li>
      <li><b>Localized Support Initiatives:</b> Offer faster replacements and clearer return workflows in regions with high refund concentration (NA & EMEA).</li>
    </ul>
  </li>
</ul>

# Interactive Dashboard

<p align="left">
  <b>Discover the story behind the data:</b><br>
  Explore dynamic trends in sales, AOV, refunds, and marketing performance through this interactive Tableau dashboard.<br>
  <a href="https://public.tableau.com/app/profile/anupa.ninan/viz/Elist_Analysis/Summary?publish=yes" target="_blank">
    🔗 <b>View Interactive Dashboard</b>
  </a>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c830b956-64d1-4829-af8c-f938c95d5c47" />
"
       alt="Elist Sales Dashboard"
       width="1000"
       height="800">
</p>



# Appendix

- Entity Relations Diagram [ERD](https://github.com/user-attachments/assets/4163b127-ebeb-456c-9577-63f7d87932f8)


