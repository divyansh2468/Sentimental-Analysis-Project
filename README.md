-->The project aims to develop a robust framework for multi-platform sentiment analysis of fan opinions, targeting FC Barcelona-related events.
By processing data from platforms like Reddit and Twitter, the system uncovers real-time and historical sentiments expressed by fans, offering a broader view of public opinion.

-->Novelty

✅ Multi-Platform Integration: Combines Reddit and Twitter to overcome the limitations of single-source data.

✅ Incident-Specific Modeling: Focuses on fan sentiments around key events rather than general discussions.

✅ Real-Time Scalability: Framework supports dynamic updates and trend analysis.

-->Modules

✅ Data Fetching: Uses APIs (e.g., Reddit's PRAW, Pushshift) to retrieve relevant posts.

✅ Filtering & Validation: Removes irrelevant data based on date, URL structure, etc.

✅ Storage: DataFrames/CSV for structured data storage.

✅ Analysis & Visualization: Uses pandas, matplotlib, and NLP libraries.

-->Implementation

✅ Built asynchronous scrapers using Python.

✅ Trained models on general and incident-specific Reddit data.

✅ Visualized sentiment distributions using matplotlib.

-->Results & Insights

✅ Extracted patterns like spikes in negative sentiment during poor match outcomes or controversies.

✅ Found greater sentiment diversity in Reddit discussions compared to Twitter.

✅ Improved model accuracy with event-focused training datasets.
