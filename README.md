# React.js Frontend Developer Assignment
# Objective
This project demonstrates a React.js application that fetches and displays a list of users from an API, supports searching, filtering, sorting, and provides a detailed view for each user.

Features
Home Page
Displays a list of users fetched from the API: https://jsonplaceholder.typicode.com/users.
Shows user details: name, email, and city.
Search bar to filter users by name.
Sorting functionality by name (A-Z, Z-A).
Clicking on a user navigates to the User Detail Page.
User Detail Page
Displays full user details, including:
Name
Email
Phone
Company Name
Website
Includes a Go Back button to return to the Home Page.
Additional Features
State Management: Implemented using the React Context API.
Responsive Design: Fully responsive for mobile and desktop views.
Loading and Error Handling:
Shows a loader while fetching data.
Displays an error message in case of API failures.
Bonus Features
Dark/Light Mode: Toggle button to switch between themes.
Pagination: Divides the user list into multiple pages.
Deployed Application: Hosted on Netlify/Vercel for easy access.
Project Setup

# 1. Clone the Repository
bash
Copy
Edit
git clone <repository_url>
cd <repository_name>

# 2. Install Dependencies
Make sure you have Node.js installed. Run the following command:

bash
Copy
Edit
npm install

# 3. Start the Development Server
Run the application locally:

bash
Copy
Edit
npm start
The app will be accessible at http://localhost:3000.

# 4. Build for Production
To create a production build:
bash
Copy
Edit
npm run build
Technologies Used
React.js: Functional components with hooks.

React Router: For navigation.
React Context API: For state management.
Styling: Tailwind CSS (or Material-UI if preferred).
API: JSONPlaceholder.


# Deployment
The application is deployed and accessible at: 👉 Deployed Link

Future Enhancements
Add more filters (e.g., city or company).
Implement additional error recovery options.
Enhance pagination for large datasets.
