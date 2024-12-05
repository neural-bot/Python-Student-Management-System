# Student Management System

A Python-based Student Management System using file handling to manage students, courses, enrollment, and grades. This project allows the storage and retrieval of data across several `.csv` files, acting as a lightweight database for student records.

## Features

- **Add New Student**: Creates a new student record with ID, name, age, and address.
- **Add New Course**: Creates a new course with details such as course name, code, and instructor.
- **Enroll Student in Course**: Links a student to a course by updating an enrollment file.
- **Add Grade for Student**: Assigns a grade to a student in a specific course.
- **Display Student Details**: Shows a student's details, including enrolled courses and grades.
- **Display Course Details**: Shows course information, instructor, and enrolled students.
- **Save/Load Data** (Coming Soon): Planned feature to save and load data in bulk.

## File Structure

The following CSV files are used to store data:

- `person.csv`: Stores student information (ID, name, age, address).
- `course.csv`: Stores course information (Course Name, Course Code, Instructor).
- `en_course.csv`: Tracks student enrollment in courses.
- `course_grade.csv`: Stores students' grades in enrolled courses.

## Setup Instructions

1. Clone the repository:

    ```bash
    git clone https://github.com/itsnajibul/Student-Management-System.git
    ```

2. Ensure you have Python installed (version 3.6+).

3. Run the script:

    ```bash
    python project_main.py
    ```

## Usage

When the program starts, a menu provides the following options:

1. **Add New Student**: Prompts for student details and stores them in `person.csv`.
2. **Add New Course**: Prompts for course details and stores them in `course.csv`.
3. **Enroll Student in Course**: Prompts for student ID and course code, linking the student to the course in `en_course.csv`.
4. **Add Grade for Student**: Prompts for student ID, course code, and grade, storing the grade in `course_grade.csv`.
5. **Display Student Details**: Displays a student's personal information, courses, and grades.
6. **Display Course Details**: Displays course information and enrolled students.
7. **Save Data from File**: Planned feature.
8. **Load Data from File**: Planned feature.
