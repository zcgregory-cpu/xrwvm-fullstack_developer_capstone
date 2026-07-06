# xrwvm-fullstack_developer_capstone

## Project Name: Best Cars Dealership - Car Dealership Reviews Website

This repository contains the Full Stack Application Development Capstone
Project for the IBM Full Stack Software Developer Professional Certificate.

**Repository name:** `xrwvm-fullstack_developer_capstone`

**Project name:** Best Cars Dealership Reviews Portal

Best Cars Dealership is a national car dealership with branches across the
United States. This web application provides a centralized portal where
customers can:

- View all dealership branches and filter them by state
- Read dealership reviews with automatic sentiment analysis
  (positive / neutral / negative)
- Register and log in to post their own reviews, including purchase
  details such as purchase date, car make, car model, and car year

## Technology Stack

- **Frontend:** HTML, CSS, Bootstrap, React
- **Backend:** Django (Python), Node.js + Express + MongoDB microservice
- **Sentiment Analysis:** Flask + NLTK microservice
- **DevOps:** Docker, GitHub Actions CI, cloud deployment

## Structure

- `server/djangoproj` - Django project
- `server/djangoapp` - Django application (users, cars, review proxy APIs)
- `server/frontend` - React frontend and static pages
- `server/database` - Node.js / Express / MongoDB dealerships and reviews API
- `server/djangoapp/microservices` - Flask sentiment analyzer
