# vue-express-prod-boilerplace

## Usage

1. Install dependencies  
  `npm install`

2. For development environment, just run  
  `npm run dev`

3. For production environment
  - build the project firstly: `gulp build`
  - copy /dist folder to your server
  - install production dependencies inside /dist folder: `npm install --production`
  - start your server by: `NODE_ENV=production PORT=<port> node index.js`
