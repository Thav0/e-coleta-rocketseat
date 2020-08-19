
<h3 align="center">
  Next Week #1 Rocketseat - E-Coleta
</h3>

## :rocket: About the project
<p>
This project is about a small Organic disposals station marketplace, establishing a connection between companies that collect organic / non-organic waste with people who need to dispose of this waste
</p>

<b>Main knowledge acquired in this project:</b>
- What is an APIRestful
  - If our API follows the REST patterns we have a RESTful api
- Typescript
  - Typescript is a superset, we can call it a language, it's a javascript with super powers
  - Why should we use typescript?
   - When working in a group, it helps us a lot to know what a particular function will receive or send, as it improves the editor's IntelliSense, allowing to determine the properties of some function or object

<p align="center">
  <img alt="Frontend" src="https://i.imgur.com/qSlD1Py.jpg" width="100%">
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
- DeepLinking (Whatsapp / Mail)

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
