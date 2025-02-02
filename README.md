# Build and Deploy a Full Stack E-Commerce App with an Admin Dashboard & CMS in 2024 | Next 14, Stripe
![e-commerce](https://i.ibb.co/Y3Hsth3/YT-Thumbnails-3.png)

---
<!--  -->
## **Table of Contents**
- [Overview](#overview)
- [Monolithic Structure](#monolithic-structure)
- [Get Started](#get-started)
---

## **Overview**
This repository is a **NextJS CMS** designed for a scalable monolithic architecture. The project is divided into multiple services and shared libraries, enabling modular development and efficient code sharing.

## Key Features:

- Modular service design
- Shared libraries for common functionality
- Hot-reloading with Webpack
- Configurable environment files for each service
- Scalable architecture for future growth
---

## **Monolithic Structure**
The repository is structured as follows:

```bash
src/                # Applications
  app/              # App folder is where frontend related components are kept
  payload/          # Payload Folder is where backend admin related components are kept

public/                # Static Files
  admin ui/            # Common static file used in the admin components
  assets/              # Common static file used in multiple components


next.config.json        # Configuration file for Nextjs project
tsconfig.json        # TypeScript configuration
package.json         # Project metadata and scripts
src/payload/payload.config.ts    # This file is the configuration file for the backend admin

```

## **Get Started**

## **Dependencies**
- [NodeJs](#nodejs) for local setup
- [Docker](#docker) for container setup


### Step by Step method
This application rely on the installation of NodeJs and Docker in the Host machine...Kindly download this before running the program...
I will encourage you to use the docker approach which is way easier than the native NodeJs approach due to less terminal commands..

### Step bey Step -> Docker Approach 
This application rely on the installation of Docker in the Host machine...Kindly download this before running the program...

## Note: 
i exposed the .env files so you can test and use my keys temporarily for few month...Exposing .env files when committing is a bad approach
because i want to make deployment easy for tester for my school project that is why i expose these keys...

## **Use Docker Compose File**
```
docker compose up -d
```

## **App Running**

| Application   | URL                           |
|--------------|------------------------------|
| Client App   | [localhost:3000](http://localhost:3000)       |
| Admin Panel  | [localhost:3000/admin](http://localhost:3000/admin) |

