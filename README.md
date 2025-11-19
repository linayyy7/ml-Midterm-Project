# ✈️ Airline Passenger Satisfaction Prediction

## 🎯 Project Overview

This project predicts airline passenger satisfaction using machine learning. By analyzing flight details and service ratings, we can identify dissatisfied passengers proactively and help airlines improve customer experience.

**Business Impact**: 5% improvement in customer retention can increase profits by 25-95%

## 📊 Problem Description

### The Challenge
Airlines struggle with:
- ❌ **Reactive approach** to customer complaints
- 📉 **High customer churn** from poor experiences  
- 💸 **Revenue loss** from dissatisfied passengers
- 🔍 **Limited insights** into service improvement priorities

### Our Solution
A machine learning model that:
- ✅ **Predicts satisfaction** using flight and service data
- 🎯 **Identifies key drivers** of passenger happiness
- 🛎️ **Enables proactive service** recovery
- 📈 **Guides strategic improvements**

## 📊 Dataset

**Gender**: Gender of the passengers (Female, Male)

**Customer Type**: The customer type (Loyal customer, disloyal customer)

**Age**: The actual age of the passengers

**Type of Travel**: Purpose of the flight of the passengers (Personal Travel, Business Travel)

**Class**: Travel class in the plane of the passengers (Business, Eco, Eco Plus)

**Flight distance**: The flight distance of this journey

**Inflight wifi service**: Satisfaction level of the inflight wifi service (0:Not Applicable;1-5)

**Departure/Arrival time convenient**: Satisfaction level of Departure/Arrival time convenient

**Ease of Online booking**: Satisfaction level of online booking

**Gate location**: Satisfaction level of Gate location

**Food and drink**: Satisfaction level of Food and drink

**Online boarding**: Satisfaction level of online boarding

**Seat comfort**: Satisfaction level of Seat comfort

**Inflight entertainment**: Satisfaction level of inflight entertainment

**On-board service**: Satisfaction level of On-board service

**Leg room service**: Satisfaction level of Leg room service

**Baggage handling**: Satisfaction level of baggage handling

**Check-in service**: Satisfaction level of Check-in service

**Inflight service**: Satisfaction level of inflight service

**Cleanliness**: Satisfaction level of Cleanliness

**Departure Delay in Minutes**: Minutes delayed when departure

**Arrival Delay in Minutes**: Minutes delayed when Arrival

**Satisfaction**: Airline satisfaction level(Satisfaction, neutral or dissatisfaction)

*Note that this data set was modified from this dataset by John D here. It has been cleaned up for the purposes of classification.*

## 🏗️ Model Approach

### Problem Type
**Binary Classification**: Predicting "satisfied" vs "neutral or dissatisfied"

### Key Features Used
- **Passenger Profile**: Age, Customer Type, Travel Purpose
- **Flight Details**: Class, Distance, Delays  
- **Service Ratings**: 14 aspects rated 1-5 (WiFi, Comfort, Food, etc.)

### Algorithms
- Random Forest Classifier
- Gradient Boosting
- Logistic Regression

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Docker (optional)

### Installation
```bash
# Install dependencies
pip install -r requirements.txt
