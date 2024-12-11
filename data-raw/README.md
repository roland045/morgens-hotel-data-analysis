# Description of the raw dataset

11 tables per hotel with data collected between 18.09.2024 and 18.10.2024:
- 1 table with data on website traffic
- 1 table with data on marketing spending
- 8 tables with search and booking data
- 1 table with occupancy data 

## Brief description of the tables (longer below):

| Dataset Name             | Description                                                                                                                                                                |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| daily_ppc_budget         | Daily advertising budget spent on Google, Microsoft, and META advertising platforms.                                                                                      |
| website_daily_users      | Daily users/sessions on the website and their associated sources/mediums/campaigns.                                                                                       |
| datepicker_daily_visitors| Daily number of visitors using the date picker.                                                                                                          |
| search_log               | Search parameters for each search, conversion (if any), and total amount.                                                                                                 |
| search_log_session       | Session, user identifiers, UTM parameters (source, medium, campaign) - identifying which marketing channels brought users to the website, who used the date picker. |
| search_log_room          | Searched rooms, number of people per room, and the selected room's price (if available).                                                                                  |
| search_log_room_child    | Age groups of children in the searched rooms.                                                                                                                             |
| search_log_room_offer    | Search results for rooms with min-max prices.                                                                                                                             |
| daily_occupancy          | Changes in occupancy data, recorded daily, broken down until 2025-08-31.                                                                                                  |
| booking_data             | Breakdown of realized booking prices, contents, discounts, and points.                                                                                        |
| upsell_data              | Listing of upsell products/services included in realized bookings.                                                               |


## Longer description of tables:

1. booking_data table
This table contains the final price breakdown of the completed bookings, showing the room rate and the value of extras and discounts.

2. daily_occupancy table
This table records the occupancy rate for each day, which shows the occupancy rate of a given hotel as a percentage up to 2025-08-31.

3. daily_ppc_budget table
This table shows the daily ad budget spent in Google, Microsoft and META advertising systems.

4. datepicker_daily_visitors table
This table shows the number of daily visitors to the Datepicker.

5. search_log table
This table contains the data of the searches performed on this website.

6. search_log_room table
This table stores the details of the rooms selected during a search.

7. search_log_room_offer board
This table contains details of offers related to searches, such as prices for rooms offered.

8. search_log_room_child table
This table shows the age of the children in the room and whether a baby cot has been requested.

9. search_log_session table
This table stores data related to search sessions, such as user sources and campaign information.

10. website_daily_users table
This table records the number of users of the hotel's website from which UTM source/medium and campaign.

11. upsell_data table
This table contains the list of extra services/products included in the bookings made.