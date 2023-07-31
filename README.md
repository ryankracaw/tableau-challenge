# Tableau Challenge

https://public.tableau.com/views/Tableau-Challenge_16907646378350/CitiBikeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

## Data Cleaning

The data was obtained from the Citi Bike Data webpage. I downloaded the May, June, and July files to take a closer look at the summer months. After downloading, I combined each csv file into one csv file using Python accompanied with the Pandas library. Then using a simple mapping I changed the 'Genders' column into their respective values. Code can be found in the file "citibike.ipynb".

## Home Dashboard

The Home Dashboard provides users with an introduction on the project as well as an interactive menu to navigate the various analyses. From here users can navigate to any of the other dashboards using the buttons provided at the bottom of the page.

## User Analysis

The Citi Bike user analysis dashboard presents a comprehensive analysis of the Citi Bike trips, taking into account various factors such as user type, gender, and age.

## Trip & Station Analysis

The Citi Bike trip and station analysis dashboard looks into the relation between trips and stations. Additionally, it compares trip patterns between weekend and weekdays.

## Geographic Analysis

The Citi Bike geographic analysis provides a visual representation of the trip patterns and frequency. The dashboard shows two maps; one being the start stations and the other being the end stations.

## Conclusion

This Tableau analysis provides a comprehensive overview of how Citibike is used over time. Interactive dashboards and visualizations highlight trends in user type, gender, age, hours, and weekdays. One noteworthy finding is that Citibike is popular in Jersey City, especially for commuting. This analysis is a valuable resource for anyone interested in Citibike, and I hope it inspires further research. One noteworthy phenomena I found was the bimodality of times that people used the bikes. Taking a closer look at the hourly heatmap, we can see that people using Citi Bikes follow the same trends as typical traffic patterns. There is a clear morning communte usage and an afternoon commute usage. This leads me to believe that Citi Bike is used by locals for work just as much as tourists. Another noteworthy phenomena I found was the popularity of certain stations. I can only assume that these stations are located at prime areas for tourism. However, further analysis may be conducted to conclude such claims.
