<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portfolio of Sriram Ramakrishnan, representing EXITO CREATORS.">
    <title>Sriram Ramakrishnan | EXITO CREATORS Portfolio</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #333; margin: 0; padding: 0; background-color: #f9f9f9; }
        header { background: #fff; padding: 2rem; text-align: center; border-bottom: 3px solid #007bff; }
        .container { max-width: 900px; margin: auto; padding: 20px; }
        img { max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); margin-top: 10px; }
        
        .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; margin-top: 20px; }
        section { background: white; padding: 20px; margin-bottom: 20px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05); }
        
        nav a { margin: 0 10px; text-decoration: none; color: #007bff; font-weight: bold; }
        
        form { display: flex; flex-direction: column; gap: 15px; max-width: 400px; }
        input, textarea { padding: 10px; border: 1px solid #ccc; border-radius: 4px; }
        button { background: #007bff; color: white; border: none; padding: 10px; cursor: pointer; border-radius: 4px; }
        button:hover { background: #0056b3; }
        
        footer { text-align: center; padding: 20px; color: #777; }
    </style>
</head>
<body>

<header role="banner">
    <!-- Updated Logo Filename -->
    <img src="exito-creators-logo.jpg" alt="EXITO CREATORS Logo" width="200">
    <h1>Sriram Ramakrishnan</h1>
    <nav role="navigation" aria-label="Main Navigation">
        <a href="#about">About</a> | <a href="#certs">Certifications</a> | <a href="#contact">Contact</a>
    </nav>
</header>

<main class="container">
    <section id="about">
        <h2>About Me</h2>
        <img src="profile.png" alt="Professional portrait of Sriram Ramakrishnan" width="300">
        <p>I am a technology enthusiast representing EXITO CREATORS. Passionate about applying modern standards to build accessible and efficient digital solutions.</p>
        <img src="lifestyle.jpg" alt="Sriram Ramakrishnan outdoors" width="300">
    </section>

    <section id="certs" aria-labelledby="certs-heading">
        <h2 id="certs-heading">Certifications</h2>
        <div class="gallery">
            <article>
                <h3>AI in Action</h3>
                <img src="cert-ai.jpg" alt="Certificate of Completion: AI in Action Job Simulation">
            </article>
            <article>
                <h3>Drone Technology</h3>
                <img src="cert-drone.jpg" alt="Certificate of Participation: Foundations of Drone Technology">
            </article>
            <article>
                <h3>AI in Pharma</h3>
                <img src="cert-pharma.jpg" alt="Certificate of Skill Competency: AI in Pharma">
            </article>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="#" method="POST" aria-label="Contact Form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <button type="submit">Send Message</button>
        </form>
    </section>
</main>

<footer role="contentinfo">
    <p>Developed and maintained by EXITO CREATORS.</p>
</footer>

</body>
</html>
