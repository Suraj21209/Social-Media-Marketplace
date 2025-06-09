# Social Media Marketplace

## Overview
Social Media Marketplace is a comprehensive Django-based platform that combines social media features with e-commerce functionality. It provides a secure authentication system, user profiles, social networking capabilities, and marketplace features all in one integrated platform.

## Features

### Authentication & User Management
- **Dual-access system**: Separate user and admin access points
- **Secure registration and login**: Email verification with OTP
- **Profile management**: Update profile pictures and usernames
- **Admin dashboard**: Comprehensive user management and reporting system

### Social Features
- **Friend requests**: Send, accept, and manage friend connections
- **Messaging system**: Private messaging between users
- **Group chats**: Create and participate in group conversations
- **Posts and comments**: Create, edit, and delete posts with commenting functionality
- **User interactions**: Save posts, follow users, and view personalized content
- **Search functionality**: Find users across the platform

### Marketplace Features
- **Buy and sell**: Purchase digital or physical items posted by other users
- **Wallet system**: Add funds and track transactions
- **Transaction verification**: OTP verification for secure purchases
- **Purchase history**: Track all your bought items

### Safety and Moderation
- **User blocking**: Block unwanted interactions from specific users
- **Reporting system**: Report inappropriate content or user behavior
- **Document verification**: Upload and verify identity documents (admin-managed)
- **Admin reports**: Comprehensive reporting dashboard for moderators

## Technology Stack
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Database**: SQLite (development) / PostgreSQL (production)
- **Authentication**: Custom Django authentication with email verification
- **File Storage**: Django's file storage system for media files

## Installation

### Prerequisites
- Python 3.8+
- pip
- Virtual environment (recommended)

### Setup
1. Clone the repository
```bash
git clone https://github.com/Suraj21209/Social-Media-Marketplace.git
cd Social-Media-Marketplace
```

2. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Run migrations
```bash
python manage.py migrate
```

5. Create a superuser (admin)
```bash
python manage.py createsuperuser
```

6. Start the development server
```bash
python manage.py runserver
```

7. Access the site at http://127.0.0.1:8000/

## Usage

### User Flow
1. Visit the homepage and select "User Access"
2. Register a new account or log in
3. Complete profile setup and explore the platform
4. Connect with friends, create posts, and engage with content
5. Browse marketplace items and make purchases

### Admin Flow
1. Visit the homepage and select "Admin Access"
2. Log in with admin credentials
3. Access the admin dashboard to manage users, review reports, and verify documents
4. Monitor platform activity and handle user issues

## Deployment
For deployment to production, consider the following platforms:
- Heroku
- PythonAnywhere
- DigitalOcean
- AWS Elastic Beanstalk

Make sure to configure the following for production:
- Use a production database (PostgreSQL recommended)
- Set up proper environment variables for secrets
- Configure static and media file storage
- Set DEBUG=False in production settings

## Security Features
- OTP verification for account registration
- Separate transaction verification for purchases
- CSRF protection for all forms
- User blocking capabilities
- Document verification system
- Admin review system for reported content

## Contributing
Contributions to the Social Media Marketplace are welcome! Please follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Contact
Project Link: [https://github.com/Suraj21209/Social-Media-Marketplace](https://github.com/Suraj21209/Social-Media-Marketplace)

---

Created by [Suraj21209](https://github.com/Suraj21209)
