# Web-Development-HTML-CSS-JAVASCRIPT-Task-1
Basics of Web Development
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apexplanet Internship</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Web Development</h1>
        <p>Web development is the process of creating and maintaining websites or web applications that run on the internet.<br> It involves everything from designing how a website looks to making sure it works properly behind the scenes.</p>
        <img src="web.jpg" width="400" alt="image here">

    </header>
    <main>
        <section id="Three main parts of web development">
            <h1>Three main parts of web development:</h1>
            <h1>1.Frontend Development (Client-Side)</h1>
            <p>This is what users see and interact with in their browser.<br>
               Technologies: HTML, CSS, JavaScript, frameworks like React, Vue, or Angular.<br>
               Focuses on layout, design, interactivity, and responsiveness.</p>
            <img src="frontend.jpg" width="300" alt="frontend picture">
        </section>

        <section>
            <h1>2.Backend Development (Server-Side)</h1>
            <p>This handles the logic, database, and server communication.<br>
               Technologies: Node.js, Python, PHP, Ruby, Java, etc.<br>
               Works with databases like MySQL, MongoDB, PostgreSQL, etc.</p>
            <img src="backend.jpg" width="300" alt="backend picture">
        </section>

        <section>
            <h1>3.Full-Stack Development</h1>
            <p>A combination of both frontend and backend.<br>
               Full-stack developers can build an entire web application from scratch, end to end.</p>
            <img src="fullstack.jpg" width="300" alt="fullstack picture">
        
        </section>

        <section id="Key Components of Web Development:">
            <h1>Key Components of Web Development:</h1>
            <p>1.Web Design: UI/UX, layout, color scheme.<br>
               2.Web Programming: Writing code that powers the site.<br>
               3.Web Hosting: Storing your website on a server to make it accessible online.<br>
               4.Databases: Managing and storing data.</p>

        </section>

        <section id="Examples of Web Development:">
            <h1>Examples of Web Development:</h1>
            <p>1.Blogs<br>
               2.E-commerce websites<br>
               3.Social media platforms<br>
               4.Web-based applications</p>

        </section>

    </main>
    <h3>Nice Alert</h3>
    <button onclick="callAlert('Hello from alert')">Call Alert</button>

    
    <script src="script.js"></script>
    <script>
        function callAlert(msg){
            alert(msg, 3000)
        }
    </script>



</body>
</html>
