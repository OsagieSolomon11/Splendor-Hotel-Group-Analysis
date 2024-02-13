# Splendor-Hotel-Group-Analysis

This is an analysis of a data analytics challenge on twitter by 
Ejike Uchenna Splendor. He gave a dataset on his Splendor Hotel Groups (SHG). As a recently recruited Business Intelligence Analyst and Data Analyst, I will be essential in solving the puzzles buried in our booking data. Renowned hospitality company SHG aims to improve visitor experiences and streamline corporate processes by utilizing data-driven insights. My task is to thoroughly examine one of our best resorts’ past booking data in order to identify trends, comprehend consumer behavior, and offer useful suggestions for tactical decision-making.

Link to dataset: https://t.co/kONq6Ib5UJ

Project Overview:

My task involves a thorough analysis of a comprehensive dataset, featuring intricate details of bookings, guest demographics, distribution channels, and financial metrics. By applying my analytical prowess, I aim to extract meaningful insights that will not only inform operational improvements but also contribute to the overall success of SHG in delivering unparalleled hospitality.

Objectives of this analysis:

The relationship between bookings cancelled with revenue generated and revenue loss.
Top 5 countries by revenue.
Revenue by customer type.
Successful bookings by distribution channel.
Average lead time (days) by distribution channel.
Revenue by distribution channel.
Average stay time (nights) by customer type.
Cancelled bookings by deposit type.



Analysis procedures:

Analytical tool used: Power BI

The raw look of the data: The raw data needs to be scrutinized through data cleaning process to make our data fit for analysis.

 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*x3K9tzzpPrNd90bAHBAj5g.png">


Using ‘Replace values’ function to change ‘0’ to ‘successful’ and ‘1’ to ‘cancelled’ in the ‘Cancelled (0/1)’ column.

 <img src="https://miro.medium.com/v2/resize:fit:226/format:webp/1*7J2s2rWvuMEPA4qF6bVALQ.png">

Outcome:
 <img src="https://miro.medium.com/v2/resize:fit:548/format:webp/1*Ym6EiRBPhxZkSa9GH0vsBA.png">



Evaluating the needed calculated values using DAX.

Cancelled bookings:

 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*EWIMPjw4VD22JUk6Hol-HQ.png">


Successful bookings:

 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*Rnt1yulRWX-hu5g0weMkKw.png">



Total number of bookings:

 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*GpYLLfkzzuvQBFze4D_cFg.png">



Total revenue:

 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*Iz6g0MFlV3Z4yEgv8cav3Q.png">



Average stay time: 

 <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*oWQTiEbe39xt6Dh0kNXCGA.png">



Solving the business questions with visualization:


 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*FDoN1KV1B6ev2jPonZgZRg.png">


Insights:

The revenue was not significantly affected by the rate of booking cancellation. Interestingly, highest revenue was generated despite having highest level of booking cancellation.

Portugal generated the highest revenue with $9M, followed by United Kingdom with $4.2M.

The Transient customer generated a huge part of the revenue which is $23M (76.68%). While the second best is Transient Party with a distant $5M (17.65%).

Online Travel Agent recorded the highest booking rate with 42,088 (55.99%). This may be due to ease of booking through online method. The second best performing channel is Offline Travel Agent with 15,786. It is obvious the role of Travel Agent is very important in this business, recording high booking rate through offline method.

The offline travel agent channel recorded highest number of days between time of hotel booking and arrival period with 136 days.

Recommendation:

Since Online Travel Agents (OTAs) recorded the highest booking rate, it’s important to optimize the online booking process further. Ensure that the website or platform is user-friendly, offers a seamless booking experience, and perhaps consider implementing features that encourage direct bookings.

Given that Transient customers contributed significantly to revenue, focus on strategies to attract and retain this customer segment. Offer personalized promotions, loyalty programs, or exclusive deals to encourage repeat business from transient guests.

The insight about the offline travel agent channel having the highest number of days between booking and arrival suggests an opportunity for improvement. Consider strategies to reduce this duration, such as promoting last-minute deals, offering exclusive discounts for early bookings, or providing incentives for quicker reservations.

Given that Portugal is the top revenue generator, consider investing more resources in marketing and promotional activities specifically targeted at the Portuguese market. While the United Kingdom is the second-highest revenue-generating region, there may be opportunities to optimize marketing strategies. Conduct market research to understand the preferences and needs of customers in the UK.

Despite high booking cancellation rates, revenue was not significantly affected. However, it’s important to keep an eye on cancellation trends. If cancellation rates start impacting revenue, consider implementing policies or incentives to reduce cancellations, such as non-refundable booking options or exclusive perks for non-cancellable reservations.
