# First-website
<!DOCTYPE html>
<html>

<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Jose Enrique Funez | Portafolio</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css"
        integrity="sha512-NhSC1YmyruXifcj/KFRWoC561YpHpc5Jtzgvbuzx5VozKpWvQ+4nXhPdFgmx8xqexRcpAglTj9sIBWINXa8x5w=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css" />
    <link rel="stylesheet" type="text/css" href="assets/css/main.css" />
    <link rel="stylesheet" type="text/css" href="assets/css/fonts.css" />
    <link rel="stylesheet" type="text/css" href="assets/css/utils.css" />
    <link rel="stylesheet" type="text/css" href="assets/css/sections.css" />
    <link rel="stylesheet" type="text/css" href="assets/css/header.css" />
    <link rel="stylesheet" type="text/css" href="assets/css/nav.css" />
    <link rel="stylesheet" type="text/css" href="assets/css/portfolio.css" />
    <link rel="stylesheet" type="text/css" href="assets/css/skillset.css" />
    <link rel="stylesheet" type="text/css" href="assets/css/experience.css" />
    <link rel="stylesheet" type="text/css" href="assets/css/contact.css" />

</head>

<body>
    <header>
        <img class="circle" src="assets/img/logos/large.png" alt="logo large" />
        <h1>Jose Enrique Funez</h1>
        <hr />
        <h2>Programmer</h2>
        <video autoplay loop muted>
            <source src="assets/video/hero.mp4" />
        </video>
    </header>
    <nav id="navbar" class="open">
        <div>
            <a href="/">
                <img class="circle" src="assets/img/logos/small.png" alt="small logo" />
                <span>Jose Enrique Funez <small>Programmer</small></span>
            </a>
            <button id="hamburger">☰</button>
        </div>
        <ul>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#skillset">Skillset</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="portfolio">
            <h3>Portfolio</h3>
            <hr />
            <div>
                <button>
                    <img src="assets/img/portfolio/1.png" />
                    <h4>Project 1</h4>
                </button>
                <button>
                    <img src="assets/img/portfolio/2.png" />
                    <h4>Project 2</h4>
                </button>
                <button>
                    <img src="assets/img/portfolio/3.png" />
                    <h4>Project 3</h4>
                </button>
            </div>
        </section>
        <section id="skillset" class="even">
            <h3>Skillset</h3>
            <hr />
            <div>
                <div>
                    <img src="assets/img/skillset/html.svg" />
                    <span class="tooltip">HTML</span>
                </div>
                <div>
                    <img src="assets/img/skillset/css.svg" />
                    <span class="tooltip">CSS</span>
                </div>
                <div>
                    <img src="assets/img/skillset/js.svg" />
                    <span class="tooltip">Javascript</span>
                </div>
    
            </div>
        </section>
        <section id="experience">
            <h3>Experience</h3>
            <hr />
            <div>
                <a>
                    <img src="assets/img/experience/1.svg" />
                    <h4>Trabajo 1</h4>
                </a>
                <a>
                    <img src="assets/img/experience/2.svg" />
                    <h4>Trabajo 2</h4>
                </a>
                <a>
                    <img src="assets/img/experience/3.svg" />
                    <h4>Trabajo 3</h4>
                </a>
                <a>
                    <img src="assets/img/experience/4.svg" />
                    <h4>Trabajo 4</h4>
                </a>
            </div>
        </section>
        <section id="contact" class="even">
            <h3>Contact</h3>
            <hr />
            
            <form action="" method="POST">
                <label>
                    Your email:
                    <input type="email" name="_replyto">
                </label>
                <label>
                    Your message:
                    <textarea name="message"></textarea>
                </label>
                <button type="submit">Send</button>
            </form>
       
        </section>
    </main>
    <footer>
        <small>Developed and designed by Tu Jose Funez. ©2022. All rights reserved.</small>
    </footer>
</body>

</html>
