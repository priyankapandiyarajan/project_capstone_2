
# PhonePe Pulse Data Visualization Project

This project aims to visualize data from PhonePe Pulse using Streamlit, a Python library for creating web applications with simple Python scripts.

## Project Overview

- Cloned data from PhonePe's GitHub repository.
- I fetched the data from cloned JSON files and sent them to Pandas DataFrames.
- Stored the data in a MySQL database using MySQL.
- Created six tables in the database:
  - Aggregated Transaction
  - Aggregated User
  - Map User
  - Map Transactions
  - Top Transactions
  - Top User
- I used an SQL cursor to fetch data from the database and send it to Pandas DataFrames.
- Created three different tabs in Streamlit:

## Explore Data

The **Explore Data** tab provides an overview of the data in two categories: transactions, and users. Users can:

- View transaction data, including transaction types and amounts, state-wise.
- See user data, including state-wise user counts.
- View choropleth maps to visualize data distribution across states.
- See top states based on various metrics like transaction amount, and user count.
- Analyze top transaction types.

## State Data

The **State Data** tab allows users to dive deeper into data for each state and district. Users can:

- Filter data by year, quarter, and state to view specific information.
- Explore transaction and user data for each state and district.
- Visualize data distribution on choropleth maps at the state and district levels.
- Gain insights into transaction, and user data for each state and district.

## Data Insights

The Data Insights tab provides the following insights:

- Yearly Growth of Transaction Amount in India
- Yearly Growth of Transaction Count in India
- Yearly Growth of Registered Users in India
- Yearly Growth of App Open in India
- Transaction Amount by State
- Transaction Count by State
- Transaction Count by Brand
- Insurance Premium Amount by State
- Insurance Premium Count by State
- Registered User by State
- App Opens by State
- State Wise - Brand & Transaction Amounts
- Transaction Types Analysis by Years and Quarters
- Average Transaction Amount by Quarter
- Percentage of Transactions by Type

## GeoView

The **GeoView** tab offers a global perspective by displaying a complete world Folium map highlighted in India. Users can:

- Visualize India's geographical location in the world.
- See the relative position of India compared to other countries.
- Gain a holistic view of India's position in the global context.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

   ```bash
   https://github.com/priyankapandiyarajan/project_capstone_2.git
   
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

3. Run the Streamlit Application:

   ```bash
   streamlit run phonepe.py

**User Interface**

![User Interface](UI.png)


## Conclusion:
**The PhonePe Pulse Data Visualization Project**, offers a user-friendly platform for exploring and analyzing PhonePe transaction, insurance, and user demographic data. Through the utilization of Streamlit and MySQL, the project enables interactive visualization of various data aspects, including transaction trends, insurance metrics, and user demographics at national and state levels. With features like the Explore Data and State Data tabs providing detailed insights and the GeoView tab offering a global perspective, the project demonstrates the efficacy of data visualization in deriving meaningful insights.

## Contributors - Priyanka Pandiyarajan

