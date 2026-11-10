# Uber Ride Booking & Revenue Analytics Dashboard

An interactive Power BI dashboard built to explore Uber ride-booking
performance, revenue, vehicle categories, trip distance, booking
outcomes, and customer ratings.

The dashboard brings key business information into one place. Users can
review overall performance, compare vehicle categories, follow monthly
trends, and explore booking and customer patterns through interactive
report pages.

## Project Overview

This project focuses on analysing ride-booking data and presenting it in
a clear, easy-to-understand format. It includes a landing page, an
overview dashboard, and a detailed revenue analysis page.

The dashboard is intended to support business reviews and data-driven
decisions. It does not create or manage ride bookings; it is an
analytics and reporting solution.

## Dashboard Pages

### 1. Landing Page

-   Displays the Uber dashboard identity.
-   Provides navigation to the Overview and Revenue sections.

### 2. Overview Page

-   Shows headline performance indicators.
-   Presents the distribution of booking statuses.
-   Tracks monthly business performance.
-   Provides a vehicle-wise performance summary.
-   Includes vehicle-category selection.

### 3. Detailed Analysis Page

-   Shows monthly completed-booking trends.
-   Compares revenue across vehicle categories.
-   Highlights frequent pickup and drop locations.
-   Displays cancelled ride information.
-   Presents monthly revenue distribution.
-   Compares customer rating information across vehicle categories.

## Key Metrics and Analysis

The dashboard includes the following measures and views:

-   **Revenue** -- Revenue generated from eligible bookings.
-   **Total Distance** -- Total distance covered by eligible completed
    trips.
-   **Completed Bookings** -- Number of bookings with completed status.
-   **Average Distance** -- Average trip distance based on the selected
    calculation.
-   **Lost Bookings** -- Bookings classified as lost under the reporting
    rules.
-   **Booking Status** -- Breakdown of completed, driver-cancelled,
    customer-cancelled, no-driver-found, and incomplete bookings.
-   **Revenue by Vehicle Type** -- Revenue comparison across vehicle
    categories.
-   **Frequent Pickup and Drop Locations** -- Most frequently used
    pickup and drop locations.
-   **Cancelled Rides** -- Count of bookings classified as cancelled.
-   **Customer Ratings** -- Rating-related analysis by vehicle category.

The exact definitions of some measures, such as lost bookings and
customer ratings, depend on the dataset and the business rules used in
the report.

## Vehicle Categories

The dashboard supports analysis across these six vehicle categories:

-   Auto
-   Bike
-   Go Sedan
-   Go Mini
-   Premier Sedan
-   Uber XL

## Interactive Features

-   Navigation between the landing, overview, and detailed analysis
    pages.
-   Vehicle-category selection.
-   Monthly and category-based analysis.
-   Cross-filtering and visual highlighting where supported by the
    report.
-   Tooltips and chart selections to explore values in more detail.

## Tools and Technologies

-   **Microsoft Power BI** -- Dashboard creation and data visualization.
-   **DAX** -- Measures and key performance indicator calculations.
-   **Power Query** -- Data preparation and transformation, where used.

## Business Value

The dashboard helps users:

-   Monitor ride-booking and revenue performance.
-   Understand booking completion and cancellation patterns.
-   Compare revenue and operational measures across vehicle categories.
-   Identify frequently used pickup and drop locations.
-   Review monthly changes and customer rating patterns.
-   Use a consolidated view of business performance to support
    decisions.

## How to View the Project

1.  Clone or download this repository.
2.  If the Power BI report (`.pbix`) is included, open it in Power BI
    Desktop.
3.  Navigate between the Overview and Revenue pages.
4.  Use the available vehicle selections and report interactions to
    explore the data.

## Notes

The dashboard values shown in the report are calculated from its
connected dataset and measures. Metric definitions, currency, distance
units, and treatment of booking statuses should be interpreted according
to the report's data model and agreed business rules.

This project is an analytical dashboard only. Ride creation, payment
processing, live vehicle tracking, driver management, and customer
account management are outside its scope.
