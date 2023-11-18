# douyin-ad-dashboard

### Introduction

_Douyin E-Commerce Ads_ is a platform under _Douyin_ (Chinese TikTok) which provides marketing solutions for its merchants and helps businesses achieve long-term growth. In order to make up for the missing backend features of the platform, this advanced, user-friendly visualized dashboard will not only offer a more comprehensive view of advertising metrics but also provide merchants with the flexibility to customize their data analysis, leading to more informed decision-making and effectively tailored marketing strategies.

This application mainly focuses on two key dimensions: the advertising account and the advertising program. Users can filter data according to their:
* **Marketing goals**, with options including _'All', 'Video',_ or _'Live’_.
* **Date ranges**, offering predefined selections such as _'Today', 'Yesterday', 'Last 7 Days',_ and _'Last 30 Days'_, along with an option for a custom date range.
* **Analysis metrics** such as _ROI (Return on Investment), CPM (Cost Per Mille), CPA (Cost Per Action),_ and _GPM (GMV Per Mille)_.
The results of the analysis, based on the selected metrics and filters, are presented in a tabular format, offering a clear and concise summary over the chosen time range.

For advertising accounts, the dashboard supports the selection of multiple analysis metrics and tracks their performance over time, representing the trends through a combination of line charts and tables. The time granularity of these trends adapts based on the selected date range: if a single day is chosen, the x-axis of the chart represents hours; for longer periods, it shifts to days.

When it comes to analyzing advertising programs, the dashboard allows users to select any three metrics for analysis. These chosen metrics are then represented in a bubble chart in which they are mapped distinctly: one to the x-axis, another to the y-axis, and the third to the size of the bubbles. Additionally, trend graph analysis for individual advertising programs is also provided, similar to the one for advertising accounts.

### Development Process

The project involved the use of _Python, Requests, Dash, Plotly, PyMongo_ and _MongoDB_. Except for the Python language, all the other technologies used in this project were entirely new to me. To effectively manage the time constraint and tackle the challenges of mastering new technologies, I followed my mentor's advice and divided the project development process into three iterative phases:

In the initial phase, my focus was on building the Plotly Dash front-end data visualization and interactive analysis features using pre-prepared advertising data in JSON format files obtained from the ad platform's API. During this stage, I primarily focused on confirming interface and functional requirements which involved iterative testing and refinement of the Dash interface to guarantee that the data was accurately represented.

In the next phase, I transitioned from using static JSON files to directly connecting to the ad platform's API for dynamic data retrieval. This included work in API integration, ensuring that the system could accurately fetch and process data. By this point, I had a functional system that could be used in practice.

In the last phase, I specifically developed a module to fetch data from the advertising platform's API, processed the data, and stored it in MongoDB. The data visualization and analysis module then accessed this data from MongoDB. This change significantly improved data loading and analysis performance, and resolved the limitation of the API only allowing data retrieval for a maximum of 180 days.

The phased approach proved to be crucial for the project's success, enabling me to complete the entire system's development within the project's timeframe. At the halfway mark of the project,  I delivered a functional software version that could be used effectively, earning recognition and praise from both my mentor and the advertising team.
