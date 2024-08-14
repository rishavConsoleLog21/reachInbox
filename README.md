# Project ReachInbox.ai

## Overview
This project involves creating a functional web application using provided designs and APIs. The application includes a login page, a main dashboard screen ("onebox" screen), data fetching capabilities, keyboard shortcuts, a custom text editor, reply functionality, and support for light and dark modes.

## Features Implemented

1. **Login Page**
   - Implemented based on provided design.

2. **Onebox Screen**
   - Users are directed here after login (/google-login endpoint).

3. **Data Fetching**
   - Integrated API to fetch data:
     - GET `/onebox/list`
     - GET `/onebox/:thread_id`
     - DELETE `/onebox/:thread_id`

4. **Keyboard Shortcuts**
   - Implemented shortcuts:
     - **D:** Delete functionality
     - **R:** Opens reply box

5. **Custom Text Editor**
   - Added custom buttons:
     - **SAVE**
     - **Variables**

6. **Reply Functionality**
   - Implemented reply feature:
     - POST `/reply/:thread_id`
     - Request body format:
       ```json
       {
         "from": "email",
         "to": "email",
         "subject": "",
         "body": "<html></html>"
       }
       ```

7. **Light and Dark Mode**
   - Implemented support for both light and dark modes.

## Usage
- Clone the repository from [github](https://github.com/rishavConsoleLog21?tab=repositories)
- Install dependencies (`npm install` or `yarn install`).
- Start the development server (`npm start` or `yarn start`).

## Technologies Used
- Frontend: HTML, CSS, TailwindCSS, JavaScript (ReactJS)
- Backend: APIs (specified in the project)

## Credits
- Design: [Rishav Kumar](https://rishavkumar.live/)

