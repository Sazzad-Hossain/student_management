
---

# Student Management System

This project is a beginner-friendly yet practical web-based application designed to help you understand and implement the concepts of forms, CRUD operations, and template management effectively using Django.

## Objective

Create a simple web-based system to manage students' records, including adding, updating, viewing, and deleting information, while utilizing Django features like HTML forms, model forms, class-based views, and template inheritance.

## Key Features

1. **Student Registration**:
   - Use HTML Forms to collect basic details such as Name, Email, Phone Number, and Course.
   - Apply HTML Built-in Validation (e.g., required fields, proper email format).

2. **Student List Page**:
   - Display all registered students using a template.
   - Create reusable templates for listing CRUD data.

3. **CRUD Operations**:
   - **Create**: Add a new student using Model Forms.
   - **Read**: Display student details on a detailed view page.
   - **Update**: Edit student details using GET & POST requests.
   - **Delete**: Remove a student using a DELETE request.

4. **Template Features**:
   - Implement Template Inheritance to structure pages (base.html for navbar, footer, etc.).
   - Use Template Blocks for customizing sections like forms, lists, and messages.

5. **Message Framework**:
   - Show success/error messages (e.g., "Student added successfully", "Record deleted").

## Tools & Technologies

- **Frontend**: HTML, CSS (optional for styling).
- **Backend**: Django (Focus on forms, views, templates).
- **Database**: SQLite (default Django database).

## Learning Outcomes

- Understand HTML forms and their validation.
- Learn how to use Django Model Forms for database integration.
- Master CRUD operations with GET, POST, UPDATE, DELETE requests.
- Create dynamic, reusable templates for forms and CRUD pages.

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/student_management.git
   cd student_management
   ```

2. **Set Up the Virtual Environment using pipenv**:
   ```bash
   pip install pipenv
   pipenv install
   pipenv shell
   ```

3. **Install Dependencies**:
   Make sure you have a `Pipfile` that lists all the dependencies. If you don't have one, create it and add the required packages.
   ```bash
   pipenv install django
   ```

4. **Apply Migrations**:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```

6. **Open the Application**:
   - Navigate to `http://127.0.0.1:8000/students/` in your web browser.

## Usage

- **Add Students**: Navigate to the "Add Student" page to register a new student.
- **View Students**: View all registered students on the "Student List" page.
- **Edit Student**: Click the "Edit" button next to a student's name to update their information.
- **Delete Student**: Click the "Delete" button next to a student's name to remove their record.

## Contributing

Feel free to fork the repository and submit pull requests. Any contributions are welcome!


---
