## PyBer_Analysis
Create line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib. And determine mean, median, and mode using Pandas, NumPy, and SciPy statistics.

# Overview of the project
- **Deliverable 1**: A ride-sharing summary DataFrame by city type
- **Deliverable 2**: A multiple-line chart of total fares for each city type
- **Deliverable 3**: A written report for the PyBer analysis [README.md]

# Deliverable 1: A Ride-Sharing Summary DataFrame by City Type
**Deliverable Requirements**:
1. The total number of rides for each city type is retrieved.
2. The total number of drivers for each city type is retrieved.
3. The sum of the fares for each city type is retrieved.
4. The average fare per ride for each city type is calculated.
5. The average fare per driver for each city type is calculated.
6. A PyBer summary DataFrame is created.
7. The PyBer summary DataFrame is formatted as shown in the example.

![1-3](https://user-images.githubusercontent.com/84139825/172227540-2a8f3183-a201-48a5-bcac-6ca542d9a7fb.PNG)
![4-6](https://user-images.githubusercontent.com/84139825/172227576-4ec33952-f7cb-4393-a388-82dfcded1216.PNG)
![7,8](https://user-images.githubusercontent.com/84139825/172227608-0489f58c-d957-4c41-b3d2-80d763af6fce.PNG)

# Deliverable 2: A multiple-line chart of total fares for each City type
**Deliverable Requirements**:
1. A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.
2. A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."
3. A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29.
4. A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.
5. An annotated chart showing the total fares by city type is created and saved to the "analysis" folder

![d2](https://user-images.githubusercontent.com/84139825/172228673-465ddccb-3ca0-4cc1-96ba-662ddb161ccd.PNG)
![PyBer_fare_summary](https://user-images.githubusercontent.com/84139825/172228697-8a1e0afb-3b6c-4bf0-8de6-a1b1309acf44.png)
