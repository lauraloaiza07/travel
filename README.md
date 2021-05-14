<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="icon" type="image" href="imagenes/favicon-removebg-preview.png" sizes="any">
    <title>Travel</title>
    <!-- Bootstrap -->
    <link href="bootstrap-4.3.1.css" rel="stylesheet">
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        <a class="navbar-brand" href="#">Travel</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#servicios">Servicios destacados</a> 
			  </li>
			   <li class="nav-item">
              <a class="nav-link" href="index.html">Productos</a> 
			  </li>
			   <li class="nav-item">
              <a class="nav-link" href="#contacto">Contacto</a> 
			  </li>
			   <li class="nav-item">
              <a class="nav-link" href="https://www.sic.gov.co/turismo" target="_blank">Legal</a> 
			  </li>
			  <li class="nav-item">
              <a class="nav-link" href="formulario.html" target="_blank">Formulario</a> 
			  </li>
          </ul>
          <form class="form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="search" placeholder="Busca aquí" aria-label="Search">
            <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Buscar</button>
          </form>
        </div>
      </div>
    </nav>
    <div class="container mt-3">
      <div class="row">
        <div class="col-12">
          <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
              <li data-target="#carouselExampleControls" data-slide-to="0" class="active"></li>
              <li data-target="#carouselExampleControls" data-slide-to="1"></li>
              <li data-target="#carouselExampleControls" data-slide-to="2"></li>
			  <li data-target="#carouselExampleControls" data-slide-to="3"></li>
			  <li data-target="#carouselExampleControls" data-slide-to="4"></li>
            </ol>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img class="d-block w-100" src="imagenes/1920x500-intercon-bora-bora-thalasso.jpg" alt="First slide">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Bora Bora</h5>
                  <p>Un destino de ensueño</p>
                </div>
              </div>
              <div class="carousel-item">
                <img class="d-block w-100" src="imagenes/1920-x-500-image-18.jpg" alt="Second slide">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Caminata ecologica</h5>
                  <p>La mejor manera de conectar con la naturaleza</p>
                </div>
              </div>
              <div class="carousel-item">
                 <img class="d-block w-100" src="imagenes/dubai.png" alt="Fourth slide">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Dubai</h5>
                  <p>Dejate deslumbrar por la megalopolis</p>
                </div>
              </div>
			  <div class="carousel-item">
                <img class="d-block w-100" src="imagenes/1920X51-2.jpg" alt="Third slide">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Amalfi</h5>
                  <p>Disfruta de lo mejor de la costa italiana</p>
                </div>
              </div>
			  <div class="carousel-item">
                <img class="d-block w-100" src="imagenes/fiji.jpg" alt="Third slide">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Fiji</h5>
                  <p>Un paraiso en la polinesia</p>
                </div>
              </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
            </a>
          </div>
        </div>
      </div>
      <hr>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-4">
          <div class="row">
            <div class="col-2"><img class="rounded-circle" alt="Free Shipping" src="imagenes/folleto.png"></div>
            <div class="col-lg-6 col-10 ml-1">
              <h4>Paquetes todo  incluido</h4>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="row">
            <div class="col-2"><img class="rounded-circle" alt="Free Shipping" src="imagenes/promociones.png"></div>
            <div class="col-lg-6 col-10 ml-1">
              <h4>Promociones todo el año</h4>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="row">
            <div class="col-2"><img class="rounded-circle" alt="Free Shipping" src="imagenes/sin-virus.png"></div>
            <div class="col-lg-6 col-10 ml-1">
              <h4>Turismo bioseguro</h4>
            </div>
          </div>
        </div>
      </div>
    </div>
    <hr>
    <h2 class="text-center" id="servicios">Servicios Destacados</h2>
    <hr>
    <div class="container">
      <div class="row text-center">
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="imagenes/cartagena.jpeg" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Cartagena 4 dias 3 noches</h5>
              <p class="card-text">La hermosa ciudad amurallada te espera con este plan para dos personas, hospedaje en el hotel Costa del sol;todo incluido por tan solo $2'500.000 COP</p>
              <a href="#" class="btn btn-primary">Añadir al carrito</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="imagenes/mpu.jpg" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Machu Picchu</h5>
              <p class="card-text">Explora el antiguo imperio Inca visitando esta maravilla del mundo moderno con tour guiado y completo a tan solo $4'000.000 COP por persona</p>
              <a href="#" class="btn btn-primary">Añadir al carrito</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="imagenes/turismo-nuqui-como-llegar.jpg" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Nuquí</h5>
              <p class="card-text">Un paraíso en la costa Pacifica ideal para el ecoturismo y avistamiento de ballenas jorobadas,no te lo pierdas, disfrutalo por $1'300.000 COP</p>
              <a href="#" class="btn btn-primary">Añadir al carrito</a>
            </div>
          </div>
        </div>
      </div>
		<div class="row text-center mt-4"></div>
	   <div class="col-md-4 pb-1 pb-md-0"></div>
    </div>
    <hr>
    <h2 class="text-center">FEATURED PRODUCTS</h2>
    <hr>
    <div class="container">
      <div class="row">
        <div class="col-lg-4">
          <ul class="list-unstyled">
            <li class="media">
              <img class="mr-3" src="100X125.gif" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">List-based media object</h5>
                Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
              </div>
            </li>
            <li class="media my-4">
              <img class="mr-3" src="100X125.gif" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">List-based media object</h5>
                Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
              </div>
            </li>
            <li class="media">
              <img class="mr-3" src="100X125.gif" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">List-based media object</h5>
                Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
              </div>
            </li>
          </ul>
        </div>
        <div class="col-lg-4">
          <ul class="list-unstyled">
            <li class="media">
              <img class="mr-3" src="100X125.gif" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">List-based media object</h5>
                Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
              </div>
            </li>
            <li class="media my-4">
              <img class="mr-3" src="100X125.gif" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">List-based media object</h5>
                Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
              </div>
            </li>
            <li class="media">
              <img class="mr-3" src="100X125.gif" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">List-based media object</h5>
                Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
              </div>
            </li>
          </ul>
        </div>
        <div class="col-lg-4"> 
          <ul class="list-unstyled">
            <li class="media">
              <img class="mr-3" src="100X125.gif" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">List-based media object</h5>
                Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
              </div>
            </li>
            <li class="media my-4">
              <img class="mr-3" src="100X125.gif" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">List-based media object</h5>
                Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
              </div>
            </li>
            <li class="media">
              <img class="mr-3" src="100X125.gif" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">List-based media object</h5>
                Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <hr>
    <div class="container text-white bg-dark p-4">
		<div class="col-6 col-md-8 col-lg-7"></div>
		<div class="row text-center"></div>
		<div class="col-sm-6 col-md-4 col-lg-4 col-12"></div>
        <div class="col-md-4 col-lg-5 col-6" id="contacto"></div>
          <address>
			 <center>
            <strong>Travel the World.Inc</strong><br>
            Cali, Colombia<br>
            <abbr title="Phone">Tel:</abbr> (+2) 568 3291<br>
            <a href="mailto:#">compras@traveltheworld.com</a>
			 </center>
          </address>
        </div>
    <footer class="text-center">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <p>Copyright© Travel The World 2021. Todos los derechos reservados.</p>
          </div>
        </div>
      </div>
    </footer>
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="jquery-3.3.1.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="popper.min.js"></script>
    <script src="bootstrap-4.3.1.js"></script>
  </body>
</html>
