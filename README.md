# user-listing-app

A React.js application that fetches and displays a list of users from an API, allows searching, filtering, and provides detailed views for each user.

## Features

- Fetch and display user data from the [JSONPlaceholder API](https://jsonplaceholder.typicode.com/users).
- Search users by name.
- Sort users alphabetically (A-Z, Z-A).
- View detailed information about each user.
- Responsive design for mobile and desktop.
- State management using React Context API.
- Loading and error handling during data fetch.
- Bonus features:
  - Dark/light mode toggle.
  - Pagination for user list.

## Tech Stack

- **React.js**: Functional components and hooks.
- **React Router**: For navigation.
- **CSS/Tailwind/Material-UI**: Styling.
- **React Context API**: State management.

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/user-listing-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd user-listing-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## Project Structure

```
user-listing-app/
├── src/
│   ├── components/
│   ├── pages/
│   │   ├── HomePage.js
│   │   ├── UserDetailPage.js
│   ├── App.js
│   ├── index.js
│   └── index.css
├── public/
├── package.json
└── README.md
```

## API Used

- [JSONPlaceholder Users API](https://jsonplaceholder.typicode.com/users)

## Deployment

The app is deployed on [Netlify/Vercel](#). Access it here: [Live Demo](#).

## Contribution

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
