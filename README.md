# Mental-Health-Dashboard
A dashboard built using the D3 Framework that provides a visual &amp; interactive breakdown of mental health data. 
An interactive data visualization dashboard that analyzes student mental health data using D3.js. This dashboard provides comprehensive insights into the relationship between student demographics, academic performance, and mental health conditions.

# Interactive Visualizations
Bar Chart: Overview of reported mental health issues (Depression, Anxiety, Panic Attacks, None)
Scatter Plot: CGPA vs Age visualization, colored by anxiety status
Parallel Coordinates: Multi-dimensional view of Gender → CGPA → Age → Anxiety relationships

# Interactive Features
Click-to-Filter: Click on any bar in the overview chart to filter all visualizations
Brush Selection: Drag to select points in the scatter plot for detailed analysis
Coordinated Views: All visualizations update simultaneously based on selections
Reset Functionality: Easy reset options for brush selections

# Visual Design
Clean, modern interface with responsive design
Color-coded data points for easy pattern recognition
Smooth transitions and animations
Intuitive hover effects and visual feedback

# Dataset
The dashboard analyzes a dataset of 101 student responses with the following attributes:
Demographics: Gender, Age, Marital Status
Academic: Course, Year of Study, CGPA
Mental Health: Depression, Anxiety, Panic Attacks
Treatment: Specialist consultation status

# Technology Stack
D3.js v5: Data visualization and DOM manipulation
HTML5: Structure and layout
CSS3: Styling and responsive design
JavaScript ES6: Interactive functionality

# Usage Guide
Explore Overview: Start by examining the bar chart showing the distribution of mental health conditions
Filter by Condition: Click on any bar to filter all visualizations by that condition
Brush Selection: Drag across the scatter plot to select specific data points
Analyze Patterns: Use the parallel coordinates to identify multi-dimensional relationships

# Advanced Features
Multiple Filters: Combine bar chart selection with brush selection for detailed analysis
Reset Views: Use the "Reset Brush" button to clear scatter plot selections
Deselect Conditions: Click on a selected bar again to remove the filter

# Key Insights
The dashboard reveals several interesting patterns:
Anxiety Prevalence: Most common mental health condition among students
Academic Performance: Relationship between CGPA and mental health status
Age Factors: Distribution of conditions across different age groups
Gender Patterns: Mental health trends by gender

# Technical Implementation
Data Processing
CGPA Normalization: Converts CGPA ranges to midpoint values for numerical analysis
Data Validation: Filters out invalid entries and standardizes categorical data
Real-time Updates: Efficient data filtering and view updates

# Visualization Techniques
Coordinated Multiple Views: All charts update simultaneously
Smooth Transitions: D3.js animations for better user experience
Responsive Design: Scales appropriately across different screen sizes

# Future Enhancements
Add more visualization types (histograms, box plots)
Include additional demographic filters
Export functionality for filtered data
Mobile-responsive design improvements
Statistical analysis features

# Acknowledgments

Dataset source: Student Mental Health Survey found on Kaggle
Built with D3.js
Inspired by modern data visualization best practices learned in ECS 163
