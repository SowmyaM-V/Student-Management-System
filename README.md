# Student Management System

A simple and modern Student Management System built with React.js. This application allows you to manage student records with full CRUD (Create, Read, Update, Delete) operations.

## Features

- ✅ Add new students
- ✅ View all students in a beautiful card layout
- ✅ Edit existing student information
- ✅ Delete students with confirmation
- ✅ Search students by name, email, or course
- ✅ Data persistence using localStorage
- ✅ Responsive design for mobile and desktop (powered by Bootstrap)
- ✅ Form validation with Bootstrap styling
- ✅ Modern, gradient UI design
- ✅ Bootstrap components (Cards, Forms, Buttons, Grid System)

## Technologies Used

- React.js 18.2.0
- Bootstrap 5.3.2 (for responsive design and components)
- CSS3 (with modern styling and custom gradients)
- LocalStorage for data persistence

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm start
```

3. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Building for Production

To create an optimized production build:

```bash
npm run build
```

This will create a `build` folder with the production-ready files.

## Project Structure

```
student-management-system/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── StudentList.js
│   │   ├── StudentList.css
│   │   ├── StudentForm.js
│   │   └── StudentForm.css
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
├── package.json
└── README.md
```

## Usage

1. **Add a Student**: Click the "+ Add New Student" button and fill in the form with:
   - Full Name
   - Email Address
   - Course
   - Phone Number
   - Age

2. **Search Students**: Use the search bar to filter students by name, email, or course.

3. **Edit a Student**: Click the "Edit" button on any student card to modify their information.

4. **Delete a Student**: Click the "Delete" button on any student card to remove them (with confirmation).

## Data Storage

The application uses browser localStorage to persist student data. This means:
- Data is saved automatically when you add, edit, or delete students
- Data persists even after closing the browser
- Data is stored locally on your device (not synced across devices)

## License

This project is open source and available under the MIT License.
