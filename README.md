# Cashbook Hive App

Cashbook Hive is a mobile application developed using Flutter, GetX, and Hive, designed to help users manage their daily spending. The app features a well-structured architecture and provides a seamless user experience with various functionalities.
## Video

[![Watch the video](https://img.youtube.com/vi/J4wfL755pDU/0.jpg)](https://www.youtube.com/watch?v=J4wfL755pDU)

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Screenshots](#screenshots)
6. [License](#license)
7. [Contributing](#contributing)
8. [Contact](#contact)

## Overview

Cashbook Hive allows users to save their daily spending amounts with detailed notes and categories. The app supports multiple languages, themes, and currency settings, providing a personalized user experience. It leverages GetX for state management, routing, dependency injection, and localization, and uses Hive for local database management.

## Features

- **Home Page**:
  - Form to add cash amount, note, and category with validation.
  - Display of the last added amount with date and all details.
- **Repository Architecture**: 
  - All Hive requests and local database interactions are handled using a repository pattern.
- **Settings Page**:
  - Language selection (Arabic and English).
  - Theme selection (Dark and Light).
  - Currency change.
- **Categories and Archive Page**:
  - Display all amounts separated by dates with pagination.
- **Report Page**:
  - Generate visual reports based on date, keywords, and categories.
- **Import and Export**:
  - Import and export all amounts using `file_picker` and `path_provider`.
- **GetX Ecosystem**:
  - Bindings, routing, `GetxService`, dependency injection, localization, state management, and middleware.

