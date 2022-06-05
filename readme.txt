
- sudo npm install -g typescript

- tsc --init
- copy content of a tsconfig.json file.
        "target": "es2018",
        "moduleResolution": "node",
        "rootDir": "./src",
        "outDir": "./dist",

- In a new terminal window
    tsc -w

- npm install express body-parser
- npm install --save-dev nodemon
- npm i --save-dev @types/node
- npm i --save-dev @types/express

- package.json
        "start": "nodemon dist/app.js"

- npm start

- POSTMAN
    - POST: http://localhost:3000/todos
        - Body:raw:JSON
            {
                "text": "Finished the course"
            }
    - GET: http://localhost:3000/todos
    - PATCH: http://localhost:3000/todos/0.29990782826515483
        - Body:raw:JSON
            {
                "text": "updated text"
            }
    - DELETE:
        http://localhost:3000/todos/0.29990782826515483
