## HTTP interceptor

Include JWT stored in localStorage in any HTTP request sent via HTTP interceptor.

*Changed files: `app.module.ts`, `auth.service.ts`, `dashboard.component.ts`, `dashboard.component.html`, `sign-in.component.ts`, `jwt-interceptor.servcie.ts`*

---

## Setup

1. Clone the repo: `git clone https://github.com/cervus-camelopardalis/angular-http-interceptor.git`
2. Create PostgreSQL database (see `database.sql` file)
3. Insert your database user and password (edit `db.js` file)
4. Install Express modules: `C:\Users\xxxxx\xxxxx\xxxxx\express-server>npm i`
5. Install Angular modules: `C:\Users\xxxxx\xxxxx\xxxxx\angular-client>npm i`
6. Start Express server: `C:\Users\xxxxx\xxxxx\xxxxx\express-server>nodemon server`
7. Run Angular app: `C:\Users\xxxxx\xxxxx\xxxxx\angular-client>ng serve -o`

---

## Screenshots

1. Sign up:

![Sign up](https://github.com/cervus-camelopardalis/angular-http-interceptor/blob/main/01-screenshot-sign-up.gif)

2. Sign in (show user data):

![Sign in](https://github.com/cervus-camelopardalis/angular-http-interceptor/blob/main/02-screenshot-sign-in.gif)