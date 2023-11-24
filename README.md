<div id="top"></div>

<!-- PROJECT SHIELDS -->
<!--
*** Thanks for checking out the ShopScout project. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue. Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<p align="center">
  <a href="https://github.com/IdealisticINTJ/Shop_Scout">		  
    <img src="https://github.com/IdealisticINTJ/Shop_Scout/assets/65449934/51c4459a-9eef-4d93-a742-f9cfda262761" alt="Logo" width="130">
  </a>
</p>

## <p align="center">elevate Your e-commerce intelligence.</p>

<p align="center">
    comprehensive full-stack web application designed for tracking the price dynamics of any product on Amazon. 
    <br/>
    <a href="https://docs.google.com/document/d/17jfGy-oLZas7haOnenJluC_ct5VxzirVCmd4PKs1Opo/edit?usp=sharing"><strong>Explore the design specification »</strong></a>
    <br />
    <a href="https://shop-scout-ctbl-k0hk5hjf8-salma-shaiks-projects.vercel.app/"><strong>View deployed website »</strong></a>
    <br />
    <a href="your-video-demo-link">View Video Demo</a>
    ·
    <a href="https://sourceforge.net/projects/ShopScout/">Check backend API docs</a>
    ·
    <a href="https://github.com/IdealisticINTJ/ShopScout.ssh/issues">Request Feature</a>
</p>

# Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup](#setup)
- [Future Scope](#future-scope)
- [Contributing](#contributing)
- [Support](#support-and-contact)
- [License](#license)

## Features

- Create an account
- Track any product's price on Amazon (future support for multiple e-commerce websites: Flipkart, BestBuy, Snapdeal, Alibaba)

## Tech Stack

- MERN Stack (MongoDB, Express, React, Node)
- Bootstrap
- Sass


## Setup

> Get your MongoDB connection string

Follow from Part 1 (Create an Atlas Account) to Part 5 (Connect to Your Cluster) in [this documentation](https://docs.atlas.mongodb.com/getting-started/). <br>

In [Part 5](https://docs.atlas.mongodb.com/tutorial/connect-to-your-cluster/), skip to [Connect to Your Atlas Cluster](https://docs.atlas.mongodb.com/tutorial/connect-to-your-cluster/#connect-to-your-atlas-cluster) and follow from Step 1 to Step 4 to get the connection string. <br>

Now, clone the repository, then:

> cd into the working directory and install dependencies in both server & client side:

```bash
cd ShopScout.ssh
npm i
cd frontend
npm i
```

> Back to the root folder and create a ".env" file:

```bash
cd ..
cd ..
touch .env
```

> In ".env", enter your mongoDB connection string and JWT secret key:

- If you're using VS Code, you can use this command to start editing

```bash
code .
```

- Paste in the code, replace mongodb-connection-string with your MongoDB connection string, and edit yourJwtSecret.

```bash
NODE_ENV=development
MONGO_URI=mongodb-connection-string
JWT_SECRET=yourJwtSecret
```

> Install concurrently to run both server and client side in one terminal, and run the app:

```bash
npm i -D concurrently
npm run dev
```

## Future Scope

- Add email management & notification about price fluctuations (raise/drop) using Nodemailer
- Add more authentication methods
- Notification via Whatsapp
- Best Deals Section
- Add password reset and email confirmation
- Add price analytics

## Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Support and Contact

For any questions, suggestions, or issues, please contact:

- **Salma Shaik**
  - GitHub: [IdealisticINTJ](https://github.com/IdealisticINTJ)
  - Email: [salmasaa02@gmail.com](mailto:salmasaa02@gmail.com)
    
## License
This project is licensed under the [GNU General Public License v3.0](LICENSE).


---------

```javascript

if (youEnjoyed) {
    starThisRepository();
}

```

-----------
