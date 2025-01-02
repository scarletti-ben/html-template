# html-template
Simple HTML / CSS / JavaScript project template for personal use

## Testing the Project on a Local Server
```powershell
C:\...\project> python -m http.server
Serving HTTP on :: port 8000 (http://localhost:8000/) ...
::1 - - [02/Jan/2025 06:55:52] "GET / HTTP/1.1" 200 -
::1 - - [02/Jan/2025 06:55:52] "GET /styles.css HTTP/1.1" 200 -
::1 - - [02/Jan/2025 06:55:52] "GET /script.js HTTP/1.1" 200 -
::1 - - [02/Jan/2025 06:55:52] "GET /test.txt HTTP/1.1" 200 -
::1 - - [02/Jan/2025 06:55:53] code 404, message File not found
::1 - - [02/Jan/2025 06:55:53] "GET /favicon.ico HTTP/1.1" 404 -
::1 - - [02/Jan/2025 06:56:11] "GET / HTTP/1.1" 304 -
```

Files can be accessed relative to the domain root 
- http://localhost:8000/styles.css
- http://localhost:8000/script.js
- http://localhost:8000/index.html
