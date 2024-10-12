# Gadgets Hub

## Overview

Gadgets Hub is a console-based application designed to simulate an online store for various electronic devices, including mobile phones, laptops, iPads, and smartwatches. The application utilizes object-oriented programming principles to manage different product categories and their respective details.

## Features

- **Product Categories**: Users can browse different categories of gadgets:
  - Mobile Phones
  - Laptops
  - iPads
  - Smart Watches

- **Customer Range Products**: Users can filter products based on their budget, allowing them to view options within their price range.

- **Class Structure**: Each category is managed through separate classes, allowing for modularity and easy maintenance.

- **User Interaction**: The application prompts users to select a product category they are interested in.

- **Discounts**: 
  - **Student Discounts**: Registered students can receive discounts on their purchases.
  - **Referral Discounts**: Users can earn discounts by referring friends who make a purchase.

## Class Structure

### 1. Product (Base Class)

- **Purpose**: A base class to represent a general product with common attributes and methods.

### 2. MobilePhone

- **Purpose**: Inherits from `Product` and represents mobile phone-specific details.
- **Attributes**: Brand, model, price, specifications.

### 3. Laptop

- **Purpose**: Inherits from `Product` and represents laptop-specific details.
- **Attributes**: Brand, model, price, specifications.

### 4. iPad

- **Purpose**: Inherits from `Product` and represents iPad-specific details.
- **Attributes**: Brand, model, price, specifications.

### 5. SmartWatch

- **Purpose**: Inherits from `Product` and represents smartwatch-specific details.
- **Attributes**: Brand, model, price, specifications.

### 6. Discounts

- **StudentDiscount**: Class that manages student eligibility and discount calculations.
- **ReferralDiscount**: Class that handles referral codes and discounts for users.

### 7. CustomerRange

- **Purpose**: Class that allows users to specify their budget and view products within that price range.

## Installation

1. Ensure you have a C++ compiler installed (e.g., g++, clang).
2. Clone or download the project files.
3. Navigate to the directory containing the source files.

## Compilation and Execution

To compile and run the application:

```bash
g++ -o gadgets_hub main.cpp
./gadgets_hub
