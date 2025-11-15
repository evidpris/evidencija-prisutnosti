# Evidencija Prisutnosti

Attendance tracking application built with .NET ASP.NET Core Web API backend and React frontend.

## Project Structure

```
evidencija-prisutnosti/
├── client/          # React frontend (Vite)
├── server/          # .NET ASP.NET Core Web API backend
└── infra/           # Infrastructure/deployment configurations
```

## Prerequisites

- .NET 10.0 SDK
- Node.js 18+ and npm

## Getting Started

### Backend (Server)

1. Navigate to the server directory:
```bash
cd server
```

2. Restore dependencies:
```bash
dotnet restore
```

3. Run the API:
```bash
dotnet run
```

The API will be available at:
- HTTP: http://localhost:5000
- HTTPS: https://localhost:5001
- Swagger UI: http://localhost:5000/swagger

### Frontend (Client)

1. Navigate to the client directory:
```bash
cd client
```

2. Install dependencies (if not already installed):
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The React app will be available at http://localhost:5173

## Development

- Backend: C# with ASP.NET Core 10.0
- Frontend: React 19 with Vite
- CORS is configured to allow requests from the React app (localhost:5173)

## Notes

- CORS is pre-configured for development
- Swagger is enabled in development mode
