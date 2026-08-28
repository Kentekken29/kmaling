<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f8f7ff;
            color: #222;
        }

        header {
            text-align: center;
            padding: 30px 20px;
            background: white;
            border-bottom: 1px solid #ddd;
        }

        header h1 {
            margin: 0 0 15px;
            font-size: 32px;
        }

        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #5b35b5;
            font-weight: bold;
        }

        section {
            text-align: center;
            padding: 50px 20px;
        }

        .intro {
            background: white;
        }

        .intro h2 {
            font-size: 28px;
            margin-bottom: 10px;
        }

        .intro p {
            color: #666;
        }

        .cards {
            display: flex;
            justify-content: center;
            gap: 25px;
            flex-wrap: wrap;
        }

        .card {
            background: white;
            padding: 25px;
            width: 250px;
            border-radius: 10px;
            box-shadow: 0 3px 10px #ddd;
        }

        .card h3 {
            color: #5b35b5;
        }

        form {
            display: flex;
            justify-content: center;
            gap: 10px;
            flex-wrap: wrap;
        }

        input, textarea {
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 6px;
        }

        input {
            width: 220px;
        }

        textarea {
            width: 300px;
            height: 80px;
        }

        button {
            padding: 12px 20px;
            border: none;
            border-radius: 6px;
            background: #5b35b5;
            color: white;
            cursor: pointer;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: white;
            color: #777;
        }
    </style>
</head>

<body>

    <header>
        <h1>Kenneth Maling</h1>

        <nav>
            <a href="#about">About Me</a>
            <a href="#services">My Services</a>
            <a href="#contact">Contact Me</a>
        </nav>
    </header>

    <section class="intro">
        <h2>Hi, I'm Kenneth Maling</h2>
        <p>Welcome to my portfolio.</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>I am a BSIS student who enjoys learning technology and creating simple projects.</p>
    </section>

    <section id="services">
        <h2>My Services</h2>

        <div class="cards">
            <div class="card">
                <h3>Web Development</h3>
                <p>Creating simple and user-friendly websites.</p>
            </div>

            <div class="card">
                <h3>Database Design</h3>
                <p>Designing organized and functional databases.</p>
            </div>

            <div class="card">
                <h3>System Design</h3>
                <p>Planning and designing information systems.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>

        <form>
            <input type="text" placeholder="Your Name">
            <input type="email" placeholder="Your Email">
            <textarea placeholder="Your Message"></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        © 2026 Kenneth Maling
    </footer>

</body>
</html>

  body {
        background-color: darkcyan;
        color: #333333;
        margin: 0;
        padding: 0;
        line-height: 1.6;
    }

    h1 {
        font-size: 2rem;
        font-weight: 400;
        letter-spacing:1rem ;
        padding: 12px;
    }

    header {
        border-bottom: 1px solid burlywood;
        padding: 2px;
        margin-bottom: 6px;
    }

    nav ul {
        list-style: none;
        display: flex;
        gap:10 px;
    }


    nav li {
        display: inline-block;
        margin: 0 15px;
    }

      nav a {
        color: #ffffff;
        text-decoration:none ;
        font-size: 20px;
      }

      nav a:hover {
        color: #f39c12;
      }
ari dui

 body {
        background-color: rgb(0, 0, 5);
        color: #181029;
        margin: 5;
        padding: 50;
        line-height: 1.6;
    }

    h1 {
        font-size: 2rem;
        font-weight: 400;
        text-align: center;
        letter-spacing:1rem ;
        padding: 12px;
    }

    header {
        border-bottom: 5px solid rgb(15, 1, 17);
        padding: 5px;
        text-align: center;
        margin-bottom: 6px;
    }

    nav ul {
        list-style: none;
        display: flex;
        gap:10 px;
    }


    nav li {
        display: inline-block;
        margin: 0 15px;
    }

      nav a {
        color: #070005;
        font-size: 30px;
      }

      nav a:hover {
        color: #000003;
      }
   
     .my-services{color:rgb(0, 0, 0)
     }

     .about-me{color:rgb(0, 0, 0)
     }

     .contact-me{color:rgb(8, 0, 4)
     }



     <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portpolio</title>
    <link rel="stylesheet" href="style.css">

</head>
<body>
    <h1> Carl benedict Ella</h1>  

    <header>
        <nav>
            <ul>
                <li>
                    <a href="#about">About</a>
                </li>
                <li>
                    <a href="#services">Services</a>
                    </li>
                    <li>
                         <a href="#contact">Contact</a></Services>
                    </li>
                </ul>
        </nav>
        </header>
        <main>
        <section  id="about">
            <h2>About me</h2>
            <p class="about-me"> Bawi bawi lang ah </p>
        </section>

        <section id="Services">
            <h2>My Services</h2>
            <p class="my-services"> matutum mag pagusto, dont lose hope </p>
        </section>

        <section id="Contacts">
            <h2>Contact me</h2>
            <form action="#">
                <!-- Name -->
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>
             
                <!-- Email -->
                <label for="email">Email</label>
                <input type="email" id="emial" name="email" required>
               
                <!-- Message -->
                <label for="message">Message</label>
                <textarea name="message" id="message" name="message" rows="5" required></textarea>
               
                <button type="submit">Send Message</button>
            </form>
        </section>
</main>
</body>
</html>