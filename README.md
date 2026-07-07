<img width="1884" height="875" alt="image" src="https://github.com/architCGI/lws-assignment/blob/redesign-ui/Screenshot%202026-07-08%20011931.png" />

# Personal Portfolio using Lightning Web Components

## Overview

This project is a personal portfolio application built on the Salesforce Platform using Lightning Web Components (LWC) and Apex.

The portfolio displays information dynamically from a Salesforce Account record, ensuring that all content is data-driven and configurable without modifying the component code.

---

## Objective

Create a portfolio page that:

- Displays personal and professional information
- Retrieves data from a Salesforce Account record
- Uses Apex for server-side data access
- Uses Lightning Web Components for presentation
- Can be embedded on a Salesforce Home Page
- Avoids hardcoded portfolio details

---

## Features

### Profile Section
Displays:

- Name
- Professional Title
- Profile Initials

### About Me
Displays a brief professional introduction from the Account Description field.

### Domain Information
Displays the area of expertise using the Account Industry field.

### Contact Information
Displays:

- Phone Number
- Portfolio / Website Link

### Responsive Design
The layout is designed to adapt to different screen sizes while maintaining readability and usability.

---

## Technical Implementation

### Frontend

- Lightning Web Components (LWC)
- HTML
- CSS
- JavaScript

### Backend

- Apex Controller
- SOQL Query

### Salesforce Services

- Lightning App Builder
- Home Page Configuration
- Account Object

---

## Data Flow

```text
Account Record
      │
      ▼
PortfolioController (Apex)
      │
      ▼
myPortfolio (LWC)
      │
      ▼
Salesforce Home Page
