# Leave Form

A web application for managing employee leave requests. This project allows users to submit, track, and manage leave forms efficiently.

## Features

- Submit leave requests with relevant details
- View pending, approved, and rejected requests
- Admin dashboard for managing requests
- User authentication and role-based access

## Project Structure

```
leave-form/
├── public/             # Static assets
├── src/                # Application source code
│   ├── components/     # React components
│   ├── pages/          # Page components
│   ├── services/       # API and business logic
│   └── App.js          # Main app entry
├── package.json        # Project metadata and dependencies
└── README.md           # Project documentation
```

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm or yarn

### Installation

```bash
git clone https://github.com/njange/leave-form.git
cd leave-form
npm install
```

### Running the App

```bash
npm start
```

The app will be available at `http://localhost:3000`.

## Usage

1. Register or log in as a user.
2. Submit a new leave request.
3. Track the status of your requests.
4. Admins can review and manage all requests.

## Contributing

Contributions are welcome! Please open issues or submit pull requests.

## License

This project is licensed under the MIT License.