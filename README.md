Project Overview
This project addresses the business challenge of unpredictable seasonal demand caused by climatic shifts in Japan. By performing time-series analysis on 70 years of historical data, this model quantifies the advancing bloom dates in Tokyo to provide actionable insights for supply chain management and strategic marketing.

<img width="1037" height="614" alt="Screenshot 2026-02-06 at 2 16 19 PM" src="https://github.com/user-attachments/assets/52a157ff-651d-41ff-baf5-78a0f06d5f99" />


**Key Business Discovery**
The Decadal Shift: Peak blooming dates have advanced by 8.1 days on average since the 1950s.

<img width="542" height="79" alt="Screenshot 2026-02-06 at 2 16 46 PM" src="https://github.com/user-attachments/assets/71168302-3f4a-4f94-98ac-0f246cac0b4f" />

Statistical Correlation: A strong negative correlation (-0.5016) confirms a persistent long-term trend, allowing for reliable multi-year strategic planning.

Decadal Velocity: With a slope of -0.146, the bloom window shifts approximately 1.5 days every decade.

<img width="1021" height="547" alt="Screenshot 2026-02-06 at 2 16 35 PM" src="https://github.com/user-attachments/assets/902f7c80-0e31-4d6a-b9e5-6970850820b1" />

**Business Applications**
Supply Chain Optimization: Mitigates "Stock-out" risks for seasonal retail products by aligning procurement timelines with the 1.5-day-per-decade shift.

Revenue Management: Serves as a foundation for Dynamic Pricing in the hospitality sector to maximize RevPAR during peak tourism windows.

Marketing Efficiency: Synchronizes multi-million dollar seasonal campaigns with actual consumer engagement peaks to maximize ROI.

**Technical Workflow**
Data Source: Historical bloom data from the Japan Meteorological Agency (JMA).

Feature Engineering: Converted calendar dates to Day of Year for numerical stability.

Modeling: Linear Regression and Time-Series Analysis used to generate a 2026 forecast (March 20th).

Tech Stack: Python (Pandas, NumPy, Matplotlib, Scikit-learn).
