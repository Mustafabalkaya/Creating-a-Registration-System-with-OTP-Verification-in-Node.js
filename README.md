# Email OTP verification

## Getting started

![Lesson image](./public/email-otp.png)

To get started with this project, run

```bash
git clone https://github.com/Mustafabalkaya/Creating-a-Registration-System-with-OTP-Verification-in-Node.js.git
```

and copy the .env.example variables present in the server folder into a separate .env file, fill them out & and then Navigate to the server folder: 
```bash
MAIL_HOST=smtp.gmail.com
MAIL_PORT=465
MAIL_USER=your-mail-adress
MAIL_PASSWORD=your-password-code
BASE_URL=http://localhost:4000
MONGO_URI=...
APP_PORT=4000
```
```bash
  cd server
```

And run the command **npm start** to start the server, and it will run on localhost:4000

```bash
  npm start
```

Then in the root folder run the command  npm run dev to start the frontend part of this application and it will start on: http://localhost:5173/

```bash
  npm run dev
```

And that's all you need to run this entire application.  
