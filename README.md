# lading-page
PA4 res
[Lading Page.html](https://github.com/user-attachments/files/23917556/Lading.Page.html)
<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <title>Website Template</title>
  <link href="css/bootstrap.css" rel="stylesheet"/>
  <link href="css/style.css" rel="stylesheet"/>
  <script src="js/jquery-3.5.1.js"></script>
  <script src="js/bootstrap.js"></script>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">


  <style>
body{
background-color: #000000;
color: #00ff66;
font-family: "Press Start 2P", system-ui;
  font-weight: 400;
  font-style: normal;
}
.navbar, footer{
background-color: #000000 !important;
}
.nav-link, .navbar-brand, footer a, footer p, footer h5{
color: #00ff66 !important;
}
.jumbotron{
background-color: #0d0d0d;
color: #00ff66;
border: 1px solid #00ff66;
}
.card{
background-color: #0f0f0f;
border: 1px solid #00ff66;
color: #00ff66;
}
.list-group-item{
background-color: #0f0f0f;
border: 1px solid #00ff66;
color: #00ff66;
}
.btn-primary{
background-color: #00ff66;
border-color: #00ff66;
color: #000000;
}
.btn-primary:hover{
background-color: #00cc55;
border-color: #00cc55;
}
h1, h2, h3, h4, h5, h6{
color: #00ff66;
}
.nav-pills .nav-link.active{
background-color: #00bd5b !important;
color: #000000 !important;
}
  </style>




</head>
<body data-spy="scroll" data-target="navbar">
  <nav id="navbar" class="navbar navbar-expand-lg fixed-top navbar-dark bg-dark">
    <a class="navbar-brand font-weight-bold" href="#">Hackers Academy</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown"
      aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="nav nav-pills">
        <li class="nav-item"><a class="nav-link" href="#Home">Inicio</a></li>
        <li class="nav-item"><a class="nav-link" href="#About">Services</a></li>
        <li class="nav-item"><a class="nav-link" href="#Services">Our team</a></li>
        <li class="nav-item"><a class="nav-link" href="#Team">Contact</a></li>
        <li class="nav-item"><a class="nav-link" href="#Contact">Join us</a></li>
      </ul>
    </div>
  </nav>
  <div id="carouselExampleIndicators" class="carousel slide pt-5" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="images/banner1.png" class="d-block w-100" alt="hack banner 1">
        <div class="carousel-caption d-none d-md-block">
          <h5>Keep your information safe</h5>
         <p>Some people may have access to your personal information.</p>
         </div>
      </div>
      <div class="carousel-item">
        <img src="images/banner2.png" class="d-block w-100" alt="hack banner 2">
        <div class="carousel-caption d-none d-md-block">
          <h5>Certified experts</h5>
         <p>Our program has the best experts in information retrieval.</p>
         </div>
      </div>
      <div class="carousel-item">
        <img src="images/banner3.png" class="d-block w-100" alt="hack banner 3">
        <div class="carousel-caption d-none d-md-block">
          <h5>Learn with us</h5>
         <p>Learn from the best experts how to avoid losing information and more.</p>
         </div>
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
  <div class="container-fluid">
    <div class="row">
      <div id="Home" class="col-md-12 pt-6" >
        <div class="jumbotron">
          <h1 class="display-5 bs-success">Get Started</h1>
          <div class="container">
            <div class="row">
              <div class="col-md-7">
                <img src="images/main.jpg" class="imgHome" alt="Gym Home" />
              </div>
              <div class="col-md-5">
                <p class="h5">How to protect your PC in 3 days</p>
                  <ul class="list-group">
                    <li class="list-group-item">Dia 1: Basic Shielding</li>
                    <li class="list-group-item">Dia 2: Protect your identity and your access</li>
                    <li class="list-group-item">Dia 3: Seguridad avanzada y hábitos anti-hacker</li>
                  </ul>
              </div>
            </div>
          </div>
          <hr class="my-4">
          <a class="btn btn-primary btn-lg" href="#About" role="button">Learn more</a>
        </div>
      </div>
    </div>
    <div class="row">
      <div id="About" class="col-md-12 pt-6">
        <div class="card mb-3">
          <div class="row no-gutters">
            <div class="col-md-4">
              <img src="images/about-gym.jpg" class="card-img" alt="About">
            </div>
            <div class="col-md-8">
              <div class="card-body">
                <h3 class="card-title font-weight-bold">About Hackers Academy</h3>
                <h5 class="card-title">Cybersecurity and Ethical Hacking</h5>
                <p class="card-text">
                  We are an academy specializing in cybersecurity, ethical hacking, and vulnerability analysis. Our goal is to train users and professionals in techniques used by experts to protect systems, networks, and applications.
                </p>
                <h5 class="card-title">Classes</h5>
                <p class="card-text">
                  We teach pentesting, malware analysis, web security, OSINT, and digital defense through hands-on labs, CTF-style challenges, and real-world professional tools.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div id="Services" class="col-md-12 pt-6">
        <h2>Services</h2>
        <div class="card-deck">
          <div class="card">
            <img src="images/exercises/crossfit.jpg" class="card-img-top" alt="Cross fit">
            <div class="card-body">
              <h5 class="card-title">Ethical Hacking</h5>
              <p class="card-text">Pruebas legales para descubrir vulnerabilidades antes que los atacantes.</p>
            </div>
          </div>

          <div class="card">
            <img src="images/exercises/Pentesting Avanzado.jpg" class="card-img-top" alt="Cross fit">
            <div class="card-body">
              <h5 class="card-title">Pentesting Avanzado</h5>
              <p class="card-text">Ataques controlados para evaluar la seguridad real de sistemas y redes.</p>
            </div>
          </div>
          
          <div class="card">
            <img src="images/exercises/Digital Forensics.jpg" class="card-img-top" alt="Cross fit">
            <div class="card-body">
              <h5 class="card-title">Análisis Forense Digital</h5>
              <p class="card-text">Investigación de incidentes para identificar qué ocurrió y cómo.</p>
            </div>
          </div>

          <div class="card">
            <img src="images/exercises/OSINT.jpg" class="card-img-top" alt="Outdoor">
            <div class="card-body">
              <h5 class="card-title">OSINT</h5>
              <p class="card-text">Búsqueda de información pública para detectar riesgos y exposición.</p>
            </div>
          </div>
          <div class="card">
            <img src="images/exercises/weightlifting.jpg" class="card-img-top" alt="Weight Lifting">
            <div class="card-body">
              <h5 class="card-title">Red Team</h5>
              <p class="card-text">Simulación de ataques reales para medir la defensa de una organización.</p>
            </div>
          </div>
          <div class="card">
            <img src="images/exercises/yoga.jpg" class="card-img-top" alt="Yoga">
            <div class="card-body">
              <h5 class="card-title">Seguridad Web</h5>
              <p class="card-text">Detección de fallas en sitios y aplicaciones web.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div id="Team" class="col-md-12 pt-6">
        <h2>Nuestros entrenadores</h2>
        <div class="card-group">
          <div class="card">
            <img src="images/trainers/JohnSmith.jpg" class="card-img-top" alt="John Smith">
            <div class="card-body">
              <h5 class="card-title">John Smith “NeonReaper”</h5>
              <p class="card-text">Programming expert</p>
            </div>
          </div>
          <div class="card">
            <img src="images/trainers/JohnDoe.jpg" class="card-img-top" alt="John Doe">
            <div class="card-body">
              <h5 class="card-title">John Doe “ZeroShade”</h5>
              <p class="card-text">Data restoration</p>
            </div>
          </div>
          <div class="card">
            <img src="images/trainers/MarkAdams.jpg" class="card-img-top" alt="Mark Adams">
            <div class="card-body">
              <h5 class="card-title">Mark Adams “DataPhantom”</h5>
              <p class="card-text">Antivirus expert</p>
            </div>
          </div>
          <div class="card">
            <img src="images/trainers/PeterMartin.jpg" class="card-img-top" alt="Peter Martin">
            <div class="card-body">
              <h5 class="card-title">Peter Martin “ChromeSpecter”</h5>
              <p class="card-text">Cybersecurity Advisor</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div id="Contact" class="col-md-12 pt-6">
        <div class="card mb-3">
          <div class="row no-gutters">
            <div class="col-md-4">
              <img src="images/contact.jpg" class="card-img" alt="Contact">
            </div>
            <div class="col-md-8">
              <div class="card-body">
                <h3 class="card-title">Contact</h3>
                <ul class="list-group">
                  <li class="list-group-item">NAME: HackTeam</li>
                  <li class="list-group-item">SOCIAL NETWORKS: GitHub, YouTube, Linkedin</li>
                  <li class="list-group-item">PHONE: (646) 392-7814</li>
                  <li class="list-group-item">EMAIL ADDRESS: Loshacker@gmail.com</li>
                  <form action="#" method="post">
                    <button type="submit" class="btn btn-success">Enviar</button>
                    <input type="email" name="email" placeholder="Ingrese su Gmail">
                  </form>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer class="container-fluid text-light pt-6">
    <div class="row">
      <div class="col-md-4">
        <h5 class="text-uppercase font-weight-bold">Hackers Academy</h5>
        <p>Trust us, we can protect<br/>you from dangerous people.</p>
      </div>
      <div class="col-md-4">
        <h5 class="text-uppercase font-weight-bold">Privacy & Terms</h5>
        <ul class="list-unstyled">
          <li><a href="#Services">Interests</a></li>
          <li><a href="#">Privacy</a></li>
          <li><a href="#">Terms</a></li>
          <li><a href="#Contact">Contact</a></li>
        </ul>
      </div>
      <div class="col-md-4">
        <h5 class="text-uppercase font-weight-bold">Navigation</h5>
        <p>
          <a href="#">Back to top</a>
        </p>
      </div>
    </div>
    <hr class="my-4"/>
    <div class="footer-copyright text-center py-3">
      © 2020 Copyright: <a href="#">Hackers Academy</a>
    </div>
  </footer>
  <script>
    $('body').scrollspy({ target: "#navbar" });
    $('.carousel').carousel({ interval: 2000 })
  </script>
</body>

</html>
