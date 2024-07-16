Here's a README for your Angular CRUD application with local storage:

# Angular-Crud-LocalStorage

This is a simple CRUD (Create, Read, Update, Delete) application built with Angular 17 to manage student data. The student information is stored in the local storage, and Bootstrap CDN is used for styling the user interface.

![UI Screenshot](/Users/yashkalra/Desktop/Projects/Crud-Angular/crud_localstorage/public/crud.png)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Add new student information
- View the list of students
- Update existing student information
- Delete student information
- Data persistence using local storage

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/Angular-Crud-LocalStorage.git
    cd Angular-Crud-LocalStorage
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

3. Start the development server:
    ```sh
    ng serve
    ```

4. Open your browser and navigate to `http://localhost:4200`.

## Usage

1. **Add Student**: Fill out the form and click the "Add Student" button to add a new student.
2. **View Students**: The list of students will be displayed below the form.
3. **Update Student**: Click the "Edit" button next to a student, modify the information, and click "Save" to update.
4. **Delete Student**: Click the "Delete" button next to a student to remove them from the list.

## Technologies Used

- **Angular 17**: A platform for building mobile and desktop web applications.
- **Bootstrap 5**: A popular CSS framework for building responsive, mobile-first sites.
- **Local Storage**: A web storage API for storing data in the browser.

## Project Structure

```
Angular-Crud-LocalStorage/
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── student-form/
│   │   │   └── student-list/
│   │   ├── services/
│   │   │   └── local-storage.service.ts
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   └── assets/
│       └── screenshot.png
├── angular.json
├── package.json
└── README.md
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any feature additions or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to replace the placeholder text (e.g., `path_to_your_screenshot.png`, `your-username`) with your actual details.