# Node and Express Course Workspace

This repository is a coursework workspace for learning Node.js, Express, MongoDB, authentication, file uploads, email, payments, and API architecture. It contains multiple tutorial projects, many with both starter and final versions.

The original course material is from John Smilga's Node/Express tutorial series. This repo is kept as a learning archive so I can reference the completed examples and starter code while building my own Node projects.

## Contents

```text
01-node-tutorial/
02-express-tutorial/
03-task-manager/
04-store-api/
05-JWT-Basics/
06-jobs-api/
06.5-jobster-api/
07-file-upload/
08-send-email/
09-stripe-payment/
10-e-commerce-api/
11-auth-workflow/
```

## Topics Covered

- Node.js fundamentals
- Express routing and middleware
- REST API structure
- MongoDB and Mongoose
- CRUD operations
- Authentication and authorization
- JWT basics
- Password hashing
- Error handling
- File uploads
- Cloudinary integration
- Email sending with Nodemailer/Ethereal/SendGrid
- Stripe payment flow
- E-commerce API patterns
- Email verification and password reset workflows

## How To Use This Repository

Each project folder has its own `package.json`. Go into the specific project you want to run, install dependencies, and use that folder's scripts.

Example:

```bash
cd 03-task-manager/final
npm install
npm start
```

Some projects require environment variables such as MongoDB connection strings, JWT secrets, Cloudinary credentials, email provider keys, or Stripe keys. Check the project folder for `.env.example`, config files, or README notes before running.

## Notes

- This is a course/practice repository, not one single application.
- Some folders are intentionally incomplete starter files.
- The final folders are better references for working implementations.
- Later projects may include generated frontend folders that still have framework-default README files.

## What I Practiced

- Reading and modifying existing backend project structure
- Connecting Express apps to databases and third-party services
- Understanding starter vs. final implementation patterns
- Building confidence with larger Node/Express codebases
