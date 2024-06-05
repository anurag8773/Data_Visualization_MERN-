# Data_Visualizer

A MERN stack application for graphical representation of JSON data using Chart.js.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [JSON Data Format](#json-data-format)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that takes JSON data as input and displays it in various graphical formats using Chart.js. The goal is to provide an intuitive interface for visualizing complex data sets.

## Features

- Interactive and responsive charts
- Dynamic data fetching and updating
- User authentication and authorization
- CRUD operations for data management
- Customizable chart types (bar, line, pie, etc.)
- RESTful API for data manipulation

## Technologies Used

- **Frontend**: React.js, Chart.js, Axios, Redux
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Styling**: CSS, Bootstrap

## Installation

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB installed and running

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Configure environment variables**

   Create a `.env` file in the `backend` directory with the following content:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. **Run the application**

   Open two terminal windows:

   - In the first terminal, start the backend server:
     ```bash
     cd backend
     npm start
     ```

   - In the second terminal, start the frontend development server:
     ```bash
     cd frontend
     npm start
     ```

   The application should now be running at `http://localhost:3000`.

## Usage

1. **Register and log in** to the application.
2. **Upload JSON data** through the provided interface.
3. **Select the type of chart** you want to generate.
4. **View and interact** with the graphical representation of your data.

## JSON Data Format

The application expects the JSON data to be in a specific format. Below is an example format:

```json
{
  "labels": ["January", "February", "March", "April", "May", "June", "July"],
  "datasets": [
    {
      "label": "Dataset 1",
      "data": [65, 59, 80, 81, 56, 55, 40],
      "backgroundColor": "rgba(75,192,192,0.4)",
      "borderColor": "rgba(75,192,192,1)",
      "borderWidth": 1
    }
  ]
}
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please contact [singhanurag8773@gmail.com].

---

Thank you for using our application! We hope it helps you visualize your data effectively.
