<!DOCTYPE html>
<html>
<head>
	<title>Bootstrap </title>
     
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">



  <style>

  .carousel-inner img {
    width: 100%;
    height: 92vh;
    display:inline-block;
    box-sizing: border-box;

  }
  .navbar{
  	height:8vh;
  }
  </style>

</head>
<body>
      <section >
       
      
       <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <a class="navbar-brand" href="#">Entertainment Guru</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Dropdown
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </li>
    
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>


<!--carousel -->
<div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
    <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://cdn.statically.io/img/3.bp.blogspot.com/-mqXByTDrhKg/XKPi7Ts2U1I/AAAAAAAABJ0/0ffMH4nm_8YXp5R_qhKnv0jYhGu5UGNWwCKgBGAs/w0/avengers-endgame-thor-stormbreaker-minimalist-uhdpaper.com-4K-58.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>First slide label</h5>
        <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://avante.biz/wp-content/uploads/Nature-HD-Wallpapers-Download/Nature-HD-Wallpapers-Download-028.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>Second slide label</h5>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://images8.alphacoders.com/587/587852.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>Third slide label</h5>
        <p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p>
      </div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
</section>


<section>
	<div class="container-fluid">
		<h1 class="text-center text-capitalize pt-5">about us</h1>
		<hr class="w-25 pb-5">

       <div class="row">
       	  <div class=" col-lg-6 col-md-6   pb-4">
       	  	<img src="https://images8.alphacoders.com/587/587852.jpg" class="img-fluid">
       	  </div>
       	  <div class="col-md-6 col-lg-6 pr-4">
       	  	<h4 class="rext-center text-capitalize"> this is my first browser</h4>
       	  	<hr class="pb-2">
       	  	<p>And one thing more, i made this website by usig bootstrap.For more straightforward sizing in CSS, we switch the global box-sizing value from content-box to border-box. This ensures padding does not affect the final computed width of an element, but it can cause problems with some third party software like Google Maps and Google Custom Search EngineLorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum</p>
       	  	<button class="btn btn-lg bg-primary ">Read more</button>
       	  </div>
       </div>

	</div>
</section>

<section>
		<div class="container pb-5">
			<h1 class="text-center pt-5 ">Services</h1>
			<hr class="pt-3 w-25">

			<div class=row>

				<div class="col-md-4 col-lg-4 ">
					<div class="card" style="width: 18rem;">
		               <img src="https://i2.wp.com/www.smartprix.com/bytes/wp-content/uploads/2018/02/wp5429982-neon-marvel-wallpapers.jpg?resize=1920%2C1080&ssl=1" class="card-img-top" alt="...">
		                 <div class="card-body">
		                   <h5 class="card-title">Web Developer</h5>
		                  <p class="card-text">Some example text</p>
		                  <a href="#" class="btn btn-primary">Save</a>
		                </div>
                   </div>
                </div>
                
                	<div class="col-md-4 col-lg-4 ">
					<div class="card" style="width: 18rem;">
		               <img src="https://i2.wp.com/www.smartprix.com/bytes/wp-content/uploads/2018/02/wp5429982-neon-marvel-wallpapers.jpg?resize=1920%2C1080&ssl=1" class="card-img-top" alt="...">
		                 <div class="card-body">
		                   <h5 class="card-title">Web Developer</h5>
		                  <p class="card-text">Some example text</p>
		                  <a href="#" class="btn btn-primary">Save</a>
		                </div>
                   </div>
                </div>

                	<div class="col-md-4 col-lg-4 ">
					<div class="card" style="width: 18rem;">
		               <img src="https://i2.wp.com/www.smartprix.com/bytes/wp-content/uploads/2018/02/wp5429982-neon-marvel-wallpapers.jpg?resize=1920%2C1080&ssl=1" class="card-img-top" alt="...">
		                 <div class="card-body">
		                   <h5 class="card-title">Web Developer</h5>
		                  <p class="card-text">Some example text</p>
		                  <a href="#" class="btn btn-primary">Save</a>
		                </div>
                   </div>
                </div>
	       
	

           </div>

	</div>
</section>

<section>
	<article>
		<div class="bg-primary text-center mx-auto mb-5 pb-2 pt-2 text-white">
			<p class=" text-center display-4 ">+91 6350321618</p>
			<p>If you wants to call me then after 5pm you an call me</p>
			<button class="btn btn-warning btn-lg">Contact</button>
		</div>
	</article>
</section>

<section>
	<div class="container ">
		<div class="text-center mb-4 ">
			<h1>Gallery</h1>
			<hr class="w-25">
		</div>
		<div class="row">
			<div class="col-sm-6 col-md-3 col-lg-3 mb-2">
				<div class="img-thumbnail">
				<img src="https://image-cdn.hypb.st/https%3A%2F%2Fhypebeast.com%2Fimage%2F2018%2F03%2Fdonald-glover-fx-deadpool-animated-tv-series-cancelled-01.jpg?quality=95&w=1170&cbr=1&q=90&fit=max" class="img-fluid"></div>
			</div>
				<div class="col-sm-6 col-md-3 col-lg-3 mb-2">
				<div class="img-thumbnail">
				<img src="https://image-cdn.hypb.st/https%3A%2F%2Fhypebeast.com%2Fimage%2F2018%2F03%2Fdonald-glover-fx-deadpool-animated-tv-series-cancelled-01.jpg?quality=95&w=1170&cbr=1&q=90&fit=max" class="img-fluid"></div>
			</div>

	<div class="col-sm-6 col-md-3 col-lg-3 mb-2">
				<div class="img-thumbnail">
				<img src="https://image-cdn.hypb.st/https%3A%2F%2Fhypebeast.com%2Fimage%2F2018%2F03%2Fdonald-glover-fx-deadpool-animated-tv-series-cancelled-01.jpg?quality=95&w=1170&cbr=1&q=90&fit=max" class="img-fluid"></div>
			</div>

	<div class="col-sm-6 col-md-3 col-lg-3 mb-2">
				<div class="img-thumbnail">
				<img src="https://image-cdn.hypb.st/https%3A%2F%2Fhypebeast.com%2Fimage%2F2018%2F03%2Fdonald-glover-fx-deadpool-animated-tv-series-cancelled-01.jpg?quality=95&w=1170&cbr=1&q=90&fit=max" class="img-fluid"></div>
			</div>

     	<div class="col-sm-6 col-md-3 col-lg-3 mb-2">
				<div class="img-thumbnail">
				<img src="https://image-cdn.hypb.st/https%3A%2F%2Fhypebeast.com%2Fimage%2F2018%2F03%2Fdonald-glover-fx-deadpool-animated-tv-series-cancelled-01.jpg?quality=95&w=1170&cbr=1&q=90&fit=max" class="img-fluid"></div>
			</div>


    	<div class="col-sm-6 col-md-3 col-lg-3 mb-2">
				<div class="img-thumbnail">
				<img src="https://image-cdn.hypb.st/https%3A%2F%2Fhypebeast.com%2Fimage%2F2018%2F03%2Fdonald-glover-fx-deadpool-animated-tv-series-cancelled-01.jpg?quality=95&w=1170&cbr=1&q=90&fit=max" class="img-fluid"></div>
			</div>

        	<div class="col-sm-6 col-md-3 col-lg-3 mb-2">
				<div class="img-thumbnail">
				<img src="https://image-cdn.hypb.st/https%3A%2F%2Fhypebeast.com%2Fimage%2F2018%2F03%2Fdonald-glover-fx-deadpool-animated-tv-series-cancelled-01.jpg?quality=95&w=1170&cbr=1&q=90&fit=max" class="img-fluid"></div>
			</div>
			 	<div class="col-sm-6 col-md-3 col-lg-3 mb-2">
				<div class="img-thumbnail">
				<img src="https://image-cdn.hypb.st/https%3A%2F%2Fhypebeast.com%2Fimage%2F2018%2F03%2Fdonald-glover-fx-deadpool-animated-tv-series-cancelled-01.jpg?quality=95&w=1170&cbr=1&q=90&fit=max" class="img-fluid"></div>
			</div>
		</div>
	</div>
</section>

<section>
	<div class="text-center bg-primary pb-3 pt-3 mb-4">
		<p class="display-4">Want To Join</p>
		<p>Be a part of Entertainment guru</p>
		<button class="btn btn-lg btn-warning" data-toggle="modal" data-target="#myModal">Join Now</button>
	</div>

      
  <!-- The Modal -->
  <div class="modal" id="myModal">
    <div class="modal-dialog">
      <div class="modal-content">
      
        <!-- Modal Header -->
        <div class="modal-header">
          <h4 class="modal-title">Signup</h4>
          <button type="button" class="close" data-dismiss="modal">&times;</button>
        </div>
        
        <!-- Modal body -->
        <div class="modal-body">
                <form action="/action_page.php">
                  <div class="form-group">
                    <label for="email">Email address:</label>
                    <input type="email" class="form-control" placeholder="Enter email" id="email">
                  </div>
                  <div class="form-group">
                    <label for="pwd">Password:</label>
                    <input type="password" class="form-control" placeholder="Enter password" id="pwd">
                  </div>
                 <div class="form-group form-check">
                    <label class="form-check-label">
                      <input class="form-check-input" type="checkbox"> Remember me
                    </label>
                  </div>
                  <button type="submit" class="btn btn-primary">Submit</button>
                </form>         
        </div> 
      </div>
    </div>
  </div>

</section>

<section>
	<div class="container mb-4">
		<h1 class="text-center ">Contact Us</h1>
		<hr class="w-25">
	
	<div class=" ">
		<form action="/action_page.php">
  <div class="form-group ">
    <label for="name">Name</label>
    <input type="name" class="form-control" placeholder="Enter name" id="name">
  </div>
  <div class="form-group">
    <label for="email">Email</label>
    <input type="email" class="form-control" placeholder="enter email" id="email">
  </div>
   <div class="form-group">
    <label for="mobile">Mobile</label>
    <input type="mobile" class="form-control" placeholder="enter mobile number" id="mobile">
  </div>
   <div class="form-group">
    <label for="text">message</label>
    <input type="text" class="form-control" placeholder="enter text" id="text">
  </div>
  <div class="form-group form-check">
    <label class="form-check-label">
      <input class="form-check-input" type="checkbox"> Remember me
    </label>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
	</div>
	</div>
</section>




<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<!-- Popper JS -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>

<!-- Latest compiled JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>

       
</body>
</html>
