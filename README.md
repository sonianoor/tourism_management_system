# tourism_management_system


Project Overview
The Tourism Management System is a web application designed to manage tourist attractions, visitors, and their reviews. It allows administrators to add, update, and delete tourist attractions, and lets visitors register, post reviews, and rate attractions. The system tracks the visitor's interaction with attractions, ensuring that visitors can only review an attraction they've visited.

Features
Attraction Management:
Add, update, and delete attractions with details such as name, location, entry fee, and rating.
Visitor Management:
Register new visitors with a unique email address and manage their visited attractions.
Review System:
Visitors can post reviews for attractions, including a rating (1-5) and optional comments.
The system ensures that visitors can only post reviews for attractions they've visited.
Attraction ratings are updated based on average scores from reviews.
Technologies Used
Backend: Node.js, Express
Database: MongoDB, Mongoose
API Routes: RESTful API routes for managing visitors, attractions, and reviews.
How It Works
Attraction Creation: Administrators can add a new attraction with necessary details (name, location, entry fee).
Visitor Registration: New visitors are registered with unique email addresses. Their visited attractions are tracked.
Review Posting: Visitors can post reviews for attractions they've visited. The review includes a score and an optional comment.
Rating Update: After a review is posted, the attraction's rating is updated based on the average score from all reviews.
Setup
Clone this repository.
Install dependencies: npm install.
Set up MongoDB and ensure it's running.
Run the server: node server.js.
Test the API using Postman or another HTTP client.
