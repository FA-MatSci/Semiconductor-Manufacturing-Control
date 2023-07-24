# Semiconductor-Manufacturing-Control
Data analytics project on semiconductor wafer processing

# Application Process Control
# Introduction
In this project, I created a Python script that imports large data sets, performs analysis and graphically illustrates the outcomes. Data used is from PVD (physical vapour deposition) tools that are used for semiconductor fabrication. Since this is a constant (24/7) process, it generates large amounts of data that cannot be analysed without employing suitable approaches (python). Information obtained from such analysis may reduce quality deviations, wafers scraps and achieving stable processes (Six Sigma).  

# Background
High-volume semiconductor fabrication is a complex and well optimised process. It consists of various processing steps where wafers undergo treatment in different tools. During processing, many process control limits (application process control) exist that should or must not be violated. However, since this is 24/7 production, limit violation occurs frequently and thus generates big data. Collected data may contain valuable time series patterns that are hardly visible without employing suitable approaches. On the other hand, it inevitably includes noise. Therefore, techniques that can extract and identify valuable trends should be employed.

# Data
The project is based on a database from a high-volume semiconductor fabrication plant. Data used was obtained from different types and providers of PVD tools during their operation. It includes useful information, in addition to noise from different stages of wafer processing. Since considerable amount of collected data is not relevant to the scope of the study, it had to be removed (data cleaning). An example of a dataset is included in the repository.

# Breakdown of the Script
The script is written in Python by employing libraries, for example pandas, NumPy or Matplotlib (visualization). At the beginning, a data file is imported, following by the user input of a tool/chamber of interest and start/end date. 
In order to remove unnecessary data within a dataset, various approaches are implemented (if statements, date conversions, generator function, nested for loops, while loops, exception handling, etc.) Finally, after performing data cleaning, results are visualized using different chart types.

# Dataset Example
In the dataset example that is provided, rows that contain possible sensitive information have been removed and labelled as x. The actual data file would contain information about process deviations and can be over 250 000 rows large. 

# Generated Images
The outcome of the script is graphical representation of process data that was generated during wafer processing at PVD tools. It should be noted that potential sensitive information, for instance type of violations, recipe names, tool numbers are not displayed (covered).
