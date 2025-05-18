# 📚 CRUD Books using Spring Webflux

## 🐳 *MongoDB Installation Guide using Docker*

### Overview 🧐

This guide will walk you through the process of setting up MongoDB using Docker, a popular containerization platform. By following these steps, you will be able to deploy a MongoDB instance with ease.

#### Prerequisites ✅

Before you begin, ensure that you have Docker installed on your machine. If you haven't installed it yet, you can download and install it from the [official Docker website](https://www.docker.com/get-started).

### Installation Steps 👇

#### Step 1: Download the MongoDB Docker Image 📥

Open your terminal and run the following command to download the official MongoDB Docker image:

```bash
sudo docker pull mongo
```

#### Step 2: Run the MongoDB Container ▶️

```bash
sudo docker run -d -p 27017:27017 --name my-reactive-mongo-container mongo
```

This command will:

 - -d: Run the container in the background (detached mode).
- -p 27017:27017: Map the local port 27017 to the container's port 27017.
- --name my-reactive-mongo-container: Assign a name to the container for easy reference.
- mongo: Name of the Docker image.

#### Step 3: Connect with MongoDB Compass 🧭

Now that your MongoDB container is running, you can use MongoDB Compass, a graphical user interface for MongoDB, to interact with your database.

Install MongoDB Compass on your machine from the [official website](https://www.mongodb.com/try/download/compass).

Open MongoDB Compass and connect to the MongoDB server at _**mongodb://localhost:27017**_
