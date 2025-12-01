

**Spotify Music Analysis Dashboard**

This project demonstrates **end-to-end music analysis dashboard using a Spotify dataset in Power BI**. The dashboard allows for exploration of music data, including total streams, tracks, average streams, trends over time, monthly and daily performance, details on the most streamed tracks, and top tracks.

Dashboard Link: https://app.powerbi.com/links/USh8UsudRO?ctid=5b240caa-c9b9-41f3-bd55-0c6ae3dc9b51&pbi_source=linkShare

**Problem Statement**

The goal of this project is to **create a comprehensive one-page dashboard to analyze Spotify data**. This involves cleaning and transforming a raw dataset, designing a visually appealing background, and building interactive visuals in Power BI to present key metrics and insights about the music tracks, artists, and streaming performance over time.

**Steps followed**

Here is a general overview of the steps taken to create the dashboard:

*   **Step 1: Acquire and Load Data**. The process begins by getting the data into Power BI Desktop, typically from a source like an Excel workbook.
*   **Step 2: Perform Data Cleaning and Transformation**. Using the Power Query Editor, the data is cleaned and transformed. This involves assessing column quality and distribution, changing data types (e.g., to Text), treating errors by removing rows, handling missing or null values by replacing them, and creating or removing columns as needed (e.g., creating a single Date column from multiple date-related columns).
*   **Step 3: Apply Data Changes and Prepare for Modeling**. The cleaning and transformation steps performed in Power Query Editor are applied to load the clean data into the Power BI report view.
*   **Step 4: Create and Configure Necessary Tables**. A new table, such as a dedicated date table, is created using formulas. This new table is then marked as an official date table, and columns within it (like month or day names) are sorted appropriately.
*   **Step 5: Establish Data Relationships**. In the Model view, relationships are created between the different tables that were loaded or created (e.g., linking the primary dataset to the date table). This allows for integrated analysis across tables.
*   **Step 6: Design the Dashboard Background and Layout**. An appealing visual background for the dashboard is designed, potentially using external tools like PowerPoint. This involves creating shapes, adding colors, gradients, shadows, inserting images (like logos), adding titles, and grouping these elements.
*   **Step 7: Import Background and Set Canvas**. The designed background is imported into the Power BI report page. Canvas settings, such as size (height and width), may be adjusted to fit the design and intended layout of visuals.
*   **Step 8: Build Core Visualizations and KPIs**. Key Performance Indicators (KPIs) like total streams, tracks, and average streams are created using card visuals. Other core visualizations such as line charts to show trends over time, tables for detailed breakdowns (e.g., streams by month), and bar charts for comparisons (e.g., streams by day) are built. These visuals are placed and basic formatting is applied.
*   **Step 9: Add Detailed Sections and Interactive Filters**. Specific sections are added to highlight details like the artist's most streamed track or the top tracks. Interactive filters (slicers) are incorporated to allow users to explore the data based on criteria like track name, date range, or artist. Visuals are formatted, including adding images where applicable.
*   **Step 10: Refine Layout, Edit Interactions, and Finalize**. The positioning and size of all visuals are adjusted to fit the canvas. Interactions between visuals and slicers are controlled using the 'Edit interactions' feature to ensure specific visuals respond as desired. The report is then considered finalized.

**Snapshot of Dashboard**

![Image](https://github.com/user-attachments/assets/04167b2f-6051-4a22-b768-d69c92ef9e15)

**Insights**

Based on the completed dashboard, several insights can be drawn from the visuals:

*   Overall Metrics: The dashboard displays the Total Streams, Total Tracks, and Average Streams from the dataset.
*   Streams over Time: The line chart shows the trend of Streams by Release Date, spanning from 193 up to 2023.
*   Monthly Performance: The table visual details Tracks and Streams by Month. It highlights differences like January having the highest number of tracks released (133), while September has the highest average streams, surpassing January and May. Conditional formatting helps visually compare average stream performance across months.
*   Daily Performance: The bar chart shows Daily Streams for all tracks. It clearly indicates that Friday has the highest number of streams compared to other days of the week.
*   Artist Most Streamed Track: A dedicated section identifies the track with the highest total streams (e.g., The Weeknd's track). It provides key details like the Track Name, Release Date, Streams, Mode, and Key.
*   Music Information: Statistics about the most streamed track, such as its Energy, Speech content, Liveliness, and Instrumental nature, are displayed.
*   Top Tracks: The dashboard features a visual showcasing the Top five most streamed tracks, allowing users to quickly identify the most popular songs by total streams and see their associated artist and cover art.
*   Filtering: Slicers allow users to filter the dashboard by Tracks, Date range, and Artist, enabling interactive exploration of the data and insights specific to selected criteria. The ability to edit interactions allows control over which visuals respond to each filter selection.

