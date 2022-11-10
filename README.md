<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Zoot01/react-apollo-auth">
    <img src="images/logo.png" alt="Logo"  >
  </a>

<h3 align="center">react-apollo-auth</h3>

  <p align="center">
     Authentication Boilerplate with Create React App and Apollo GraphQL built with typescript and MongoDB. Making use of Jwt access and refresh tokens and the powerful Apollo Context API. 
    <br />

  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

![profile-screenshot]
![login-screenshot]
![signup-screenshot]

This is a blank boilerplate template for anyone looking to use Create React App and Apollo GraphQL, with authentication. This template uses Cookies for more secure authentication and authorization. This authentication Boilerplate with Create React App and Apollo GraphQL built with typescript and MongoDB. Making use of Jwt access and refresh tokens and the powerful Apollo Context API.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

- [![React][react.js]][react-url]
- [![MongoDB][mongodb]][mongodb-url]
- [![Typescript][typescript]][typescript-url]
- [![Apollo GraphQL][graphql]][graphql-url]
- [![Expressjs][express]][express-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

Please follow the simple steps below to get the project running on your local machine.

### Prerequisites

You will need a local instance of MongoDB or a MongoDB atlas connection, along with NodeJS and NPM.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/anzal1/apollo-react-authentication-boilerplate.git
   ```
2. Install NPM packages for the client
   ```sh
   cd client
   npm install
   ```
3. In a new terminal install NPM packages for the server

   ```sh
   cd server
   npm install
   ```

4. Enter environment variables by chaning `.env.example` to `.env` and entering variables

   ```js
   DATABASE_URL = "mongodb://localhost:27017/react-apollo-auth";
   JWT_ACCESS_SECRET = "somereallylongsecretkey";
   JWT_REFRESH_SECRET = "somereallylongsecretkey";
   ```

5. Start the client

   ```sh
   cd client
   npm run start
   ```

6. Start the server

   ```sh
   cd server
   npm run dev
   ```

7. Vist application and explore
   ```sh
    Local:            http://localhost:3000
    On Your Network:  http://192.168.1.153:3000
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

Register a user and login to see all the the applications features. This is just a starting point, explore, add, contribute, critique. Remember this is a bolierplate so features are minimal. The goal is to keep this a barebones as possible.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [✅] Jwt Access Token Cookie - Short lived 30 seconds
- [✅] Jwt Refresh Token Cookie - Long lived 7 days
  - [📛] Add use authorization roles
- [✅] User Profile Dropdown
- [✅] React Context API
- [✅] GraphQL Codegen



<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make things better. Please contribute!

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->



<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Discord: Zoot#7045

Project Link: [https://github.com/anzal1/apollo-react-authentication-boilerplate](https://github.com/anzal1/apollo-react-authentication-boilerplate)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
