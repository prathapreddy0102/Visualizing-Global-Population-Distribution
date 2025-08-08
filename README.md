# Visualizing-Global-Population-Distribution
🎓 Project Goal: Visualize the distribution of a continuous variable — population — using a bar chart and a histogram.

📦 Why use pandas?
Pandas is the go-to library for working with tabular data in Python. Here's why it was perfect for your population dataset:

Feature: Why It Helps Here
✅ Easy CSV loading. The World Bank file is a .csv — pandas read it fast and clean.
✅ Data selection: You can easily select specific rows/columns (like Country Name and 2024).
✅ Filtering: Want just 10 countries? .isin() or boolean indexing makes it simple.
✅ Cleaning: Drop empty/missing values with .dropna().

📊 Why use matplotlib?
Matplotlib is one of the most powerful and flexible plotting libraries in Python. Here's why it's a good fit:

Feature: Why It Helps Here
✅ Customizable charts: Add titles, labels, grids, colors, and control everything.
✅ Bar chart supports	visualizing categorical comparisons (like countries) is easy.
✅ Histogram support	helps show the distribution of population values.
✅ Publication-quality: Great for printing or inserting into university reports.

While matplotlib was used for this project due to its high level of customization and compatibility with static academic reports, alternative libraries like seaborn offer quicker and aesthetically pleasing plots, while plotly is ideal for interactive visualizations and dashboard-style outputs.
