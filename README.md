npm init --yes
npm i --save json-server


npm start

> todo-server-api@1.0.0 start
> npx json-server -p 3006 -w db.json

--watch/-w can be omitted, JSON Server 1+ watches for file changes by default
JSON Server started on PORT :3006
Press CTRL-C to stop
Watching db.json...

(˶ᵔ ᵕ ᵔ˶)

Index:
http://localhost:3006/

Static files:
Serving ./public directory if it exists

Endpoints:
http://localhost:3006/todos
