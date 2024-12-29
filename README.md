# Favourite-Student-List

This project is a simple web application that allows users to manage a list of students. Users can:

- Add new students to the list.
- Mark students as "favorites."
- View and remove favorite students on a separate page.

The application uses **HTML**, **CSS**, and **JavaScript** to create an interactive user experience. LocalStorage is used to persist the list of favorite students.

## Features

- **Add Student:** Users can add new students to the list by entering their name.
- **Add to Favorites:** Users can mark a student as a favorite, which updates the button to show that the student has been added to the favorites list.
- **Remove Student:** Users can remove students from the main list, and if they are in the favorites list, they will be removed from there as well.
- **View Favorites:** There is a separate page to view all favorite students. The list is stored in the browser's localStorage, so it persists across page reloads.
  
## Pages

1. **index.html**  
   - Displays the main list of students.
   - Allows users to add new students and mark them as favorites.
   - Provides a link to the favorites page.

2. **favourite_list.html**  
   - Displays a list of all favorite students.
   - Allows users to remove students from the favorites list.
   - Provides a link back to the main student list.

## Technologies Used

- **HTML**: For the structure and content of the pages.
- **CSS**: For styling the pages and making the user interface responsive and attractive.
- **JavaScript**: For handling interactions like adding/removing students, marking favorites, and using localStorage for persistence.

## Instructions

1. Clone or download the project to your local machine.
2. Open `index.html` in your browser to start interacting with the students list.
3. You can add new students, mark them as favorites, and view/remove favorite students from the `favourite_list.html` page.

### Files in this Project

- `index.html`: Main page to display and manage students.
- `favourite_list.html`: Page to display and manage favorite students.
- `style.css`: Styles for both pages (included in each HTML file for simplicity).
- `script.js`: JavaScript logic for adding/removing students and handling favorite actions.

## How it Works

1. When a student is added, the list is updated dynamically on the page.
2. When a student is marked as a favorite, their name is stored in the browser's `localStorage`.
3. On the favorites page, the list of favorites is retrieved from `localStorage` and displayed.
4. If a favorite student is removed, they are also removed from `localStorage` and the list is updated.

## Local Storage Usage

- The list of favorite students is stored in the browser's `localStorage`, which allows data to persist even after a page reload.
- Local storage is automatically updated when a student is added to or removed from the favorites list.

## Future Improvements

- Add validation to check if a student already exists in the list before adding them.
- Implement a search functionality to quickly find students in the list.
- Use a backend to store student data persistently instead of relying on `localStorage`.

## License

This project is open-source and free to use. Feel free to fork or modify the code for your personal use.
