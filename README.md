# 🏠 Airbnb Analytics: Power BI Dashboard

An interactive **Power BI dashboard** designed to analyze Airbnb listing, host, pricing, rating, and review data. The project transforms raw Airbnb data into meaningful business insights through data cleaning, data modeling, DAX calculations, interactive visualizations, and analytical reporting.

---

## 📌 Short Description / Purpose

The **Airbnb Analytics Dashboard** is an interactive Power BI project developed to explore Airbnb listings and understand important patterns related to hosts, properties, cities, pricing, ratings, Superhost performance, and customer reviews.

The dashboard enables users to explore Airbnb data through multiple analytical pages and helps identify trends that may influence listing performance, pricing decisions, host performance, and customer experience.

---

## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

* 📊 **Power BI Desktop** – Used to design and develop the interactive dashboard.
* 📂 **Power Query** – Used for data cleaning, transformation, and preparation.
* 🧠 **DAX (Data Analysis Expressions)** – Used to create calculated measures, KPIs, percentages, averages, and cumulative calculations.
* 🔗 **Data Modeling** – Used to establish relationships between tables and enable accurate filtering and analysis.
* 📈 **Data Visualization** – Cards, line charts, bar charts, column charts, combo charts, matrices, and other interactive visuals were used.
* 🎛️ **Interactive Filtering** – Used to allow dynamic analysis of the Airbnb dataset.
* 🎨 **Dashboard Design** – Custom layouts, icons, images, shapes, and formatting were used to improve dashboard usability and presentation.
* 📁 **File Format** – `.pbix` for Power BI dashboard development.

---

## 📂 Data Source

The project uses an **Airbnb dataset** containing information related to listings, hosts, properties, locations, ratings, prices, and reviews.

The dataset includes fields such as:

* Listing ID
* Host ID
* Host joining date
* City
* Property type
* Room type
* Pricing information
* Reviewer information
* Ratings
* Cleanliness
* Accuracy
* Communication
* Location
* Superhost status
* Profile verification
* Review information

The raw data was cleaned and transformed using **Power Query** before being used for analysis and dashboard creation.

---

# ✨ Features / Highlights

## 💼 Business Problem

Airbnb contains a large amount of information about properties, hosts, prices, ratings, and customer reviews.

Analyzing this information directly from raw tables makes it difficult to quickly answer important questions such as:

* Which cities have the highest number of Airbnb listings?
* What types of properties are commonly listed?
* Which room types have higher average prices?
* How do ratings vary across different cities?
* How do Superhost listings compare with regular listings?
* How frequently do customers leave reviews?
* What percentage of reviewers have verified profiles?
* How has the number of Airbnb listings changed over time?

A visual analytical dashboard makes these patterns easier to understand.

---

## 🎯 Goal of the Dashboard

The main goal of this project is to create an interactive analytical solution that:

* Provides an overview of Airbnb listings and hosts.
* Analyzes listing growth over time.
* Compares ratings across cities.
* Examines Airbnb pricing across different room types.
* Compares Superhost and non-Superhost listings.
* Studies customer review frequency.
* Analyzes reviewer profile verification.
* Converts Airbnb data into useful and understandable business insights.

---

# 📊 Dashboard Walkthrough

The Power BI report contains **3 main dashboard pages**:

## 1️⃣ Overview

The **Overview page** provides a high-level summary of the Airbnb dataset.

### Key KPI Cards

The page contains KPI cards highlighting important information such as:

* 🏠 Total Listings
* 👤 Total Hosts
* 🏢 Property Types
* 🌆 Cities
* ⭐ Reviewers

### Airbnb Listings Over Time

A **line chart** analyzes the growth and variation of Airbnb listings based on the host joining period.

It also allows comparison between different accommodation/property categories such as:

* Entire Place
* Hotel Room
* Private Room
* Shared Room

This visual helps understand how Airbnb listings and accommodation preferences have changed over time.

---

## 2️⃣ Ratings

The **Ratings page** focuses on customer ratings, pricing, and host performance.

### ⭐ Ratings by City

A column chart compares the **Average Rating across different cities**, helping identify locations with stronger customer satisfaction.

### 📋 Rating Categories

A matrix-style visual analyzes different rating components such as:

* Accuracy
* Cleanliness
* Communication
* Location

This helps understand which aspects of Airbnb stays receive stronger or weaker ratings.

### 💰 Average Price by Room Type

A bar chart compares the **Average Price** for different Airbnb room types.

This makes it easier to understand how accommodation type affects pricing.

### 🏅 Superhost vs Non-Superhost Listings

A combination chart compares:

* Superhost Listings
* Non-Superhost Listings
* Cumulative Percentage

This provides insight into the distribution of Superhosts across different cities.

---

## 3️⃣ Reviews

The **Reviews page** provides deeper analysis of Airbnb customer reviews and reviewer behaviour.

### 📈 Review Frequency Analysis

A combination chart analyzes:

* Number of Reviewers
* Reviews per Reviewer
* Cumulative Review Frequency %

This helps identify how frequently Airbnb customers leave reviews and how review activity is distributed.

### ✅ Reviewer Profile Verification

The dashboard also contains KPI calculations showing different combinations of reviewer verification and profile availability, including:

* Verified users with profiles
* Verified users without profiles
* Non-verified users with profiles
* Non-verified users without profiles

These metrics help understand the reliability and profile-completion behaviour of Airbnb reviewers.

---

# 🧠 Power BI Concepts Applied

This project allowed me to practically apply a wide range of Power BI concepts, including:

* Data Importing
* Data Cleaning
* Data Transformation
* Power Query Editor
* Data Type Management
* Data Modeling
* Table Relationships
* DAX Measures
* Calculated Measures
* Average Calculations
* Percentage Calculations
* Cumulative Percentage Calculations
* KPI Cards
* Line Charts
* Bar Charts
* Column Charts
* Combo Charts
* Matrix/Table Visualizations
* Interactive Filtering
* Cross Filtering
* Visual Formatting
* Dashboard Navigation
* Custom Images and Icons
* Shapes and UI Elements
* Report Page Designing
* Business Insight Generation

---

# 💡 Business Insights & Impact

### 🏠 Listing Analysis

The dashboard allows Airbnb listings to be analyzed across locations, property types, and accommodation categories, helping users understand the overall composition of the marketplace.

### 💰 Pricing Analysis

Average pricing by room type can help identify premium accommodation categories and understand how different types of Airbnb properties are positioned.

### ⭐ Customer Satisfaction

City-level ratings and individual rating categories help identify locations with stronger customer experiences and areas where service improvements may be required.

### 🏅 Host Performance

Comparison between Superhost and non-Superhost listings provides insight into host quality and the distribution of high-performing Airbnb hosts.

### 📝 Customer Behaviour

Review-frequency analysis helps understand how actively Airbnb customers provide feedback after their stays.

### ✅ Reviewer Reliability

Profile-verification analysis provides another perspective on reviewer credibility and user profile completion.

---

# 🚀 How to Use the Project

1. Download or clone this repository.
2. Download the `.pbix` dashboard file.
3. Open the file using **Microsoft Power BI Desktop**.
4. Navigate through the **Overview, Ratings, and Reviews** pages.
5. Interact with the dashboard visuals and filters to explore the data.

---

# 🎓 Project Learning

This project was created as part of my hands-on Power BI learning journey with the help of a YouTube tutorial.

While building the project, I practiced and implemented the complete Power BI workflow, including **data preparation, Power Query transformations, data modeling, DAX calculations, visualization, interactive reporting, and dashboard design**.

The project helped strengthen my practical understanding of transforming raw data into meaningful business insights using Power BI.

---

# 📌 Note

This project was created for **learning and portfolio purposes**. The dashboard implementation was completed while following and learning from a YouTube tutorial, with the objective of gaining practical experience using Power BI.

---

