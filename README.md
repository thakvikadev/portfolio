# A developer's portfolio

If you're a developer, it's important to have a portfolio that showcases your skills and experience. It may not be enough to simply show off your code—you'll need to share more about what you've done and why it's impressive. This a portfolio website built with React, Prisma and NestJS.

## Table of Contents

1. [About](#about)
2. [Features](#features)
3. [Versions of Technology](#versions-of-technology)
4. [Setup](#setup)
5. [Folder Structure](#folder-structure)
6. [License](#license)
7. [Community](#community)

## About

This project has 2 sub-folders - frontend and backend.

1. Frontend

    All the design has been generated with [tailwindcss](https://tailwindcss.com/).
    Find all the theme related configuration inside tailwind.config.js

    This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

    This project is integrated with a [Tailwind CSS](https://tailwindcss.com/) setup, a new utility-first css framework, in an CRA environment. You can read more over on [Getting Started with Tailwind](https://tailwindcss.com/docs/installation).

    Figma: https://www.figma.com/file/7rSTh3w3EF5XVvEbi8BYeA/Portfolio?node-id=4%3A1630

2. Backend

    For the backend, [Prisma](https://www.prisma.io/) and [NestJs](https://nestjs.com/) is used.

    Prisma is next-generation Node.js and TypeScript ORM used to Perform database operations. For this project, SQLite database is used to store and retrieve data using Prisma.

    NestJs A progressive Node.js framework for building efficient, reliable and scalable server-side applications. For this project a backend server, accessible through REST APIs to store and retrieve data from the database.

## Features

In this portfolio, following sections are covered.
1. Basic Information with resume download
2. Skills
3. Services
4. Price Plans
5. Recommendations
6. Education
7. Work History
8. Portfolio
9. Medium Blogs
10. Contact

## Versions of Technology
1. Nodejs version >= 14
2. NestJs version >= 9
3. Prisma version >=4

## Setup
Front-end runs on port:3000 and backend runs on port:8081.
1. from the root ``` cd portfolio-frontend && npm i```
2. from the root ``` cd portfolio-backend && npm i ``` 
3. create .env with variable ```DATABASE_URL="file:folio.db"``` file in ```portfolio-backend``` folder and run ```npx prisma generate``` when you are running the project for the first time. 
4. from the root ```npm start```

> Note: This project is setup in such a way that you can start the server and client from the root folder using ```npm start```

## Folder Structure

```
├── portfolio
│   ├── portfolio-frontend --- client
│   ├── portfolio-backend  --- server
├── package.json
├── README.md
```
Detailed folder structure is inside the readme of respective folder.