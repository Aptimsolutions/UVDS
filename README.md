# UVDS
UVDS- Leachate Basin Calculator
UVDS Leachate Basin Capacity
Welcome to the UVDS Leachate Basin Capacity web application. This README provides an overview of the site's functionalities, its purpose, and how to use it.

Table of Contents
Introduction
Features
How to Use
Technologies Used
Data Points & Interpolation
Further Development
License & Acknowledgments
1. Introduction
The UVDS Leachate Basin Capacity web application assists in calculating the cumulative volume and remaining capacity of a leachate basin based on a user-provided depth gauge reading. Accurate volume calculations are critical for basin management and this tool offers a simple interface to access that data.

2. Features
Depth Gauge Input: Accepts numerical inputs to represent the depth gauge reading of the leachate basin.
Cumulative Volume Calculation: Determines the volume of leachate that has accumulated based on the depth gauge reading.
Remaining Capacity Calculation: Determines how much more leachate the basin can accommodate.
Visual Representation: Provides a pie chart to visually compare used volume against remaining capacity.
Data Validation Reminder: Advises users to validate the provided data especially if there have been changes in basin structure or topography.
3. How to Use
Navigate to the UVDS Leachate Basin Capacity website.
Enter the depth gauge reading into the provided input field.
Click on the "Calculate" button.
The site will display the cumulative volume, both in cubic feet and gallons, as well as the remaining capacity in the same units.
For a visual representation, refer to the pie chart that breaks down the used volume and remaining capacity.
4. Technologies Used
HTML & CSS: For structuring and styling the web application.
JavaScript: For the site's interactivity and calculations.
Google Charts: To generate the pie chart visualization.
5. Data Points & Interpolation
The application uses pre-defined data points to represent cumulative volumes at specific depths. If a user's depth gauge reading falls between two data points, the application uses linear interpolation to estimate the cumulative volume.

6. Further Development
Future enhancements may include:

Automatic Data Retrieval: Integration with IoT devices to automatically fetch the latest depth gauge reading.
Historical Data: Providing a graph that shows historical depth readings and volume changes over time.
Alerts: Notifying users when the basin is nearing its capacity.
7. License & Acknowledgments
This project is licensed under the MIT License. Special thanks to the UVDS team for their support and collaboration.
