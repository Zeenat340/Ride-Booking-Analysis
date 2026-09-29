# Ride-Booking-Analysis

## Tools Used
Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

## Key Findings
- Only 62% of bookings are completed, the rest fail due to driver cancellations, customer cancellations, no driver found, or incomplete trips. Customer-related issues actually contribute to over double the failed bookings than they first appear, since many driver cancellations are also caused by the customer (mostly illness).

- A few areas, Old Gurgaon, Paharganj, and Vinobapuri — consistently lose 9-10% of bookings simply because no driver is available, despite having average demand. This points to a driver coverage gap in specific outer NCR locations rather than a general shortage.

- On revenue, weekends generate 45-50% more revenue per ride than weekdays, even though weekend booking volume isn't any higher — weekend rides are simply worth more, likely due to longer or more leisure-based trips.

- Notably, vehicle type, payment method, ride distance, and wait times showed no real relationship with ratings or completion — the real drivers of performance are location coverage and timing, not ride mechanics.

## Recommendations
- Fix driver supply in specific locations : Old Gurgaon, Paharganj, and Vinobapuri have unusually high "no driver found" rates despite average demand; targeted driver incentives here could recover meaningful lost bookings.
- Review the illness-related cancellation pattern : ~6,800 driver cancellations were attributed to customer illness, the single biggest customer-related cause of failed rides.
- Grow weekend demand : weekend rides are worth significantly more per trip, so even small increases in weekend bookings would have an outsized revenue impact.
- Investigate the "driver asked to cancel" reason : a notable share of customer cancellations may actually be driver-initiated in disguise.
