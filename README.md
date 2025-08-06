# Titanic_Survey
TASK 1 - Data Cleaning & Feature Engineering

Handles missing values in Age and Embarked.

Converts data types (e.g., Age to integer).

Drops unhelpful or high-cardinality columns like Cabin, Name, and Ticket.

Adds meaningful features:

Title: Extracted from the passenger's name.

TicketPrefix: Extracted from the ticket string.

FamilySize: Total number of family members aboard.

Finalizes a cleaned version of the dataset for analysis.

TASK 2 – Exploratory Data Analysis (EDA)

Uses Seaborn and Matplotlib to visualize the cleaned dataset.

Charts included:

Count plots for Survived, Sex, and Pclass.

Histograms of Age and Fare with survival overlay.

Boxplots to identify outliers in Age and Fare.

Correlation heatmap to visualize relationships between numeric features.

Computes survival rates by Sex and Pclass.
