# Application
Petful - Server

## Built By
Jared Angel Escobedo

## Links
Live site: https://petful-client-cyan-six.vercel.app  
Server: https://fathomless-depths-11895.herokuapp.com   
Client Repo: https://github.com/JaredAngel/petful-client  
Server Repo: https://github.com/JaredAngel/petful-server-side

### Summary
This app demonstrates a pet adoption application that implements a queue data structure in JavaScript, React, and Node.js

## Technologies
- Front End
  * HTML
  * CSS
  * JavaScript
  * React
- Back End
  * Node.js
  * Express

## API
GET: `/people` - { person1, person2, person3 } // view all people in queue  
POST: `/people` - { person1 } // add a name to queue  
GET: `/pets/cats` && `/pets/dogs` - {name, breed, gender, age, story, description } // pet details  
DELETE: `/pets/cats` && `/pets/dogs` // remove pet from adoption queue
