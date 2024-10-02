
# Assigment : React-Node.js
## Table of Contents
- [Assignment: React-Node.js](#assignment-react-nodejs)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Running the Application](#running-the-application)
- [Dependencies](#dependencies)

## Assignment: React-Node.js
This project replicates the frontend of an Airbnb-style hotel booking website using React.
The application displays hotel information fetched from a backend API built with Express.js, which contains data corresponding to the frontend's hotel details. It includes features like shimmer loading for an improved user experience and 404 page handling for invalid routes, ensuring a smooth and user-friendly interface.
 
** TODO: Implement Backend 

## Features

- Responsive design for 
- desktop and mobile
- Shimmer loading while 
- fetching data
- Use configuration JSON file for static values, such as the API base URL.
- 404 page for unknown 
- Reusable React components


## Technologies Used

- React
- React Router
- Shimmer Loader

## Project Structure 

```
project/
├── public/               
├── config.json           
│   
├── src/                            
│   ├── components/                        
│   ├── App.js            
│   ├── index.js           
│   └── ...
├── .gitignore             
├── package.json           
├── README.md             
```

## Setup and Installation
- Clone project
  ```bash
  https://github.com/samayunPathan/React-assignment.git
  ``` 
- Navigate to the frontend directory:
```bash
cd React-assignment
```

- Install dependencies:
```bash
npm install
```


## Running the Application

Start the development server:
```bash
npm start
```

Access the application at your own base url which store at config.json 

## Routes

`/hotel/:hotelSlug: `Display details for a specific hotel
`*: 404 page for unknown routes`

## Configuration

`src/config.json`
Contains API base URL and other static values

## Dependencies
- React Router Dom
- Shimmer Loder
  

