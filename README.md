## 🌦️ Weather Insights: Multi-City Weather Analytics Dashboard

A dynamic, interactive data visualization tool built to explore real-time and forecasted weather data across multiple cities — focusing on current conditions, forecast trends, air quality, and rain probability.

## Short Description / Purpose

The Weather Insights Dashboard is a visually engaging and analytical Power BI report designed to help users track and compare live weather conditions across cities like Lucknow, Mumbai, and Punjab Singhwala. The dashboard highlights key weather metrics such as temperature, humidity, wind speed, air quality, and sunrise/sunset timings. This tool is intended for use by weather enthusiasts, travel planners, and everyday users who want a quick, visual snapshot of current and upcoming weather conditions.

## Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Main data visualization platform used for report creation.
- 📂 **Power Query** – Data transformation and cleaning layer for reshaping and preparing weather data.
- 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures, dynamic cards, and conditional formatting.
- 📝 **Data Modeling** – Relationships established among Current, Forecast_day_data, Forecast_hour_data, and Locations tables to enable cross-filtering and city-based comparisons.
- 📁 **File Format** – .pbix for development and .png for dashboard previews.

## Data Source

Source: Weather API (real-time and forecast weather data feed).

Data on multiple cities including current temperature, "feels like" conditions, humidity, wind speed, visibility, pressure, UV index, precipitation, hourly/daily forecasts, air quality index (PM10, PM2.5, SO2, CO, O3, NO2), and chance-of-rain percentages by day.

## Features / Highlights

**Business Problem**
Weather information is often scattered across multiple apps and hard to compare across locations. Travelers, planners, and analysts often lack a single, intuitive view to compare current and forecasted conditions across cities. Questions such as:
- Which city currently has the best weather?
- How is the air quality trending?
- What is the chance of rain this week?
- When is sunrise/sunset for planning outdoor activities?

...are difficult to answer quickly without a consolidated view.

**Goal of the Dashboard**
To deliver an interactive visual tool that:
- Enables users to check live weather conditions across multiple cities at a glance.
- Supports quick decision-making for travel, outdoor planning, and daily routines.
- Uncovers trends in temperature, air quality, and rainfall probability over the week.

**Walkthrough of Key Visuals**

- **Current Weather Card (Top Left)** – Displays the selected city's live condition (e.g., Mist, 28.0°C), last updated time, and a quick city-switcher for comparing nearby locations (Lucknow, Mumbai, Punjab Singhwala).
- **7-Day Forecast Strip (Top Right)** – Small cards showing upcoming daily temperatures and general conditions (Fri, Mon, Sat, Sun, Thu, Tue, Wed).
- **Forecast Weather (Line Chart)** – Tracks temperature trend across the week, helping identify warming or cooling patterns.
- **Sunrise and Sunset Panel** – Displays daily sunrise and sunset timings for outdoor planning.
- **Quick Stats Tiles** – Visibility, Pressure, Humidity, Wind Speed, UV Index, and Precipitation shown as individual KPI cards for fast scanning.
- **Air Quality Index (Donut + Metrics)** – Visualizes PM10 as the central metric, with supporting pollutant levels (SO2, CO, O3, PM2.5, NO2) and an overall air quality status message.
- **Chance of Rain (Bar/Table Panel)** – Day-wise rain probability percentages with comparison indicators, helping users plan ahead for wet weather.

**Business Impact & Insights**
- **Travel Planning:** Users can instantly compare weather across cities before planning a trip.
- **Health & Safety:** Air quality metrics help sensitive groups plan outdoor exposure accordingly.
- **Daily Planning:** Sunrise/sunset and rain-chance data assist in scheduling outdoor activities.
- **Trend Awareness:** The forecast line chart highlights upcoming temperature shifts at a glance.

## Screenshots / Demos

Include a screenshot of the dashboard here showing the current weather card, forecast strip, air quality panel, and chance-of-rain section.
 ![Dashboard Preview](https://github.com/RudraPratapSingh10/Weather-Application-Dashboard-/blob/main/Dashboard.png)
