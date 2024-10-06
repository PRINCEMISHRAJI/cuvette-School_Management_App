# School Management App - Cuvette Assignment

## Live Demo

- [Frontend](https://cuvette-school-management-app.onrender.com)
- [Backend](https://cuvette-school-management-app-api.onrender.com)

## Introduction

The School Management App is a CRM application designed for teachers, students, and administrators. It allows users to view personal details and classroom information. Students can build their profiles and see their assigned teachers and classes, while teachers can view the students they teach.
![Screenshot (26)](https://github.com/user-attachments/assets/a5ba3b31-71b3-4f76-a84d-475cf9e3e97d)
![Screenshot (27)](https://github.com/user-attachments/assets/a3376175-bc6a-4d0a-a6d1-de41b6d852e6)
![Screenshot (28)](https://github.com/user-attachments/assets/2e58bc67-7844-43fa-87da-3a7e23e1e38e)

## Challenge

The goal is to develop a web-based school management application using the MERN stack (MongoDB, Express.js, React.js, Node.js) along with Tailwind CSS. This application will manage classes, teachers, and students, providing analytics as well. High standards of professionalism in code quality and user experience (UX) are essential, prioritizing a UX-first approach in design and development.

## Proposed Solution

The application will be user-friendly and include the following functionalities:

### Data Management

Three core models will be implemented:

- **Class**: 
  - Stores details such as class name, year, teacher, student fees, and student list.
  
- **Teacher**: 
  - Contains information including name, gender, date of birth, contact details, salary, and assigned classes.
  
- **Student**: 
  - Holds information such as name, gender, date of birth, contact details, fees paid, and assigned class.

### Features

- **CRUD Operations**: 
  - Full Create, Read, Update, and Delete operations for all models.
  
- **Reusable React Components**: 
  - Development of reusable components for forms and tables.
  
- **Dynamic Forms**: 
  - Forms that dynamically render input fields based on the selected model (Class, Teacher, Student).
  
- **Student Limit**: 
  - Implementation of a limit on the number of students in each class.
  
- **Analytics Pages**: 
  - **Class Analytics**: Clicking on a class in the management page will open a detailed analytics page displaying the class's name, year, teachers, and student list. It will also feature a graph showing the number of male and female students in that class.
  - **Financial Analytics**: A dedicated page to showcase expenses on teacher salaries and income generated from student fees.

## Contributing

Contributions are welcome! If you would like to contribute, please fork the repository and create a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
