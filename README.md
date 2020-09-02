# Deploy React website 
 # install 
- npm install --save gh-pages
 
 # เพิ่มไปยังpackage.json
- "homepage": "https://ชื่อผู้ใช้.github.io/ชื่อโปรเจค/",  
- “predeploy”: “npm run build”,
- “deploy”: “gh-pages -d build”,

----------------------------------------------------------------------------------------------------
- "name": "chueproject",
-  "version": "0.1.0",
-   "homepage": "https://ชื่อผู้ใช้.github.io/ชื่อโปรเจค/",   <-------------------------
-   "private": true,
-   "dependencies": {
-     "@testing-library/jest-dom": "^4.2.4",
-     "@testing-library/react": "^9.5.0",
-     "@testing-library/user-event": "^7.2.1",
-     "gh-pages": "^3.1.0",
-     "react": "^16.13.1",
-     "react-dom": "^16.13.1",
-     "react-scripts": "3.4.1"
-   },

-----------------------------------------------------------------------------------------------------
- "scripts": {
-  "predeploy": "npm run build",    <-------------------------
-  "deploy": "gh-pages -d build",   <-------------------------
-  "start": "react-scripts start",
-  "build": "react-scripts build",
-  "test": "react-scripts test",
-  "eject": "react-scripts eject"
- },

