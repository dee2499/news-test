# News Aggregator API

## Overview
The News Aggregator API is a Laravel-based RESTful API that aggregates articles from various news sources. It includes features for user authentication, article management, user preferences, and scheduled data aggregation from multiple news APIs.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Data Sources](#data-sources)
- [Installation](#installation)
- [Docker Setup](#docker-setup)
- [API Authentication](#api-authentication)
- [Testing](#testing)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Authentication**: 
  - Registration and login endpoints with Laravel Sanctum for API token management.
  - Password reset functionality.
  
- **Article Management**:
  - Fetch articles with pagination and search capabilities.
  - Retrieve detailed information about individual articles.
  
- **User Preferences**:
  - Manage user preferences for news sources, categories, and authors.
  - Personalized news feed based on user preferences.
  
- **Data Aggregation**:
  - Regularly fetch articles from multiple news APIs and store them locally.

## Requirements
- PHP >= 8.0
- Composer
- MySQL or compatible database
- Docker (optional for containerized setup)

## Data Sources
This API aggregates articles from the following sources:
1. [NewsAPI](https://newsapi.org)
2. [The Guardian](https://open-platform.theguardian.com/)
3. [The New York Times](https://developer.nytimes.com/)

*Note: Registration and API keys are required for accessing these APIs.*

## Installation
### Clone the Repository
```bash
git clone https://github.com/yourusername/news-aggregator-api.git
cd news-aggregator-api
