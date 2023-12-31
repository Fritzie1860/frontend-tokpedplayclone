# Tokped Play Clone (Frontend)

A repository that is part of the final project of the Fullstack Track in Generasi Gigih 3.0, which produces a cloning of Tokopedia Play. This repository is the frontend component using Create React App.

See [backend repository](https://github.com/Fritzie1860/backend-tokpedplayclone)


## **Table of Contents**

- [Routes](#routes)
- [Server Hosting Information](#server-hosting-information)
- [How to run in local](#how-to-run-in-local)


## **Routes**

| Route                 | Page Description                                 |
| --------------------- | ------------------------------------------------ |
| /                     | Dashboard of the app.                            |
| /videos/:id           | Video page based on video_id.                    |


## **Server Hosting Information**

The server is hosted on the 000webhost.com platform with the server link: https://tokpedplay-fritzie.000webhostapp.com.

**How to Access the Server:**

To interact with the server, you can use the provided link: https://tokpedplay-fritzie.000webhostapp.com.

Please note that this link serves as the base URL for making API requests to the server. Make sure to include the relevant endpoints in your requests as needed.


## **How to run in local**

**Pre-requisites**

Node.js and npm installed on your machine.

**Instructions**

1. Clone the repository to your local machine:

```
git clone https://github.com/Fritzie1860/frontend-tokpedplayclone.git
```

2. Install the required npm packages:
```
   npm install
```

3. Replace the URL: 

Since environment variables aren't utilized in this setup, please be aware that you'll need to manually adjust the URLs if you're switching between local development and production environments. Also, if you're running the backend on a different port, make sure to update the backend port. 

4. Running:

If you're running the backend separately, start the server using either of the following commands:
```
   npm start
```
To run the frontend and backend together, you may need to see this [repository](https://github.com/Fritzie1860/FinalProject-TokpedPlayClone).