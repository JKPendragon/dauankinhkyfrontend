- Deploy frontend to the vercel : 
Step 1: create .env file with the content : 
REACT_APP_API_URL=https://dauankinhkybackend-production.up.railway.app/api
Step 2: go to src/services/api.js, change baseURL to : baseURL: process.env.REACT_APP_API_URL,
Step 3: commit and replace all the file in the github it will autumation Deploy into vercel.