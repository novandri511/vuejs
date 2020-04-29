<template>
    <html>
    <head>
        <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700|Roboto+Slab:400,700|Material+Icons" />
        
    </head>
    <body class="profile-page">

            <v-parallax
                src="../assets/img/bg2.jpg"
                height="300"
            >
            </v-parallax>
            <v-container
            class="mt-n12 mb-0 pb-0"
           
            >
            <v-card
            elevation="12"
            max-width="1600"
            height="1470"
            class="text-center"
           >
            <div class="row">
              <div class="col-md-6 ml-auto mr-auto mb-0 pb-0">
                <div class="col-lg-5 mt-n12 pb-10 ml-auto mr-auto">

                
                <v-img src="../assets/img/faces/20200429_145620.png"
                    alt="me"
                    max-height="180"
                    max-width="180"
                    class="rounded-circle shadow-lg">

                </v-img>
      
                </div>

                <v-card-text >
                   <h2>Rachmadwipa Novandri</h2>
                   
                   <h5 class="text-black-50">
                    FrontEnd Web Developer
                    </h5>
                </v-card-text>
              </div>
            </div>
                <v-col
                >
              
            <div class="text-center mt-n7">

            <v-col
            >
                <a href="#" class="btn btn-just-icon btn-link btn-dribble"> 
                    <v-img
                    src="../assets/icons/040-dribbble.png"
                    max-height="20"
                    max-width="20"
                    color="grey darken-1"
                    >
                    </v-img>
                </a>
                  
                <a href="#" class="btn btn-just-icon btn-link btn-dribble"> 
                    <v-img
                    src="../assets/icons/029-instagram.png"
                    max-height="20"
                    max-width="20"
                    >
                    </v-img>
                </a>
                
                <a href="#" class="btn btn-just-icon btn-link btn-dribble"> 
                    <v-img
                    src="../assets/icons/027-linkedin.png"
                    max-height="20"
                    max-width="20"
                    >
                    </v-img>
                </a>
            </v-col>
            </div>
            </v-col>
            <p class="description text-center">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
            
           
            <div class="row">
                <div class="col-md-6 ml-auto mr-auto">
                    <div class="profile-tabs">

                        <ul class="nav nav-pills nav-pills-icons justify-content-center" id="pills-tab" role="tablist">
                            <li class="nav-item">
                                <a href="#studio" role="tab" id="1a-tab"  data-toggle="pill" class="nav-link active" aria-controls="1a" aria-selected="true">
                                    <i class="material-icons">camera</i>
                                    Studio</a>
                            </li>

                            <li class="nav-item">
                                <a href="#work" role="tab" id="2a-tab" data-toggle="pill" class="nav-link" aria-controls="2a" aria-selected="false">
                                    <i class="material-icons">palette</i> Work</a>
                            </li>
                            <li class="nav-item">
                                <a href="#favorit" role="tab" id="3a-tab" data-toggle="pill" class="nav-link" aria-controls="3a" aria-selected="false">
                                    <i class="material-icons">favorite</i> Favorite</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
                <div class="tab-content tab-space" id="pills-tabContent">
                    <div class="tab-pane show active gallery fade" id="studio" role="tabpanel" aria-labelledby="1a-tab">
                        <div class="row">
                            <div class="col-md-3 ml-auto">
                                <img src="../assets/img/examples/studio-1.jpg" class="rounded">
                                <img src="../assets/img/examples/studio-2.jpg" class="rounded">
                                
                            </div>

                            <div class="col-md-3 mr-auto">
                                <img src="../assets/img/examples/studio-5.jpg" class="rounded">
                                <img src="../assets/img/examples/studio-4.jpg" class="rounded">
                                
                            </div>
                        </div>
                    </div>

                    <div class="tab-pane show text-center gallery fade" id="work" role="tabpanel" aria-labelledby="2a-tab" >
                        <div class="row">
                            <div class="col-md-3 ml-auto">
                                <img src="../assets/img/examples/olu-eletu.jpg" class='rounded'/>
                                <img src="../assets/img/examples/clem-onojeghuo.jpg" class='rounded' />
                                <img src="../assets/img/examples/cynthia-del-rio.jpg" class='rounded' />
                            </div>

                            <div class="col-md-3 mr-auto">
                                <img src="../assets/img/examples/olu-eletu.jpg" class='rounded' />
                                <img src="../assets/img/examples/studio-1.jpg" class='rounded' />
                            </div>
                        </div>
                    </div>

                    <div class="tab-pane text-center gallery fade" id="favorit" role="tabpanel" aria-labelledby="3a-tab">
                        <div class="row">
                            <div class="col-md-3 ml-auto">
                                <img src="../assets/img/examples/mariya-georgieva.jpg" class='rounded'/>
                                <img src="../assets/img/examples/studio-3.jpg" class='rounded' />
                                
                            </div>

                            <div class="col-md-3 mr-auto">
                                <img src="../assets/img/examples/clem-onojeghuo.jpg" class='rounded' />
                                <img src="../assets/img/examples/olu-eletu.jpg" class='rounded' />
                                <img src="../assets/img/examples/studio-1.jpg" class='rounded' />
                            </div>
                        </div>
                    </div>
                </div>
           
            
            </v-card>
            </v-container>
          <footer class='footer footer-default'>
            <div class="container">
                <nav class='float-left'>
                    <ul>
                        <li>
                            <a href="#">
                                About me
                            </a>
                        </li>

                        <li>
                            <a href="#">
                                blog
                            </a>
                        </li>

                        <li>
                            <a href="#">
                                Licenses
                            </a>
                        </li>
                    </ul>
                </nav>

                <div class="copyright float-right">
                  &copy;
                  2020, made with <i class="material-icons">favorite</i>
                    by me for a portofolio web.
                </div>
            </div>
        </footer>

        
        </body>
    </html>
</template>
        
 
  




<style>
/* styling description */
.description{
  margin: 1.071rem auto 0;
  max-width: 600px;
  color: #999;
}

.profile-page .profile-tabs {
  margin-top: 4.284rem;
}
/* .round{
  border-radius: 200px;
} */
.rounded{
    border-radius: 6px ;
}
.nav-pills .nav-item i {
  display: block;
  font-size: 30px;
  padding: 15px 0;
}
.nav-pills .nav-link {
  border-radius: 0.25rem;
}
.navbar .navbar-nav .nav-item .nav-link {
  position: relative;
  color: inherit;
  padding: 0.9375rem;
  font-weight: 400;
  font-size: 12px;
  text-transform: uppercase;
  border-radius: 1px;
  line-height: 20px;
}

.navbar .navbar-nav .nav-item .nav-link:not(.btn-just-icon) .fa {
  position: relative;
  top: 2px;
  margin-top: -4px;
  margin-right: 4px;
}

.navbar .navbar-nav .nav-item .nav-link .material-icons,
.navbar .navbar-nav .nav-item .nav-link .fa {
  font-size: 1.25rem;
  max-width: 24px;
  margin-top: -1.1em;
}

.navbar .navbar-nav .nav-item.active .nav-link,
.navbar .navbar-nav .nav-item.active .nav-link:hover,
.navbar .navbar-nav .nav-item.active .nav-link:focus {
  background-color: rgba(255, 255, 255, 0.1);
}



.navbar .btn,
.navbar .navbar-nav .nav-item .btn {
  margin-top: 0;
  margin-bottom: 0;
}

.nav-pills .nav-item .nav-link {
  line-height: 24px;
  text-transform: uppercase;
  font-size: 12px;
  font-weight: 500;
  min-width: 100px;
  text-align: center;
  color: #555;
  transition: all .3s;
  border-radius: 5px;
  padding: 10px 15px;
}

.nav-link.active {
  color: rgba(0, 0, 0, 0.87);
  border-color: #9c27b0;
}


.tab-content>.tab-pane {
  display: none;
}

.tab-content>.active {
  display: block;
}

.tab-content .collections .card .card-body {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.tab-content .collections .card .card-body .badge {
  display: inline-table;
  margin: 0 auto;
}

.gallery {
  margin-top: 3.213rem;
  padding-bottom: 50px;
}

.gallery img {
  width: 100%;
  margin-bottom: 2.142rem;
}


/* styling footer */
footer {
  padding: 0.9375rem 0;
  text-align: center;
  display: -webkit-flex;
  /* Safari */
  /* Safari 6.1+ */
  display: flex;
}

footer ul {
  margin-bottom: 0;
  padding: 0;
  list-style: none;
}

footer ul li {
  display: inline-block;
}

footer ul li a {
  color: inherit;
  padding: 0.9375rem;
  font-weight: 500;
  font-size: 12px;
  text-transform: uppercase;
  border-radius: 3px;
  text-decoration: none;
  position: relative;
  display: block;
}

footer ul li a:hover {
  text-decoration: none;
}

footer ul li .btn {
  margin: 0;
}

</style>

