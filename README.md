<div align="center">
  <a href="https://github.com/dimassagngsptr/pijar-mama-recipe.git">
      <img src="https://github.com/Azhar-54/mama-recipe-nextjs/blob/main/public/images/img_barbecue_1.svg" width="300"/>
  </a>

  <h1 align="center">Mama Recipe</h1>

  <p align="center">
     Food Recipe Implementation
    <br />
    <br />
     <a href="" target="_blank">View Demo</a>
    ·
     <a href="https://github.com/Azhar-54/mama-recipe-nextjs" target="_blank">View Front-End Repo</a>
  </p>
</div>

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Contributing](#contributing)
- [Contact](#contact)
- [Documentation](#documentation)
- [Acknowledgements](#acknowledgements)




## About The Project

This back-end project for Mama Recipe was developed by muhammadrisano. Feel free to explore the source code, which I have forked from the original repository. It includes all the files and documentation needed to develop and run the server side of this application. Thank you for developing this back-end project.

### Built With

- [Express.js](https://expressjs.com/)
- [Node.js](https://nodejs.org/en)
- [Prisma](https://www.prisma.io/)
- [Postgre Sql](https://www.postgresql.org/)

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Ensure you have the following installed on your local machine:

- Node.js
- npm
- PostgreSQL

### Installation

1. Clone Repo

   ```sh
     git clone https://github.com/Azhar-54/pijar-mama-recipe.git
   ```

2. Go to workspace

   ```
      cd pijar-mama-recipe
   ```

    Open VsCode

    ```
      code .
    ```

3. Install NPM packages

   ```
     npm install
   ```

4. Set up your database

   ```
     npx prisma migrate dev --name init
   ```

### Start Development Server

To start the development server:

```
    nodemon
```
if doesnt work

```
  node index.js
```

The server will start on port 3000 by default. You can use Postman to interact with the endpoints in [Documentation](#documentation).

## Usage

To use this project, follow the instructions below for understanding the project structure and how to use the provided API documentation.

### Project Structure

```
be-mama-food-recipe-app/
├── prisma/
│   └── schema.prisma
├── src/
│   ├── controllers/
│   │   ├── auth.js
│   │   ├── recipes.js
│   │   ├── upload.js
│   │   └── users.js
│   ├── herlpers/
│   │   ├── auth.js
│   │   └── common.js
│   ├── middlewares/
│   │   ├── auth.js
│   │   └── upload.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── index.js
│   │   ├── recipes.js
│   │   ├── upload.js
│   │   └── users.js
│   ├── utils/
│   │   └── cloudinary.js
│   └── app.js
├── .gitignore
├── README.md
├── index.js
├── package-lock.json
├── package.json
├── vercel.json
└── yarn.lock
```

### Documentation

Access the API documentation for the **Mama Recipe** project, also created by [him](https://github.com/muhammadrisano). Use this documentation to test endpoints and understand the structure and functionality of the available APIs in this project.

[![Mama Recipe API Postman Documentation](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/7675329/2sA3QqerrC#0e5dea50-1ec3-4ffe-b096-b1d0ab42d5c1)

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact

If you have any questions or inquiries regarding this project, don't hesitate to reach out:

Email: burhanuddinazhar2@gmail.com

For issues related to the back-end, please contact the original developer, [Muhammad Risano](https://github.com/muhammadrisano). 

We're here to help!

## Acknowledgements

Feel free to check it out:

- [Img Shields](https://shields.io)
- [Choose an Open Source License](https://choosealicense.com/)
- [GitHub Pages](https://pages.github.com/)

  ### Project Related

:rocket: [`Mama Recipe Front End`](https://github.com/Azhar-54/mama-recipe-nextjs)

🚀 [`Demo Back-End`](https://pijar-mama-recipe.vercel.app/)
