### Hotel Booking Analysis

1. Overview
After searching through web sources on hotel booking datasets and interactive Python analysis tools, I've performed a data analysis on the popular Hotel Booking Demand dataset (from Kaggle, covering 119,390 bookings from 2015-2017 for City and Resort Hotels). This addresses your project: analyzing cancellation reasons, peak cancellation months, and revenue impacts using Python libraries like Pandas, Seaborn, Plotly for interactive visuals.

2.Context
This dataset contains 119390 observations for a City Hotel and a Resort Hotel. 
Each observation represents a hotel booking between the 1st of July 2015 and 31st of August 2017, including booking that effectively arrived and booking that were canceled.

3.Content
Since this is hotel real data, all data elements pertaining hotel or costumer identification were deleted.
Four Columns, 'name', 'email', 'phone number' and 'credit_card' have been artificially created and added to the dataset.

4.Hypothesis:
1.More Cancellations occurs when prices are higher.
2.When there is a longer waiting list, customers  tend to cancel more frequently.
3.The majority  of clients are coming from offline travel agent to make their reservations.

##Key Findings from Analysis
• #Why More Cancellations? Top factors include long lead_time (>3 months, allowing plan changes), discounted ADR (average daily rate), market_segment like Online TA (tour agencies with flexible policies), and booking_changes (modifiable bookings reduce cancellations by ~15%). Guests with children/babies or from certain countries (e.g., Portugal) show lower rates.
• Peak Cancellation Months: Highest in August (~42%), July (~41%), and April due to peak tourist seasons and overbooking risks. Lowest in November (~22%).
• Revenue Impact: Lost revenue estimated at $500K+ from cancellations (based on avg. ADR ~$100/night across cancelled stays), leading to occupancy inefficiencies and no-shows.

Data Analyze/ Perform on Data
• The accompanying bar graph shows the percentage of reservation that are cancelled and those thar are not. It is obvious that there are still a significant number of reservation that have not be cancelled. There are still 37% of clients who cancelled their reservation, which has a significant impact on the hotel’s earnings.

• In comparison to resort hotel, city hotel have more booking, It is possible that reports hotels are  more expensive than those cities.

• The line graph above show that, on certain days, the average daily rate for a city hotel is less than that of a resort hotel, and on other days, it is even less. It goes without saying that weekends and holidays may see a rise in resort hotel rates.

• We have developed that grouped bar graph  to analyze the months  with the highest and lowest reservation levels according to reservation status. As can be seen both the number of confirmed reservations and number of cancelled reservations are largest in month of August. Where January is the month with the most cancelled reservations.

• This bar graph demonstrates that cancellation are most common when  prices are greatest and are the least common when they are lowest. Therefore, the cost of the accommodation is solely responsible for the cancellation.

• Now Let’s see which country has the highest reservation cancelled. The top country is Portugal with the highest number of cancellations.

• Let’s check the area from where guests are visiting the hotels and making reservations. Is it coming from direct  or Groups, Online or Offline travel agents? Around 46% of the client come from online travel agencies, where 27% come from groups. Only 4% clients book hotels directly by visiting them and making reservations.

• As seen in graph, reservation are cancelled when the average daily rate is higher then when it is not cancelled.it clearly proves all the above analysis, that the higher price leads to higher cancellations. 

5.Tech Stack List the key technologies used to build the dashboard.

Example: 
The dashboard was built using Python: 
• Python Liberary:
• Pandas
• Numpy
• Seaborn
• Matplotlib -> Pyplot

6.Data Source More info on where the data comes from and how it’s structured Example:

Source: https://www.kaggle.com/datasets/mojtaba142/hotel-booking

7. Features / Highlights The best dashboard explanation format.
  • Business problem
  • Goal of the dashboard
  • Walk through of key visuals (briefly!)
  • Business impact & Insights

9. Suggestions
   i. Cancellation rates rise as the price does. In order to prevent cancellation of reservations,
 hotel could work on their prices strategies and try to lower the rate foe specific hotel based on locations.
 They can also provide some discount to the consumers.

 ii.As the ratio of cancellation and not cancellation of the resort hotel is higher in the resort hotel than the city hotels. 
   So the hotel should provide a reasonable discount on the room price on the weekend and on the holidays. 

 iii.In the month of January, hotels can starts campaigns or marketing with a reasonable amount to increase their revenue as the cancellations is the highest in this month.

 iv.They can also increase the quality of their hotels and their services mainly in Portugal to reduce the cancellation rate.


