# CareerBridge Full-Stack Placement Portal

## Folder structure
- `frontend/` — HTML, CSS, browser JavaScript
- `backend/` — Node.js + Express REST API
- `database/` — local JSON persistence file (starter database)

## Requirements
Install Node.js 18+ from https://nodejs.org

## Run
1. Open a terminal in `CareerBridge_FullStack/backend`.
2. Run `npm install`.
3. Run `npm start`.
4. Open `frontend/index.html` in a browser (or VS Code Live Server).

Backend runs at http://localhost:3000.

## API
- GET `/api/health`
- GET `/api/data`
- PUT `/api/data`
- GET `/api/companies`
- GET `/api/questions`

This starter stores portal data in `database/data.json`. It is not a production database. For real student data, add authentication, access control, validation, backups and a hosted SQL database. Companies' eligibility criteria and interview rounds change; verify with official career pages/placement cell.
