# Student Management (Node.js + Express)

## Run in VS Code
1. File → Open Folder → select `student-management`
2. Open terminal (Ctrl + `)
3. `npm install`
4. `npm start`   (or `npm run dev` for auto-restart)
5. Open http://localhost:3000

## REST API
| Method | URL                  | Description          |
|--------|----------------------|----------------------|
| GET    | /api/students        | List (?search=text)  |
| GET    | /api/students/:id    | Get one              |
| POST   | /api/students        | Create               |
| PUT    | /api/students/:id    | Update               |
| DELETE | /api/students/:id    | Delete               |

Body (JSON): `{ "name": "Arun", "email": "arun@mail.com", "course": "B.E CSE", "age": 20 }`

Data is saved in `data/students.json`.
