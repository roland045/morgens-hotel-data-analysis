# Description of the raw dataset

11 tables per hotel with data collected between 18.09.2024 and 18.10.2024:
- 1 table with data on website traffic
- 1 table with data on marketing spending
- 8 tables with search and booking data
- 1 table with occupancy data 


| Dataset Name             | Description                                                                                                                                                                |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| daily_ppc_budget         | Daily advertising budget spent on Google, Microsoft, and META advertising platforms.                                                                                      |
| website_daily_users      | Daily users/sessions on the website and their associated sources/mediums/campaigns.                                                                                       |
| datepicker_daily_visitors| Daily number of visitors using the date picker (Booking Step 0).                                                                                                          |
| search_log               | Search parameters for each search, conversion (if any), and total amount.                                                                                                 |
| search_log_session       | Session, user identifiers, UTM parameters (source, medium, campaign) - identifying which marketing channels brought users to the website, who used the date picker (Booking Step 0). |
| search_log_room          | Searched rooms, number of people per room, and the selected room's price (if available).                                                                                  |
| search_log_room_child    | Age groups of children in the searched rooms.                                                                                                                             |
| search_log_room_offer    | Search results for rooms with min-max prices.                                                                                                                             |
| daily_occupancy          | Changes in occupancy data, recorded daily, broken down until 2025-08-31.                                                                                                  |
| booking_data             | Breakdown of realized booking prices, contents, discounts, and points (Purchase).                                                                                        |
| upsell_data              | Listing of upsell products/services included in realized bookings (products/services from Booking Step 2).                                                               |
