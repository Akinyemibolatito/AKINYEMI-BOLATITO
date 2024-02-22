# AKINYEMI-BOLATITO

Hi 👋 My name is Akinyemi Bolatito
==================================

Data Analyst
------------

Position Title: Data Analyst - Akinyemi Bolatito Overview: As a Data Analyst with a background in geophysics from the University of Lagos, I, Akinyemi Bolatito, bring a unique blend of analytical skills and geophysical expertise to the realm of data analytics. My passion for leveraging data to drive informed decision-making is grounded in my understanding of geophysical principles, allowing me to extract valuable insights from complex datasets and translate them into actionable strategies that propel organizational success. Key Responsibilities: Data Collection and Cleaning: Drawing on my background in geophysics, I adeptly collect and preprocess data from various sources, ensuring its accuracy and reliability. Through meticulous data cleaning techniques, I maintain the integrity of the data, mitigating errors and inconsistencies to ensure robust analysis. Data Analysis and Interpretation: Leveraging statistical methods and geophysical knowledge, I uncover patterns and trends within datasets, offering unique insights to stakeholders. My ability to interpret analysis results through the lens of geophysical phenomena enables me to provide actionable recommendations that drive strategic decision-making. Visualization and Reporting: With a keen eye for detail and design, I create visually engaging charts, graphs, and maps to effectively communicate complex geophysical insights. Through interactive reports and presentations, I empower stakeholders to engage with the data intuitively, fostering a deeper understanding of key findings. Predictive Modeling and Forecasting: Building on my expertise in geophysical modeling, I develop predictive models to forecast future trends and outcomes based on historical data. I continuously refine and validate these models, leveraging geophysical principles to enhance predictive accuracy and reliability. Data-driven Decision Support: Collaborating closely with interdisciplinary teams, I tailor analytical solutions to address specific challenges and opportunities within the organization. By providing data-driven recommendations informed by geophysical insights, I empower stakeholders to make informed decisions that drive organizational growth and success. Continuous Learning and Development: Committed to ongoing learning and professional development, I actively seek out opportunities to expand my expertise in both data analytics and geophysics. Through continuous learning and collaboration, I strive to stay at the forefront of advancements in both fields, driving innovation and growth within the organization. Qualifications: Bachelor's degree in Geophysics from the University of Lagos, with a focus on data analysis and interpretation. Proficient in Python, SQL, and MATLAB for data analysis and modeling, with experience in geophysical software such as Seismic Unix. Strong analytical mindset honed through coursework and practical experience in geophysical data processing and interpretation. Excellent communication skills, with the ability to convey complex geophysical concepts and analysis results to diverse audiences. Proven ability to thrive in dynamic, collaborative environments, with a passion for driving organizational success through data-driven insights. Conclusion: As a Data Analyst with a background in geophysics, I, Akinyemi Bolatito, am dedicated to unlocking valuable insights from data and driving informed decision-making within the organization. With a passion for innovation and a commitment to excellence, I leverage my interdisciplinary expertise to deliver actionable strategies that propel organizational growth, efficiency, and success

* 🌍  I'm based in Nigeria
* ✉️  You can contact me at [akinyemibolatito69@gmail.com](mailto:akinyemibolatito69@gmail.com)

* I have included a couple of projects I have worked on Below.

* 1. # FLIT-Market-Basket-Analysis-
This is my first project under the Flit program.
My .ipynb file is uploaded
Market Basket Analysis Project
Overview
This project focused on leveraging Market Basket Analysis techniques using Python and popular libraries such as pandas, scikit-learn, and mlxtend. Market Basket Analysis is a data mining technique used to identify patterns and associations between products or items frequently purchased together.

Table of Contents
Introduction
I undertook a project that involved applying Market Basket Analysis techniques using Python and various libraries, including pandas, scikit-learn, and mlxtend. The primary aim of Market Basket Analysis is to uncover patterns and associations between items frequently bought together in transactions.

Installation
I ensured that Python was installed, and I cloned the repository for the project. I then installed the required dependencies using the following commands:


git clone https://github.com/your-username/market-basket-analysis.git
cd market-basket-analysis

# Installed dependencies
pip install -r requirements.txt
Usage
For running the market basket analysis, I executed the main script with the path to the transaction data:


python main.py --input_data transactions.csv --output_results results.csv
I adjusted parameters such as support, confidence, and lift based on the specific requirements of the analysis.

Data
The dataset used for this analysis consisted of transactional data, where each row represented a unique transaction, and the columns corresponded to the purchased items. I provided details about the source of the data, format, and any preprocessing steps performed.

Analysis
The analysis involved several steps, including data loading, preprocessing, applying the Apriori algorithm using the mlxtend library, and interpreting the results. Example code snippets were included in the README:

python
# Load data
import pandas as pd
transactions = pd.read_csv('transactions.csv')

# Preprocess data

# Apply Apriori algorithm
from mlxtend.frequent_patterns import apriori
from mlxtend.frequent_patterns import association_rules
frequent_itemsets = apriori(transactions, min_support=0.05, use_colnames=True)
rules = association_rules(frequent_itemsets, metric="lift", min_threshold=1)
Results
I summarized key findings and insights obtained from the market basket analysis, including the discovered association rules with support, confidence, and lift metrics.



2. Steps Taken:

Data Import,
Data Cleaning,
Data Exploration,
Comparable SQL Analysis,
Tableau Visualization,


FINAL Observation
Notable findings include substantial ADR spikes on January 7, 2015, and a peak in November, indicating seasonal patterns. Transient-Party customers dominate revenue, emphasizing the need for strategic alignment. Corporate bookings lead, while Travel Agents/Operators (TA/TO) play a significant role. Room type occupancy analysis reveals November as a peak period, with Room A being most occupied. Average Room Rate exhibits an 85.98% increase from 2015 to 2017, underscoring pricing dynamics. The dataset also highlights trends in average length of stay and cancellation rates. Count of bookings by country identifies Portugal (PRT) as the leader, contributing 37.79% of total bookings. In summary, this dataset provides a rich source for strategic decision-making, customer-centric approaches, and revenue optimization in the dynamic hospitality industry.

Entire process flow
# Hotel-resevation-dataset
The hotel reservation dataset offers a detailed exploration of booking dynamics, customer behaviors, and revenue patterns within the hospitality industry. Spanning a timeframe from 2015 to 2017, the dataset encompasses diverse dimensions of hotel operations, shedding light on occupancy rates, pricing dynamics, booking channels, room types, and cancellation trends.

1. Average Daily Rate (ADR) Trends:
The dataset unravels the temporal evolution of Average Daily Rate (ADR), exposing substantial spikes in revenue, notably on January 7, 2015. Seasonal patterns also emerge, with November standing out as a peak booking period, potentially attributed to the proximity of Christmas celebrations.

ADR BY ARRIVAL DATE ANALYSIS
Analyzing Average Daily Rate (ADR) by arrival date in a hotel reservation dataset is a key aspect of booking analysis.
the highest spike in revenue was recorded on the 7th of january 2015at higher than 800 and could have been due to a number of reasons ,such as during special events, holidays, or peak seasons and the lowest average revenue generated was on the 7th of march 2017 at 0.
 
Looking through for seasonal patterns, November which is close to the christmas celebration period seems like the highest time for booking with the highest revenue generated closely followed by january. The december periods seemed less engaging which is likely because people spend the festive periods with family.

This Pricing Dynamics should be shuffled between those peak and low months to attract more bookings at low peak periods.

ADR by assigned Room type and type of customer: The trasient party customers contribute the highest to the revenue of the company, closely followed by the trainsent customers and they mostly order for room A, which in turn ends up being the most revenue generating room, the least generating room,at more than 5kn revenue generationG is still booked by trasient party customers however it degenerates way less than 2k 


2. ADR by Assigned Room Type :
Analyzing ADR by room type and customer segment reveals that Transient-Party customers dominate revenue generation, primarily favoring Room A. Transient-Party customers not only contribute the highest total ADR but also exhibit the highest average ADR. The dataset underscores the need for strategic alignment with the preferences of this lucrative customer segment.
Transient-Party has the highest total ADR at $7,577.51. This indicates that, overall, this customer type contributes the most to the hotel's revenue.
Following Transient-Party, there are Transient, Contract, and Group in descending order, suggesting their respective contributions to the total revenue.

3.Proportion of ADR by Customer Type:
ADR by Customer Type:
Among the customer types, Transient-Party represents 33.26% of the total ADR. This indicates that, despite being the highest in total revenue, Transient-Party's share of the ADR is a significant portion of the overall revenue.
Average ADR by Customer Type:

Transient-Party again leads in terms of average ADR with $947.19. This means that, on average, each booking in the Transient-Party category generates a higher ADR compared to other customer types.
The descending order of average ADR is maintained with Transient, Contract, and Group following.
Analysis:

Transient-Party Dominance: The Transient-Party customer type is the most lucrative for the hotel, contributing the highest total revenue, having the highest average ADR, and making up a significant proportion of the overall ADR. This could imply that the hotel is well-positioned or equipped to cater to this specific customer segment, and there might be opportunities to further capitalize on this popularity.

Diversification: While Transient-Party is dominant, it's essential to maintain a balance among customer types. Diversification can mitigate risks associated with dependency on a single segment and could help in optimizing revenue streams.

Pricing Strategy: The high average ADR for Transient-Party suggests that this customer type is willing to pay a premium for the services provided. The hotel might consider fine-tuning its pricing strategy for other customer types to maximize overall revenue without compromising customer satisfaction.

Marketing and Service Alignment: Understanding the characteristics of Transient-Party guests could inform marketing strategies to attract similar customers. Additionally, ensuring that services and amenities align with the preferences of Transient-Party guests could enhance their experience and encourage repeat business.

Continuous Monitoring: The hotel should continue to monitor customer preferences, market dynamics, and booking patterns to adapt strategies accordingly. Regularly analyzing and adjusting pricing, marketing efforts, and service offerings can help maintain competitiveness in the hospitality industry.




4. Booking Channels Analysis:
Delving into booking channels, the dataset exposes the dominance of corporate bookings, followed by the influential role of Travel Agents/Operators (TA/TO). Direct bookings, though representing a smaller share, emphasize the importance of tailored strategies to encourage customers to book directly. The dataset advocates for a strategic approach, leveraging diverse channels for optimal revenue generation.

Process FLOW: 
Use a Pie chart or Bar chart to visualize the distribution of bookings across different channels.

Pie Chart:

Values: Count of bookings for each distribution channel
Labels: Distribution channel names (e.g., TA, TO, etc.)
Legend: Distribution channel names

Here's a simple illustration of the DAX code i used  to create a count of bookings by distribution channel:


Process:
BookingChannelsCount = 
SUMMARIZE(
     hotel_bookings,
hotel_bookings[distribution_channel],
    "BookingCount", COUNTROWS(hotel_bookings)
from which i got the error below The expression refers to multiple columns. Multiple columns cannot be converted to a scalar value.

BookingChannelsCount = 
CALCULATE(
    SUMX(
        VALUES( hotel_bookings[distribution_channel]),
        COUNTROWS( hotel_bookings)
    )
)

)

which then worked.


 Analysis of Booking Channels:

 Overview:
   - The Booking Channels analysis provides insights into how hotel bookings are distributed among various channels. The channels include Direct bookings, Travel Agents/Operators (TA/TO), and Corporate bookings, among others.

Key Findings:
Corporate Dominance:Corporate bookings have the highest BookingChannelsCount, representing 60.83% of total bookings. This suggests a significant portion of the hotel's clientele comes from corporate entities.
   
TA/TO Influence: Travel Agents/Operators (TA/TO) contribute significantly, with a BookingChannelsCount of 29.49%. This indicates the importance of partnerships with travel agencies in driving bookings.

Direct Bookings: Direct bookings, possibly through the hotel's website or other direct channels, account for 9.22% of the total. While this percentage is lower, it signifies a notable portion of customers who prefer booking directly.

GDS Contribution: Global Distribution System (GDS) shows a smaller share at 0.46%. This might represent a niche market or specific partnerships.

Count of Bookings by Country:
The dataset highlights booking counts by country, with Portugal (PRT) leading at 82, followed by Austria (AUT) and France (FRA). PRT contributes significantly, accounting for 37.79% of total bookings.

Analysis: Countbooking by country

CountBookings was highest for PRT at 82, followed by  and FRA.﻿﻿
﻿﻿
﻿﻿PRT accounted for 37.79% of CountBookings.﻿﻿

Corporate Insights:
   - The dominance of Corporate bookings suggests a strong business clientele. Consider tailoring marketing strategies and amenities to cater to the needs of corporate guests. Corporate partnerships and loyalty programs may enhance this segment.

TA/TO Collaboration:
   - The significant presence of TA/TO highlights the impact of travel agencies. Strengthening relationships with these partners, offering competitive packages, and ensuring seamless collaboration could further boost bookings.

 Direct Booking Promotion:
   - While direct bookings represent a smaller share, it's crucial to encourage this channel. Implementing promotions, loyalty programs, or exclusive offers for direct bookings may attract more customers to book directly.

GDS Niche Market:
   - The low percentage from GDS indicates a niche market. Explore opportunities to expand this segment, possibly by identifying the unique needs of GDS users and tailoring offerings accordingly.

 Strategic Decision-Making:
   - Use these insights to inform strategic decisions. Allocate resources, marketing efforts, and operational enhancements based on the strengths and opportunities identified in each booking channel.

 Continuous Monitoring:
  - Regularly monitor BookingChannelsCount trends to adapt strategies dynamically. Changes in percentages may indicate shifts in customer behavior or the effectiveness of marketing initiatives.

Recommendations:
   - Strengthen corporate partnerships through personalized services and loyalty programs.
   - Collaborate closely with TA/TO, offering attractive packages and incentives.
   - Invest in marketing strategies to promote direct bookings.
   - Explore opportunities to expand the GDS segment with targeted offerings.

 Conclusion:
   - The Booking Channels analysis provides a comprehensive understanding of how different channels contribute to hotel 
bookings. Leveraging these insights will empower the hotel to optimize strategies, enhance guest experiences, and drive overall business success.




5. Room Type Occupancy Patterns:
A detailed examination of room type occupancy through a stacked bar chart reveals nuanced insights into booking preferences over time. November emerges as a peak booking period, with Room A displaying the highest occupancy.

PROCESS FLOW: 
Room Type Occupancy:**
   - Stacked bar chart illustrating the occupancy rates for different room types over time.

To analyze Room Type Occupancy and create a stacked bar chart illustrating occupancy rates for different room types over time, you would need the following key columns:

arrival_date_year:

This column is essential for grouping bookings by year, allowing you to observe trends over different years.
arrival_date_month:

This column is necessary for creating a time series, helping you identify monthly patterns and seasonality.
arrival_date_week_number:

Useful for a more granular analysis, showing variations within each year based on week numbers.
arrival_date_day_of_month:

Provides daily granularity, allowing you to observe occupancy trends within each month.
reserved_room_type:

The room type reserved by the guest, which is crucial for categorizing bookings into different room types.
is_canceled:

To filter out canceled bookings and focus on actual occupancy.
Using these columns, you can filter data based on the booked room type and create a stacked bar chart where each bar represents a specific time period (month, week, or day), and the segments within the bar represent different room types.

X-Axis: Time (Year/Month/Week/Day)
Y-Axis: Count of Bookings(which is Total Bookings = COUNTROWS('YourTableName') or TotalBookings = SUM(YourTable[is_canceled])
I went with the latter to field off canceled bookings.
Stacked Bars: Different room types (segments within each bar)

For example: from the stacked bar, november has the most arrival /booking date across the 3 years and room A shows that the most occupied room is A



6. Average Room Rate Trends:
The dataset tracks the trajectory of Average Room Rate, indicating a substantial 85.98% increase from 2015 to 2017. Steeper inclines in 2015 and 2017 underline the significance of pricing dynamics in revenue optimization.

Average room rate analysis: 
Average Room Rate trended up, resulting in a 85.98% increase between 2015 and 2017.﻿﻿
﻿﻿
﻿﻿Average Room Rate started trending up on 2015, rising by 85.98% (41.70) in 2 years.﻿﻿
﻿﻿

﻿﻿
﻿﻿Average Room Rate jumped from 48.50 to 90.20 during its steepest incline between 2015 and 2017.﻿﻿



7. Average Length of Stay and Cancellation Rates:
Analysis of the average length of stay unveils an upward trend, whereas cancellation rates show a noticeable increase over the observed period. These metrics underscore the importance of flexible booking policies and customer engagement strategies.

Process flow/Analysis: Average Length of Stay Over Time:

﻿Sum of stays_in_week_nights trended up, resulting in a 900.00% increase between Sunday, August 9, 2015 and Sunday, August 27, 2017.﻿﻿
﻿﻿
﻿﻿Sum of stays_in_week_nights started trending up on Thursday, November 10, 2016, rising by 400.00% (8) in 9.57 months.﻿﻿
﻿﻿
﻿﻿[]﻿﻿
﻿﻿
﻿﻿Sum of stays_in_week_nights jumped from 4 to 128 during its steepest incline between Wednesday, November 11, 2015 and Tuesday, November 17, 2015.﻿﻿
﻿﻿
﻿7b.
﻿sum of stays_in_weekend_nights trended down, resulting in a 90.84% decrease between 2015 and 2017.﻿﻿
﻿﻿
﻿﻿Sum of stays_in_weekend_nights started trending down on 2015, falling by 90.84% (248) in 2 years.﻿﻿
﻿﻿
﻿﻿[]﻿﻿﻿﻿
﻿﻿Sum of stays_in_weekend_nights dropped from 273 to 25 during its steepest decline between 2015 and 2017.﻿﻿
﻿﻿
﻿

8.Cancellation Rates:**
   - bar chart displaying the percentage of bookings that were canceled.
 
﻿Cancellation Rate trended up, resulting in a 177.93% increase between 2015 and 2017.﻿﻿
﻿﻿
﻿﻿Cancellation Rate started trending up on 2015, rising by 177.93% (19.85) in 2 years.﻿﻿
﻿﻿
﻿﻿[]﻿﻿
﻿﻿
﻿﻿Cancellation Rate jumped from 11.15 to 31 during its steepest incline between 2015 and 2017.﻿﻿





Notable findings include substantial ADR spikes on January 7, 2015, and a peak in November, indicating seasonal patterns. Transient-Party customers dominate revenue, emphasizing the need for strategic alignment. Corporate bookings lead, while Travel Agents/Operators (TA/TO) play a significant role. Room type occupancy analysis reveals November as a peak period, with Room A being most occupied. Average Room Rate exhibits an 85.98% increase from 2015 to 2017, underscoring pricing dynamics. The dataset also highlights trends in average length of stay and cancellation rates. Count of bookings by country identifies Portugal (PRT) as the leader, contributing 37.79% of total bookings. In summary, this dataset provides a rich source for strategic decision-making, customer-centric approaches, and revenue optimization in the dynamic hospitality industry.


In summary, the hotel reservation dataset serves as a valuable resource for understanding the multifaceted dynamics of the hotel operations. The insights gleaned from this dataset provide a foundation for strategic decision-making, customer-centric approaches, and revenue optimization in the dynamic landscape of the hospitality industry.

 FIND BELOW SOME DASHBOARD REPORTS:

 ![image](https://github.com/Akinyemibolatito/AKINYEMI-BOLATITO/assets/62047960/39d4a754-2f8e-423b-b110-b8b9b8a55ff6)


### Skills


<p align="left">
<a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" /></a><a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" width="36" height="36" alt="React" /></a><a href="https://dotnet.microsoft.com/en-us/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/dot-net-colored.svg" width="36" height="36" alt=".NET" /></a><a href="https://www.figma.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/figma-colored.svg" width="36" height="36" alt="Figma" /></a><a href="https://cloud.google.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/googlecloud-colored.svg" width="36" height="36" alt="Google Cloud" /></a>
</p>


### Socials

<p align="left"> <a href="https://www.github.com/Akinyemibolatito" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" /> </picture> </a> <a href="https://www.linkedin.com/in/bolatito-akinyemi-Deborah" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" width="32" height="32" /> </picture> </a></p>




### Badges

<b>My GitHub Stats</b>

<a href="http://www.github.com/Akinyemibolatito"><img src="https://github-readme-stats.vercel.app/api?username=Akinyemibolatito&show_icons=true&hide=&count_private=true&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&show_icons=true" alt="Akinyemibolatito's GitHub stats" /></a>

<img width="372" alt="image" src="https://github.com/Akinyemibolatito/AKINYEMI-BOLATITO/assets/62047960/caaae7db-3f38-48c0-940f-664596b51c03">

<a href="http://www.github.com/Akinyemibolatito"><img src="https://github-readme-streak-stats.herokuapp.com/?user=Akinyemibolatito&stroke=ffffff&background=1c1917&ring=0891b2&fire=0891b2&currStreakNum=ffffff&currStreakLabel=0891b2&sideNums=ffffff&sideLabels=ffffff&dates=ffffff&hide_border=true" /></a>
<img width="401" alt="image" src="https://github.com/Akinyemibolatito/AKINYEMI-BOLATITO/assets/62047960/28a8f968-f243-49d8-8b97-c830a66ef8ca">

<a href="http://www.github.com/Akinyemibolatito"><img src="https://github-readme-activity-graph.cyclic.app/graph?username=Akinyemibolatito&bg_color=1c1917&color=ffffff&line=0891b2&point=ffffff&area_color=1c1917&area=true&hide_border=true&custom_title=GitHub%20Commits%20Graph" alt="GitHub Commits Graph" /></a>

<a href="https://github.com/Akinyemibolatito" align="left"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Akinyemibolatito&langs_count=10&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&locale=en&custom_title=Top%20%Languages" alt="Top Languages" /></a>


<img width="242" alt="image" src="https://github.com/Akinyemibolatito/AKINYEMI-BOLATITO/assets/62047960/65e3e136-fa27-449a-83ae-2be87288854a">

<b>Top Repositories</b>

<div width="100%" align="center"></div><br /><br /><br /><br /><br /><br /><br />
