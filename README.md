# douyin-ad-dashboard

### Introduction

_Juliang Qianchuan_ is an e-commerce advertising platform under _Douyin_ (Chinese TikTok) which provides marketing solutions for its merchants and helps businesses achieve long-term growth. In order to make up for the missing backend features of the platform, this advanced, user-friendly visualized dashboard will not only offer a more comprehensive view of advertising metrics but also provide merchants with the flexibility to customize their data analysis, leading to more informed decision-making and effectively tailored marketing strategies.

This application mainly focuses on two key dimensions: the advertising account and the advertising program. Users can filter data according to their:
* **Marketing goals**, with options including _'All', 'Video',_ or _'Live’_.
* **Date ranges**, offering predefined selections such as _'Today', 'Yesterday', 'Last 7 Days',_ and _'Last 30 Days'_, along with an option for a custom date range.
* **Analysis metrics** such as _ROI (Return on Investment), CPM (Cost Per Mille), CPA (Cost Per Action),_ and _GPM (GMV Per Mille)_.
The results of the analysis, based on the selected metrics and filters, are presented in a tabular format, offering a clear and concise summary over the chosen time range.

For advertising accounts, the dashboard supports the selection of multiple analysis metrics and tracks their performance over time, representing the trends through a combination of line charts and tables. The time granularity of these trends adapts based on the selected date range: if a single day is chosen, the x-axis of the chart represents hours; for longer periods, it shifts to days.

When it comes to analyzing advertising programs, the dashboard allows users to select any three metrics for analysis. These chosen metrics are then represented in a bubble chart in which they are mapped distinctly: one to the x-axis, another to the y-axis, and the third to the size of the bubbles. Additionally, trend graph analysis for individual advertising programs is also provided, similar to the one for advertising accounts.

### Skills

Python, Dash, Plotly, MongoDB
