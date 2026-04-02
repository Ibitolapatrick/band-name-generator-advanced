# 🎸 Band Name Generator
A dynamic web app built with Node.js and Express that generates random band names. This project focuses on the Request-Response cycle and server-side rendering.

# ⚡ Key Features
POST Route Handling: Processes form submissions to trigger name generation.

EJS Templating: Uses embedded logic to dynamically update the UI.

Conditional Rendering: Utilizes locals to switch between the "Welcome" state and the "Result" state as well as the implementation of 
partials, and the concept of "static" images and styles.

# 🛠️ Tech
Backend: Node.js, Express.js

Frontend: EJS, HTML5, CSS3

# 📖 Main Takeaway
The biggest challenge was managing Data Flow. I learned how to capture data on the server during a POST request and pass it back to the client safely using EJS tags (<%= %>) and logical guards (if/else).
![Project Preview](/band-generator.png)
