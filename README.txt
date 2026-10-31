SONY LIV-INSPIRED INDIA vs NEW ZEALAND LANDING PAGE
=================================================

Files:
- index.html : Responsive HTML/CSS/JavaScript landing page
- Dockerfile : Nginx container setup
- README.txt : This guide

Run locally:
1. Extract this ZIP.
2. Open index.html in a browser, or open the folder in VS Code.
3. For VS Code, use the Live Server extension.

Run with Docker:
  docker build -t sonyliv-ind-nz:v1 .
  docker run -d --name sonyliv-ind-nz -p 8080:80 sonyliv-ind-nz:v1

Open:
  http://localhost:8080

The page is an unofficial practice concept, not the official SonyLIV site.
No streaming, login, ticketing, or live score functionality is connected.
The match schedule is displayed as published for the 2026 India tour of New Zealand
and can change. The hero background image is loaded from an external image URL.
