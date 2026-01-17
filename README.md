# powerbi_spotify_dashboard
An interactive Power BI dashboard analyzing Spotify’s most-streamed songs, highlighting top performers, artist dominance, and the relationship between total and daily streaming activity.

📊 Spotify Streaming Performance Dashboard

This project presents an interactive Power BI dashboard built using a Spotify streaming dataset to analyze song popularity, artist contribution, and streaming behavior.
The dashboard enables users to explore both lifetime performance and current popularity trends through dynamic visuals and slicers.

🗂 Dataset

Format: CSV

Contains song-level streaming metrics:

Total Streams

Daily Streams

Song and Artist information

No major preprocessing was required; only data-type validation and Top N filtering were applied within Power BI.

📌 Dashboard Features
Key Metrics

Total Songs: ~3K

Total Streams: ~2 Trillion

Average Daily Streams: ~504K

Visualizations

Top 10 Songs by Total Streams – identifies all-time most successful tracks

Top 10 Songs by Daily Streams – highlights currently trending songs

Streams vs Daily Streams (Scatter Plot) – compares long-term success with current momentum

Top 7 Artists Contribution (Donut Chart) – shows artist-level dominance in total streams

Top 10 Songs Contribution (Donut Chart) – reveals concentration of streams among top tracks

🎛 Interactive Slicers

Artist slicer (Top 7 by total streams)

Song slicer (Top 10 songs by streams)

Streams range slicer for flexible exploration


💡 Key Insights

Streaming activity is highly concentrated, with a small number of songs contributing a significant share of total streams.

Some tracks show high daily streams but lower total streams, indicating emerging or currently viral songs.

Legacy hits dominate total streams but often display lower daily momentum, reflecting stabilized popularity.

A limited group of artists accounts for a disproportionately large portion of overall streams.

The scatter plot clearly distinguishes between long-term popularity and short-term engagement, offering deeper performance context.

🛠 Tools Used

Power BI Desktop

Microsoft Excel / CSV data source
