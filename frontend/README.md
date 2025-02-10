# Project Title

## Description
This project is a job application platform that connects job seekers with employers. It provides functionalities for user authentication, job listings, and application management.

## Installation

### Backend
1. Clone the repository.
2. Navigate to the `backend` directory.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Create a `.env` file in the `backend` directory and set the necessary environment variables.
5. Run the backend server:
   ```bash
   npm start
   ```

### Frontend
1. Navigate to the `frontend` directory.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the frontend server:
   ```bash
   npm run dev
   ```

## Usage
- The backend server runs on `http://localhost:3000`.
- The frontend server runs on `http://localhost:5173`.

### API Endpoints
- **User Routes**: `/api/v1/user`
- **Company Routes**: `/api/v1/company`
- **Job Routes**: `/api/v1/job`
- **Application Routes**: `/api/v1/application`

### Frontend Routes
- `/`: Home
- `/login`: Login
- `/signup`: Signup
- `/jobs`: Job Listings
- `/description/:id`: Job Description
- `/browse`: Browse Jobs
- `/profile`: User Profile
- `/admin/...`: Admin functionalities (protected routes)

## Features
- User authentication (login/signup)
- Job listings and descriptions
- Admin panel for managing companies and jobs

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
