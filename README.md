# PC Parts E-Commerce Website

A full-featured e-commerce platform for computer components and PC parts built with Flask and Bootstrap 5.

## Features

### User Authentication
- User registration with email verification
- Secure login/logout functionality
- Password hashing for security
- User session management

### Product Management
- Browse products by categories
- Detailed product pages with specifications
- Stock tracking
- Product image support
- Featured products section

### Shopping Experience
- Shopping cart functionality
- Add/remove items
- Quantity adjustment
- Order summary
- Secure checkout process

### Order Management
- Order history
- Order status tracking
- Order confirmation emails
- Shipping information management

### User Interface
- Responsive design with Bootstrap 5
- Modern and clean interface
- Mobile-friendly layout
- Intuitive navigation
- Category-based browsing
- Search functionality

### Additional Features
- Contact form
- Feedback system
- Newsletter subscription
- About us page

## Technology Stack

### Backend
- Python 3.x
- Flask web framework
- SQLAlchemy ORM
- SQLite database
- Flask-Login for authentication
- Werkzeug for security

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- Bootstrap Icons
- Responsive design

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd projrct
```

2. Create a virtual environment:
```bash
python -m venv venv
```

3. Activate the virtual environment:
- Windows:
```bash
venv\Scripts\activate
```
- Unix or MacOS:
```bash
source venv/bin/activate
```

4. Install required packages:
```bash
pip install -r requirements.txt
```

5. Initialize the database:
```bash
python
>>> from app import db
>>> db.create_all()
>>> exit()
```

6. Run the application:
```bash
python app.py
```

7. Access the website at `http://localhost:5000`

## Project Structure

```
projrct/
├── app.py                 # Main application file
├── requirements.txt       # Python dependencies
├── README.md             # Project documentation
├── static/               # Static files
│   ├── css/             # CSS files
│   ├── js/              # JavaScript files
│   └── images/          # Image files
└── templates/           # HTML templates
    ├── index.html       # Home page
    ├── product.html     # Product details
    ├── cart.html        # Shopping cart
    ├── checkout.html    # Checkout process
    ├── contact.html     # Contact page
    └── feedback.html    # Feedback page
```

## Configuration

The application can be configured through environment variables:

- `SECRET_KEY`: Flask secret key for session management
- `DATABASE_URL`: Database connection string
- `MAIL_SERVER`: Email server for notifications
- `MAIL_PORT`: Email server port
- `MAIL_USERNAME`: Email account username
- `MAIL_PASSWORD`: Email account password

## Development

To contribute to this project:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## Security Features

- Password hashing using Werkzeug
- CSRF protection
- Secure session management
- Input validation and sanitization
- Protected routes with login_required

## Future Enhancements

- Payment gateway integration
- Advanced search functionality
- Product reviews and ratings
- Admin dashboard
- Inventory management system
- Wishlist functionality
- Social media integration
- Product recommendations

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please email [support@email.com] or open an issue in the repository.

## Contributors

- [Your Name]
- [Other Contributors]

## Acknowledgments

- Flask documentation
- Bootstrap team
- SQLAlchemy documentation
- Open source community
