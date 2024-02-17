# CodeAvengers
AI Fusion Competition Repo

Team Members:
Sanskar Shree
Akshit Rana
Faiz
Isha Tyagi 
Students of Hindu College of Engineering, Sonipat

# Drone Delivery System for Medical Supplies

## Overview

This project aims to develop a drone delivery system for efficiently delivering medical supplies to war-hit areas. The system includes a web application for user interaction, an AI-based pharmacy recommender for recommending medicines, and an AI model for green cover identification and drone path planning.

## Features

- **Mobile Application:**
  - Users can log in to the system, including government officials, charity foundations, and individuals.
  - Delivery of medical supplies is facilitated through an intuitive Google Maps interface.
  - Users can select delivery locations via GPS coordinates or by clicking on the map.

- **AI-Based Pharmacy Recommender:**
  - Recommends medicines based on the severity and type of attack in the specified area.
  - Utilizes a RandomForestClassifier trained on a dataset of severity levels and corresponding medicines.

- **Green Cover Identification:**
  - Employs a PyTorch-based model for semantic segmentation (DeepLabV3) to identify green cover.
  - Provides valuable information for safe drone landing spots.

- **Drone Path Planning:**
  - Utilizes an AI model for path planning that avoids areas with a high risk of drone attacks.
  - Incorporates real-time data and potential threats for dynamic adjustments to the delivery route.

## Usage

1. **Clone the Repository:**

   https://github.com/akshitrana7/CodeAvengers


python app.py
How to Contribute
If you would like to contribute to the project, follow these steps:

Fork the repository.
Create a new branch for your feature: git checkout -b feature-name.
Make your changes and commit them: git commit -m 'Add feature-name'.
Push to the branch: git push origin feature-name.
Submit a pull request.
License
This project is licensed under the MIT License.

Acknowledgments
Thanks to Google Maps API for providing mapping functionality.
The PyTorch team for the DeepLabV3 model.
Feel free to reach out for any questions or collaboration opportunities.

