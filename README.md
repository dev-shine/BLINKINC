# HI Justin Gordon
It is composed in React/Redux and Express Server
You can register with ROLE_MEMBER by default.
At this time you can not see admin panel.
And you can change server/models/user.js 
role: {
    type: String,
    enum: [ROLE_MEMBER, ROLE_CLIENT, ROLE_OWNER, ROLE_ADMIN],
    default: ROLE_ADMIN
},
Then you can register with Admin and so you can see admin panel.
Best Regards.

PS. Frontend must have not register fucntionality as Admin role.

# How to Run 
In server . open terminal and folow this command.
npm install
npm run dev
Server is running on port 3000
In Frontend . open terminal and follow this command.
npm install
npm start
Server is running on port 8080
# Open web brower and localhost:8080
#Best Regards.XiaoJin