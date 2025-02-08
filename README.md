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

![Neighbourhood by host listings](https://github.com/user-attachments/assets/6a602068-43b4-4094-9382-6488aaa597ed)


This pie chart depicts London Airbnb neighborhoods by the percentage count of host listings, each slice of the pie represents a different neighborhood. The size of each slice corresponds to the percentage of total host listings that belong to that specific neighborhood. This visualization provides a quick overview of the distribution of host listings across different neighborhoods, highlighting the proportional contribution of each area to the overall listings count.

Westminster neighborhood with 25.69% has the highest percentage count of host listing while Barking and Dagenham with 0.09% has the lowest percentage count of host listings.

![Room type by price](https://github.com/user-attachments/assets/41f5a049-c55d-492b-bb0f-fec0290cadcb)
This illustrates room types by average price. The bars on x-axis represent different room types and the height of each bar refers to the average price of the room type. This simple representation allows for a straightforward comparison of pricing across different room types, helping to identify which types are more expensive or affordable.
Out of the four room types, entire homes/apartments are the most expensive with average price of £207.6 Hotel rooms are the second most expensive with average price of £171.9, followed by private rooms with £85.5. The cheapest of all is the shared room type with average price of £39.7

![Minimum nights vs number of reviews](https://github.com/user-attachments/assets/24305afb-9b92-4c60-ac33-d4943262ef25)
This is a bar chart illustrating room type by number of reviews by minimum nights. The x-axis shows information on minimum nights, number of reviews and price for each room type while the y-axis represents the value of each entity in numbers. 

Private room type has the highest number of reviews (77,980,600) while the entire home/apartment type has the highest price and highest minimum number of nights (2,159,597). The shared room type has the lowest minimum nights, price and lowest number of reviews.
A simple conclusion that can be drawn from this analysis is that guests who make use of London Airbnb prefer the entire home/apartment type irrespective of how expensive it is. It is advisable for a prospective Airbnb host to invest in the entire home/apartment type or private room type rather than hotel room type or shared room type.

![Map of London by room type](https://github.com/user-attachments/assets/b6945eb8-aadc-4756-ac60-e284641f14c5)

In this map illustrating room types, different markers or colours on the map represent distinct room types. Each location on the map corresponds to a property, and the marker or colour indicates the type of room available at that particular location. This visualisation provides a spatial understanding of the distribution of room types across different areas in London.  
This map reveals that entire homes/apartments are well distributed all over London, meaning that there's high competition for this particular room type in London Airbnb. A relatively new host who wants less competition but still wants his room to be well rented should explore investing in private room types.

![Room type by number of reviews](https://github.com/user-attachments/assets/6d5b0608-fb81-4ee3-a558-58ca04e34ad5
This illustrates the average number of reviews available for each room type. It shows that private room type has the highest number of average reviews while entire homes/apartments have the lowest number of average reviews. The availability of reviews for prospective guests assists them in making their choices of room types in London Airbnb.

![Host with most listings](https://github.com/user-attachments/assets/eb3be549-fcfb-4716-bf5a-75608a46795f)

In  this horizontal bar chart showcasing hosts with the most listings, each bar represents a different host, and the length of the bar corresponds to the number of listings they have. This visualisation allows for easy identification of the host with the highest number of listings, as well as comparisons with other hosts in terms of their listing count. Paul is the host with the most listings, followed by James and Mark.

![Popular room type](https://github.com/user-attachments/assets/3e829bc5-79ed-4c9f-83fd-f43e1c627f5a)

Each group of bars represents a room type, and within each group, there are two bars: one for the count of IDs (listings) and another for the average price of listings for that room type. This allows for a comprehensive comparison of room types, considering both popularity (count of IDs) and pricing. The most popular room type by count of IDs is Private room type and by average price is Entire home/apartments.

![Host with the most reviews](https://github.com/user-attachments/assets/fc1949e8-af58-4d18-9792-07cc0fab9477)

This is a horizontal bar chart used to visualise the host with the most reviews. Each bar represents a different host, and the length of the bar corresponds to the total number of reviews they have received. This visualisation provides a clear comparison of hosts based on the number of reviews they've garnered, highlighting the most reviewed host prominently. Paul is clearly shown to be the most reviewed host. The reviews can be used by prospective guests to make a choice and can also provide insights into customer preference and behaviour.

### CONCLUSION

##Overall trends from visualisation analysis

	The important findings obtained from the visualisations are:
1. Private room type is the most popular based on the count of ID listings with 383,514.
2. Entire homes/apartments have the highest average number of minimum nights (6.940), meaning that they are the most occupied.
3. Entire homes/apartments are the most expensive followed by hotel rooms.
4. Paul is the host with the most listings and reviews.
5. The most expensive neighbourhood is Kensington and Chelsea with average price of 303.0 and the cheapest neighbourhood is Sutton with average price of 58.2


###Data mining results

The data mining algorithm used is Decision trees - J48. The confusion matrix showed a high number of true positives and true negatives, which is a good indication that the model is a good fit for the data. The 3rd iteration result has the highest percentage of correctly classified instances 83.76% which is further indication that the model is well refined and a good fit for the data.
The decision tree analysis highlighted predictors of room type classification. Price, availability_365, calculated_host_listings, and minimum_nights emerged as the prominent features in determining room type. A distinct pattern discovered showed that properties with higher prices are more likely to be classified as entire homes/apartment type while those with lower prices are most likely classified as private room type.

###Business Intelligence
	 
  The findings can  be used by AirBnb.Inc, guests and hosts. AirBnb can focus on getting more hosts for entire home types in expensive neighbourhoods and private room types in cheap neighbourhoods. They can provide discounts for other room types to improve their sales. Guests can use the findings to select neighbourhood and room type for their bookings depending on their budget. New hosts can view less competitive neighbourhoods for their choice of listings and decide the room type to list.






