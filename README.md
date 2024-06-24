# Tableau-Dashboard-Project 
# New York City Airbnb 2023 Dataset Analysis

# IFT 533: Data Visualization & Reporting for IT
# Project Team 8:
Stuti Pandey
Anagha Nitin Navale
Harsh Ketan Khona
Jayesh Borkar

**Team’s mural dashboard:**
https://app.mural.co/t/533project3003/m/533project3003/1712091604307/8fcee73b12ba135b97b31722bbf93dedf0c7ba76?sender=c8015161-2117-43ce-942b-933be3cedcec

**New York City Airbnb 2023 Public Data from Kaggle**
https://www.kaggle.com/datasets/godofoutcasts/new-york-city-airbnb-2023-public-data/data

**Link to Dashboard:**
https://public.tableau.com/app/profile/anagha.nitin.navale/viz/530_Project_Team_8_Final/Dashboard2


## Description
The New York City Airbnb 2023 Dataset provides a comprehensive overview of the city's short-term rental market, encompassing vital information such as listing details, host profiles, neighborhood categorization, pricing dynamics, and review statistics. With its rich array of attributes, including unique identifiers, geographical coordinates, room types, and availability data, this dataset serves as an invaluable resource for stakeholders in the hospitality and tourism industries.

## Dataset Overview
- **Source:** Public Data from Kaggle
- **Total Rows:** 42,931
- **Total Columns:** 18

### Columns and Data Types
- **ID:** Unique alphanumeric identifier assigned to each Airbnb listing (Nominal)
- **Name:** Textual name given to the Airbnb listing (Nominal)
- **Host_id:** Unique alphanumeric identifier assigned to each Airbnb host or user (Nominal)
- **Host_name:** First name(s) of the Airbnb host or user (Nominal)
- **Neighbourhood_group:** Neighborhood group categorization based on the listing's latitude and longitude coordinates (Nominal)
- **Neighbourhood:** Neighborhood categorization, same as the neighbourhood_group (Nominal)
- **Latitude:** Latitude coordinate of the listing's location (Ratio)
- **Longitude:** Longitude coordinate of the listing's location (Ratio)
- **Room_type:** Categorization of the listing into one of four room types: Entire home/apt, Private room, Shared room, or Hotel room (Nominal)
- **Price:** Nightly rental price for the listing in US dollars (Ratio)
- **Minimum_nights:** Minimum number of nights required for a guest to book a stay at the listing (Ratio)
- **Number_of_reviews:** Total count of reviews received by the listing (Ratio)
- **Last_review:** Date when the listing last received a review (Interval)
- **Reviews_per_month:** Average number of reviews the listing receives per month (Ratio)
- **Calculated_host_listings_count:** Total number of listings owned or managed by the same Airbnb host (Ratio)
- **Availability_365:** Number of days in a year that the listing is available for rent (Ratio)
- **Number_of_reviews_ltm:** Number of reviews the listing received in the last 12 months (Ratio)
- **License:** Status of the license or legal permit held by the property owner for operating the listing (Nominal)

## Data Type Summary
- **Nominal (Categorical):** ID, Name, Host_id, Host_name, Neighborhood_group, Neighbourhood, Room_type, License
- **Ratio:** Latitude, Longitude, Price, Minimum_nights, Number_of_reviews, Reviews_per_month, Calculated_host_listings_count, Availability_365, Number_of_reviews_ltm
- **Interval:** Last_review

## Range of Values
- **ID, Host_id:** Unique alphanumeric identifiers
- **Name, Host_name:** Text strings
- **Neighborhood_group:** Names within New York City (e.g., Manhattan, Brooklyn, Queens, Bronx, Staten Island)
- **Neighborhood:** Names within New York City
- **Latitude, Longitude, Price:** Numeric values
- **Room_type:** 'Entire home/apt', 'Private room', 'Shared room', 'Hotel room'
- **Minimum_nights, Number_of_reviews, Calculated_host_listings_count:** Non-negative integer values
- **Reviews_per_month, Number_of_reviews_ltm:** Non-negative integer values
- **Last_review:** Date values
- **Availability_365:** Integer values between 0 and 365
- **License:** 'Exempt', 'Issued', 'Pending', 'Unlicensed'

## Prospective Dashboard Users
1. **City Planners and Urban Development Experts:**
   - Utilize the dashboard to examine trends in neighborhoods and assess how short-term rentals affect housing availability and affordability, guiding urban planning decisions and policies.
2. **Hospitality and Tourism Industry Stakeholders:**
   - Monitor Airbnb's market share, pricing trends, and consumer preferences across neighborhoods to develop competitive strategies and customize offerings.
3. **Real Estate Investors and Property Managers:**
   - Pinpoint high-demand neighborhoods for short-term rentals and evaluate the potential profitability of investing in or managing Airbnb properties.
4. **Researchers and Academics:**
   - Analyze the impact of the sharing economy on housing markets, gentrification patterns, and neighborhood dynamics, advancing research in these fields.
5. **Airbnb Hosts and Potential Hosts:**
   - Understand pricing patterns, occupancy rates, and competition levels in various neighborhoods, optimizing pricing strategies and listing choices.
6. **Policymakers and Regulatory Authorities:**
   - Monitor adherence to short-term rental regulations, identify any illegal activities, and assess the necessity for policy interventions or adjustments.

## List of User Requirements
- City planners use NYC Airbnb data for informed urban development decisions.
- Hospitality stakeholders analyze market trends for competitive strategies.
- Real estate investors evaluate property profitability with dataset insights.
- Researchers study rental impact on housing markets and neighborhoods.
- Airbnb hosts optimize pricing and occupancy with dataset insights.
- Policymakers monitor compliance and regulate short-term rentals.

## Potential Questions
1. What are the different neighborhoods in New York City?
2. Which year had the highest/lowest bookings?
3. Which neighborhood group has the largest and smallest number of neighborhoods?
4. Which neighborhoods in New York City have the highest/lowest number of Airbnb hosts?
5. How many reviews for a given year?
6. What is the overall trend observed over the years for a specific neighborhood group, such as an increase or decrease in bookings?
7. Which neighborhood group has the highest/lowest average price?
8. What is the total number of hosts in the city, and in a given neighborhood group?
9. Which month observes the least/most bookings in a neighborhood group?
10. Which neighborhood group has the highest/lowest average ratings?
11. Which host has the maximum/minimum number of reviews?
12. For a given month, which are the top 3 neighborhood groups based on bookings?
13. Which room type in each neighborhood is most/least popular while booking, based on reviews?
14. What neighborhood for a given neighborhood group exhibits the highest/lowest price, based on room type?
15. Which is the most expensive neighborhood in all the neighborhood groups in the entire city?

## How to Use This Repository
1. Clone the repository to your local machine.
   ```sh
   git clone https://github.com/stutipandey20/Tableau-Dashboard-Project.git
2. Open the dataset in your preferred data analysis tool (e.g., Tableau, Python, R).
3. Explore the dataset and create visualizations based on the potential questions and user requirements listed above.


We welcome contributions to enhance the analysis and visualizations. Please fork the repository and submit a pull request with your improvements.
