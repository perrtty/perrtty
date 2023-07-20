<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous">
    <link rel="stylesheet" href="./css/style.css">
  </head>
  <body>
    <header>
        <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"><img id="im1" src="./images/new logo.png" alt="" width="200px" height="100px"></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        
        
        
      </ul>
      <form class="d-flex" role="search">
        <button class="btn  me-2" type="submit" style="position: relative;left: 650px;margin-left: 90px;"><img src="./images/new search.png" alt="" width="30px" height="30px" style="
          position: relative;"></button>
         <input class="form-control me-2" type="search" aria-label="Search" style="width: 20%;position: relative;left: 670px;">
      </form>
      &nbsp &nbsp &nbsp &nbsp &nbsp;
      <!-- Button trigger modal -->
      <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal" style="
      position: relative;
      left: 500px;">
         Login
          </button>
  
  <!-- Modal -->
  <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="exampleModalLabel">Modal title</h1>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          ...
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
          <button type="button" class="btn btn-primary">Save changes</button>
        </div>
      </div>
    </div>
  </div>
  &nbsp &nbsp &nbsp &nbsp &nbsp;
  <button class="btn" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight" style="
    position: relative;
    left:490px;"><img src="./images/three strip images.png" alt="" width="30px" height="30px"></button>

  <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasRight" aria-labelledby="offcanvasRightLabel">
    <div class="offcanvas-header">
      <h5 class="offcanvas-title" id="offcanvasRightLabel">Offcanvas right</h5>
      <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
    </div>
    <div class="offcanvas-body">
      ...
    </div>
  </div>
    </div>
  </div>
</nav>
    </header>
    <section>
      <div class="bg1">
        <h1 id="bg2">11+ New Escapes</h1>
        <p id="bg2">Endless stories to tell</p>
        <p id="bg2">Nice | Malaga | Mykonos | Beijing | Birmingham | Johannesburg | Dar Es Salaam | Kano | Chittago...</p>
        <button type="button" class="btn">Book now</button>
      </div>
    </section>
    <section>
       <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="ch1">
              <ul class="nav nav-pills mb-3" id="pills-tab" role="tablist">
                <li class="nav-item" role="presentation">
                  <button class="nav-link active" id="pills-home-tab" data-bs-toggle="pill" data-bs-target="#pills-home" type="button" role="tab" aria-controls="pills-home" aria-selected="true">Home</button>
                </li>
                <li class="nav-item" role="presentation">
                  <button class="nav-link" id="pills-profile-tab" data-bs-toggle="pill" data-bs-target="#pills-profile" type="button" role="tab" aria-controls="pills-profile" aria-selected="false">Profile</button>
                </li>
                <li class="nav-item" role="presentation">
                  <button class="nav-link" id="pills-contact-tab" data-bs-toggle="pill" data-bs-target="#pills-contact" type="button" role="tab" aria-controls="pills-contact" aria-selected="false">Contact</button>
                </li>
                <li class="nav-item" role="presentation">
                  <button class="nav-link" id="pills-contact-tab" data-bs-toggle="pill" data-bs-target="#pills-contact" type="button" role="tab" aria-controls="pills-contact" aria-selected="false">Contact</button>
                </li>
              </ul>
              <div class="tab-content" id="pills-tabContent">
                <div class="tab-pane fade show active" id="pills-home" role="tabpanel" aria-labelledby="pills-home-tab" tabindex="0">
                  
                </div>
                <div class="tab-pane fade" id="pills-profile" role="tabpanel" aria-labelledby="pills-profile-tab" tabindex="0">...</div>
                <div class="tab-pane fade" id="pills-contact" role="tabpanel" aria-labelledby="pills-contact-tab" tabindex="0">...</div>
                <div class="tab-pane fade" id="pills-contact" role="tabpanel" aria-labelledby="pills-contact-tab" tabindex="0">...</div>
              </div>
            </div>
          </div>
        </div>
       </div>
      
    </section>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-geWF76RCwLtnZ8qwWowPQNguL3RmwHVBC9FhGdlKrxdiJJigb/j/68SIy3Te4Bkz" crossorigin="anonymous"></script>
  </body>
</html> 
css

media screen {
    .offcanvas {
        position: relative;
        left: 200px;
    }
    .form-contro2{
         border-radius: 3rem !important;
    }
    .form-control{
        width: 20% !important;
    }
    .bg-body-tertiary {
        /* --bs-bg-opacity: 1; */
         background-color: #171727!important; 
         
    }
    
}
#im1{
    background-color: #171727;
}
.bg1{
    width: 100%;
    height: 400px;
    background-image: url(../images/background\ img.jpg);
    background-size: cover;
}
#bg2{
    color: white;
    position: relative; left: 80px;
    position: relative;top: 100px;
    
}
.bg1 button{
    color: white;
    position: relative;top: 120px;
    position: relative;left: 80px;
}
.btn {
    border-color: rgb(184, 157, 91);
    background-color: rgb(184, 157, 91);
    
}
.ch1{
    width: 100%;
    height: 200px;
    background-color:whitesmoke

    
}
#pills-tab{
    padding-left: 10px;
    padding-top: 10px;
}
#pills-home input{
    position: relative;left: 50px;
    
}
section{
    background-color: #171727;
}
    

