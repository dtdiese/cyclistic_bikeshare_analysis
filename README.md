# cyclistic-bikeshare-analysis

Google Data Analytics Capstone Project: Cyclistic Bike Share Case Study

## Business Task:
How do casual riders and annual paid members use Cyclistic bikes differently? The goal is to provide insights into user behavior that will aid the marketing team in how to convert casual riders into annual paid subscribers.

## Project Phases:
- [1] Ask
  - What is the problem we are trying to solve?
    - Increasing revenue by converting casual riders to annual paid members.
  - How can our insights drive business decisions?
    - By identifying behavioral differences in bike usage between casual and member riders, we can deliver insights into how we can convert casuals into members.
  - Key stakeholders:
    - The director of marketing, the marketing team as a whole and the executive team responsible for final decisions.
- [2] Prepare
  - The data can be found here: https://divvy-tripdata.s3.amazonaws.com/index.html
    - All data is public and contains no personal information of any riders.
    - Note that months 04/2025 through 03/2026 were used for this analysis.
  - The data is organized into csv files by each month. There appears to be a significant percentage of missing values in the columns containing station names and        IDs. Each individual ride has it's own unique ride ID.
- [3] Analyze

  - After cleaning the data, I analyzed behavioral differences between casual and member riders across several dimensions:
    - **Ride Length:** Casual riders had longer average rides (19.15 min) and median rides (11.33 min) compared to members (12.03 min average, 8.58 min median), suggesting more leisure-oriented usage.
    - **Day of Week:** Casual ridership peaked heavily on weekends, while member ridership was highest on weekdays, with a slight bump on Tuesday, Wednesday, and Thursday consistent with hybrid work schedules.
    - **Hour of Day:** Members showed clear commuter patterns with ridership spikes from 7-8am and 3-6pm. Casual riders showed no morning spike, with activity increasing starting at 11am and peaking at 5pm, indicating non-commute usage.
    - **Seasonality:** Both groups peaked in ridership during August, but casual ridership dropped off far more sharply in winter months, suggesting members rely on bikes year-round while casual riders are largely fair-weather users.
    - **Bike Type:** Both groups showed a similar preference for electric bikes (roughly two-thirds of all rides). However, casual riders rode classic bikes nearly twice as long on average as electric bikes, suggesting twot casual rider behaviors: leisurely rides on classic bikes versus quicker point A to pint B trips on electric bikes.

- **Station Location:** Casual rider activity clustered heavily around tourist destinations (Millennium Park, Shedd Aquarium, Michigan Avenue), while member activity clustered around street intersections likely representing office and residential commuting routes.
