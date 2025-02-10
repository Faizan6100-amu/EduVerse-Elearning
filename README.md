# EduVerse - An E-Learning Portal

## 📌 Project Overview
**EduVerse** is a full-stack PHP-based e-learning platform designed to provide a dynamic and interactive environment for online education. Inspired by platforms like Udemy, EduVerse enables instructors to create and manage courses while allowing students to enroll, learn, and track their progress seamlessly.

## 🚀 Features

### 🧑‍🏫 For Instructors:
- Course creation with rich content (videos, PDFs, quizzes, and assignments)
- Course pricing (free/paid) and discount management
- Student enrollment tracking
- Discussion forums for better engagement
- Analytics dashboard for performance insights

### 🎓 For Students:
- Course browsing, searching, and filtering
- Secure user authentication & profile management
- Interactive quizzes and assignments
- Discussion forums and Q&A sections
- Course progress tracking with completion certificates

### 🔧 Admin Panel:
- User management (Instructors, Students, Admins)
- Course approval and moderation
- Payment and transaction monitoring
- Site-wide announcements and notifications

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** PHP, Laravel (or Core PHP with MVC)
- **Database:** MySQL
- **Authentication:** JWT/Auth-based login system
- **Payment Integration:** Stripe/PayPal
- **Video Hosting:** AWS S3, Vimeo, or self-hosted storage

## 📂 Project Structure
```
EduVerse/
│-- index.php             # Main entry point
│-- config/               # Database configuration
│-- assets/               # CSS, JS, images
│-- templates/            # Common UI templates
│-- views/                # Frontend pages
│-- controllers/          # Handles business logic
│-- models/               # Database interactions
│-- routes/               # Handles URL routing
│-- uploads/              # Course materials and user uploads
│-- vendor/               # Composer dependencies
```

## 🔧 Installation & Setup
### Prerequisites:
- PHP 8+
- MySQL 5.7+
- Apache/Nginx
- Composer (for dependency management)
- Node.js & npm (for frontend dependencies, if applicable)

### Steps:
1. **Clone the repository**
   ```bash
   git clone https://github.com/Faizan6100-amu/EduVerse.git
   cd EduVerse
   ```
2. **Install dependencies**
   ```bash
   composer install
   ```
3. **Configure the database**
   - Create a `.env` file from `.env.example`
   - Update database credentials
   - Run migrations
     ```bash
     php artisan migrate
     ```
4. **Start the server**
   ```bash
   php -S localhost:8000 -t public/
   ```

## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
We welcome contributions! Feel free to fork the repo, create a feature branch, and submit a pull request.

## 📬 Contact
For any queries or collaboration opportunities, contact Faizan Anwar Khan at anwarfaizankhan@gmail.com
