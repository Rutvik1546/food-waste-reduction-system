# food-waste-reduction-system
1. Project Title: Local Food Waste Reduction System

2. Project Overview:
        The Local Food Waste Reduction System is a web-based application developed using PHP with MVC (Model-View-Controller) architecture to reduce food waste and promote community welfare. The system serves as a bridge between donors — such as restaurants, grocery stores, and households with surplus food — and receivers, including NGOs, shelters, and individuals in need. By enabling donors to share excess food before it spoils, the system helps minimize food wastage and supports hunger relief efforts.

The application allows users to register, log in, list food items, request donations, and manage transactions through an interactive interface. The target audience includes restaurants, households, NGOs, and local community members who wish to contribute to food redistribution in their area.

3. Project Objectives:
	To develop a user-friendly and responsive web application for local food sharing.
	To implement MVC architecture for better code organization and scalability.
	To establish a secure authentication system for donors and receivers.
	To provide efficient CRUD functionalities for managing food listings, users, and requests.
	To reduce food waste by connecting food donors with receivers in real time.
	To promote environmental sustainability and social responsibility through technology.

4. Project Scope:
  1. Authentication Module
  	User Registration (Signup): Donors and receivers can create accounts.
  	User Authentication (Sign in): Secure login with session management.
  	Change Password: Users can update passwords after logging in.
  	Forgot Password: Allows password recovery via email.
  	Profile Management: Edit or update personal and organization details.

  2. User Management – User CRUD
  	User Listing: Admin can view all registered users with search and pagination.
  	Create/Save User: Add new users manually (for admin).
  	Edit/Update User: Modify existing user information.
  	Delete/Remove User: Remove inactive or fake users.

  3. Food Management – Food CRUD
  	Add Food Item: Donors can upload food details (name, quantity, expiry, location).
  	View Food Listings: Receivers can browse available food items.
  	Update Food Info: Donors can edit or mark food as unavailable.
  	Delete Food Item: Remove expired or already-donated items.

  4. Request Management – Request CRUD
  	Create Request: Receivers can request available food.
  	Update Request: Donors can approve or reject requests.
  	View Requests: Admin and donors can monitor active and completed requests.
  	Delete Request: Remove old or canceled requests.

  5. Admin Panel
  	Manage users, food listings, and requests.
  	View system statistics (total donations, active users, food saved).
  	Maintain data authenticity and prevent duplication.

  6. Frontend (End User Interface)
  	Responsive and interactive interface using HTML5, CSS3, Bootstrap, and JavaScript.
  	Separate dashboards for Donors, Receivers, and Admin.
  	Easy navigation for food listings, requests, and profile updates.



5. Notification System:
  The system includes an email-based notification feature to keep users informed about important updates. Receivers get notified when their food requests are accepted, and donors receive alerts for new requests. Admins are notified of new user registrations and donation activities, ensuring smooth and interactive communication among all participants.

Technologies Used:
	Frontend: HTML5, CSS3, Bootstrap, JavaScript
	Backend: PHP (MVC Architecture)
	Database: MySQL
	Server: Apache (XAMPP)
