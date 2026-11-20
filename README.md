# 🍱 FoodShare – Food Donation Management Platform

### Donate Food. Reduce Waste. Feed Lives.

## 🌍 Project Overview

FoodShare is a web-based food donation management platform designed to reduce food wastage by connecting food donors with NGOs and people in need.

The platform provides a simple and user-friendly interface where restaurants, hotels, supermarkets, and individuals can share information about surplus food available for donation.

The primary goal of FoodShare is to encourage food redistribution, minimize food wastage, and make food donation more accessible to communities.

## 🌐 Live Demo

**Visit the deployed application:**

🔗 https://d38lq72pjxw0wy.cloudfront.net

## ✨ Key Features

- **Home Page:** Introduces the FoodShare platform and its mission.
- **Food Donation:** Provides an interface for sharing surplus food details.
- **Available Donations:** Displays food donation information.
- **Search and Filter:** Helps users explore food based on location and category.
- **Request Food:** Provides an interface for interacting with available donations.
- **Impact Section:** Highlights the importance of reducing food wastage.
- **Responsive Design:** Supports different screen sizes and devices.
- **About Section:** Explains the purpose and vision of the platform.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling and responsive design |
| JavaScript | Frontend functionality |
| Amazon S3 | Static website hosting and storage |
| Amazon CloudFront | Content delivery and distribution |

## ☁️ AWS Cloud Deployment

FoodShare is deployed using Amazon Web Services (AWS) to make the website accessible over the internet.

### AWS Services Used

**1. Amazon S3**
- Created an S3 bucket to store website files.
- Uploaded HTML, CSS, JavaScript, and other frontend assets.
- Used S3 as the website's static content origin.

**2. Amazon CloudFront**
- Created a CloudFront distribution.
- Configured the S3 bucket as the origin.
- Enabled content delivery through CloudFront.
- Generated a public CloudFront distribution URL.

### Deployment Architecture

```text
        User / Browser
              |
              v
       CloudFront CDN
              |
              v
          Amazon S3
              |
              v
      HTML, CSS, JavaScript
              |
              v
       FoodShare Website
```

### Deployment Information

| Configuration | Details |
|---|---|
| Hosting Service | Amazon S3 |
| CDN Service | Amazon CloudFront |
| Distribution ID | E2C8RMUXK2DUPY |
| Live Website | https://d38lq72pjxw0wy.cloudfront.net |
| Deployment Type | Static Website Hosting |

## 📂 Project Modules

1. **Home** – Introduction to the FoodShare platform.
2. **Donate Food** – Interface for providing surplus food details.
3. **Available Donations** – Displays available donation information.
4. **Search Food** – Helps users explore food donations.
5. **Impact** – Highlights the importance of food redistribution.
6. **About Us** – Provides information about the project.

## 🎯 Project Objectives

- Reduce food wastage through food donation.
- Connect food donors with NGOs and people in need.
- Encourage responsible food consumption.
- Promote community participation in food redistribution.
- Provide an accessible platform for food donation information.

## 📊 Results and Screenshots

### 1. Home Page

The homepage introduces FoodShare and highlights its mission to reduce food waste.

![FoodShare Homepage]("C:\Users\KUMUDHA\OneDrive\Documents\Attachments\เอกสาร\Pictures\Screenshots\homepage.png")

### 2. Food Donation Page

The donation page allows users to submit food donation details, including food category, quantity, pickup location and contact information.

![Food Donation Page]("C:\Users\KUMUDHA\OneDrive\Documents\Attachments\เอกสาร\Pictures\Screenshots\donation-page.png")

### 3. Available Food Listings

Users can explore available food donations, view quantities, locations and pickup details.

![Available Food Listings]("C:\Users\KUMUDHA\OneDrive\Documents\Attachments\เอกสาร\Pictures\Screenshots\available-food.png")

## 🚀 Future Enhancements

- User registration and authentication.
- Database integration for storing donation details.
- Real-time food donation requests.
- NGO and donor management dashboards.
- Location-based donor and recipient matching.
- Email and SMS notifications.
- Food donation history and analytics.

## 📌 Project Status

**Current Status: Frontend Development and AWS Deployment Completed**

The current implementation focuses on the frontend interface and cloud deployment using Amazon S3 and Amazon CloudFront.

Backend integration, database connectivity, and real-time donation management can be introduced in future development.

## 🌱 Expected Impact

FoodShare aims to create awareness about food wastage and encourage individuals and organizations to donate surplus food to people in need.

By making food donation information more accessible, the platform promotes sustainability, social responsibility, and a community-driven approach to reducing hunger.

---

## ❤️ Our Mission

**Donate Food. Reduce Waste. Feed Lives.**

Together, we can make a difference, one meal at a time.

