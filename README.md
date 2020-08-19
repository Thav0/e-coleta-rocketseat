
<h3 align="center">
  Next Week #1 Rocketseat - E-Coleta
</h3>

## :rocket: About the project
<p>
The goal of this project was to build a solution for  web app and mobile app to find developers near the client, using distance calculation in a radio of 10km
</p>

<p align="center">
  <img alt="Frontend" src="https://github.com/Rocketseat/semana-omnistack-10/raw/master/.github/devradar.png" width="100%">
</p>


## :airplane: NodeJS

- NodeJS Principles
- HTTP principles
   - HTTP verbs and how to use it properly
- Express
- Insomnia to test API
- Queries with knex
- Axios (Promise based HTTP client for the browser)
- How to use CORS (Security Policy Middleware)
- Migrations / Seed

Libs used:
- Celebrate (validate input data)
- Cors (cross-origin)
- Express (micro-framework to build routes)
- Knex (Query builder)
- Multer (accept multipart/form-data)
- Sqlite3

## :helicopter: ReactJs

- How to choose a technology before start a project
    - Analyse what the market is looking for
    - Check the community e ecosystem around those technologies
    - Who is behind the development
    - Which companies are using the technologies
    - Which cases can we apply it
- Differences between tradicional way and SPA (Single page application)
- React Concepts
    - Components
        - JS Functions
            - Return HTML
    - Props
        - Custom values between components
    - State
        - Source of Data
    - Declarative
    - Virtual DOM
        - React find the best way to re-render the DOM using Virtual DOM
    - Unidirectional Dataflow
- React CLI
- Folder structure
- ES6 functions
- Flexbox
- Interact with maps
- Fetch brazil states/cities Api - IBGE

## :steam_locomotive: React Native

- Tradicional way of developing for Mobile (Objective-C Swift) | (Java Kotlin Android) VS React Native
- How to use EXPO
    - Without expo we need to install Android Studio and Xcode to get SDKs
    - We can test the app inside expo
    - We can access all libraries needed to develop for mobile
- Differences between ReactJS and React Native
- No semantic Tag
- How to use a good folder structure and good practices
- Types of mobile navigation
- How to style elements
- How to use google maps
- Get user current location using mobile GPS permission

### **How to use it**

## Server
cd /server

```
yarn (to install dependencies)

yarn knex:migrate (create tables)
yarn knex:seed (insert default data)

yarn dev
```

## Web
cd /web

```
yarn (to install dependencies)

yarn start

http://localhost:3000/
```

## Mobile
cd /mobile

```
Search for expo on GooglePlay / Apple Store and install it

yarn (to install dependencies)

yarn start

Scan QRCode with expo
```
