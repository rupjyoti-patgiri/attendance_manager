## <span style="color:cyan; font-weight:bold">Attendance Manager</span>
---
### <span style="color:lime">Technologies Used</span>
- Nextjs
- Tailwind CSS
- Chakra UI
- Express
- Mongodb
- Mongoose
---
### <span style="color:lime">Salient Features</span>
- User Registration
- User Login/Logout
- View Attendance Dashboard
- Add/Delete Subject
- Mark Present/Absent
---
### <span style="color:lime">Setup Locally</span>

#### <span style="color:skyblue">Database</span>
- Create a new mongodb database named `neuclide`.
    - you can set other names also, then it needs to be updated in `.env` file also.

#### <span style="color:skyblue">Server</span>
- `cd ./server`
- install the dependencies
  - `yarn` 
  - copy `.env.example` to `.env` and fill the contents
    - `cp .env.example .env`
- run the server
  - `yarn devstart`

#### <span style="color:skyblue">Client</span>
- `cd ./client`
- install the required node modules 
  - `yarn`
- run it 
  - `yarn dev`

---
