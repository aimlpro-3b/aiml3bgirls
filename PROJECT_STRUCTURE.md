# Automatic Resume Builder and Job Submit Pro

## Project Structure

```plaintext
aiml3bgirls/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
│   ├── tests/
│   ├── .env
│   ├── package.json
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── styles/
│   │   └── App.js
│   ├── package.json
│   └── .env
└── database/
    ├── migrations/
    ├── seeds/
    └── db.js
```  

## Description

- **backend/**: Contains the API and server logic.
  - **controllers/**: Handle the incoming requests and response formatting.
  - **models/**: Define the database schema and interact with the database.
  - **routes/**: Define the API endpoints.
  - **services/**: Business logic that interacts with controllers and models.
- **frontend/**: Contains the client-side code.
  - **components/**: Reusable UI components.
  - **pages/**: Different pages of the application.
  - **styles/**: CSS and styling files.
- **database/**: Manage database configurations, migrations, and seeds.
