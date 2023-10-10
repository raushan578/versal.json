# versal.json
While uploading server for testing___ 
Add this_
{  
    "builds": [
      { "src": "index.js",
       "use": "@vercel/node" 
      }
    ],
    "routes": [
      { "src": "/(.*)",
        "dest": "/index.js" 
      }
    ]
  }
