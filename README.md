 Project Description

This project is a Local Rental Website developed as a Graduation Project using Laravel.
The platform connects lenders and customers, providing a secure rental workflow with real-time availability management, online payments, and an admin dashboard.

The system ensures that once an item is requested by a customer, it becomes unavailable to others until the booking is confirmed or expires.

 Project Objectives

Build a real-world rental platform

Implement role-based authentication & authorization

Design a secure rental workflow

Integrate online payments using Stripe

Apply background jobs for automated system tasks

Deploy the system to a production environment

 User Roles
--> Admin

Manage users (lenders & customers)

Manage items and categories

Monitor rentals 

View system analytics

--> Lender

Add and manage rental items

Approve or reject rental requests

Track rental history

--> Customer

Browse available items

Request rentals

Complete payments

View current and previous rentals

--> Authentication & Authorization

Secure authentication system

Role-based access control:

Admin

Lender

Customer

Each role has restricted access to specific features

--> Rental Workflow

Customer sends a rental request

Item status changes to Locked (not available to other customers)

Lender approves the request

Customer completes payment via Stripe

Item status becomes Rented

After rental period ends:

Background Job automatically changes status to Available

--> Background Jobs & Scheduling

Jobs handle:

Rental expiration

Automatic item availability reset

Implemented using Laravel Queue & Scheduler

--> REST API

Fully implemented RESTful API

Used for:

Authentication

Items & categories

Rental requests

Payments

Ready for frontend or mobile applications

--> Payment System

Stripe payment gateway integration

Secure checkout

Payment confirmation and tracking

--> Technologies Used

Backend: Laravel 10

Frontend: React 

Authentication: Role-based Auth

API: RESTful API

Payments: Stripe

Database: MySQL

Jobs: Laravel Queue & Scheduler

Hosting: Hostinger

⚡ Installation & Setup
git clone https://github.com/username/local_rental.git
cd local_rental
composer install
npm install
npm run dev

Environment Configuration

Create .env file

Configure:

Database credentials

Stripe keys (STRIPE_KEY, STRIPE_SECRET)

php artisan migrate --seed
php artisan serve

 Deployment

Deployed on Hostinger

Configured for production environment



Academic Information

Project Type: Graduation Project

Field: Web Development

Technology Stack: React & Laravel & REST API

Purpose: Apply real-world backend concepts in a production-ready system

📝 License

This project is licensed under the MIT License.
