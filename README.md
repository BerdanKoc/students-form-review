# students-form-review

# Description
This project is a web application for collecting and analyzing form data. It allows users to create custom forms, collect user responses, and display statistics and analysis based on those responses.

# Key Features
- **Custom Form Creation:** Users can create forms by adding various types of questions, including text, multiple choice, rating scale, etc.
- **Form Sharing:** Forms can be shared with other users via securely generated links.
- **Response Collection:** The application enables the collection of user responses to forms, with time tracking and data validation.
- **Display of Statistics and Analysis:** Responses are presented in the form of charts and reports for visual data analysis.

# Technologies Used
- **Backend:** Laravel, PHP
- **Frontend:** HTML, CSS, JavaScript (Vue.js)
- **Database:** MySQL
- **Visualization Tools:** Chart.js
- **Security:** Authorization management, URL signing for secure forms.

# Installation
1. Clone the repository: **git clone https://github.com/BerdanKoc/students-form-review.git**
2. Install dependencies: **composer install && npm install**
3. Configure environment: **Copy .env.example file to .env and fill in the database information.**
4. Generate application key: **php artisan key:generate**
5. Run migrations: **php artisan migrate**
6. Start the development server: **php artisan serve**

# Contributing
Contributions are welcome! For suggestions or issues, please open an issue or submit a pull request