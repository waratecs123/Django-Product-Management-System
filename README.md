# Django Product Management System

![Django](https://img.shields.io/badge/Django-5.2-green)
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![SQLite](https://img.shields.io/badge/SQLite-3-lightgrey)

A comprehensive product management system built with Django that allows CRUD operations for products with category organization, filtering, and pagination.

## Features

- **Product Management**:
  - Create, Read, Update, Delete (CRUD) operations
  - Category organization
  - Price and quantity tracking
- **Advanced Filtering**:
  - Custom product filtering system
  - Search functionality
- **Pagination**:
  - Built-in pagination for product lists
  - Custom URL handling for pagination
- **Form Validation**:
  - Minimum length requirements
  - Unique name validation
  - Price/quantity non-negative validation
- **Admin Interface**:
  - Ready-to-use Django admin panel
  - Direct model management

## Technologies Used

- **Backend**: Django 5.2
- **Frontend**: Django Templates
- **Database**: SQLite (production-ready databases supported)
- **Additional Packages**:
  - django-filters for product filtering
  - Custom template tags and filters

## Installation

### Prerequisites
- Python 3.8+
- pip package manager

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/django-product-system.git
   cd django-product-system
