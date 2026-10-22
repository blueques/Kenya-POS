Kenya POS - Project Description
Kenya POS is a comprehensive Point of Sale (POS) system designed to be used in any retail environment.

Architecture
The project is built with a full-stack architecture:

Backend - Django REST Framework

Python-based API server using Django 4.2.11
RESTful API with JWT authentication (simplejwt)
CORS support for cross-origin requests
Rate limiting for API protection
Frontend - React with Vite

Modern React 18 UI built with Vite bundler
Styled with Tailwind CSS
State management using Zustand
Responsive components with Lucide icons
Core Features (by Module)
Accounts & Permissions - User authentication, authorization, and role-based access control
Inventory Management - Product stock tracking and management
Sales - Point of sale transactions and order processing
Customers - Customer management and profiles
Products - Product catalog and pricing
Payments - Payment processing with M-Pesa integration
Business - Business configuration and settings
Suppliers - Supplier management
Reports - Sales and business analytics
Audit - Transaction logging and audit trails
Key Technologies
Backend: Django, Django REST Framework, Python 3.x
Frontend: React, Vite, Tailwind CSS, React Router
Database: SQLite (with migrations support)
PDF Generation: jsPDF, html2canvas (for receipts/reports)
Payments: M-Pesa integration
Charts: Recharts for data visualization
Forms: React Hook Form for validation
The system is designed to handle retail operations with comprehensive features for inventory, sales, payments, and business analytics.

