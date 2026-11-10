
## 1. Study Area and Dates

For this lab, I chose to focus on vessel traffic around Seattle and Puget Sound, Washington, because I live in Seattle and I am familiar with this area. I downloaded my own dataset from AccessAIS by selecting a small area around Seattle and Bainbridge Island from October 3 to October 6, 2025. The dataset was about 75.92 MB, which helped me keep the data manageable. I used the Google Colab notebook provided in class to convert the CSV into JSON. The original data uses UTC, but my map displays the time in Seattle's local time.

## 2. Interpretation

After exploring my map, I noticed that vessel traffic flows along different routes around Seattle and Puget Sound instead of moving randomly. For example, I could see several routes connecting Seattle's waterfront to nearby areas and some longer routes going through Puget Sound. This makes sense because Seattle is a major waterfront city with different types of marine transportation. I also tried the vessel filters to see how different ships move. I selected Passenger and the map showed 50 paths. I noticed that some routes were longer while others appeared closer to Seattle's waterfront. I also used the time slider to stop the animation at October 2, 2025, around 8:06 PM PDT. I think the animation is useful because it helps me understand how ship locations change over time instead of seeing every movement at once.

## 3. Feature Proposal for a Potential User

If I could add one more feature to my map I would create a popup that shows information about a ship when someone clicks on it. For example, it could display the vessel's name, type, and the time it was recorded. I think this feature would be helpful for port workers or people who are interested in tracking marine transportation around Seattle. Instead of only watching the moving paths, they could click on a particular ship to learn more about it. I think adding this feature would make my map more interactive and useful for understanding vessel traffic.