# Las-Vegas-Strp_TripAdvisor
# This is a Basic Exploratory Data Analysis on TripAdvisor Las Vegas Hotel Reviews from the Las Vegas Strip Dataset extracted from TripAdvisor (http://www.tripadvisor.com).
The dataset contains 504 entries of quantitative and categorical records on visitors to the Las Vegas Strip over the given period.
There were 504 rows and 20 columns of data. The columns were ('Country', 'Total Reviews', 'Hotel Reviews', 'Helpful Votes', 'Rating','Stay Period', 'Traveler Type', 'Has Pool', 'Has Gym', 'Has Tennis Court', 'Has Spa', 'Has Casino', 'Has Free Internet','Hotel Name', 'Hotel Stars', 'Hotel Rooms', 'Continent','Membership Years', 'Review Month' and 'Review weekday')
There were no null values in the dataset.
The dataset required minimal cleaning and manipulation
The 'Membership Years' column had a negative value of -1806 as its minimum value which negatively skewed the data. For ease of data analysis, all values less than 0 were made null (NaN)
While the database included data of visitors from 47 countries, 87.3% of visitors were from the Top 10 countries (USA: 217, UK: 72, Canada: 65, Australia: 36, Ireland: 13, India: 12, Mexico: 8, Germany: 7, Egypt: 5, Brazil: 5
23 countries each had 1 visitor only ( Kenya, Korea, Japan, Czech Republic, Kuwait, Taiwan, Denmark,Honduras, Saudi Arabia, Iran, China, Jordan, Greece, France, Syria, Puerto Rico, Belgium, Phillippines, South Africa, Swiss, Croatia, Hungary, Italy)
Due to the bulk of data being from a small number of countries, the results may have been skewed in certain areas such as 
Mar-May is the most popular Stay Period among visitors from the Top 10 countries with 114 visitors, followed by Dec-Feb with 112 visitors while 107 visitors visited the Las Vegas hotels during Jun-Aug and Sep-Nov respectively
More visitors from USA stayed at The Cosmopolitan and Bellagio Las Vegas, while UK guests mainly stayed at Caesars Palace and The Cromwell and visitors from Canada stayed mostly at Circus Circus and The Palazzo Resort Hotel
