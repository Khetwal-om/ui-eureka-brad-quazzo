1. Navbar

```html
<!DOCTYPE html>
<html>

<head>
  <!--Import Google Icon Font-->
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <script defer src="https://use.fontawesome.com/releases/v5.0.6/js/all.js"></script>
  <!--Import materialize.css-->
  <link type="text/css" rel="stylesheet" href="css/materialize.min.css" media="screen,projection" />
  <link type="text/css" rel="stylesheet" href="css/main.css" />

  <!--Let browser know website is optimized for mobile-->
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Custom Materialize Theme</title>
</head>

<body>
  <!-- Header -->
  <header class="main-header">
    <nav class="transparent">
      <div class="container">
        <div class="nav-wrapper">
          <a href="#" class="brand-logo">Quazzu</a>
          <a href="#" data-activates="mobile-nav" class="button-collapse">
            <i class="fa fa-bars"></i>
          </a>
          <ul class="right hide-on-med-and-down">
            <li>
              <a class="active-link" href="index.html">Home</a>
            </li>
            <li>
              <a href="solutions.html">Solutions</a>
            </li>
            <li>
              <a href="signup.html">Sign Up</a>
            </li>
            <li>
              <a href="#" class="btn purple">Login</a>
            </li>
            <li>
              <a href="https://facebook.com">
                <i class="fab fa-facebook"></i>
              </a>
            </li>
            <li>
              <a href="https://twitter.com">
                <i class="fab fa-twitter"></i>
              </a>
            </li>
            <li>
              <a href="https://instagram.com">
                <i class="fab fa-instagram"></i>
              </a>
            </li>
          </ul>
          <ul class="side-nav" id="mobile-nav">
            <h4 class="purple-text text-darken-4 center">Quazzu</h4>
            <li>
              <div class="divider"></div>
            </li>
            <li>
              <a href="index.html">
                <i class="fa fa-home grey-text text-darken-4"></i> Home</a>
            </li>
            <li>
              <a href="solutions.html">
                <i class="fa fa-cog grey-text text-darken-4"></i> Solutions</a>
            </li>
            <li>
              <a href="signup.html">
                <i class="fa fa-users grey-text text-darken-4"></i> Sign Up</a>
            </li>
            <li>
              <div class="divider"></div>
            </li>
            <li>
              <a href="#" class="btn purple">Login</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- Showcase -->
    <div class="showcase container">
      <div class="row">
        <div class="col s12 m10 offset-m1 center">
          <h5>Welcome To Quazzu</h5>
          <h1>Build For The Future</h1>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sit fugit deserunt quos provident aliquam inventore.</p>
          <br>
          <br>
          <a href="solutions.html" class="btn btn-large white purple-text">Learn More</a>
          <a href="signup.html" class="btn btn-large purple white-text">Sign Up</a>
        </div>
      </div>
    </div>
  </header>






  <!--Import jQuery before materialize.js-->
  <script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
  <script type="text/javascript" src="js/materialize.min.js"></script>
  <script>
    $(document).ready(function () {
      // Custom JS & jQuery here

    });
  </script>
</body>

</html>
```

**css**

```css
.main-header {
  background: url(../img/background.jpg);
  background-size: cover;
  background-position: center;
  min-height: 600px;
  color: #fff;
}

.main-header .showcase {
  padding-top: 100px;
}

.active-link {
  color: #d847f1;
  font-weight: bold;
}

```



2. section icon boxes

```html
<!--  section icon boxes-->

  <section class="section section-icons center">
    <div class="container">
      <div class="row">
           <div class="col s12 m4">
              <div class="card-panel">
                <i class="fa fa-user fa-3x deep-purple-text text-darken-2"></i>
                <h5 class="grey-text darken-4">Free Account</h5>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Esse, laudantium.</p>

              </div>
           </div>

        <div class="col s12 m4">
          <div class="card-panel">
            <i class="fa fa-database fa-3x deep-purple-text text-darken-2"></i>
              <h5 class="grey-text darken-4">Free Account</h5>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Esse, laudantium.</p>
          </div>
        </div>


        <div class="col s12 m4">
          <div class="card-panel">
            <i class="fa fa-bolt fa-3x deep-purple-text text-darken-2">            </i>

            <h5 class="grey-text darken-4">NOSQL databases</h5>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Esse, laudantium.</p>
          </div>
        </div>

      </div>
    </div>
  </section>

```



3. About section

```html

<!--    Section:  about-->

  <section class="section section-about grey lighten-4">
     <div class="container">
       <div class="row">
         <div class="col s12 m6">
           <h3><span class="deep-purple-text text-darken-1">About</span> Us</h3>
           <p class="flow-text">
             Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus delectus dolores ducimus eveniet expedita fugit iste, quasi repudiandae saepe totam?
           </p>

         </div>

         <div class="col s12 m6">
           <img src="img/tech.jpg" class="circle responsive-img">
         </div>

       </div>
     </div>
  </section>

```



4. Section developers

```html



<!--   Section developers-->

  <section class="section section-developers white-text">
      <div class="primary-overlay valign-wrapper">
        <div class="container">
          <div class="row">
            <div class="col s12 center">
              <h3>For Developers,By Developers</h3>
            </div>
          </div>
        </div>
      </div>
  </section>




```

```css
.primary-overlay{
  background: rgba(112,81,176,0.7);
  position: absolute;
  top:0;
  left: 0;
  width: 100%;
  height: 100%;
  overflow: hidden;
}


.main-header {
  background: url(../img/background.jpg);
  background-size: cover;
  background-position: center;
  min-height: 600px;
  color: #fff;
}

.main-header .showcase {
  padding-top: 100px;
}

.active-link {
  color: #d847f1;
  font-weight: bold;
}



.section-developers{
  position: relative;
  background: url("../img/code.jpg");
  background-size: cover;
  background-position: center;
  border-top: #333 solid 5px;
  border-bottom: #333 solid 5px;
  min-height: 180px;
}
```



# Section languages

```html



<!--   Section languages  -->

  <div class="section section section-languages grey lighten-4">
    <div class="container">
      <div class="row">
        <h4 class="center">Work with <span class="deep-purple-text text-darken-1">
          Any language
        </span></h4>
        <br><br>

        <div class="row">
          <div class="col s2">
            <img src="img/python-logo.png" class="responsive-img">
          </div>
          <div class="col s2">
            <img src="img/ruby-logo.png" class="responsive-img">
          </div>
          <div class="col s2">
          <img src="img/node-logo.png" class="responsive-img">
        </div>
          <div class="col s2">
          <img src="img/c-sharp-logo.png" class="responsive-img">
        </div>

         <div class="col s2">
          <img src="img/java-logo.png" class="responsive-img">
        </div>

        </div>
      </div>
    </div>
  </div>

```





# Podcast section

```html

<!--  section Podcast-->

  <section class="section section-podcast white-text">
    <div class="primary-overlay valign-wrapper">
      <div class="container">
        <div class="row">
          <div class="col s12 m8">
            <h4>Listen to the Quazzu podcast</h4>
            <p>Every thursday at 5 pm IST</p>
          </div>
          <div class="col s12 m4">
            <a href="#" class="btn purple btn-large">
              <i class="fa fa-podcast"></i>Listen
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

```



```css
.primary-overlay{
  background: rgba(112,81,176,0.7);
  position: absolute;
  top:0;
  left: 0;
  width: 100%;
  height: 100%;
  overflow: hidden;
}


.main-header {
  background: url(../img/background.jpg);
  background-size: cover;
  background-position: center;
  min-height: 600px;
  color: #fff;
}

.main-header .showcase {
  padding-top: 100px;
}

.active-link {
  color: #d847f1;
  font-weight: bold;
}



.section-developers{
  position: relative;
  background: url("../img/code.jpg");
  background-size: cover;
  background-position: center;
  border-top: #333 solid 5px;
  border-bottom: #333 solid 5px;
  min-height: 160px;
}







.section-podcast{
  position: relative;
  background: url("../img/circuit.jpg");
  background-size:cover;
  background-position: center;
  border-top: #333 solid 5px;
  border-bottom: #333 solid 5px;
  min-height: 160px;
}

.section-podcast .primary-overlay{
  background: rgba(112,81,176,0.9);
}


.section-podcast{
  margin-top: 30px;
}


@media(max-width: 501px) {
  .section-developers,
  .section-podcast{
    min-width: 240px;
  }
}
```




#  Carousel section

```html
<!--  Testimonial Carousel Section-->

  <div class="section section section-testimonial grey lighten-4">
    <div class="container">
      <div class="row">
        <div class="col s12">
            <div class="carousel carousel-slider center">
                <div class="carousel-item" href="#one!">
                   <h2>Testimonial 1</h2>
                  <p class="flow-text">"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto cum iure minus nulla omnis, perferendis veritatis? Aliquam asperiores beatae eveniet hic magnam nostrum vel. Aperiam in itaque quae vitae voluptate!
                    <em>-John Hazard from Mircosystems</em>
                  </p>
                  <div class="carousel fixed-item center hide-on small down">
                    <a href="#" class="grey">Read MOre</a>
                  </div>
                </div>

              <div class="carousel-item" href="#one!">
                <h2>Testimonial 2</h2>
                <p class="flow-text">"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto cum iure minus nulla omnis, perferendis veritatis? Aliquam asperiores beatae eveniet hic magnam nostrum vel. Aperiam in itaque quae vitae voluptate!
                  <em>-Eden  from Budapest</em>
                </p>
                <div class="carousel fixed-item center hide-on small down">
                  <a href="#" class="grey">Read MOre</a>
                </div>
              </div>

              <div class="carousel-item" href="#one!">
                <h2>Testimonial 3</h2>
                <p class="flow-text">"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto cum iure minus nulla omnis, perferendis veritatis? Aliquam asperiores beatae eveniet hic magnam nostrum vel. Aperiam in itaque quae vitae voluptate!
                  <em>-Steve from Techsoft</em>
                </p>
                <div class="carousel fixed-item center hide-on small down">
                  <a href="#" class="grey">Read MOre</a>
                </div>
              </div>

            </div>
        </div>
      </div>
    </div>
  </div>

```

# Something  is still missing with testimonials

```html
  <div class="section section section-testimonial grey lighten-4">
    <div class="container">
      <div class="row">
        <div class="col s12">
            <div class="carousel carousel-slider center">
                <div class="carousel-item" href="#one!">
                   <h2>Testimonial 1</h2>
                  <p class="flow-text">"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto cum iure minus nulla omnis, perferendis veritatis? Aliquam asperiores beatae eveniet hic magnam nostrum vel. Aperiam in itaque quae vitae voluptate!
                  <p> <em>-Eden  from Budapest</em></p>
                  </p>
                  <div class="carousel fixed-item center hide-on small down">
                    <a href="#" class="grey">Read MOre</a>
                  </div>
                </div>

              <div class="carousel-item" href="#one!">
                <h2>Testimonial 2</h2>
                <p class="flow-text">"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto cum iure minus nulla omnis, perferendis veritatis? Aliquam asperiores beatae eveniet hic magnam nostrum vel. Aperiam in itaque quae vitae voluptate!
                <p> <em>-Eden  from Budapest</em></p>
                </p>
                <div class="carousel fixed-item center hide-on small down">
                  <a href="#" class="grey">Read MOre</a>
                </div>
              </div>

              <div class="carousel-item" href="#one!">
                <h2>Testimonial 3</h2>
                <p class="flow-text">"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto cum iure minus nulla omnis, perferendis veritatis? Aliquam asperiores beatae eveniet hic magnam nostrum vel. Aperiam in itaque quae vitae voluptate!
                <p><em>-Eden  from Budapest</em></p>
                </p>
                <div class="carousel fixed-item center hide-on-small-and-down">
                  <a href="#" class="grey">Read MOre</a>
                </div>
              </div>
            </div>
        </div>
      </div>
    </div>
  </div>

```


**css**

```css
.carousel-item p{
  font-size: 21px !important;
}
```



# Footer and login modal


```html
<!--Footer -->

  <footer class="page-footer deep-purple lighten-1">
    <div class="container">
      <div class="row">
        <div class="col l6 s12">
          <h5 class="white-text">About Us</h5>
          <p class="grey-text text-lighten-4">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto delectus dicta distinctio dolore, provident repudiandae sit ut! Fuga, illo, velit?</p>
        </div>
        <div class="col l4 offset-l2 s12">
          <h5 class="white-text">Links</h5>
          <ul>
            <li><a class="grey-text text-lighten-3" href="#!">home</a></li>
            <li><a class="grey-text text-lighten-3" href="#!">solutinos</a></li>
            <li><a class="grey-text text-lighten-3" href="#!">Signup</a></li>
            <li><a class="grey-text text-lighten-3" href="#!">Link 4</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="footer-copyright deep-purple darken-1">
      <div class="container">
        Quazzu &copy;  2019
        <a class="grey-text text-lighten-4 right" href="#!">More Links</a>
      </div>
    </div>
  </footer>

```

    
    
**Login Modal**
    
    
```html
<!--  Modal at the bottom-->

  <div id="login-modal" class="modal">
    <div class="modal-content">
       <h4>Account Login</h4>
      <p>Login to access your account dashboard</p>
      <form>
        <div class="input-field">
          <input type="email" name="" id="email">
          <label for="email">Email</label>
        </div>

        <div class="input-field">
          <input type="password" name="" id="password">
          <label for="password">Password</label>
        </div>

      </form>
    </div>


    <div class="modal-footer">
      <a href="#!" class="modal-action modal close btn grey">
        <i class="fa fa-sync"></i>
        Reset Password
      </a>


      <a href="#!" class="modal-action modal close btn purple">
        <i class="fa fa-lock"></i>
        Login
      </a>

    </div>

  </div>



```



```jquery-css
        $('.modal').modal();
```


# Solutions Page

```html
<!DOCTYPE html>
<html>

<head>
    <!--Import Google Icon Font-->
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <script defer src="https://use.fontawesome.com/releases/v5.0.6/js/all.js"></script>
    <!--Import materialize.css-->
    <link type="text/css" rel="stylesheet" href="css/materialize.min.css" media="screen,projection" />
    <link type="text/css" rel="stylesheet" href="css/main.css" />

    <!--Let browser know website is optimized for mobile-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Quazzo</title>
</head>

<body>
<!-- Header -->
<header class="main-header-inner">
    <nav class="transparent">
        <div class="container">
            <div class="nav-wrapper">
                <a href="#" class="brand-logo">Quazzu</a>
                <a href="#" data-activates="mobile-nav" class="button-collapse">
                    <i class="fa fa-bars"></i>
                </a>
                <ul class="right hide-on-med-and-down">
                    <li>
                        <a class="active-link" href="index.html">Home</a>
                    </li>
                    <li>
                        <a href="solutions.html">Solutions</a>
                    </li>
                    <li>
                        <a href="signup.html">Sign Up</a>
                    </li>
                    <li>
                        <a href="#login-modal" class="btn purple modal-trigger">Login</a>
                    </li>
                    <li>
                        <a href="https://facebook.com">
                            <i class="fab fa-facebook"></i>
                        </a>
                    </li>
                    <li>
                        <a href="https://twitter.com">
                            <i class="fab fa-twitter"></i>
                        </a>
                    </li>
                    <li>
                        <a href="https://instagram.com">
                            <i class="fab fa-instagram"></i>
                        </a>
                    </li>
                </ul>
                <ul class="side-nav" id="mobile-nav">
                    <h4 class="purple-text text-darken-4 center">Quazzu</h4>
                    <li>
                        <div class="divider"></div>
                    </li>
                    <li>
                        <a href="index.html">
                            <i class="fa fa-home grey-text text-darken-4"></i> Home</a>
                    </li>
                    <li>
                        <a href="solutions.html">
                            <i class="fa fa-cog grey-text text-darken-4"></i> Solutions</a>
                    </li>
                    <li>
                        <a href="signup.html">
                            <i class="fa fa-users grey-text text-darken-4"></i> Sign Up</a>
                    </li>
                    <li>
                        <div class="divider"></div>
                    </li>
                    <li>
                        <a href="#login-modal" class="btn purple modal-trigger">Login</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- Showcase -->
    <div class="showcase container">
        <div class="row">
            <div class="col s12 m10 offset-m1 center">
                <h5>Welcome To Quazzu</h5>
                <h1>Cloud Solutions</h1>

            </div>
        </div>
    </div>
</header>






<!--Footer -->

<footer class="page-footer deep-purple lighten-1">
    <div class="container">
        <div class="row">
            <div class="col l6 s12">
                <h5 class="white-text">About Us</h5>
                <p class="grey-text text-lighten-4">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto delectus dicta distinctio dolore, provident repudiandae sit ut! Fuga, illo, velit?</p>
            </div>
            <div class="col l4 offset-l2 s12">
                <h5 class="white-text">Links</h5>
                <ul>
                    <li><a class="grey-text text-lighten-3" href="#!">home</a></li>
                    <li><a class="grey-text text-lighten-3" href="#!">solutinos</a></li>
                    <li><a class="grey-text text-lighten-3" href="#!">Signup</a></li>
                    <li><a class="grey-text text-lighten-3" href="#!">Link 4</a></li>
                </ul>
            </div>
        </div>
    </div>
    <div class="footer-copyright deep-purple darken-1">
        <div class="container">
            Quazzu &copy;  2019
            <a class="grey-text text-lighten-4 right" href="#!">More Links</a>
        </div>
    </div>
</footer>



<!--  Modal at the bottom-->

<div id="login-modal" class="modal">
    <div class="modal-content">
        <h4>Account Login</h4>
        <p>Login to access your account dashboard</p>
        <form>
            <div class="input-field">
                <input type="email" name="" id="email">
                <label for="email">Email</label>
            </div>

            <div class="input-field">
                <input type="password" name="" id="password">
                <label for="password">Password</label>
            </div>

        </form>
    </div>


    <div class="modal-footer">
        <a href="#!" class="modal-action modal close btn grey">
            <i class="fa fa-sync"></i>
            Reset Password
        </a>


        <a href="#!" class="modal-action modal close btn purple">
            <i class="fa fa-lock"></i>
            Login
        </a>

    </div>

</div>





<!--Import jQuery before materialize.js-->
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript" src="js/materialize.min.js"></script>
<script>
    $(document).ready(function () {
        // Custom JS & jQuery here

        $('.carousel-slider').carousel({
            fullWidth:true
        });

        $('.button-collapse').sideNav();

        $('.modal').modal();

    });
</script>
</body>

</html>
```



```css

.main-header-inner{
  background: url(../img/background.jpg);
  background-size: cover;
  background-position: center;
  min-height: 350px;
  color: #fff;
}

.main-header .showcase {
  padding-top: 100px;
}
```




# Sign up page


```html


<!--Section :Signup-->
<div class="section section section-signup">
    <div class="container">
        <div class="row">
            <div class="col s12 m6">
                <h4>Get a  free account</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur blanditiis consectetur consequuntur cum deserunt dolorum eveniet incidunt nemo perferendis ut.</p>
                <h4>Get a  free account</h4>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur blanditiis consectetur consequuntur cum deserunt dolorum eveniet incidunt nemo perferendis ut.</p>

                <h4>Get a  free account</h4>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur blanditiis consectetur consequuntur cum deserunt dolorum eveniet incidunt nemo perferendis ut.</p>

                <h4>Download the free one</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur blanditiis consectetur consequuntur cum deserunt dolorum eveniet incidunt nemo perferendis ut.</p>
                <h4>Get a  free account</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur blanditiis consectetur consequuntur cum deserunt dolorum eveniet incidunt nemo perferendis ut.</p>

                <h4>Get a  free account</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur blanditiis consectetur consequuntur cum deserunt dolorum eveniet incidunt nemo perferendis ut.</p>
            </div>

            <div class="col s12 m6">
                <div class="card-panel grey lighten-4 grey-text text-darken-4 z-depth-0">
                    <div class="input-field">
                        <input type="text" id="first_name">
                        <label for="first_name">First name</label>
                    </div>
                    <div class="input-field">
                        <input type="text" id="last_name">
                        <label for="last_name">Last name</label>
                    </div>

                    <div class="input-field">
                        <input type="email" id="email">
                        <label for="name">email</label>
                    </div>
                    <div class="input-field">
                        <input type="password" id="password">
                        <label for="password">password</label>
                    </div>
                    <div class="input-field">
                        <input type="text" id="company">
                        <label for="name">company</label>
                    </div>

                    <div class="input-field">
                        <select name="" id="role">
                            <option value="" disabled selected>Select Role</option>
                        <option value="professional">Professional</option>
                        <option value="manager">Manager</option>
                        <option value="other">Other</option>
                        <option value="student">Student</option>
                        </select>

                    </div>

                    <input type="submit" value="signup" class="btn btn-large purple btn-extend">



                </div>
            </div>

        </div>
    </div>
</div>

```




```css


.btn-extend{
  display: block;
  width: 100%;
}

```

