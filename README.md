# London-Airbnb Analysis

### Project Overview

The dataset analysed in this report is the London Airbnb dataset. The dataset is a collection of data of Airbnb listings in London. It contains the following information: ID, property name, host name, host ID, neighbourhood, latitude and longitude, room type, price and reviews. This dataset can be used to study patterns in Airbnb pricing, neighbourhood differences, guest preferences and understand how Airbnbs are used in London. It will help business managers make informed decisions about property rentals and investments. This dataset was obtained from Inside Airbnb website [Download here](https://insideairbnb.com/).
According to Inside Airbnb website, the data is sourced from publicly available information on the Airbnb site.

### Tools Used

. Excel - Data Cleaning

. Tableau - Creating Reports

. Weka -  

### Data Cleaning/Preparation

For the data to be used in tableau, it had to be cleaned. The following steps were carried out:
1. The dataset was checked for duplicity but no duplicates were found.
2. 'Neighbourhood group' column was removed because it was empty.
3. Blank cells from the data were removed and headers made clear.
4. After cleaning, the dataset has 87597 rows and 16 columns.


### Data Analysis And Visualisation

![Most and least expensive neighbourhood](https://github.com/user-attachments/assets/90945af7-107c-4343-9406-cc1049069960)

This visualization allows for quick comparisons, revealing which neighborhoods have higher or lower average Airbnb prices in descending order.

The most expensive neighborhood is Kensington and Chelsea while the cheapest neighborhood is Sutton. The top five neighborhoods with higher average prices are Kensington and Chelsea (£303.0), Westminster (£213.0), City of London (£192.7), Camden (£147.6) and Islington (£143.0). The least five neighborhoods with lower average prices are Hillingdon (£68.8), Harrow (£67.0), Croydon (£60.0), Redbridge (£59.1) and Sutton (£58.2).


![Room type by minimum night](https://github.com/user-attachments/assets/cd4ddb2e-8d13-4928-bc27-aedb3ee51c3a)

The largest circle represents 'Entire room/apartments' with 6.940 average minimum nights while the smallest circle represents 'Shared room' with 1.367 average minimum nights. This visualization reveals the preference of guests in Airbnb London based on the average minimum nights spent in each room type. It reveals that guests spend longer periods in entire homes/apartments followed by private rooms. Also, guests spend shorter periods in hotel rooms and private rooms.
