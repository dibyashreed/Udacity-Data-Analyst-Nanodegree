## Data
The data contains information about over 3 million Ford Go-Bike Data including information about age, gender, total miles, trip information, etc. We will be using the Bay Area Bike Share Trips Data (https://cloud.google.com/bigquery/public-data/bay-bike-share). Due to the way the Ford Go-Bike app accepts data, we have some records that have ages beyond 100 years. So, for the sake of keeping the calculations accurate, we will only consider data that has age in the 16 - 70 range. To better analyze the age related data, we have segregated them into bins.

Also, the data includes ride info in San Francisco, Oakland and San Jose. To accrately analyze the data and keeping the traffic in mind, we will only be considering data related to San Francisco.

## Insights gained from the Data
Fall and summer months are popular for bike riding
About 90% of the riders use it during weekdays
The age groups of 30-40 use the bikes the most followed by the age group of 20-30
Males took 78% of rides and females took 22% of rides
We see that 5 PM is the peak usage time.
The peak bike rides time for all members is around commute time.

## Opening the Jupyter Notebook
The project Analyzing_Ford_GoBike_Data.ipynb can be read using a Jupyter Notebook. There's also an HTML version Analyzing Ford GoBike Data.html included for easier viewability.

Open your Command Prompt (PC) or terminal (Mac or Linux).
On a PC click the Start button and search for "Command Prompt".
On a Mac type command + spacebar. Then, type "terminal" in the Spotlight Search. You can also search for "terminal" in finder.
Navigate to the directory where you downloaded the Jupyter notebook file.
On a PC you might type: cd C:\Users\username\Downloads, replacing your username. Learn more about basic terminal commands.
On Mac or Linux you might type: cd ~/Downloads.
Run the command jupyter notebook Analyzing_Ford_GoBike_Data.ipynb in your terminal.
