# Project Management Full Stack Application

## Overview

This project is a full-stack application designed for managing projects, tasks, and teams. It includes a client-side application built with Next.js and a server-side application using Express and Prisma for database management. The application also integrates with AWS services for authentication and storage.

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:

- Node.js
- npm or yarn
- PostgreSQL (for the database)
- AWS CLI (for managing AWS services)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/pm-full-stack.git
   cd pm-full-stack
   ```

2. **Install dependencies for the client:**

   ```bash
   cd client
   npm install
   ```

3. **Install dependencies for the server:**

   ```bash
   cd ../server
   npm install
   ```

### Environment Setup

1. **AWS Configuration:**

   Ensure your AWS CLI is configured with the necessary credentials and permissions to access AWS services used in this project, such as Cognito for authentication and S3 for storage.

2. **Client:**

   Create a `.env` file in the `client` directory and add your environment variables, including AWS-related variables like `NEXT_PUBLIC_AWS_REGION`, `NEXT_PUBLIC_COGNITO_USER_POOL_ID`, etc.

3. **Server:**

   Create a `.env` file in the `server` directory and add your environment variables, including the `DATABASE_URL` for your PostgreSQL database and any AWS-related variables.

### Running the Project

1. **Start the client:**

   ```bash
   cd client
   npm run dev
   ```

2. **Start the server:**

   ```bash
   cd server
   npm run dev
   ```

### Building the Project

1. **Build the client:**

   ```bash
   cd client
   npm run build
   ```

2. **Build the server:**

   ```bash
   cd server
   npm run build
   ```

## Usage

Once both the client and server are running, you can access the application at `http://localhost:3000` in your web browser. The application uses AWS Cognito for user authentication and AWS S3 for storing project-related files.

## Contributing

Contributions are welcome! Please submit issues or pull requests for any improvements or bug fixes.

## License

This project is licensed under the MIT License.

## Contact

For any inquiries, please contact [your-email@example.com](mailto:your-email@example.com).
